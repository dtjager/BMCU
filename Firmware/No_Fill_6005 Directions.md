Thinking about getting a BMCU? What I've learned!

**Disclaimer:** I'm extremely new to the BMCU system and just finished putting mine together today, so take everything that I say with a grain of salt and proceed at your own risk. With this being said, there were a couple of times throughout the process where I was stumped, so I'd like to share what I've learned and I'll update this post if I ever have to troubleshoot in the future. Just for reference, I have an A1. Also, most of what I write below will be in reference to the version that I have from the specific seller that I bought it from, as well as mostly for the A1. Please let me know if I am wrong about anything that I wrote below, as I just want to make sure that people have an easy introduction into the BMCU.

**Please read my points number 28 and 39 before you even attempt to assemble the BMCU!**

**1\. What is the difference between the BMCU and AMS?** The BMCU and AMS will give you the same results: multi-color printing. However, with this being said, the BMCU is an open-source, non-official Bambulab product. So, technically, Bambu can theoretically release updates that prevent the system from working. But fortunately, as of now, you can always revert back to previous updates on Bambu.  

**2\. What versions does the BMCU work on?** According to the seller that I bought it from, it works with the A1 and A1 mini. It also experimentally works with the P1S P1P, which you can find posts about in the reddit groups that I have listed below. Additionally, it could possibly work with the X1 series but it is unproven.  

**3\. If it's open source, can I just order all the parts separately myself?** Yes, people have done so in the groups that I have listed below, but I personally have not. The good thing about this is that if you order a kit and accidentally break a piece, you can order a specific replacement part (usually for pretty cheap). And just so you know, people also upload replacement pieces on MakerWorld.  

**4\. What's the difference between a BMCUx and BMCUc?** The BMCUc supports bi-directional buffering, making the system softer on your printer.  

**5\. What are some of the other BMCU options?** Some BMCUs use a 130 motor while others use a 370 motor. Additionally, some use glass bearings and some use steel bearings. I'm not really sure what the difference is, but the one I ordered has a 370 motor and glass bearings.  

