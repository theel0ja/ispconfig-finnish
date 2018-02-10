# ISPConfig Codes
There is my [ISPconfig](http://www.ispconfig.org) codes and translations.

## How to install Translation
Open terminal in your server (or use SSH)

Then use these commands:
```sh
cd /usr/local/ispconfig/interface/lib/lang/
mv fi.lng fi.lng.bak
wget http://raw.githubusercontent.com/theel0ja/ispconfig/master/fi.lng
# If everything went good, remove fi.lng.bak with this command:
rm fi.lng.bak
```
