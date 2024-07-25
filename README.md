!!!!!!!!!!!!!
The author created this guide for himself as a checklist of what needs to be done for a new system and if something breaks on yours, I will not be held responsible for it

if you want to add to my guide or correct it, write to "Issue"
!!!!!!!!!!!!!
Used LibreTranslate,GoogleTranslate :(

1.Set GRUB Password
2.Use Hardened Kernel
3.Use completely free distributions (or at least minimize the presence of proprietary code on your system)

The community can't review proprietary code, so it's best to keep it to a minimum.
4.Minimalism
The less code you have on your system, the less likely it is that a vulnerability will appear in your system.

5.Use utilities to run programs in isolated environments, such as Firejail and Bubble Wrap, or simply use virtual machines for these purposes.

You can do it like in QubesOS

Separate virtual machines for accessing the Internet, working with documents...
Do you understand what I mean

Of course, you can immediately use QubesOS (if your device can run it)
6.Set "special" rules for different folders in fstab

For example, you can block the execution of programs in certain directories, for example in those where it is not needed, and this allows you to make life more difficult for viruses
7.Use programs like SeLinux, AppArmor

8.If you are using Debian/Devuan-like
Then you can connect the KickSecure or Whonix repository (The repository will not break dependencies, tested on Devuan GNU/Linux)

there are profiles for AppArmor, Utilities for convenient work with Tor, etc.

9.Use Whonix,VPN,Tor(only + VPN),Security and Privacy hardened Browser(https://brainfucksec.github.io/firefox-hardening-guide)
For browser need also install privacy and security extension
uBlock Origin
NoScript
Privacy Badger
ClearURLs
Decentraleyes
Disconnect
CanvasBlocker
LibreJS(optional, Not necessarily, because it breaks 90% of sites because it blocks all Javascript licensed under a proprietary license

You can also use systems to counter the DPI system(GoodBye DPI-like)


You can install SearX on your system(has analogues,
Can be run locally, which is more secure)

10.Use the "kloak" utility - this utility prevents the browser from de-anonymizing your fingerprint when typing on the keyboard, but may slow down keyboard input a little.

11.use macchanger on system start

Changing the mac address during boot (OpenRC "macchanger" service)


