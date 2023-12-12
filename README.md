# Autoinstall Ajenti

Installing
Caution
Supported operating systems:

Debian 9 or later

Ubuntu Bionic or later

RHEL 8 or later

Other Linux-based systems might work, but you’ll have to use manual installation method.

# Installation

curl https://raw.githubusercontent.com/ajenti/ajenti/master/scripts/install.sh | sudo bash -s -

# Systemd
sudo systemctl stop ajenti.service

sudo systemctl disable ajenti.service

sudo systemctl daemon-reload

sudo rm -f /lib/systemd/system/ajenti.service

# SysVinit
/etc/init.d/ajenti stop

rm -f /etc/init/ajenti.conf

# Configuration files
If you don’t need it for later, just delete the directory 

/etc/ajenti/:

sudo rm -rf /etc/ajenti/

###
# Thank You. 