**6\. Where did you buy yours from?** I bought Set A from this link: [**https://www.aliexpress.us/item/3256809034433237.html?spm=a2g0o.order\_list.order\_list\_main.5.49ea1802L3PVEx&gatewayAdapt=glo2usa#nav-specification**](https://www.aliexpress.us/item/3256809034433237.html?spm=a2g0o.order_list.order_list_main.5.49ea1802L3PVEx&gatewayAdapt=glo2usa#nav-specification)  

**7\. What is the difference between Set A vs Set C?** Set A is for those that want to print in up to 4 colors. Set C is typically bought by those that have print farms and only want the option of having two spools in case one runs out as a backup, because to them, time is money, rather than having the option of printing 4 colors.  

**8\. How hard is it to assemble?** Not hard at all, _but you'll need a soldering iron and solder (aka wire meant for soldering)._ If it's your first time soldering, don't worry. It was my first time ever dealing with electronics or soldering. I'll post some reference videos below. Also, here are some tools that I would recommend printing to help you with soldering. Links: [https://www.printables.com/model/843353-solder-scroll-ergonomic-adjustable-solder-tool](https://www.printables.com/model/843353-solder-scroll-ergonomic-adjustable-solder-tool) and [https://makerworld.com/en/models/487984-soldering-tool-holder-flexible-arms-helping-hands?from=search#profileId-402509](https://makerworld.com/en/models/487984-soldering-tool-holder-flexible-arms-helping-hands?from=search#profileId-402509)  

**9\. Why does the seller that you bought it from have another kit with the same title and description, but sometimes different prices?** To be honest, no idea. But, if someone knows why, post it in the comments of this post so that others can learn from it.  

**10\. Where can I find the instructions for the kit that you purchased?** This drive contains the instructions, firmware, and STLs from the seller. Also, people recommend to print the pieces in PETG. Link: [https://drive.google.com/drive/folders/1XAFt80xYqbaAVDwtqItvBLUezMbsYlGM](https://drive.google.com/drive/folders/1XAFt80xYqbaAVDwtqItvBLUezMbsYlGM)

**11\. I'm limited on space. Is there a print that will allow me to mount both the spools and the BMCU on my A1?** Yup, there sure is! Go to the link I will paste, print it out of PETG, and select the print profile by me, TheHerd, on MakerWorld, if you have an A1 and are confused about which pieces are compatible with it and don't feel like arranging the pieces to fit on your A1 build plate. Don't worry, the original creator still gets the points. And, instead of screwing it, I used mounting tape from the Gorilla brand because I didn't want to risk my model not being compatible with where they wanted me to screw it in. And, just and fyi, it is fine to print out the PTFE supports with PLA instead of PETG. You can find that stl in the Google drive folder that I posted the link to in my 10th bullet point. Link: [https://makerworld.com/en/models/1429013-bmcu-stand-for-a1-a1-mini-ams-lite-vertical-mount#profileId-1485599](https://makerworld.com/en/models/1429013-bmcu-stand-for-a1-a1-mini-ams-lite-vertical-mount#profileId-1485599)  

**12\. Won't adding all that weight be rough on my printer?** Probably, so you may want to print out these Z-axis supports in PETG from the link I will paste if you have an A1. Print the print profile that is titled "A1 mini Big feet" instead of the one from the creator, as you only need the bottom part. Don't worry about the title saying it's for the mini. Link: [https://makerworld.com/en/models/92486-ams-lite-top-mount-for-a1#profileId-100105](https://makerworld.com/en/models/92486-ams-lite-top-mount-for-a1#profileId-100105)

**13\. Where are some good resources if I want to ask questions about the BMCU?** [https://www.reddit.com/r/OpenBambu/](https://www.reddit.com/r/OpenBambu/) and [https://www.reddit.com/r/BMCU/](https://www.reddit.com/r/BMCU/)  

**14.** **One of the bushings that BLV mentioned in Step 4 of the assembly guide isn't fitting. What do I do?** Yup, and it won't ever fit perfectly in there for some reason, no matter how many times you reprint the STL. Not saying that you should superglue it, but that's what I did. Try and find glue that is heat and vibration resistant.  

**15.** **I'm on Step 5 of the assembly guide and don't know how to solder. Help!** First of all, I'd recommend using the part of the tool that I have the arrow point to to strip the wire. Place the wire where the arrow is pointing, then pull it. Second of all, personally, before I add solder to the wire, I twist the "hairs" so they aren't "frazzled". Make sure to strip and add solder to both ends of the wire. It's a surprise tool that will help us later. Here's the link that I used to learn how to solder for the motor: [https://youtu.be/XkpGsMpGGqQ?si=qGBOIP5blRSgvldF](https://youtu.be/XkpGsMpGGqQ?si=qGBOIP5blRSgvldF) . While the video says to place the black wire on the red dot, and it technically doesn't matter if you solder it to the negative on the daughter board. However, I'd highly recommend just keeping it aligned with the instructions and SOLDERING RED TO RED.

[![r/OpenBambu - Thinking about getting a BMCU? What I've learned!](https://preview.redd.it/thinking-about-getting-a-bmcu-what-ive-learned-v0-tdrll9tojlff1.png?width=663&format=png&auto=webp&s=3e6910d2c4d7d8de2b19eee8f3e479769339feec)](https://preview.redd.it/thinking-about-getting-a-bmcu-what-ive-learned-v0-tdrll9tojlff1.png?width=663&format=png&auto=webp&s=3e6910d2c4d7d8de2b19eee8f3e479769339feec "Image from r/OpenBambu - Thinking about getting a BMCU? What I've learned!")

**16\. I'm on Step 8 of the assembly guide. What does BLV mean when they say "with the pointed end facing up"?** They just mean to place the hex nut in vertically rather than horizontally.  

**17\. I'm on Step 9 and the slider isn't moving easily.** **What do I do?** You likely just need to shave the sides of the slider. I used a wood carving tool, personally, but you can probably just file it down or use sand paper.  

**18\. What in the world is BLV talking about in Step 10?** In the bag, there are two pieces that look very similar and seem to have the same diameter. For this step, the assembly guide is wanting you to take out the one with the black screw on the side. You'll have to take out the screw before you can insert the shaft then screw it back once you've already inserted it.  

**19\. In Step 12, does the filament seem to face a little resistance even though I can still push it through?** Yup, you didn't do anything wrong. There are little teeth inside of the metal outlet that causes this.  

**20\. I'm on Step 20 of the assembly guide. How do I do this now?** Watch this video. It is okay if you get some metal on the black part, but make sure not to let the metal from the positive end and negative end touch one another. [**https://youtu.be/y0xDR3St5Gg?si=RhCsTe45R3gjiS3f**](https://youtu.be/y0xDR3St5Gg?si=RhCsTe45R3gjiS3f)  

**21\. I accidentally got grease on the end of the solder wire. What do I do?** Use some rubbing alcohol to wipe, get a clean napkin and wipe off the alcohol, then wait for the rest to evaporate. The alcohol will evaporate quickly.  

**22\. In step 22, it says that I should feel a bend. What bend?** You'll just feel a slight resistance, but not anything that screams "bend".  

**23\. Did you have leftover parts when you finished?** Yup!  

**24\. When you plug in the BMCU, which port on the back of the A1 do you use?** Doesn't matter, they're the exact same!

**25\. Why is the AMS screen on my printer appearing but not giving me any options to load, unload, or edit?** You have to push the filament all the way through the BMCU first, but don't go all the way to the actual print head. Once you pass it through the BMCU, you'll have the options to load, which is when you need to push it all the way to the print head.

**26\. Huh, what do they mean in step 27 when they say to push on the slider vs when they say to pull on the slider?** So, what the assembly manual really means, is that you need to push down on the trigger thingy until the printer says that it has finished loading. If you release the trigger before it has completed loading, it will pull the filament back towards the spool rather than towards the print head. With this being said, before you actually load the filament (refer to my 25th point), you need to press the trigger just to load the filament all the way through the BMCU. After doing so, you can release the trigger. Then, on the printer, click load. One the screen says to push in the filament, you MUST press the trigger the entire time while you are pushing it through the print head. Keep holding it until it moves on to the purge step. After it reaches the purge step, you can release the trigger.  

**27\. In step 30 of the assembly guide, when it says to not cut the PTFE tubes too short, what exactly does that mean?** So, quick tip, I went to "controls" on the printer and moved the hot end all the way to the left because the furthest slot was towards the right. That gave me the maximum length that I needed for the PTFE tube, roughly. Make sure to account for the fact that a small portion of the tube will be hidden in the BMCU and print head. For the mount that I pasted a link to, I put the mount roughly in the middle (I tried to center it but it was a little to the left), and the longest strand I need was 33 inches.

**28\. How do I remove the cord from the back?** _BEFORE YOU EVEN PLUG IN THE BMCU, PRINT THIS TOOL TO REMOVE THE WIRE!!!!_ Even with this tool, I had to use quite a bit of force, and I tend to be rough on things. I printed the tool out of PETG and used 100%% infill. Link: [https://www.printables.com/model/382058-bambu-ams-disconnect-tool](https://www.printables.com/model/382058-bambu-ams-disconnect-tool)

**29\. When I try to unload filament, it just pushes more filament further**. **What do I do?** When you unload the filament, when it says to "pull back current filament" on the printer screen, you have to press the trigger.

**30\. I'm trying to unload the filament and I am pressing the trigger, but it still won't let me unload it. What do I do?** Turn off your printer then unplug the cord from the back (reference my 31st bullet). After doing so, turn your printer back on. Then, even though the AMS option won't show up, this is what we want. Click unload filament from a single roll like you had done before the BMCU. This will allow you to remove all the filaments. When finished removing the filament, turn your printer off again, then plug the BMCU back in, turn the printer on and proceed normally.

**31\. The printer keeps clogging. Help!** It is probably because even regular AMS systems are known for clogging what is apparently called "the filament hub". I didn't think that mine was clogged, and nothing seemed to have come out, but it apparently worked. Watch this video to see how to unclog it. The video also features unclogging the hot end. If it is your first time removing the filament hub, you're probably going to have to use a little more force than what's shown in the video. Link: [https://www.youtube.com/watch?v=cNBu2mcOH8E](https://www.youtube.com/watch?v=cNBu2mcOH8E) . Also, if you notice that the filament seems brittle, dry it. I noticed that PLA I had never had problems with in the past kept breaking. If you need a dryer, I would recommend buying one from Creality. While I have heard not to buy printers from them, their dryers work fine. Sometimes, people sell them for really cheap on Facebook Marketplace (saw one for $25).

**32\. How do I actually load all 4 spools?** Someone had to help me with this, and I still probably added too many extra steps for myself, but here is what I did, and it at least worked. LOL

*   Press down on the trigger and push the filament into the bottom of the module you’re trying to load. Keep going until the filament light turns on. (Earlier, I mentioned pushing it until you can see it come out the other side—sometimes the filament can get stuck in the buffer section with the spring, so just make sure it’s made it through.)
    
*   If you just want to check that the module works, you can load the filament straight into the extruder using the printer’s touchscreen—no need to mess with the slicer yet.
    
*   Once you’ve tested that loading and unloading works for all the modules, go ahead and unload the last filament you tested. If I remember right, it won’t fully eject—and that’s okay. Just leave it as is.
    
*   Turn off the printer, then push filament through the BMCU for all modules, but not all the way to the print head. Then, turn the printer back on.
    
*   Now you can go into Bambu Studio, pick the filament or filaments you want to use, and start your print. The printer will take care of all the loading and unloading automatically based on what you picked.
    
*   Make sure that the filament type that you enter into the slicer is the same as the filament AMS screen on your printer (even though you should NOT click "load"). Just click "edit"
    

**33\. Why in the world will the PTFE tubes not stay connected to the filament hub?!** This is apparently another common problem even with the official AMS. It will seem unreasonably difficult to pull apart if it is your first time removing it. Watch this video: [https://www.youtube.com/watch?v=hmByMHddxLE](https://www.youtube.com/watch?v=hmByMHddxLE)

**34\. I took out the hot end and now I can't get the latch back on, what do I do?** I don't know why this works, but it does. On your printer, go to "Control", click "Nozzle", then enter 200. Once you see that the nozzle has heated up to 200 degrees, use pliers to close the latch. BE CAREFUL! IT WILL BE HOT!! Once you've gotten the latch on, change the nozzle temperature to 0 degrees. Don't worry, it won't actually change it to 0 degrees, it will just stop applying heat so that the hot end will reach room temperature. I'd also recommend printing a fan cover for the side of the A1 print head, as I always tend to try to grip there. It shouldn't be hot, but I don't want to wear out the motor by accidentally stopping the fan with my hands.

**35\. Why did the motor of one of the modules stop running when trying to feed filament?** Turn off the printer and remove the PTFE tube from the print head. Hold the trigger of the module and try manually feeding it through the tube. If it is hard to do, you have a bend in your PTFE tube. Try to unbend it, then if you can't, cut it.

**36 I'm trying to print a multicolor model. Why do the colors look fine in the "Prepare" tab but change when I go to the "Preview" tab?** The "Preview" tab colors aren't the actual colors that the model will be printed in. The colors just represent different parts of the print, such as thin walls, overhang, etc.

**37\. How do I "color" my models for the BMCU?** This video helped me: [https://youtu.be/5aJZyhfY74s?si=KYn5aTZj5bulu6uI](https://youtu.be/5aJZyhfY74s?si=KYn5aTZj5bulu6uI)

**38\. How do I "color" prints that are flush, like logos?** Here's a detailed, yet short video: [https://www.youtube.com/watch?v=em\_t5sK13CM](https://www.youtube.com/watch?v=em_t5sK13CM)

**39.** **Are there replacement pieces that I should print just in case?** Yes, there absolutely are! I'd recommend printing a spare of each of these before even attempting to connect the BMCU to your printer.

*   Filament hub cap: [https://makerworld.com/en/models/745171-ams-lite-hub-cap-4-way-replacement-a1#profileId-1072550](https://makerworld.com/en/models/745171-ams-lite-hub-cap-4-way-replacement-a1#profileId-1072550)
    
*   Filament hub connector: [https://makerworld.com/en/models/1105767-bambu-ams-lite-filament-hub-connector#profileId-1173093](https://makerworld.com/en/models/1105767-bambu-ams-lite-filament-hub-connector#profileId-1173093)
    

Please make sure to print the spare filament hub cap and filament hub connector. The below aren't necessary, but are definitely recommended to help prevent you from needing a spare in the first place.

*   Filament hub connector and PTFE tube removal tool: [https://makerworld.com/en/models/1267494-amazing-a1-and-a1-mini-ams-hub-tool#profileId-1293506](https://makerworld.com/en/models/1267494-amazing-a1-and-a1-mini-ams-hub-tool#profileId-1293506)
    
*   Cable Clips: [https://makerworld.com/en/models/1277493-a1-cable-clip-1-1-replacement?from=search#profileId-1305146](https://makerworld.com/en/models/1277493-a1-cable-clip-1-1-replacement?from=search#profileId-1305146)
    

Hopefully this helps someone :)