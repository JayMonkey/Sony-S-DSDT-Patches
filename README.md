Sony Vaio-S DSDT Patches
========================

I am currently working on a series of DSDT/SSDT patches for use with MaciASL

These patches will allow for clean running of OSX Mavericks & Yosemite on a Sony VPC-SE2C5E Laptop, However most of the patches will be generic for all Sony Vaio S series laptops (SA/SB/SC). Certain patches will require specific variants for items such as the display resolution and support for the Sony Sheet battery option (Mavericks Only)

Please note that the 'Disable ATI GPU' patch is experimental and may need some manual fine tuning to work on your laptop if not Vaio SE2. I have since moved to using a patched SSDT to disable the ATI GPU. I've left the patch in the repo for those who want to experiment.

Update 28th March 2015
----------------------

Updated repo with SSDT patch to remove unused Pkg Buffer placeholders which resolves the PARSEOP erros when compiling.


How to Use
----------

Add the my REPO to {MaciASL->Preferences->Sources}

Name: JayMonkey

URL: http://raw.github.com/JayMonkey/Sony-S-DSDT-Patches/master

See my guides for instructions on how to install OSX on Sony Vaio VPCSE2C5E

Mavericks Guide: http://www.tonymacx86.com/mavericks-laptop-support/114961-jays-monkeybook-pro-ultimate-sony-vpc-se-customac-build.html#post699323

Yosemiet Guide: http://www.tonymacx86.com/yosemite-laptop-guides/156533-guide-update-sony-s-series-clover-yosemite.html

If you are starting with a native DSDT then these pattches should be used in conjunction with ReHabMans generic laptop patches which you can also use with MaciASL by adding the following REPO to {MaciASL->Preferences->Sources}

Name: ReHabMan

URL: http://raw.github.com/RehabMan/Laptop-DSDT-Patch/master

For more info on patching a DSDT for Sony S serires laptops see my post on the latest guieds thread :-

http://www.tonymacx86.com/yosemite-laptop-guides/156533-guide-update-sony-s-series-clover-yosemite-8.html#post997754

Cheers

Jay
