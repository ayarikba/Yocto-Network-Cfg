# Yocto-Network-Cfg
Aims to make permanent ethernet config with ethtool 


nano /etc/systemd/system/ethtool-ethX.service 

**systemctl enable ethtool-ethx.service**


**systemctl start ethtool-ethx.service**


**systemctl status ethtool-eth1.service**