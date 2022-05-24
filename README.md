ansible-module-grub
===================

A module to modify grub configurations (grub 1 & 2)

Examples
---------

Add/Change root=/dev/sda1 to the kernel line(s)

grub: koption=root kvalue=/dev/sda1

Remove the quiet kernel option

grub: state=absent koption=quiet

Set the default boot stanza to 0

grub: default=0

Change the grub wait timeout to 15

grub: timeout=15


TODO
-----

- Test on grub 0.97 & previous on RHEL-like systems
- Test on any non-RHEL-type system
