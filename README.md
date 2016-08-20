ISPConfig Codes
=========
There is my ISPconfig (http://www.ispconfig.org) codes and translations.

How to install Translation
=========
Open terminal in your server (or use SSH)

Then use these commands:
```
user@yourserver:~$ cd /usr/local/ispconfig/interface/lib/lang/
user@yourserver:~$ mv fi.lng fi.lng.bak
user@yourserver:~$ wget http://raw.githubusercontent.com/theel0ja/ispconfig/master/fi.lng
user@yourserver:~$ # If everything went good, remove fi.lng.bak, with this command:
user@yourserver:~$ rm fi.lng.bak
```
