# network-config
This project contains the OpenWRT configuration files to setup a home network with three subnets:
- IoT: for smart home devices like Chromecast
- Main: for trusted devices like laptops
- Guest: to provide internet, through a VPN, to guest devices

In OpenWRT you need to create firewalls to seperate VLANS

This is a simplification of how those should work:

![image](https://github.com/user-attachments/assets/35dff2c1-b406-49f6-8066-59b4827261e2)
