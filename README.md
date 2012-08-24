To test load up ArchBang latest testing live iso 

If using with Virtualbox please partition drive manually, make sure NC is not set with boot flag

Open a terminal then:

sudo pacman -Syy git

git clone git://github.com/mrgreen3/abinstall.git 

cd abinstall

sudo ./abinstall

Currently working on grub-bios install, check /tmp/grub.log prior to 
rebooting to make sure grub installed correctly.

Added an syslinux option to installer, very much work in progress.

Removed menu variables to a lib file to allow for additional language versions.

For testing purposes we have now a -i [skip install] -c [skip configuration]

These options assume you have an installation on target device.
