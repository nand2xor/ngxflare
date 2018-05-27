# ngxflare
Nginx-Cloudflare Scripts (Automize Cloudflare IP Whitelists in Nginx)

**Description**

Nginx-Cloudflare-scripts is script written in bash to fetch all ipv4 and ipv6 ranges used by all cloudflare hosts and implement them into a www-allow.conf list in your nginx config. Using the nginx directories; _allow_ and _deny all_ to only allow cloudflare traffic to your backend server. Poor-mans firewall for the people without ip-tables.

**Credits**

This script was not purely made by me @nand2xor rather derived from [Marekbosman](https://marekbosman.com/site/automatic-update-of-cloudflare-ip-addresses-in-nginx/) and modified by @nand2xor. 

The purpose is simply to help the public domain manage their nginx cloudflare whitelists more easily.
