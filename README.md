Repository to host Meizu Pro 5 (m86/turbo) non-free binaries.

Branch:
  ubports-ubtouch-16.04 - binaries sourced from UBPorts Ubuntu Touch images

Currently these files are distributed for download by UBPorts project which continues
Ubuntu Touch development after Canonical.

For Meizu m86 Linux Kernel version 3.10.100.

Most of original UBPorts (former Ubuntu) non-free software is currently distributed
from https://system-image.ubports.com/pool/ location as device images. Historically
server location and paths changed, still when updating it is the most stable
location to use directly or to search for. Some portion of non-free software is
contained in device-*.xz files. The software is packaged directly in
the file as well as in filesystem images found inside the file.
Other pieces of non-free software redistributed by UBPorts are located in
UBTouch packages. For example, fingerprint support is scattered across
device-*.xz:system/var/lib/lxc/android/system.img ext4 image and in biometryd-bin dpkg.

Original files used (sha512sum/name):
2d0923babd469422b967a0148ca2ae0f9f53e99a7ed4d6dd1de250c0f73423fe767b332592b0f6e97e34087305d9743a03e4d974cea84a6608ee416121d58f53  device-9362ef8ed39f89be39049802d33244d9f85ad9ebb29bd0b86411f544b0863fe7.tar.xz