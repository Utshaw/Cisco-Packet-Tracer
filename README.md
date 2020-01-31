# Cisco-Packet-Tracer
"Cisco Packet Tracer is an innovative network simulation and visualization tool. This free software helps you to practice your network configuration and troubleshooting skills via your desktop computer or an Android or iOS based mobile device." [Ref: [Packet tracer course](https://static-course-assets.s3.amazonaws.com/I2PTNet11/en/index.html#1.1.1.1)]
## Installation
### Ubuntu-19.10
- Install libdouble-conversion1 manually from `https://packages.debian.org` site Example: [2.0.1-4 version](https://packages.debian.org/stretch/amd64/libdouble-conversion1/download)
- Install qt-at-spi manually from `https://packages.debian.org` site Example: [0.4.0-5 version](https://packages.debian.org/stretch/amd64/qt-at-spi/download)
- If there is an error from the last step says:
```
qt-at-spi:amd64 depends on libqt4-dbus (>= 4:4.8.0); however:
Package libqt4-dbus is not installed.
qt-at-spi:amd64 depends on libqtcore4 (>= 4:4.8~); however:
Package libqtcore4 is not installed.
qt-at-spi:amd64 depends on libqtgui4 (>= 4:4.8~); however:

``` 
Install the dependencies using command: 
```
sudo apt install libqt4-designer libqt4-opengl libqt4-svg libqtgui4 libqtwebkit4
```
- Download packet tracer from [Cisco Packet Tracer official site](https://www.netacad.com/portal/resources/packet-tracer)
- Use command `sudo dpkg -i `

## Introduction
- For each intermediate devices (routers, switches) two types of configurations are there. CLI and GUI based
- Some of the end devices (PC and laptops) provide desktop interface that gives access to IP configuration, wireless configuration, command prompt etc. 