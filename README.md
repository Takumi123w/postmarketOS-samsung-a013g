# postmarketOS-samsung-m013f
Device and Kernel Packages for Galaxy M01/A01 Core devices to boot postmarketOS
These packages can be used with pmbootstrap to build kernel and rootfs to boot postmarketOS
in Galaxy M01/A01 Core devices.

# Status
Things working :
1.Currently xfce4 can be used as GUI other desktop-environments aren't working. Because there are no userspace GPU drivers.
2.USB networking.
3.Charging
4.OTG
5.Display
6.Storage/SD card booting.
7.Touchscreen

# How to Install
Install pmbootstrap using your package manager or see postmarketOS porting guide.

Copy "device-samsung-m013f" and "linux-samsung-m013f" to /path/pmbootstrap/cache_git/pmaports/device/testing; Where /path is Where you cloned pmbootstrap sources, default is /home/your_username/.local/var.

After copying packages, Open terminal and use following commands :
pmbootstrap init
Select edge as os vresion
select samsung as manufacture
type m013f as device.
Then Complete other steps.
To buid run :
pmbootstrap install
