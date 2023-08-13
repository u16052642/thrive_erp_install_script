# [Thrive](https://www.thrivebureau.com "Thrive ERP's Homepage") Install Script

This script will also give you the ability to define an xmlrpc_port in the .conf file that is generated under /etc/
This script can be safely used in a multi-thrive code base server because the default port is changed BEFORE the ERP is started.


##### 1. Download the script:
sudo wget https://github.com/u16052642/thrive_erp_install_script/blob/main/thrive1669_install.sh

sudo chmod +x thrive1669_install.sh

sudo ./thrive1669_install.sh

/etc/init.d/thrive1669-server restart

/etc/init.d/thrive1669-server stop

/etc/init.d/thrive1669-server start

