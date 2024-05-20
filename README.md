# vaio-ux-dotfiles
Collection of files to make vaio ux more operational.

# List of contents

## Breeze-Dark-Light-Lxqt-Ob.tar.gz

Breeze dark for Lxqt.

## mouse.tar.gz

Modified kernel PS/2 driver to disable annoying drag on the pointer stick. Didn't really use it as its for kernel 3 and currently we have like <insert kernel version here>. I might apply the patches on newer kernel in the future though. Leaving for archival purposes.

## r5u870-0.3.2.tar.gz

Firmware for the camera. Sadly despite firmware being loaded, `/dev/video0` does not pop up. From what I've seen it's due to driver support missing but I could also mess up something. Leaving for archival purposes

## vaiofand-0.10.1.tar.xz

Fan control software. Although if you wanna use something else you simply need to wrte to sysfs. Leaving for archival purposes.

## /etc/udev/rules.d/99-touch.rules

Touch calibration. Your values might be different.

## /etc/udev/rules.d/99-zram.rules

You NEED zram on this bad boi.

## /etc/systemd/system/vaiofand.service

From the vaiofand software.

## /etc/systemd/system/zram.service

Another zram piece.

## /etc/modprobe.d/zram.conf

zram module parameters

## /etc/modules-load.d/zram.conf

Actually loading zram module.

## /etc/vaiofand.conf

Changed max and cooled temperatures, otherwise it was burning my hand.
