# MELON
Minecraft Enhanced Linux Operating eNvironment. A image of arch just for Minecraft, nothing else. Made for lols, not very serious.

## Goal
To make an live arch system to flash to a USB, and run Minecraft on even the slowest computers. There will be no other functionality other than Minecraft. No other background operations other than what Arch needs.

## Build instructions
To build the image, assuming you are inside the source directory:
`docker run --rm -it -v [PATH TO SORUCE DIRECTORY]:/mnt/build --privileged $(docker build -q melon-builder)`

## Todo list
- [x] Modifying Arch to have minimal packages
- [ ] MultiMC on bootup of image
- [ ] Persistent storage (to store settings and `.minecraft` using a seperate partition) 
- [ ] Shortcuts for reboot, shudown and debug
- [ ] Be able to set wifi settings 
- [ ] Peformance enhancing (Optifine? Sodium+Phosphor+Lithium?)
- [ ] Hardware support (Especially Nvidia)
- [ ] Instead of supporting only mc support tf2
- [ ] pre bundled saw: the videogame w/wine

UPGRADED BY HYU 