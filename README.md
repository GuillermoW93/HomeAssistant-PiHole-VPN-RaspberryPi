# Raspberry-Pi
> Docker containers on Raspberry Pi.

![](header.png)

## Installation

Make sure to have a new/clean Raspberry Pi instance:

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
_For more examples and usage, please refer to the [Wiki][wiki]._

## Release History

* 0.1.0
    * The first proper release
    * CHANGE: added README.md
* 0.0.1
    * Work in progress

## Meta

Distributed under the XYZ license. See ``LICENSE`` for more information.

[https://github.com/yourname/github-link](https://github.com/GuillermoW93/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request