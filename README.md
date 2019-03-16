Easy-LAMP-Installation on Ubuntu
===========================

This shell script will install (and uninstall) the LAMP Stack automatically on Ubuntu OS

How to use it:
-------------

Download the following shell script on your Ubuntu server or clone it with the following command.

```
git clone https://github.com/nawazm/Easy-LAMP-Installation.git
```
Give the execution right to it.
------------------------------
```
chmod +x install.sh
```

OR

```
chmod +x install7.2.sh
```

Then to install latest PHP version run it as sudo user.
-------------------------
```
sudo ./install.sh
```

for PHP7.2, go with install7.2.sh
-------------------------
```
sudo ./install7.2.sh
```

How to uninstall:
-------------

Give the execution right to it.
------------------------------
```
chmod +x uninstall.sh
```
Then run it as sudo user.
-------------------------
```
sudo ./uninstall.sh
```