# Mc-OS-themes
(Formerly known as Gnome-OSC-themes) 

This is a repository that contains Mac OS-themes for the Linux-Gnome desktop made by PaulXFCE (myself)

These are high end and thorougly developed GTK-themes for the gnome desktop (3.20+ through 3.28) that interpretes the Mac Os themes to the gnome-environment. 

In the latest version (McOS-MJV)  I've modernized it in every little detail. There is nothing (not a single item) that is not new. Resulting in a completely rewritten GTK.CSS-file.  it also contains the dark-mode (for applications that use it)

The dark-mode is also available as a seperate theme (McOS-MJV-Dark-Mode), which has the benifit of having GTK2-applications enjoy the same dark mode. 
 
## McOS-MJV

This is a gnome-interpretation of the Mac OS Mojave (TM) desktop, with the benifit of the dark mode 

![s](https://cn.pling.com/img/2/b/6/5/43d9a69282e978e27e9a6bd7c178c0e4debd.jpg)

## McOS-MJV-Dark_Mode

MC-OS-MJV-Dark-Mode :this is the gnome-interpreation of the Mac OS Mojave-dark-theme (TM)

![s](https://cn.pling.com/img/4/8/5/6/573788fee69c4b0bb0e698141900f232a6a1.jpg)

## McOS-HS

This one contains the Mac OS High Sierra (TM) interpretation ( McOS-HS)

![s](https://cn.pling.com/img/9/0/f/9/9cbbb4b03c5fc47510e717c3661cc81949ba.jpg)

## McOS-YS

This older theme is the gnome-adaptation of the OSX-Yosemite (TM) 

![s](https://cn.pling.com/img/8/5/0/b/73c79b20d0ed5c4b18b278eac1273e2df0bf.jpg)

## McOS-SPG

And finally a gnome-theme based on the looks of Logic Pro (TM) and Garageband (TM) called: McOS-SPG

![s](https://cn.pling.com/img/3/0/0/e/85b9c2c5ea25a5d7632f2ca79015a7f6ee84.jpg)

## How to install:

First: Download the file; extract it; and somethimes you will find two themes. a version with transparency, another with (not-transparent); copy both files to a '.themes'-folder you make in your home directory. Or to your USR/SHARE/THEMES-folder for system-wide use (certainly for theming of SNAP-packages)
Then use Tweak-tool to select the GTK and shell theme.
LOG OUT AND BACK IN for changes to take effect !

Second: McOS uses titlebuttons on the left-side:
To put the buttons to the left open a terminal:

gsettings set org.gnome.desktop.wm.preferences button-layout "close,minimize,maximize:"

To put the buttons back to the right in case you want to revert:

gsettings set org.gnome.desktop.wm.preferences button-layout ":minimize,maximize,close"

In Gnome 3.26+ gnome-tweak has a option to change the position of the titlebuttons, so the above steps are not necessary. 

## Troubleshouting

When, as such, theming does not look the way it should be: make sure you have installed the necessary theme-"engines":

- The gnome-themes-standard package,
- The murrine engine. This has different names depending on your distro.
gtk-engine-murrine (Arch Linux)
gtk2-engines-murrine (Debian, Ubuntu, elementary OS)
gtk-murrine-engine (Fedora)
gtk2-engine-murrine (openSUSE)
gtk-engines-murrine (Gentoo)

sudo apt-get install gtk2-engines-pixbuf is the terminal command, usually solves the issues with GTK2.



--------------------------------------------------------------------------------------------------------
Trademarks:
Apple, Mac OS High Sierra, Mac OS Mojave, OS X Yosemite, Garageband and Logic PRO 
are are registered trademarks of Apple Inc, registered in the U.S. and other countries.
