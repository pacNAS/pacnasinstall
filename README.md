**Abinstall**

To test load up ArchBang latest testing live iso

If using with Virtualbox please partition drive manually, make sure NC is not set with boot flag

Open a terminal then:

*for best results edit your /etc/pacman.d/mirrorlist before running following commands*

    sudo pacman -Syy git
    git clone git://github.com/mrgreen3/abinstall.git
    cd abinstall
    sudo ./abinstall

For all options run 'sudo ./abinstall -h' 

