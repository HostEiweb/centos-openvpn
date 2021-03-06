##openvpn-install
OpenVPN [road warrior](https://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

###Installation
Run the script and follow the assistant:

`wget https://raw.github.com/HostEiweb/centos-openvpn/master/vpn-install.sh -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

###New features
- Automatic inline .ovpn file generation for Android devices
- Google DNS servers
- Port 53 enabled by default for captive portal bypass

###I want to run my own VPN but don't have a server for that
There are reliable providers where you can get a little VDS for even less than one buck a month.

- Host-Eiweb.net ([VDS Netherlands](http://host-eiweb.net/vds-netherlands.html), [VDS Bulgaria](http://host-eiweb.net/vds-bulgaria.html), [VDS Latvia](http://host-eiweb.net/vds-latvia.html), [VDS Ukraine](http://host-eiweb.net/vds-ukraine.html), [VDS United States](http://host-eiweb.net/vds-usa.html))

Minimal configuration (CPU: 1x3400 Mhz "Xeon", RAM: 512 mb, SSD: 15 Gb, 1IPv4 1IPv6) - $3.74/mo.

Website: [host-eiweb.net](http://host-eiweb.net/) 
