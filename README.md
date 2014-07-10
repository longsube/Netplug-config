Netplug-config
==============

Configuration file for Netplug on Ubuntu, useful for multi-NIC cloud configurations.

Instructions:
-------------

- Install netplug:
	sudo apt-git install netplug

- Download the following file and copy it to 
	/etc/netplug/netplug

That's it - your machine will detect network connects/disconnects and will update the interfaces file


Cloud image setup:
------------------
Assuming you started with a vanilla Ubuntu install, follow the instructions above and then:
- delete ~/.ssh/authorized_keys
- power off the instance
- Create an image/snapshot of the instance.

That's it - your image is ready.


