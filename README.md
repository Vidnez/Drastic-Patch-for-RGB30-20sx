# Drastic patch for RGB30/20sx

A patch for RGB30/20sx that allow multiple screen layouts and sizes in Drastic standalone emulator. The patch is only for ArkOS.

![preview](https://github.com/user-attachments/assets/99778fbb-24e1-4400-9f86-8833e6ef1c20)

# How to use

The patch has 5 layouts, which are invoked with the images in PNG format that the patch installs in roms/nds/bg or roms2/nds/bg depending on the user setup. Drastic only allows you to use two layouts at a time, so only keep the PNGs of the layouts you want to use in the bg folder (except for bg_horizon_single.png which must always be in the folder). You can also rename the PNGs of the layouts that you DO NOT want to use, so only the two layouts that you are going to use are left with the correct name. And if you don't like overlays, you can create trasparent pngs with the name of the layouts you want to use so the patch uses the layouts you choose.

# Installing the patch:

1.- Download the patch for your setup in the releases section (1 or 2 SD).

2.- Unzip the ZIP file and copy the ndspatch.sh and ndspatch.tar.gz files into the ports folder and run ndspatch from game list of port section in emulation station.

3.- Go to roms/nds/bg folder or roms2/nds/bg folder to select and keep the two PNG you want to use. (Do not delete bg_horizon_single.png)

You can apply the patch as many times as you want to restore the config file or images of the layouts.

Additionally, in the main page you can download overlays with a grid effect if you prefer.

