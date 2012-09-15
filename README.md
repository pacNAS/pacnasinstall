**Abinstall**

To test load up ArchBang latest testing live iso

If using with Virtualbox please partition drive manually, make sure NC is not set with boot flag

Open a terminal then:

*for best results edit your /etc/pacman.d/mirrorlist before running following command*

`sudo pacman -Syy git`

`git clone git://github.com/mrgreen3/abinstall.git`

`cd abinstall`

`sudo ./abinstall`

On latest testing isos you know have a script that will pull in latest abinstall

`git-abinstall`

Removed menu variables to a lib file to allow for additional language versions.

For all options run 'sudo ./abinstall -h' 

