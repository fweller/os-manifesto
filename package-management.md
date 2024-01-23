# Package Management

[List of software package management systems](https://en.wikipedia.org/wiki/List_of_software_package_management_systems#Linux)
[Package Managers](https://en.wikipedia.org/wiki/Package_manager)
[Package Formats](https://en.wikipedia.org/wiki/Package_format)

## Distribution package formats

- [DEB](https://en.wikipedia.org/wiki/Deb_%28file_format%29) used in Debian (Ubuntu, Mint)
- [RPM](https://en.wikipedia.org/wiki/RPM_Package_Manager) used in Red Hat (Fedora) and SUSE
- [PKG.tar.zst](https://wiki.archlinux.org/title/pacman) used in Arch (Manjaro)
- [ebuild](https://wiki.gentoo.org/wiki/Ebuild) used in Gentoo, is just a test file with instructions on how to build

## Application package formats

These package formats can be added to any Linux distribution

- [Flatpak](https://en.wikipedia.org/wiki/Flatpak)
  - [Flathub](https://flathub.org/apps) is the app store
  - This is the most popular format
- [AppImage](https://en.wikipedia.org/wiki/AppImage)
  - [AppImage](https://appimage.github.io/apps/) is the attempt at an application store
  - This format is less popular
- [Snap](https://en.wikipedia.org/wiki/Snap_%28software%29)
  - [Snapcraft](https://snapcraft.io/store) is the application store
  - Owned by Canonical (Ubuntu)
  - Receives a lot of criticism but is actually a very good platform

## Package Manager Front Ends

- for [DEB](https://en.wikipedia.org/wiki/Deb_%28file_format%29)
    - [DPKG](https://en.wikipedia.org/wiki/Dpkg) (Debian Package) base 
    - [APT](https://en.wikipedia.org/wiki/APT_%28software%29) (Advanced package tool) core package manager
    - [Aptitude](https://en.wikipedia.org/wiki/Aptitude_%28software%29) front end for APT
    - Nala
- for [RPM](https://en.wikipedia.org/wiki/RPM_Package_Manager) (Red Hat Package Manager)
    - [YUM](https://en.wikipedia.org/wiki/Yum_%28software%29) (Yellowdog Update Manager) base
    - [DNF](https://en.wikipedia.org/wiki/DNF_%28software%29) (Dandified YUM) base, next gen from YUM
    - [ZYpp](https://en.wikipedia.org/wiki/ZYpp)  (Zen / YaST Packages Patches Patterns Products)
        - ZYpper is the command line interface for Zypp
    - [Urpmi](https://en.wikipedia.org/wiki/Urpmi) w/ rpmdrake - Mageia only
    - [Up2date](https://en.wikipedia.org/wiki/Up2date) - old Red Hat only
- For [PKG.tar.zst](https://wiki.archlinux.org/title/pacman) 
    - [Pacman](https://en.wikipedia.org/wiki/Arch_Linux#Pacman) (package manager)
- For [ebuild](https://wiki.gentoo.org/wiki/Ebuild)
    - [Portage](https://en.wikipedia.org/wiki/Portage_%28software%29#Emerge)
        - Emerge is the front end

Other package managers

- [Nix](https://nixos.org/) 
    - Purely functional package manager
- [GNU Guix](https://en.wikipedia.org/wiki/GNU_Guix) - BSD
- [Homebrew](https://en.wikipedia.org/wiki/Homebrew_%28package_manager%29) - MacOS
    - This package manager makes MacOS usable!  I have used it since 2015
- EOPKG (Evolve OS Package) is a fork of PiSi package manager

