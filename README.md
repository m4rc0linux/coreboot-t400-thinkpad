# coreboot-t400-thinkpad
coreboot rom for thinkpad t400 

Image has been created with VGA rom and gbe.bin has been added with a random MAC address

./cbfstool t400vga1.rom add-int -i 1000 -n etc/boot-menu-wait has been applied to reduce the waiting time

No secondary payloads present

"esc" - to access to menu - working on reboot only

added a simple coreboot bootspash image


