# Raspberry-Pi with HomeAssistant/PiHole/VPN
> Installation guide for running Docker Containers e.g. on Raspberry Pi.

![](header.png)

## Installation

Prerequisites:
1. Make sure to have a new/clean Raspberry Pi instance:
2. Have an SD-card ~32GB min.
3. Follow these steps below:

```sh
https://www.raspberrypi.com/software/ 
```

```sh
Download Raspberry Pi Imager > Choose OS: "Raspberry Pi OS Lite"
```

```sh
Connect SD Card to the PC and make sure to create "SSH" file on boot partition of the SD Card. 
```

```sh
Login to Raspberry Pi and issue && sudo apt-get install docker
```

```sh
sudo apt-get install git
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com 
git clone https://github.com/GuillermoW93/Raspberry-Pi
```

## Usage example

Next, run the playbooks from my GitHub Repository to have 'HomeAssistant and Unifi Network' available. 

```sh
sudo docker run -d --restart=always --name="home-assistant" -e "TZ=Europe/Amsterdam" -v /home/docker/home-assistant:/config --net=host homeassistant/raspberrypi4-homeassistant:stable
```

```sh
docker run -d --restart=unless-stopped --init -p 8080:8080 -p 8443:8443 -p 3478:3478/udp -p 10001:10001/udp -e TZ='Europe/Amsterdam' -v /opt/unifi:/unifi --name unifi jacobalberty/unifi
```
## Release History

* 0.0.1
    * Initial release
* 0.0.2
    * CHANGE: added README.md
    * CHANGE: P1Monitor, PiHole & HomeAssistant
