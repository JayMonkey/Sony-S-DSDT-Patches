Sony Vaio-S DSDT Patches
========================

I am currently working on a series of DSDT patches for use with MaciASL, I recommend using ReHabMan's fork of MaciASL available for download here :-

https://github.com/RehabMan/OS-X-MaciASL-patchmatic

These patches will allow for clean running of OSX Mavericks on a Sony VPC-SE2C5E Laptop, However most of the patches will be generic for all Sony Vaio S series laptops (SA/SB/SC). Certain patches will require specific variants for items such as the display resolution and support for the Sony Sheet battery option. 

Update: 9th Jan 2014

I have made some of my patches public and redy for beta test, ain order to use them please add the follwing REPO to MaciASL->Preferences->Sources.

Name: JayMonkey
URL: http://raw.github.com/JayMonkey/Sony-S-DSDT-Patches/master

For full instructions on how to install OSX Mavericks on Sony Vaio VPCSE2C5E laptop and a pre-patched DSDT please see my guide at TonyMacx86:-

http://www.tonymacx86.com/mavericks-laptop-support/114961-jays-monkeybook-pro-ultimate-sony-vpc-se-customac-build.html#post699323

If you are using the DSDT that I provide in the guide then you should only need to use one of the three EDID injection patches to change the screen resolution and panel options to suit your Sony Vaio model (SA/SB/SC/SE)

If you are starting with a native DSDT then these pattches should be used in conjunction with ReHabMans generic laptop patches which you can also use with MaciASL by adding the following REPO to MaciASL->Preferences->Sources

Name: ReHabMan
URL: http://raw.github.com/RehabMan/Laptop-DSDT-Patch/master

I will be publishing a new guide on how to extract your native DSDT and patch it using these edits sometime in the future.

Cheers and good luck.
Jay
