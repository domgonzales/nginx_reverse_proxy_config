# nginx_reverse_proxy_config


#
* Nginx Reverse Proxy config for 
* Homeassistant
* Sighthound Video
* Octoprint
* Unifi Controller
* Opensprikler
#

I came up with this config to minimize my port forwarding footprint since I was seeing alot of scans on my syslog server.
Everything is proxied through subdomains to make things easy for me to remember.
Overall this is a simple config but works for my needs. I needed two Sighthound Video entries as one will translate an IPv6 to IPv4 address and the Android App needs and IPv4 to IPv4 connection to work. 




# Download File and add to your Nginx Sites-Available
**/etc/nginx/sites-available/**

You will obviously need to modify internal IP addresses and subdomains for this to work. 
