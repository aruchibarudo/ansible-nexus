*********************************
LibVirt driver installation guide
*********************************

Requirements
============

* Configure libvirt

ansible modules
----
* ansible.posix
* community.crypto
* ansible.netcommon
* community.general

python modules
----
* libvirt-python

apt pkg
---
* libvirt-dev

ubuntu
---
dpkg-statoverride --update --add root root 0644 /boot/vmlinuz-`uname -r`

Install
=======

