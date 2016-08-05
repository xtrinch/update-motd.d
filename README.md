# MOTD bash scripts

## Requirements
- fortune, cowsay

## Displays:
 -  distribution info
 -  last login
 -  system load
 -  ip
 -  uptime
 -  memory usage
 -  disk usage
 -  swap usage
 -  number of active ssh sessions
 -  number of processes, total and owned by user

## Installation (debian jessie)
- remove /etc/motd and symlink dynamic motd with ln -s /var/run/motd /etc/motd
- remove default "last login" text in /etc/ssh/sshd_config
- install lsb_release, fortune and cowsay via apt-get or aptitude
- copy/clone files into /etc/update-motd.d/

## Screenshot

<img src='https://raw.githubusercontent.com/xTrinch/update-motd.d/master/motd-screenshot.PNG' alt='motd screenshot'>
