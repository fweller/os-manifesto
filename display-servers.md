# Display Servers

A display server or window server is a program whose primary task is to coordinate the input and output of its clients to and from the rest of the operating system, the hardware, and each other. The display server communicates with its clients over the display server protocol, a communications protocol, which can be network-transparent or simply network-capable.

## List of Display Servers

- [X11 display WM](https://www.x.org/wiki/)
  - This is what nearly ever distro has been using for decades
  - X = [X Window System](https://en.wikipedia.org/wiki/X_Window_System))
  - X11 = [Version 11 of the X Window System](https://en.wikipedia.org/wiki/X_Window_System_protocols_and_architecture)
  - Xorg = [X.org](https://www.x.org/wiki/) = Open-source implementation of X
- [Wayland](https://wayland.freedesktop.org/)
  - This is the future display server that is intended to replace X.org
  - Xwayland  is  an  X  server  that  uses a Wayland Compositor as backend
- Mir
  - Was develoed by Canonical for the Unity Desktop Enviroment
  - Is mostly dead
- OpenGL ES
  - Used by Android
- Quartz Compositor
  - Used by Apple MacOS
