[Display Managers](https://wiki.archlinux.org/title/Display_manager)

an X display manager is a graphical login manager which starts a login session on an X server from the same or another computer.

- Graphical
    - [ssdm](https://en.wikipedia.org/wiki/Simple_Desktop_Display_Manager) (Simple Desktop Display Manager) = KDE default.
        - Used as default by KDE, Fedora, and LXQt.
        - Slightly better user interface
        - Recommended for Plasma and LXQt
    - [gdm](https://en.wikipedia.org/wiki/GNOME_Display_Manager) (GNOME Display Manager) = Gnome default.
        - Used as default by Gnome
        - Slightly easier to customize
    - LXDM (Lightweight X Desktop Environment Display Manager)
        - default for LXDE
    - [LightDM](https://en.wikipedia.org/wiki/LightDM)
        - Lighter and faster than gdm3
    - [XDM](https://en.wikipedia.org/wiki/XDM_%28display_manager%29) [(X Display Manager)](https://www.x.org/archive/X11R7.6/doc/man/man1/xdm.1.xhtml)
        - Xorg default.
    - [SLiM](https://github.com/iwamatsu/slim) (Simple Login Manager) for X11
        - Abandoned 9 years ago
- Console
    - [Ly](https://github.com/fairyglade/ly) - X11 & Wayland!!!
        - Lightweight TUI (ncurses-like)
        - Works with every display server
        - Works with X11 and Wayland
        - Recommended for use with i3wm
    - [CDM](https://github.com/evertiro/cdm) (Console Display Manager)
        - Written in Bash