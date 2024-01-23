# GPU (Graphical Processing Unit) Hardware

- The GPU (Graphical Processing Unit) used in a computer will affect your enjoyment of Linux
- My recommendation is to avoid using an Nvidia GPU if at all possible

## How the GPU is included in a system makes a difference

- Integrated = In the same package as the CPU
  - This is the best experience
- Discrete = Is a separate chip or PC board that communicates with the CPU over PCIe
  - Usually a good experience
- Hybrid - Both of the above
  - Used by laptops
  - Switches between integrated and discrete
  - Most common with an Intel or AMD CPU paired with a discrete GPU from Nvidia or AMD
  - Can be a nightmare to configure properly
  - Can cause stability issues
  - Very few distro's are able to support this

## The GPU supplier makes a big difference

- AMD is excellent!  Fully open source drivers.
- Intel is excellent!  Fully open source drivers.
- Nvidia is a nightmare.  Their drivers are not open source and thus must be installed separately.
- ARM is okay.  Fully open source drivers.
