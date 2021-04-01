# Sheikah-Slate

This is an early hardware prototype for a clustered computer which uses and replicates pinned DINARLY e-learning resources via IPFS.

This is inspired by communities who currently do not have a reliable internet connection, for example in mountainous regions. This solution would allow for those people to access e-learning resources regardless of having an internet connection.

This prototype is mostly using open source hardware. The eventual idea will be most likely to switch to a RISC-V AI accelerator in the future. It depends what happens in the future and what hardware is released.

In summary we have:

* A Docker Swarm cluster of 5 Raspberry Pi 4Bs networked together with an NVIDIA Jetson Nano (4GB).
* A Raspberry Pi 4B for receiving a satellite connection via a LimeSDR Mini.
* 28x 64-bit cores with 32GB (initial prototype) up to 52GB RAM and USB-C SSD.

The future hardware goals are to manufacture a single PCB with open source schematics. However, this will depend on the RISC-V hardware being released and subsequent licensing around that.

This repo is a work in progress.

![Prototype](/img/sheikah-slate-early-prototype.jpg)