# network-config
This project contains the OpenWRT configuration files to setup a home network with three subnets:
- IoT: for smart home devices like Chromecast
- Main: for trusted devices like laptops
- Guest: to provide internet, through a VPN, to guest devices

In OpenWRT you need to create firewalls to seperate VLANS

This is a simplification of how those should work:

![image](https://github.com/akademsubotnik/network-config/assets/44036625/05589f76-c017-4136-a9f7-5089d96f64ef)
