1.CentOS 5.X standard without X-Windows.
Before you restore it you should backup some files.
/etc/resolv.conf
/etc/sysconfig/network
/etc/sysconfig/network-scripts/ifcfg-eth0
If your server is base on VPS you will need to backup some files more.
/etc/sysconfig/network-scripts/ifcfg-venet0:0
If you have more then one network card you will also need to backup more.
/etc/sysconfig/network-scripts/ifcfg-venet0:1
/etc/sysconfig/network-scripts/ifcfg-venet0:2
etc.
and make sure your server can be connect to the Internet.
How to install?
cat noxcentos.0