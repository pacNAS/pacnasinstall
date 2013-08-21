pacNASinstall
=============

Basic install scripts for the pacNAS distribution.

Howto setup git repository
==========================

* git checkout git://github.com/pacNAS/pacnasiso.git
* git remote add archbang https://github.com/mrgreen3/abinstall.git
* git fetch archbang
* git checkout -b archbang archbang/master

After these steps, I have already merged the archbang/master into our own master branch.
Changes on the archbang/master could be merged regularly if necessary.

--> Original README.md -->
* Needs to get adopted


**Abinstall git hub**

To test load up ArchBang latest testing live iso

Open a terminal then:

*for best results edit your /etc/pacman.d/mirrorlist before running following commands*

    sudo pacman -Syy git
    git clone git://github.com/mrgreen3/abinstall.git
    cd abinstall
    sudo ./abinstall

For all options run 'sudo ./abinstall -h'
