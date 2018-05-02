# Infrastructure
This is a small set of ansible scripts to set up and maintain a small infrastructure.

It includes stuff for:
- SSH
- NTP
- DNS
- Mail MX
- 802.1X

## Introduction
These plays can be used as inspiration when setting up a small infrastructure with 
basic services like SSH, DNS, NTP and so on. Please note that many of the plays need
external stuff to really work.

### SSH


### NTP
Basically just a template for ntp.conf that uses a pre defined list of servers.

### DNS
Currently only configures nsd slaves to serve pre defined zones and receive notifications from the master.

### Mail MX
Simple static configuration of postfix to relay mails for a list of pre defined domain names.

### 802.1X
Configures wpa_supplicant to authenticate wired connections using EAP-TLS

