# Network Command Cheat Sheet

## ifconfig/ipconfig

## arp
Address Resolution Protocol

## ping

## ip

## traceroute (tracert)

## netstat

## net/nbtstat

## dig (nslookup)
```
dig google.com

#反復問い合わせの確認
dig google.com +trace
```
* nsレコードとは, 次に問い合わせるべきDNSサーバー  

root-serverは13個
```
; <<>> DiG 9.10.6 <<>> google.com +trace
;; global options: +cmd
.			67230	IN	NS	b.root-servers.net.
.			67230	IN	NS	c.root-servers.net.
.			67230	IN	NS	d.root-servers.net.
.			67230	IN	NS	e.root-servers.net.
.			67230	IN	NS	f.root-servers.net.
.			67230	IN	NS	g.root-servers.net.
.			67230	IN	NS	h.root-servers.net.
.			67230	IN	NS	i.root-servers.net.
.			67230	IN	NS	j.root-servers.net.
.			67230	IN	NS	k.root-servers.net.
.			67230	IN	NS	l.root-servers.net.
.			67230	IN	NS	m.root-servers.net.
.			67230	IN	NS	a.root-servers.net.
```
## tcpdump

