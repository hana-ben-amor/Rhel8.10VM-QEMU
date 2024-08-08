command to run the qcow2 image inside output in wsl is : qemu-system-x86_64
-enable-kvm
-cpu host
-m 2048
-smp 2
-drive file=output/packer-rhel
