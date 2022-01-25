Run the emulation with:

 qemu-system-m68k -M virt -kernel output/images/vmlinux -initrd output/images/rootfs.cpio.xz -append "console=ttyGF0" --nographic # /qemu_m68k_virt_petitboot_defconfig

The petiboot menu will appear in the terminal where QEMU has been started.
