# nginx_reverse_proxy_config


__Bold__
* List Nginx Reverse Proxy config for 
* List Homeassistant
* List Sighthound Video
* List Octoprint
* List Unifi Controller
* List Opensprikler


I came up with this config to minimize my port footprint since I was seeing alot of scans on my syslog server.
Overall this is a simple config but works for my needs. I needed two Sighthound Video entries as one will translate an IPv6 to IPv4 address and the Android App needs and IPv4 to IPv4 connection to work. 




# Download File and add to your Nginx Sites-Available
**Bold** 
/etc/nginx/sites-available/
