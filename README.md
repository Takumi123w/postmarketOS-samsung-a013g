# postmarketOS-samsung-a013g
Device and Kernel Packages for Galaxy M01/A01 Core devices to boot postmarketOS
These packages can be used with pmbootstrap to build kernel and rootfs to boot postmarketOS
in Galaxy M01/A01 Core devices.

# Status

Stuck for a013g idk why

# How to Install
Install pmbootstrap using your package manager or see postmarketOS porting guide.

Copy "device-samsung-a013g" and "linux-samsung-a013g" to /path/pmbootstrap/cache_git/pmaports/device/testing; Where /path is Where you cloned pmbootstrap sources, default is /home/your_username/.local/var.

After copying packages, Open terminal and use following commands :

pmbootstrap init

Select edge as os vresion

select samsung as manufacture

type m013f as device.

Then Complete other steps.

To buid run :

pmbootstrap install
