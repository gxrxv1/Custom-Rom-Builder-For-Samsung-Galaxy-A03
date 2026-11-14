# Custom-Rom-Builder-For-Samsung-Galaxy-A03
- This tool can create an ODIN super.tar to flash to your device
- After running this workflow you'll get a .7z file in the releases section.
- Extract that 7z file you'll get a super.tar. Just a .tar with the custom GSI.
- Then Flash the super.tar using ODIN in AP Section.
- You must select a custom PHH GSI with Android Version below 12.
- You install this at your own risk. Me not responsible for any bootloops, data loss, soft-brick, or hardware damage.

# How to Use this

<br>⚬ Fork into your Github Account and use via Github actions</br>

<br>1. Add Direct link of GSI</br>

- You can directly use the link of GSI (.xz/.gz/.zip/.7z/.img) from Github.
- Like This:
```sh
https://github.com/ponces/treble_build_aosp/releases/download/v2023.12.01/aosp-arm64-ab-gapps-14.0-20231201.img.xz
```
- If you use link from Sourceforge.net;
<br>⚬ Copy Download link of your GSI you'll get a link like this:</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-20.x/lineage-20.1-20231116-UNOFFICIAL-arm64_bgN.img.xz/download
 ```
<br>⚬ Then delete the /download at the end of the link, it will be like the link below;</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-20.x/lineage-20.1-20231116-UNOFFICIAL-arm64_bgN.img.xz
 ```
<br>⚬ The link must be end with .xz or a .gz or a .zip or a .7z</br>
<br>2. Add Rom Name</br>
<br>⚬ Then add the rom name it should be [rom_name]-[version]-[device version]-[arm64]-[gapps_or_vanila].7z<br>
like this LineageOS-20.1-a035fxxnn-arm64-gapps.7z

<br>3. Add Baseband Version </br>

<br>4. Add Vendor IMG Link
  - Use direct Link or remove /download from the ending of link if you use sourceforge link
  - Link must end like vendor.img
 # Credits:
 These people have helped this project in some way or another, so they should be the ones who receive all the credit:
- [Phhusson](https://github.com/phhusson)
- [bruh™](https://github.com/Exynos-nibba)
- [gauravv.x1](https://github.com/gauravv-x1)

  # Lists of GSIs I used (Endemanset) # should be my part here :)
- [LineageOS GSI](https://sourceforge.net/projects/andyyan-gsi/files)
- [AOSP (Oldest)](https://github.com/ponces/treble_build_aosp/releases/)
- [Evolution X and some more GSIs](https://sourceforge.net/projects/thegsis/files/)
- [PixelOS GSI Downloads](https://sourceforge.net/projects/misterztr-gsi/files/PixelOS/Android%2014/)
- [PixelOS GSI Github](https://github.com/MisterZtr/PixelOS_gsi/releases)
- [AOSP (Second One)](https://developer.android.com/topic/generic-system-image/releases#android-gsi-14)
- [ArrowOS GSI](https://github.com/naz664/ArrowOS_gsi/releases)

- moved
- # Note from Endemanset
- The reason why i forked this was just to make GSIs for unfortunate Bit 9 Security Layout users like me
- I will do all the work for you all 
- Both LineageOS 20 and 21 + Pre Quarterly Platform Release 21 build and AOSP 14 works (Based on SM-A035F)
- Since the OG repo hasnt been updated, i am updating this
- User Tests contains : PixelOS TD (Android 14), Evolution X, AOSP 14 (GMS UP1A), NotVanilla LineageOS 21 P-QPR2 and ArrowOS
- I recommend ArrowOS for stability (because of size), LineageOS 21 (NotVanilla P-QPR2) for Google Play and smooth Android 14, AOSP 14 (Oldest) for a Pixel Experience (get it?), LineageOS 20 for Smooth Android 13 (like ArrowOS)
- SourceForge test and LineageOS 21 (latest) are the same
- Remember to change your Vendor, Product and System_EXT
- DO NOT USE VNDKLITE FOR YOUR CUSTOM ROM. ONLY USE NON VNDKLITE. IT WILL BOOTLOOP YOUR DEVICE




























































































































































