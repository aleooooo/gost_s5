systemctl stop firewalld.service
systemctl disable firewalld.service
yum -y install gcc
yum -y install wget
wget https://github.com/ginuerzh/gost/releases/download/v2.11.1/gost-linux-amd64-2.11.1.gz
gunzip gost-linux-amd64-2.11.1.gz
mv gost-linux-amd64-2.11.1 /usr/bin/gost
chmod -R 777 /usr/bin/gost
nohup gost -L root:asd12345@0.0.0.0:443
