#Archlinux
What is an AUR Helper?
We’ll begin by stating two main approaches to installing AUR packages. The first is purely manual, involving the execution of several sequential commands to clone the corresponding package’s build files, build the package itself, and finally install it.

This method has two obvious drawbacks. First, it is more difficult to use for less experienced Arch users. Second, it lacks a mechanism to automatically update the package when an updated version is published to the AUR.

We stress that while Pacman may update all packages on your system that are installed from the official Arch repositories, it is not intended to interact with AUR. As a result, the well-known `pacman -Syu` command will not provide you with an AUR package update.

This is when the [AUR helpers](https://wiki.archlinux.org/title/AUR_helpers) come into play. The most simple way to think of them is as Pacman for AUR. In other words, these are small programs that are specifically designed to search for, install, or build AUR packages.

In addition, you may also use them to automatically update all of your AUR-installed packages, just like Pacman on your Arch Linux system.

It is crucial to highlight that the AUR helpers, like the AUR packages, are a result of the work of Arch users all around the world. In other words, Arch Linux developers do not support or develop them.

As a result, there are at least a dozen AUR helpers, with yay, pikaur, paru, pacaur, and others being the most popular and widely used by Arch users.

We’ll look at **[[Yay (AUR Helper)]]**, one of the most popular AUR helpers, and how we can use it to install AUR packages on our Arch Linux system easily.