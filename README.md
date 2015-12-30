iptables helper shell script
=====

Whitelist style iptables firewall configuration script for simple public traffic rules.

Usage
====

`./iptables.sh ...*services*`

Supported Services
====

dns (53)

http (80)

https (443)

imap (143)

imaps (993)

mysql (3306)

pop3 (110)

pop3s (995)

postgres (5432)

smtp (25,587)

smtps (465)

ssh (22) -- *limit 4 attempts per IP, per 300s*


Example
====

`./iptables.sh http ssh`

