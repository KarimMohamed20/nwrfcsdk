```
cd /usr/local
sudo mkdir sap
cd sap
sudo git clone https://github.com/KarimMohamed20/nwrfcsdk
cd ~/
vim .bashrc # (Type the following in .bashrc, export SAPNWRFC_HOME=/usr/local/sap/nwrfcsdk)
source .bashrc
sudo su
sudo vim /etc/ld.so.conf.d/nwrfcsdk.conf # (enter the following line /usr/local/sap/nwrfcsdk/lib)
```
