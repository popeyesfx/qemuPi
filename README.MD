Virtualise a Raspberry Pi under Linux
==================================================

A Debian 9 virtual machine running in VMWare Fusion 8, in which QEMU v2 will run
a raspberry pi image.

GNU General Public License Version 2.0 <http://www.gnu.org/licenses/gpl-2.0.txt>

The example code using this library is released in the public domain.

Overview
--------
The included project notes are a step by step guide to installing and running the virtual machine.
Note: this project was developed on OSX 10.11 

Software Requirements
----------
VMWare Fusion 8.5.8 <https://www.vmware.com>

Debian 9 - debian-live-9.2.0-amd64-gnome.iso <https://www.debian.org>

Raspbian Stretch - 2017-09-07-raspbian-stretch-lite.zip <https://www.raspberrypi.org>

Qemu Kernel - kernel-qemu-4.4.34-jessie



Here is a video of how it looks
[![Runtext][run-vid]](http://youtu.be/OJvEWyvO4ro)




Credits
-----------
These are the sites i found helpful in this endeavour, many thanks to there writers.

<https://blog.agchapman.com/using-qemu-to-emulate-a-raspberry-pi/>
<http://nairobi-embedded.org/a_qemu_tap_networking_setup.html>
<https://www.raspberrypi.org/forums/viewtopic.php?t=45265>


[hub75]: ./img/hub75.jpg
[matrix64]: ./img/chained-64x64.jpg
[time]: ./img/time-display.jpg
[pp-vid]: ./img/pixelpusher-vid.jpg
[run-vid]: ./img/running-vid.jpg
[pixelpush]: https://github.com/hzeller/rpi-matrix-pixelpusher
[sparkfun]: https://www.sparkfun.com/products/12584
[ada]: http://www.adafruit.com/product/1484
[git-submodules]: http://git-scm.com/book/en/Git-Tools-Submodules
[emlid-rt]: http://www.emlid.com/raspberry-pi-real-time-kernel-available-for-download/
[rt-paper]: https://www.osadl.org/fileadmin/dam/rtlws/12/Brown.pdf