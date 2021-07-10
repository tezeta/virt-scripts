# virt-scripts
A collection of scripts used to automate CPU pinning and safe suspend/shutdown of the host system when VFIO is in use. Do not just copy and paste these scripts. In particular, the qemu hook will require modifications based on your CPU topology. 
To be used with elogind and libvirt. Requires https://pypi.org/project/vfio-isolate/ for core isolation.

    pip3 install vfio-isolate

