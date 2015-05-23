HTPC Guides Media Server for ARM Devices
========================

![SOHO server](http://www.igorpecovnik.com/wp-content/uploads/2014/11/sohoserver1.png)

Samba, TV headend, BitTorrent Sync, SoftEther VPN server, CUPS, scanner + buttons + OCR, Temper, Rpimonitor + 3 additional sensors, Transmission, ISPConfig  (Apache2 or NginX, PHP, Mysql with phpMyAdmin, Postfix, Dovecot)

Project realisation:
[http://www.igorpecovnik.com/2013/12/10/micro-home-server/](http://www.igorpecovnik.com/2013/12/10/micro-home-server/)

Tips:
- mail server install (ISPConfig) will work **only with Debian Wheezy**
- set fixed ip address
- for those who use ramlog. You can enable ramlog back when installation is finished
- installation is based on [http://www.howtoforge.com/perfect-server-debian-wheezy-nginx-bind-dovecot-ispconfig-3](http://www.howtoforge.com/perfect-server-debian-wheezy-nginx-bind-dovecot-ispconfig-3)

HTPC Guides Media Server Installation
------------------

```shell
sudo apt-get -y install git
cd ~
git clone https://github.com/igorpecovnik/Debian-micro-home-server
chmod +x ./Debian-micro-home-server/install.sh
cd ./Debian-micro-home-server
sudo ./install.sh
```

Donate to Igor's project
------------------

[![Paypal donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CUYH2KR36YB7W)

![My bitcoin address](http://www.igorpecovnik.com/wp-content/uploads/2014/10/bitcoinigor.png)

17vT6hV83EQ6rizbWeasfy1tWEzFpzYqEE
