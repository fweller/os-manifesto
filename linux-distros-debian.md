# Debian distributions

All the distributions listed on this page are either actually Debian or are downstream of Debian

- The package format is RPM
- The package managers are DPKG, APT, Aptitude

The most popular distributions on the page are

- Debian
- Ubuntu (including Kubuntu, Xubuntu)
- Linux Mint
- PopOS

## Debian actual

- [Debian](https://www.debian.org/) *Popular*
  - Oldest Linux Distro #2 after Slackware
  - This is the Source!
  - The Good
    - First Linux Distro that was open for every developer to contribute, and is still the most significant non-commercial distributor of Linux
    - Has the largest team of volunteer contributors.
    - There is corporate support for Debian, but no corporate ownership
    - High quality documentation is readily available online
    - All of the embedded Linux processors and boards that I support and use have Linux BSP’s that are ultimately derived from Debian, such as Rasberry Pi OS and NXP Embedded Linux.
    - The Calamares installer used on the Live version of the Debian ISO is significantly better than the Debian installer
  - The Bad
    - Debian insists on installer images being free software only, so important drivers are missing. This is extremely annoying and limits the ability of novices to successfully install this distro.  Unofficial installers are available with drivers though, but its not easy to identify them.  The Live version of the ISO provides drivers.
    - The Debian official installer is the slowest installer I have ever used.  One simple installation took over 8 hours compared to 10 minutes for any other installer.
- Debian branches
  - [Debian “Sid” Unstable](https://wiki.debian.org/DebianUnstable)
    - Rolling release
    - Bleeding-edge like Arch but slightly more stable
    - This is a good choice for developers or enthusiasts who want the very latest
  - [Debian Testing](https://wiki.debian.org/DebianTesting)
    - Rolling release
    - Downstream of Debian Sid
    - Packages are still fairly fresh
    - This is a good choice for developers or enthusiasts who want the latest but after some initial testing
  - [Debian Stable](https://www.debian.org/)
    - THE MOST STABLE!
    - Point release with a 2-year cadence
    - Downstream of Debian Testing
    - This is what most people use for desktop, and should be the only branch used on servers
    - [Debian Backports](https://backports.debian.org/) can keep Debian Stable feeling fresh for workstations

## Downstream of Debian

- [Siduction](https://siduction.org/) *Underrated*
  - Based on Debian "Sid" Unstable
  - Rolling release
  - Most developers are located in Germany
  - Focused on these DEs only: KDE Plasma, Xfce, Lxqt
  - They write their own user [manual](https://manual.siduction.org/siduction-manual_en.pdf)  
  - Their [github](https://github.com/siduction) stores the configuration and mods to offer to build their distro
  - The installer is configured for the Btrfs filesystem with Snapper rollback, all sitting on top of LUKS encryption.
    - This allows the user to roll back their system to a more stable instance should there be a stability issue
  - This distro is nicely polished and I like it a lot; I am running this on three of my computers.  
- [Spiral Linux](https://spirallinux.github.io/) *New and Promising*
  - This is more of a Debian installer than an actual distro
    - One could think of this as Debian installed properly
  - Based on Debian stable but easily upgraded to Testing or Sid
  - Single developer previously maintained Gecko Linux and has switched to Debian from OpenSUSE
  - Supporting all the major DEs: KDE Plasma, Cinnamon, Xfce, Gnome, etc.
  - Default install configuration uses BtrFS + LUKS, Flatpack management through GUI, zRAM, etc. This is very modern.
  - I used this distro on two of my computers.  
  - This distro installed on my MacBook Pro (Intel)
    - I still had to manually install the Broadcom Wi-Fi/BT drivers and the classic Nvidia GPU driver
- [DebianEasy](https://debianeasy.github.io/)
  - Forked from Spiral and removed some default install apps
  - This distro has potential but as of early 2024 the project is too sloppy to be taken seriously
- [Neptune](https://neptuneos.com/en/start-page.html)
  - Based on Debian stable but with newer kernel, newer drivers, newer utilities, newer DE, persistent USB installer
  - KDE Plasma
  - Germany
  - I tested this in early 2023 and it is decent.  There are some nice KDE Plasma themes.  Install is okay. I feel that this distro is not getting enough developers to make it excellent.
- [Sparky](https://sparkylinux.org/)
  - Poland
- [SolydXK](https://solydxk.com/)
  - Based on Debian Stable  
  - Netherlands
  - Originally started as Linux Mint Debian Edition with KDE Plasma DE
  - There are two DE flavors: KDE and Xfce
    - SolydK: KDE Plasma
      - I tried SolydK in 2023.  It had not been updated since 2021 and was based on the previously released debian distro, so it felt old.  default partitioning was strange, seperating home from root but using ext4 is not ideal.  at least it allowed me to use xfs filesystem or btrfs on the install, so that has some promise.   it ships with some interesting kde plasma themes which may be worth looking at.
    - SolydX: Xfce
- [MX Linux](https://mxlinux.org/) - *POPULAR*
  - Downstream of Debian Stable
  - KDE Plasma, XFCE, SysVInit w/ systemd-shim
  - Greece, venture between the antiX and former MEPIS Linux
- [Netrunner](https://www.netrunner.com/)
  - Downstream of Debian Stable
  - KDE Plasma, Calamares Installer, Kvantum theme
- [Deepin](https://www.deepin.org/en/) *POPULAR*
  - Downstream of Debian Stable
  - Chinese
  - The Deeping DE is very attractive
- [Kali](https://en.wikipedia.org/wiki/Kali_Linux)
  - Downstream of Debian testing
  - For penetration testing, not for general usage
- [Armbian](https://www.armbian.com/)
  - Debian stable
  - For ARM aarch64
  - XFCE is the DE
  - This is the default distro for the Raspberry Pi, and it is very good
- [AntiX](https://antixlinux.com/)
  - For old computers
  - SysV instead of systemd
  - Using very lightweight DE
- [Nitrux](https://nxos.org/)
  - OpenRC instead of systemd  
  - KDE Plasma
  - [NX Desktop](https://nxos.org/english/nxd/) is a customization layer for Plasma 5 by Nitrux
- [Devuan](https://www.devuan.org/)
  - Debian with SysVinit instead of Systemd

## Ubuntu actual

- [Ubuntu](http://www.ubuntu.com/) *Popular*
  - Most Popular Linux Distro #1 (From 2004 through 2022 at least)
  - Ubuntu pulls packages from Debian "Sid" Unstable and Debian Testing
  - Uses Gnome as their official DE (briefly used Unity)
  - United Kingdom, London & Isle of Man, USA
  - Ubuntu is massively popular because Canonical took a snapshot of Debian testing and made it easy to install and use at a time when Debian was the opposite of easy to install.
  - I have used this distro non-stop since 2006, it has been installed on nearly every computer I own, I have used it for work and personal, and I have always come back to it after a bout of distro hopping, until version 21.04
  - The Good
    - The Ubuntu 6-month point release cadence is very nice compared to the Debian 2-year point release cadence
      - This 6-month cadence makes Ubuntu extremely attractive to those who consider Debian's 2-year cadence to be too infrequent
    - Ubuntu is a high quality distribuion that will work on most computers with most hardare and will experience few bugs
    - There is a lot of training material online for Ubuntu
    - Ubuntu server is excellent
  - The bad
    - I fear that Canonical has lost focus on keeping Ubuntu competitive as a desktop and laptop distro
    - The canonical installers are barely functional, yet they refuse to adopt Calamares
    - The installers previously support more advanced filesystems and alternative install techniques, but now can barely handle the most basic requests
    - Ubuntu is continually losing popularity to other distros that are putting more attention into their product than Canonical is

## Ubuntu Flavors

- [Derivatives of Ubuntu](https://wiki.ubuntu.com/DerivativeTeam/Derivatives) (nearly everything on the list below)
- [Ubuntu Flavors](https://ubuntu.com/desktop/flavours) Official flavors
  - [Kubuntu](https://kubuntu.org/) *Popular*
    - KDE Plasma DE
    - This is the best version of Ubuntu
    - Should be switching to Calamares installer soon
  - [Ubuntu Studio](https://ubuntustudio.org/) Multimedia focused
    - KDE Plasma DE with nice themeing
    - This is a really awesome distro to install and immediately get an A/V workstation
    - Kernel modified to support low-latency for better audio usage
  - [Xubuntu](https://xubuntu.org/) XFCE
  - [Lubuntu](https://lubuntu.net/) LXDE/LXQT
  - [Ubuntu Cinnamon](https://ubuntucinnamon.org/) Cinnamon
  - [Ubuntu MATE](https://ubuntu-mate.org/) Mate
  - [Ubuntu Budgie](https://ubuntubudgie.org/) Budgie
    - Budgie DE (from Solus) but based on Ubuntu
    - looks just like MacOS
  - [Ubuntu Unity](https://ubuntuunity.org/)
    - Unity 7 with Yaru
- Ubuntu community remixes (Unofficial flavors)
  - [Ubuntu DDE](https://ubuntudde.com/)
    - Deepin DE without using Chinese Deepin OS
    - I tried version 22.04 and it had [stability problems](https://www.debugpoint.com/ubuntudde-remix-22-04-review/)

## Downstream of Ubuntu

- [Linux Mint](https://linuxmint.com/) *Popular*
  - Most Popular Linux Distro #2 after Ubuntu
  - Downstream of Ubuntu LTS (long-term support)
  - Cinnamon developer
  - This is the most refined Linux distro in the Debian/Ubuntu ecosystem, and among the very best amongst all Linux distros.
  - This distro could be called "Ubuntu configured properly and with a better desktop environment"
  - I have tested this distro many times over the past 10 years, most recently 2022, and i find that i like the cinnamon desktop a lot.  it is simple, clean, attractive, functional.  
  - with gTile I am able to customize window grid snapping.
- [LMDE (Linux Mint Debian Edition)](https://www.linuxmint.com/download_lmde.php)
  - Is downstream of Debian instead of Ubuntu
  - Cinnamon default
  - Continues to improve in quality.  As of 2023 is considered good enough to use as a daily use distro.
  - [Needs some tuning to work nicely](https://linuxmint.com/rel_elsie.php)
- [Pop!_OS](https://pop.system76.com/) *Popular*
  - Gnome default
  - Supports almost every type of [desktop](https://support.system76.com/articles/desktop-environment/)
  - Good for graphics cards.  Two ISO's: AMD vs Nvidia. [roadmap](https://support.system76.com/articles/roadmap/)
  - [Documentation](https://support.system76.com/#pop)
  - I tested this distro multiple times, 2022 most recently, they do some things very well, especially concerning proprietary drivers.  
  - I found the Pop desktop to be distracting and annoying on Gnome, and awful on KDE plasma; perhaps i need more time to understand the desktop.
  - Some people love this distro, others (like me) greatly dislike it
- [KDE Neon](https://neon.kde.org/index) *Underrated*
  - based on Ubuntu LTS
  - From KDE for "the best" KDE experience
  - KDE Plasma on Wayland by default
  - Calamares installer
  - The first distro with KDe Plasma 6 support
  - Some people report issues with the installation
- [Zorin OS](https://zorin.com/os/)
  - Beautiful alternative to MacOS and Win10
  - Gnome or Xfce
  - Ireland
  - There is a paid support "Pro" version available
- [Elementary OS](https://elementary.io/)
  - Beautiful alternative to MacOS and Win10
  - Panthea Desktop
- [PureOS](https://pureos.net/)
  - Fully Auditable Operating System
  - Offered with Purism laptops
- [Regolith](https://regolith-desktop.com/)
  - Do i3wm tiling window management on Ubuntu and keep Gnome in the back pocket
  - I tested this distro.  It is a good way to learn how i3wm works while inside a familiar Ubuntu experience.
- [Bodhi](http://www.bodhilinux.com/)
  - Moksha WM
- [Feren OS](https://ferenos.weebly.com/)
  - Downstream of Debian and Ubuntu (previously downstream of Mint)
  - Clamares installer
  - KDE Plasma
  - United Kingdom
  - I never tried this, but it could prove a useful way to install Ubuntu
- [Tuxedo OS](https://www.tuxedocomputers.com/en/TUXEDO-OS_1.tuxedo)
  - [Downstream of Ubuntu/Kubuntu](https://www-tuxedocomputers-com.translate.goog/de/Infos/Hilfe-Support/Haeufig-gestellte-Fragen/Was-unterscheidet-TUXEDO-OS-von-Ubuntu/Kubuntu-_1.tuxedo?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp)
  - KDE Plasma default
  - Designed for Tuxedo Hardware but works on other hardware
  - Calamares installer, no snap, Firefox is DEB not snap
  - This distro has potential
  - [download](https://os.tuxedocomputers.com/)
- [Slimbook OS](https://slimbook.es/en/tutoriales/aplicaciones-slimbook/438-slimbook-operating-system)
  - Downstream of Ubuntu/Kubuntu
  - Designed for Slimbook Hardware

## Downstream of Ubuntu but not using DEB packaging

- [Rhino Linux](https://rhinolinux.org/)
  - Downstream of Ubuntu but somehow they made it a rolling release
  - Xfce only at this time
  - Using Pacstall (The AUR for Ubuntu)
