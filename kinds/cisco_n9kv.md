# Cisco Nexus 9000v / n9kv

Folked from https://github.com/hellt/vrnetlab/blob/master/n9kv/README.md.

This is the vrnetlab docker image for Cisco Nexus 9000v virtual switch.


## Building the docker image

Put the .qcow2 file in this directory and run make docker-image and you should be good to go. The resulting image is 
called vr-n9kv. You can tag it with something else if you want, like my-repo.example.com/vr-n9kv and then push it to 
your repo. The tag is the same as the version of the NXOS image, so if you have nxosv.9.2.4.qcow2 your final docker 
image will be called vr-n9kv:9.2.4


## System requirements

* CPU: 4 core
* RAM: 10 GB
* Disk: <3GB

Usage
-----
```
docker run -d --privileged --device=/dev/net/tun -ti vrnetlab/cisco_n9kv:9.3.8

ssh vrnetlab@127.0.0.1
VR-netlab9
```