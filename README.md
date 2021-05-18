# Messor # - p2p IPS 
![Messor Network](https://messor.network/images/github_soc_banner.jpeg)

![GitHub repo size](https://img.shields.io/github/repo-size/messor-network/messor)
![GitHub all releases](https://img.shields.io/github/downloads/messor-network/messor/total)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/messor-network/messor)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/messor-network/messor)

## Overview ##
Messor is a set of scripts to detect and block various network attacks.
Hybrid P2P network with routing servers for collecting and exchanging a database of malicious IP addresses, and blocking them.
The main difference from other ids / ips is its network structure.
Connected sites form a single Messor-Network.
The network consists of clients, they are peers and routing servers. 
Each participant collects data about intruders and sends information to other network participants, which allows receiving daily updates of the database of malicious IP addresses.
The database also contains a regular expression for detecting attacks using UserAgent, get/post/cokie data and a list of traps (honeypot) for detecting scans.

## Installation
```shell
git clone https://github.com/messor-network/messor/
```

## Submitting bugs
You can report issues directly on Github, that would be a really useful contribution given that we lack some user testing on the project. 
Please document as much as possible the steps to reproduce your problem (even better with screenshots).
Reporting a bug: <https://github.com/messor-network/messor/issues>

## License



## ScreenShot
![Messor ScreenShot](https://messor.network/images/screenshot-1.png)
![Messor ScreenShot](https://messor.network/images/screenshot-2.png)
![Messor ScreenShot](https://messor.network/images/screenshot-3.png)


## Links
Official site:   [messor.network](https://messor.network/)

Documentatation: [doc.messor.network](https://doc.messor.network/)

Releases:        <https://github.com/messor-network/messor/releases>

Reporting a bug: <https://github.com/wwood-dev/messor/issues>
