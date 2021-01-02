# bash scripts

[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

(Ubuntu tested >=18.04)

Compatible with [Basher](https://github.com/basherpm/basher)

# Details

Sometimes using several monitors on Nvidia drivers can lead to flickering and black repaints.

There is a bug on the Nvidia drivers and the screen don't get repainted and thus black screen on some windows.

## Bugs listed

- https://forums.developer.nvidia.com/t/screen-randomly-flickers-flashes-to-black-on-kubuntu-18-04-with-nvidia-rtx-2080ti-and-driver-435-21/82500/2

# Troubleshoot

If you experience login manager black screen, you might need this [package](https://github.com/gnud/bash-fix-ssdm-login)

# Usage

You can launch this script using:

- Alt + F2 run command (krunner)

If for some reason this script is not availabe, just type: ```kwin --replace``` and then launch the script from somewhere

- Using Desktop Launcher and run it via plasma application menu

- Launching it in Dolphin or any other File manager

- From virtual console, but it will leave kwin to print to STDOUT, but use this in case of emergency, afterwards run the script from Dolphin

Don't forget to use DISPLAY=:0 fix-kwin-nvidia
