# Debian distributions

All the distributions listed on this page are either actually Debian or are downstream of Debian

- The package format is DEB
- The package managers are DPKG, APT, Aptitude

The most popular distributions on the page are

- Debian
- Ubuntu (including Kubuntu, Xubuntu)
- Linux Mint
- PopOS
- MX Linux
- Deepin
- Zorin OS

## Debian actual

- [Debian](https://www.debian.org/) 
  - The Source!
  - Oldest Linux Distro #2 after Slackware
  - First Linux Distro that was open for every developer to contribute, and is still the most significant non-commercial distributor of Linux
  - Has the largest team of volunteer contributors. 
  - There is corporate support for Debian, but no corporate ownership.
  - High quality documentation is readily available online.
  - All of the embedded Linux processors and boards that I support and use have Linux BSP’s that are ultimately derived from Debian, such as Rasberry Pi OS and NXP embedded linux.
  - The Debian official installer is the slowest installer I have ever used.  One simple installation took over 8 hours compared to 10 minutes for any other installer.
  - The Calamares installer used on the Live version of the Debian ISO is significantly better.
  - Debian insists on installer images being free software only, so important drivers are missing. This is extremely annoying and limits the ability of novices to successfully install this distro.  Unofficial installers are available with drivers though, but its not easy to identify them.  The Live version of the ISO provides drivers.
- Debian branches:
  - [Debian “Sid” Unstable](https://wiki.debian.org/DebianUnstable)
    - Rolling release
    - Bleeding-edge like Arch but slightly more stable
    - Ideal for developers
  - [Debian Testing](https://wiki.debian.org/DebianTesting)
    - Rolling release
    - Downstream of Debian Sid
    - Packages are still fairly fresh
    - Ideal for desktops
  - [Debian Stable](https://www.debian.org/)
    - THE MOST STABLE!
    - Point release, cadence is every 2 years
    - Downstream of Debian Testing
    - This is what most people use for desktop, and should be the only branch used on servers
    - [Debian Backports](https://backports.debian.org/) can keep Debian Stable feeling fresh for workstations

## Downstream of Debian

- [Siduction](https://siduction.org/)
  - Based on Debian "Sid" Unstable
  - Rolling release, Germany
  - KDE Plasma, Xfce, Lxqt
  - They write their own user [manual](https://manual.siduction.org/siduction-manual_en.pdf).  Their [github](https://github.com/siduction) stores the configuration and mods to offer to build their distro.
  - The installer is configured for Btrfs with Snapper rollback, all sitting on top of LUKS encryption.
  - This distro is nicely polished and I like it a lot.  I am running it on three of my computers.  
- [Spiral](https://spirallinux.github.io/)  Linux - *NEW AND PROMISING*
  - This is more of a Debian installer than an actual distro
  - Based on Debian stable but easily upgraded to Testing or Sid
  - Single developer previously maintained Gecko Linux and has switched to Debian from OpenSUSE
  - KDE Plasma, Cinnamon, Xfce, Gnome, etc
  - BtrFS + LUKS, Flatpack management through GUI, zRAM,
- [DebianEasy](https://debianeasy.github.io/)
  - Forked from Spiral, removed some default install apps
  - Can download the [ISO](https://sourceforge.net/projects/debianeasy-bookworm/files/2023_6_11/) or the [build system](https://github.com/DebianEasy/DebianEasy-iso)
  - This distro has potential but as of early 2024 the project is too sloppy to be taken seriously
- [Neptune](https://neptuneos.com/en/start-page.html)
  - Based on Debian stable, newer kernel, newer drivers, newer utilities, newer DE, persistent USB installer
  - KDE Plasma
  - Germany
  - I tested this in early 2023 and it is decent.  There are some nice KDE Plasma themes.  Install is okay.  
- [Sparky](https://sparkylinux.org/)
  - Poland
  - Stable and Testing
- [SolydXK](https://solydxk.com/)
  - Based on Debian Stable.  
  - Netherlands.
  - Originally started as Linux Mint Debian Edition with KDE Plasma DE
  - There are two flavors, KDE and Xfce
  - SolydK: KDE Plasma DE
    - I tried SolydK in 2023.  It had not been updated since 2021 and was based on the previously released debian distro, so it felt old.  default partitioning was strange, seperating home from root but using ext4 is not ideal.  at least it allowed me to use xfs filesystem or btrfs on the install, so that has some promise.   it ships with some interesting kde plasma themes which may be worth looking at.   I will not use this.
  - SolydX: Xfce nDE
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
- [Kali](https://en.wikipedia.org/wiki/Kali_Linux)
  - Downstream of Debian testing
  - For penetration testing.  always root
- [Armbian](https://www.armbian.com/)
  - Debian stable
  - For ARM aarch64
  - XFCE
  - I tested this distro on the Raspberry Pi4.  It is decent.
- [AntiX](https://antixlinux.com/)
  - For old computers
  - SysV instead of systemd
  - Using very lightweight DE
- [Nitrux](https://nxos.org/)
  - OpenRC instead of systemd.  
  - KDE Plasma
  - [NX Desktop](https://nxos.org/english/nxd/) is a customization layer for Plasma 5 by Nitrux.
- [Devuan](https://www.devuan.org/)
  - Debian with SysVinit instead of Systemd

## Ubuntu actual

- [Ubuntu](http://www.ubuntu.com/) - *POPULAR*
  - Ubuntu pulls packages from Debian Sid (Unstable) and Debian Testing
  - Most Popular Linux Distro #1 (From 2004 through 2022 at least)
  - Uses Gnome as their official DE (previously used Unity)
  - United Kingdom, London & Isle of Man, USA
  - Ubuntu is massively popular because Canonical took a snapshot of Debian testing and made it easy to install and use at a time when Debian was the opposite of easy to install. 
  - My thoughts
    - I have used this distro non-stop since 2006, it has been installed on nearly every computer I own, I have used it for work and personal, and I have always come back to it after a bout of distro hopping, until recently.
    - PROs: I respect Canonical and the work it has done in the past for Ubuntu, and I trust the quality (stability) of the Ubuntu product, and the focus on security.  These are very good reasons to use Ubuntu, especially in a corporate setting.
    - CONs: I feel that Ubuntu 20.04 was the pinnacle release, and every release afterwards has been a devolution.  Canonical has lost focus on keeping Ubuntu competitive as a desktop & laptop distro.  I feel that Canonical is focused on Ubuntu server (which is excellent) and services, and they use the desktop products to maintain their presence in the community. I do not like that modern filesystems are not easily supported by the installer (although it is possible to manually use them).  I feel that Ubuntu is sitting still technologically, while all other distros are adopting better methods (installer, filesystems, features). I also feel that Ubuntu is not a well polished distro, it seems roughly put together, compared to the more polished distros like Manjaro.
  - [Derivatives of Ubuntu](https://wiki.ubuntu.com/DerivativeTeam/Derivatives) (nearly everything on the list below)
- [Ubuntu Flavors](https://ubuntu.com/desktop/flavours) - Official flavors
  - [Kubuntu](https://kubuntu.org/) KDE Plasma - This is my favorite flavor of Ubuntu
  - [Lubuntu](https://lubuntu.net/) LXDE/LXQT
  - [Xubuntu](https://xubuntu.org/) XFCE
  - [Ubuntu Cinnamon](https://ubuntucinnamon.org/) Cinnamon
  - [Ubuntu MATE](https://ubuntu-mate.org/) Mate
  - [Ubuntu Budgie](https://ubuntubudgie.org/) Budgie 
    - Budgie DE (from Solus) but based on Ubuntu
    - looks just like MacOS
  - [Ubuntu Unity](https://ubuntuunity.org/)
    - Unity 7 with Yaru
    - [2022-10 is an official flavor of Ubuntu again](https://ubuntuunity.org/blog/ubuntu-unity-becomes-an-official-flavor/)
  - [Ubuntu Studio](https://ubuntustudio.org/) - Multimedia focused
    - KDE Plasma is default
    - Audio routing tools
    - Kernel modified to support low-latency for better audio usage
    - This is a decent distro
- Ubuntu community remixes - Unofficial flavors
  - [Ubuntu DDE](https://ubuntudde.com/)
    - Deepin DE without using Chinese Deepin OS
    - I tried version 22.04 and it had [stability problems](https://www.debugpoint.com/ubuntudde-remix-22-04-review/)

## Downstream of Ubuntu

- [Linux Mint](https://linuxmint.com/) - *POPULAR*
  - Downstream of Ubuntu LTS
  - Cinnamon developer
  - Most Popular Linux Distro #2 after Ubuntu
  - This is the most refined Linux distro in the Debian/Ubuntu ecosystem, and among the very best amongst all Linux distros.
  - This distro could be called "Ubuntu configured properly and with a better desktop environment"
  - I have tested this distro many times over the past 10 years, most recently 2022, and i find that i like the cinnamon desktop a lot.  it is simple, clean, attractive, functional.  with gTile I am able to customize window grid snapping. 
- [LMDE (Linux Mint Debian Edition)](https://www.linuxmint.com/download_lmde.php)
  - Is actually downstream of Debian instead of Ubuntu
  - Cinnamon default
  - [Needs some tuning to work nicely](https://linuxmint.com/rel_elsie.php)
- [Pop!_OS](https://pop.system76.com/) - *POPULAR*
  - Gnome default
  - Supports almost every type of [desktop](https://support.system76.com/articles/desktop-environment/)
  - Good for graphics cards.  Two ISO's: AMD vs Nvidia. [roadmap](https://support.system76.com/articles/roadmap/)
  - [Documentation](https://support.system76.com/#pop)
  - I tested this distro multiple times, 2022 most recently.  they do some things very well, especially concerning proprietary drivers.  i found the Pop desktop to be distracting and annoying on Gnome, and awful on KDE plasma; perhaps i need more time to understand the desktop. 
- [KDE Neon](https://neon.kde.org/index) 
  - Ubuntu LTS
  - From KDE for "the best" KDE experience
  - KDE Plasma on Wayland by default
  - Calamares installer
- [Zorin OS](https://zorin.com/os/) - *POPULAR*
  - Beautiful alternative to MacOS and Win10
  - Gnome or Xfce
  - Pro version is paid
  - Ireland
- [Elementary OS](https://elementary.io/)
  - Beautiful alternative to MacOS and Win10
  - Panthea Desktop
  - I tested this distro but I would not use it because it seems too simple for me
- [PureOS](https://pureos.net/)
  - Fully Auditable Operating System
  - Offered with Purism laptops
- [Regolith](https://regolith-desktop.com/)
  - Do i3wm tiling window management on Ubuntu and keep Gnome in the back pocket
  - I tested this distro.  It is a good way to learn how i3wm works while inside a familiar Ubuntu experience.
- [Bodhi](http://www.bodhilinux.com/)
  - Moksha WM, lightweight
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
  - Calamares installer, no snap, Firefox is DEB not snap, 
  - [download](https://os.tuxedocomputers.com/)
- [Slimbook OS](https://slimbook.es/en/tutoriales/aplicaciones-slimbook/438-slimbook-operating-system)
  - Downstream of Ubuntu/Kubuntu
  - Designed for Slimbook Hardware
- [Exton|OS](https://www.exton.net/?p=952) 
  - Downstream of Ubuntu LTS
  - KDE plasma 
  - Uses Calamares installer
  - Designed for Android development
- [Macbuntu](https://sourceforge.net/projects/macbuntu/) - EOL
  - looks like MacOS.  Uses Unity + heavy modification.  Has not been updated in 12 years.

## Downstream of Ubuntu but not using DEB packaging

- [Rhino Linux](https://rhinolinux.org/)
  - Downstream of Ubuntu but somehow they made it a rolling release
  - Xfce only at this time
  - Using Pacstall (The AUR for Ubuntu)

