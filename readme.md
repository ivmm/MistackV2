
apt-get install php7.1-fpm php7.1-common php7.1-dev php7.1-mysql php7.1-gd php7.1-bcmath php7.1-mcrypt php7.1-curl php7.1-xml php7.1-xmlrpc php7.1-dba php7.1-mbstring php7.1-intl php7.1-opcache -y
ln -s /etc/init.d/php7.0-fpm /etc/init.d/php7.1-fpm
systemctl daemon-reload

**本 REPO 为 Oneinstack 的一个 Patch**