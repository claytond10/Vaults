error: failed to commit transaction (conflicting files) linux-firmware-nvidia: /usr/lib/firmware/nvidia/ad103 exists in filesystem linux-firmware-nvidia: /usr/lib/firmware/nvidia/ad104 exists in filesystem linux-firmware-nvidia: /usr/lib/firmware/nvidia/ad106 exists in filesystem linux-firmware-nvidia: /usr/lib/firmware/nvidia/ad107 exists in filesystem Errors occurred, no packages were upgraded.

```bash
sudo rm -r /usr/lib/firmware/nvidia/ad10{3,4,6,7}
```

