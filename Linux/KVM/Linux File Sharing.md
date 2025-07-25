1. add Filesystem to VM
2. Start VM
3. Create local mountpoint
	- mkdir -o /home/clayton/host-share
4. Modify fstab
```
sudo vim /etc/bash
```
5. Mount all filesystems
6.
	- Add:
	```
	
	host-share      /home/clayton/host-share        virtiofs        defaults        0 0
	
```


		
5. 
	``` bash
sudo mount -a
```
sudo mount -a
5. Change ownership of shared folder 
	- sudo chown clayton:clayton /home/clayton/host-share 
