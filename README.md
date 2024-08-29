# IMT-MGB PCB

This is a MGB(Game Boy Pocket) replacement board. This board is made to be used with only backlit LCD kits and does not include the components or voltages that are required for the OEM display. The board uses most of the components from an original MGB board and omits a few. The only new components you will need are 2x 27pF capacitors and a toggle switch to replace the contrast wheel. This was made in KiCad using gekkio's reverse-engineered [MGB schematics](https://github.com/Gekkio/gb-schematics/tree/main/MGB-xCPU). 

# Features
- Removes the voltages and components of the old LCD
- Has an option for tactile buttons
- New toggle switch in place of the old contrast wheel
- New convenient soldering pads for: A, B, Select, Battery
- A few other minor changes and add-ons

# Disclaimer
This board is designed with ample spacing between components to make soldering easier. However, if you lack experience with SMD (Surface-Mount Device) soldering, you risk damaging your components or Game Boy. I strongly recommend acquiring an SMD soldering kit and practicing beforehand if you're not already proficient.

Soldering these components is just one part of the process; you’ll also need a solid understanding of schematics for troubleshooting. While I have successfully built five of these using different MGB boards, I cannot guarantee compatibility with every MGB board due to the many variables involved. I’m not obligated to assist with debugging or troubleshooting, and will only do so at my discretion. Fortunately, there is a wealth of documentation and resources available that can help resolve the majority of issues you might encounter.

If you do come across an actual issue or have any suggestions you'd like to make to improve the board please reach out to me.

# Ordering

The board is available to be ordered through PCBWay. **Please remember to choose 1mm as the thickness and ENIG for the finish. If you are planning on using tactile switches, HASL will work.**

# Bill of Materials & Assembly

To successfully build this board, it’s recommended to have a soldering iron, a hot air rework station, a quality solder sucker, and solder wick on hand. While I offer equipment suggestions on my website, the exact tools are flexible depending on your preference: [Recommended Tools](https://www.jackvmakes.com/guides/tools).

As mentioned earlier, soldering is only part of the process. You’ll also need to troubleshoot any issues that arise, which requires familiarity with schematics and possibly the use of a multimeter. Fortunately, Gekkio's schematics provide all the information necessary for effective troubleshooting. Since this PCB utilizes original MGB components, diagnosing issues should be relatively straightforward. Transplanting components from an original MGB eliminates the need for additional purchases unless you’re concerned about the condition of the original parts. However, you will need to order two additional 0603 capacitors and the toggle switch itself to replace the contrast wheel. I’ve included a Bill of Materials (BOM) in case you lose a component or prefer to order new ones.

# LCD Kits

Any LCD kit that is made to be used with the MGB should work. The ones I've tested are kits from:

- Hispeedido
- Cloud Game Store
- FunnyPlaying

All these kits are available from [RetroGameRepairShop.com](https://retrogamerepairshop.com/?ref=HSj4v5OO) or AliExpress.

# Power Regulators

This board is compatible with multiple power regulators, including the OEM regulator or various aftermarket options such as The Frogulator, Bucket Mouse's PMPB, Marshallh's GBPP, my POG regulators, or Skimzor's SZ-REG.
Note: I have not tested any USB-C regulators, so I cannot guarantee their compatibility. However, since this board follows the same design as the OEM MGB, I don't anticipate any issues.

# Credit and Thanks

Huge thanks to multiple people for making this possible. Gekkio for doing the hardwork of reverse-engineering the MGB schematics, BucketMouse for providing a lot of the footprints and edge cuts used in this project, Skimzor for his work on his MGB, Natalie The Nerd for board scans, and Console And Casks for some of his footprints.

Please check out their Githubs and projects:

https://github.com/Gekkio/
https://github.com/MouseBiteLabs
https://github.com/skimzor/
https://github.com/nataliethenerd/
https://github.com/ConsolesandCasks/





# License

 [![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
 
This project/PCB is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. ***Under this license, you are not permitted to profit from or commercialize this project.***