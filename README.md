# network-config
This project contains the OpenWRT configuration files to setup a home network with three subnets:
- IoT: for smart home devices like Chromecast
- Main: for trusted devices like laptops
- Guest: to provide internet, through a VPN, to guest devices

In OpenWRT you need to create firewalls to seperate VLANS

This is a simplification of how those should work:

![image](https://github.com/user-attachments/assets/7719a0b9-6562-4436-9db3-7ac69693ada9)
