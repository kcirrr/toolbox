# Toolbox

Container image with some tools for troubleshooting.

## Usage
```
kubectl run toolbox --rm -i --tty --image ghcr.io/kcirrr/toolbox:alpine -- /bin/bash
```

## Included tools
* ab
* curl
* dig
* dnsutils
* git
* host
* htpasswd
* info
* lsof
* mongocli
* mtr-tiny
* mysql-client
* net-tools
* nmap
* openssl
* ping
* ping6
* postgresql16-client
* redis-tools
* rclone
* rsync
* ssh
* strace
* unzip
* vim
* wget
* whois
* zip
