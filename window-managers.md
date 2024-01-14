# Window Managers

A window manager is system software that controls the placement and appearance of windows within a windowing system in a graphical user interface.

- [What kinds of window managers are there?](https://askubuntu.com/questions/65083/what-kinds-of-desktop-environments-and-shells-are-available)

## There are 3 types of window managers

- [Compositing](https://en.wikipedia.org/wiki/Compositing_window_manager)
  - This is the standard type used for most Desktop Environments
  - Provides applications with an off-screen buffer for each window
  - Compositing window managers can offer [Grid Tiling](grid-tiling.md) as an extension
- [Stacking](https://en.wikipedia.org/wiki/Stacking_window_manager) AKA Floating
  - Draws and allows windows to overlap without using a compositing algorithm
  - For low-end hardware
- [Tiling](https://en.wikipedia.org/wiki/Tiling_window_manager)
  - For people (mostly developers) who demand fast window tiling on multiple monitors
  - "tile" the windows so that none are overlapping
  - They usually make very extensive use of key-bindings and have less (or no) reliance on the mouse
  - Tiling window managers may be manual, or offer predefined layouts, or both
  - [Comparison of tiling window managers](https://wiki.archlinux.org/title/Comparison_of_tiling_window_managers)

## Compositing Window Managers

- [KWin](https://en.wikipedia.org/wiki/KWin)
  - Used by KDE Plasma and many others
- [Mutter](https://en.wikipedia.org/wiki/Mutter_%28software%29)
  - Used by Gnome 3
  - Replaced Metacity
- Xfwm
- Enlightenment
- [Compbiz](https://en.wikipedia.org/wiki/Compiz)
  - Not popular anymore?
- Metacity
- Muffin
- SurfaceFlinger
  - Android
- Quartz
  - Apple MacOS
- Desktop Window Manager
  - Microsoft Windows

## Stacking Window Managers

- [OpenBox](https://en.wikipedia.org/wiki/Openbox)
  - Used by LXDE and LXQt
- [IceWM](https://ice-wm.org/)
  - Lightweight and customizable
  - Text file configurable
- FluxBox
- AfterStep
- Motif

## Tiling Windows Managers

Tiling Window Managers come in three types

- Manual
- [Dynamic](https://en.wikipedia.org/wiki/Dynamic_window_manager)
- Hybrid

### Manual Tiling WMs

- [i3 improved tiling WM](https://i3wm.org/)
  - Supports X11 only
  - can be installed preconfigured on ubuntu with [Regolith](https://regolith-desktop.com/)
  - Most recommended for first time users to manual tiling WMs
  - Uses a tree data structure
- [i3-gaps](https://github.com/Airblader/i3)
  - Is a fork of i3 with gaps and some other features
- [Sway](https://swaywm.org/)
  - Is a drop-in replacement for i3wm that runs on Wayland instead of X11
  - Sway allows you to arrange your application windows logically, rather than spatially
- [Herbstluftwm manual tiling WM](https://herbstluftwm.org/)
  - X11 only
  - [github](https://github.com/herbstluftwm/herbstluftwm), [tutorial](https://herbstluftwm.org/tutorial.html), configured with text file
- [Ratpoison](https://www.nongnu.org/ratpoison/)
  - Configured with text

### Dynamic Tiling WMs

- [Awesome](https://awesomewm.org/)
  - supports both tiling and stacking
  - dwm derivative
  - scripted in Lua scripting language
- [dwm](https://dwm.suckless.org/) (dynamic window manager)
  - tiled, monocle, and floating layouts
  - no Lua (thankfully)
  - customized by editing source code thus keeping userbase small and elitist
- [qtile](http://www.qtile.org/)
  - X11 & Wayland support
  - Written and scripted in Python
- [SpectrmWM](https://github.com/conformal/spectrwm)
  - X11 only?
  - based on xMonad and DWM
  - configured with text
- [xMonad](https://xmonad.org/)
  - X11 only?
  - Configured with the Haskel language
  - Forked by leftwm and spectrwm
- [wmii](https://github.com/0intro/wmii)
  - X11 only?
- [Hyprland](https://hyprland.org/)
  - Wayland
  - New and gaining in popularity
  - Written in C++ and based on the wlroots library

### Hybrid Tiling WMs

- [bspwm](https://github.com/baskerville/bspwm)
  - X11 only?
  - represents windows as the leaves of a full binary tree.
  - Most recommended for experienced users
