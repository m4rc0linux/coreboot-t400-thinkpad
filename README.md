# coreboot-t400-thinkpad
coreboot version 4.13 rom for thinkpad t400 featuring seabios v. 1.14.0 https://seabios.org/Releases#SeaBIOS_1.14.0

commit 5c186c6777c9438ff4681929c9c25c98dee28bef

now it has been compiled to use libgfixnit graphics initialization with resolution 1280x800

gbe.bin has been added with a random MAC address 00:11:22:33:44:55

No support to intel wifi and bluetooth

./cbfstool t400m4rc0.rom add-int -i 1000 -n etc/boot-menu-wait has been already applied to reduce the waiting time

added flashregion_0_flashdescriptor.bin from libreboot

ich9fdgbe_8m.bin with 00:11:22:33:44:55 mac address

No secondary payloads added

capable to boot any linux, bsd and windows

You can add added a bootspash image (the ones in the repo are already set to be used with coreboot, colours will be fine)
./cbfstool t400m4rc0.rom add -f (file).jpg -n bootsplash.jpg -t raw

To see how this (or my others built images) works, just have a look into my youtube https://www.youtube.com/user/marcolinoxz
