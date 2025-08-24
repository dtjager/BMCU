If you did **not** solder the motherboard yourself, flashing is usually **not required**. Unless you want to upgrade the firmware.

[¶](#️-warning) ⚠️ **WARNING**
------------------------------

🔥 **Before flashing, ensure there are no soldering issues!!!! Check for power short circuits!!!!** 🔥  
🔥 **Before flashing, ensure there are no soldering issues!!!! Check for power short circuits!!!!** 🔥  
🔥 **Before flashing, ensure there are no soldering issues!!!! Check for power short circuits!!!!** 🔥  

[¶](#required-tools) **Required Tools**
---------------------------------------

1.  **Multiple Dupont Wires** (To connect the flasher and the BMCU mainboard).
2.  **USB to Serial Adapter**
3.  **Computer** runs windows. -> If you're using a Mac/Linux, flashing is possible, but I don't have any tutorials or resources for mac.
4.  **Software: WCHISPTool**  
    The classic version used in this tutoriel : [wchisptool-v3.3.7z](/assets/files/wchisptool-v3.3.7z)  
    A newer version : [download at WCH website](https://www.wch-ic.com/downloads/WCHISPTool_Setup_exe.html)

[¶](#flashing-with-uart-ttl-using-ch340) Flashing with UART (TTL) using CH340
=============================================================================

### [¶](#h-1-connect-the-bmcu-mainboard-and-usb-serial-tool) 1. **Connect the BMCU Mainboard and USB Serial Tool**

⚠️ **DO NOT connect the BMCU to the printer during the entire process!**

*   Open the software  
    ![1.png](/assets/images/bmcu_flashing/1.png)
    
*   Connect wires according to the wiring instructions.
    
    BMCU
    
    USB Serial Tool
    
    R
    
    TXD
    
    T
    
    RXD
    
    ➕
    
    3V3
    
    ➖
    
    GND
    

> You may receive a yellow jumper cap, if it is similar to the converter on the right, no need to use it.  
> Connect 3.3V as VCC to the '+' pin on the BMCU mainboard.

![wiring_diagram_1.jpg](/assets/images/bmcu_flashing/wiring_diagram_1.jpg)  
![wiring_diagram_2.png](/assets/images/bmcu_flashing/wiring_diagram_2.png)

> If you don't see a serial device here, please install the CH340 chip driver  
> [https://www.arduined.eu/ch340-windows-10-driver-download/#google\_vignette](https://www.arduined.eu/ch340-windows-10-driver-download/#google_vignette)

### [¶](#h-2-connect-the-usb-serial-tool-to-your-pc) 2. **Connect the USB Serial Tool to Your PC**

*   Your computer should recognize the serial port automatically.
*   The COM port number might differ from the example in the image.

![3.png](/assets/images/bmcu_flashing/3.png)

* * *

### [¶](#h-3-configure-wchisptool-settings) 3. **Configure WCHISPTool Settings**

Open the `WCHISPTool` software and set the following options:

*   **Chip Model:** `CH32V203`
*   **Download Type:** `SerialPort`
*   **DI – Baud Rate:** `1M`
*   **SerialPort:** Auto-detected (your COM port)
*   **User File:** Choose the firmware `.bin` file (available from our wiki)

![bmcu_flash.png](/assets/images/bmcu_flashing/bmcu_flash.png)

* * *

### [¶](#h-4-unlock-the-chip-protection) 4. **Unlock the Chip Protection**

This is a **critical step** before flashing the firmware.

#### [¶](#recommended-method) ✅ Recommended Method:

1.  **Hold down the B button** (do **not** release it throughout).
2.  While holding B, **briefly press the R button** once.
3.  While **still holding B**, click the **"Remove Protect"** button in the WCHISPTool software.  
    ![4.png](/assets/images/bmcu_flashing/4.png)

If successful, you’ll see a red **“Unlocked”** message in the tool.  
![remove protect successful.png](/assets/images/bmcu_flashing/remove_protect_successful.png)

> ⚠️ If it keeps failing:  
> If you build your own PCB, please always check first for any soldering issues, such as solder bridges on resistor arrays, solder bridges on the CH32V chip, or short circuits in the circuit.
> 
> *   First, try again using the same button sequence carefully, hold always the B button.
> *   Second, **double-click the “Download” button** to force the chip into response mode, then try "Remove Protect" again.
> *   （Rare but indeed some chips will perform like this) try **swapping the TX and RX wires** (i.e., TX-to-TX and RX-to-RX instead of cross).

* * *

### [¶](#h-5-flash-the-firmware) 5. **Flash the Firmware**

Click the **Download** button.

*   Be patient during the process.
*   If flashing is successful, it should look like this:  
    ![download_successful.png](/assets/images/bmcu_flashing/download_successful.png)

#### [¶](#️-if-flashing-fails) ⚠️ If Flashing Fails:

*   Try **pressing and holding the B button** while clicking “Download”.
*   Alternatively, try changing the **baud rate to 115200**.
*   In rare cases, try **reversing TX and RX** (TX-to-TX, RX-to-RX) if not already done.

* * *

### [¶](#h-6-reboot-the-board) 6. **Reboot the Board**

*   Press the **R button** once.
*   The **red LED on the mainboard** should now light up.
*   🎉 **Congratulations! Firmware flashing is complete!** 🎉

[¶](#with-type-c-interface) With Type-C interface
=================================================

### [¶](#open-the-software) Open the software

![1.png](/assets/images/bmcu_flashing/1.png)

### [¶](#configure-wchisptool-settings) Configure WCHISPTool Settings

Open the `WCHISPTool` software and set the following options:

*   **Chip Model:** `CH32V203`
*   **Download Type:** Still `Serial Port`
*   **DI – Baud Rate:** `1M`
*   **User File:** Choose the firmware `.bin` file (available from our wiki)
*   Tick the "Serial Auto DI" option.

![bmcu_flash_typec.png](/assets/images/bmcu_flashing/bmcu_flash_typec.png)

### [¶](#action-sequence) Action sequence

Click : `Remove Protect` -> `Download` -> `Remove Protect` Again -> `Download` Again -> Repeat this loop until done(normolly the second download will be successful, if not check if you done something wrong)  
You might see some error messages during the first loop.

[¶](#using-mac-linux) Using Mac / Linux
=======================================

todo

[¶](#testing) Testing
=====================

**⚠️⚠️⚠️Avoid hot plugging and unplugging the motherboard and printer cables.⚠️⚠️⚠️**  
The right approach（just in case you are not sure what to do):

1.  Power off the printer
2.  Connect the BMCU to the printer
3.  Switch on the printer power
4.  You should see AMS appear in the consumables option, even if you have not inserted consumables, it may show that consumables are present in some channels (known bug)
5.  Power off the printer
6.  Disconnect the BMCU cable
