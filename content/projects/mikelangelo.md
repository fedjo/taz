+++
date = "2019-06-18"
title = "Mikelangelo"
tags = [
    "mikelangelo",
    "vps",
    "okeanos",
    "grnet",
]
categories = [
    "Services",
    "operations",
]
series = ["Setup Space", "Cloud"]
+++

## Who is *mikelangelo*

Mikelangelo is a Virtual Private Server hosted on [~okeanos](https://okeanos.grnet.gr/home/)
cloud infrastructure. This service is provided by Greek National Network,
Cloud Computing and IT infrastructure and services provider, [GRNET](https://grnet.gr/en/company/).

Mikelangelo operates on GNU/Linux Debian Stretch with kernel version 4.9.0-8-amd64

## The infrastructure consists:

1. 2 x CPU cores
2. 4096 MB RAM memory
3. 20 GB Boot disk (also /dev/vda1) mounted on /
4. 80 GB Data disk (also /dev/vdb) mounted on /data

## Network

### IPv4

83.212.102.18  (Public IPv4 Network)

### IPv6

2001:648:2ffc:1225:a800:ff:fe8f:5394  (Public IPv6 Network)

## What *mikelangelo* serves

* [Etherpad](83.212.102.18:9002) at port 9002
* [Deluge](83.212.102.18.8112) at port
* Tor Relay Node at port
* [World of The News project](83.212.102.18/wof) (WOF) at port 80
* OpenSSH server at port 22
* OpenVPN server at port 1194

## Future thougths about *mikelangelo*

