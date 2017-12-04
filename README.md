# lsnse
Quick search for nmap NSE scripts

I was a bit tired of searching all the time for nmap NSE scripts so I made a small tool to help me doing this quicker.
It basically list all files matching your search pattern and then display the first line of description of each NSE script found.

Feel free to take a look at this little thing and share your ideas/improvements :)

![screenshot](https://raw.githubusercontent.com/netro/lsnse/master/lsnse.png)


# Installation
This is a quick-and-dirty how to but you will get the idea :
```
sudo wget -O /usr/bin/lsnse https://raw.githubusercontent.com/netro/lsnse/master/lsnse
sudo chmod 755 /usr/bin/lsnse
sha256sum /usr/bin/lsnse

```
You should check the commands you copy/paste to your terminal and you should check the signature of the file.
There is no check for update feature so be aware this tool might be improved over the time.
Here is the SHA256 signature of the file : 4e5361d52ca15caab7279f46b88001e2f608649cb6a18f0d280af83fcfa6cc39

# TODO List
 - Manage no results
 - Manage the ^ char for searches only begining with pattern
 - Magage finding path of scripts folder
 - Manage search through description only (i.e. CVE for http ASA) with new option


   
