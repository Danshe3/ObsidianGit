#Archlinux 
To begin, install some dependencies required for yay to function. To do this:

`sudo pacman -S git base-devel`

Then, clone, build locally, and install the yay package itself by running the three commands listed below in that order.

`git clone https://aur.archlinux.org/yay-bin.git cd yay-bin makepkg -si`Code language: PHP (php)

That’s all. The yay AUR helper should now be installed and ready to use on your Arch Linux system. You can check if everything is working correctly by running the command below, which will display the yay version.

`yay --version`

**Intsalling Packages from [[Archlinux User Repository (AUR)]] using YAY**

![[Pasted image 20240910214132.png]]
Once we know the exact name of the package we want to install, we all have to pass to the yay command option ‘`-S`‘ followed by the package’s name to be installed.

`yay -S gnome-shell-extension-dash-to-dock`

**Upgrading AUR Packages**
To do this, type: `yay -Sua`
