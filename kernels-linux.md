# Linux Kernels

- Distributions customize the kernel for their use, and do a very good job of it
- The Linux kernel can be custom built by the end user or by the distro maintainer
- In my experience the kernel is already highly optimized and any successful attempts to customize the kernel will result in an improvement in one area while other areas will see a regression.

## Interesting articles

- [Canonical specifies what they offer](https://ubuntu.com/kernel/variants)
- [Manjaro is amazing in how they let the user select a kernel](https://wiki.manjaro.org/index.php/Manjaro_Kernels)
- [Phoronix performance tests](https://www.phoronix.com/review/xanmod-liquorix-510) on XanMod, Liquorix, and default kernels, focused on throughput and not on system responsiveness

## The usual type of kernels from most Linux distributions

- Stable = The latest stable kernel
- LTS = The latest long term support kernel
- Hardened = Stable with upstream security patches
- Low-Latency = Not quite real-time but does a good job making the system more responsive
- Real-Time = Guaranteed improvement and jitter on service time

## Customized Linux kernels

- [Xanmod](https://xanmod.org/)
  - stable, responsive and smooth desktop experience.
- [Zen Kernel](https://github.com/zen-kernel/zen-kernel)
  - tuned for performance
  - aimed at improving performance of desktops at the cost of throughput and power usage
  - low latency and high-frequency scheduling.
- [Liquorix](https://liquorix.net/)
  - desktop, multimedia, and gaming workloads.
  - Liquorix was created as a way for desktop Debian users to run a low-latency, desktop-optimized kernel based on the Zen kernel sources.
  - [Info](https://blog.desdelinux.net/en/liquorix-kernel-mejores-kernels-distro-linux/)
- [linux-ck](http://repo-ck.com/)
  - CPU-specific & optimized linux-ck packages for Arch Linux
