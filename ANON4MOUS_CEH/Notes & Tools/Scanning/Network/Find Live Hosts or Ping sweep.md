### Nmap Method (Doesn't really matter as not gonna be a huge range){faster}
- nmap -sn 192.168.179.0/24

### Netdiscover method(slower)
- netdiscover -i {interface} -r {range}
	- example: netdiscover -i eth0 -r 192.168.0.0/16

