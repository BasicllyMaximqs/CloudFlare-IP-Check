# CloudFlare-IP-Check
A Simple php script that detects if the user is connected to the Server via a Cloudflare Proxy or not.

### How it works
It simply checks if a Standard CloudFlare header exists.
The header used in this is "HTTP_CF_CONNECTING_IP".

### Requirements
This was tested on Ubuntu 20.04, nginx/1.18.0 with PHP 7.2.
To check your nginx version, simply use "nginx -v".
Minimum Requirements are PHP 5.8 with nginx 1.12.0.
