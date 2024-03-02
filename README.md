# Raspberry-Pi
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

## Release History

* 0.0.1
    * Initial release
* 0.0.2
    * CHANGE: added README.md