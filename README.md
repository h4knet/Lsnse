# lsnse [![Github All Releases](https://img.shields.io/github/downloads/h4knet/lsnse/total)](https://github.com/h4knet/lsnse/releases/latest/download/lsnse)
Quick search for nmap NSE scripts

I was a bit tired of searching for nmap NSE scripts so I made a small tool to help me doing this quicker.
It basically list all files matching your search pattern and then display the first line of description of each NSE script found.

![screenshot](https://raw.githubusercontent.com/netro/lsnse/master/lsnse.png)


### Installation
A quick how-to:
```
sudo wget -O /usr/local/bin/lsnse https://github.com/h4knet/lsnse/releases/latest/download/lsnse
sudo chmod 755 /usr/local/bin/lsnse
```
There is no check for update feature so be aware this tool might be improved over time.

### Usage examples
```
lsnse ntp
lsnse cisco
lsnse smtp
```

### TODO List
 - Manage no results
 - Manage the ^ char for searches only begining with pattern
 - Magage finding path of scripts folder
 - Manage search through description only (i.e. CVE for http ASA) with new option
