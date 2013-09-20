iptables-nat
============

Simple nat setup for iptables.

External interface is eth0. 
Internal interface is eth1.

If you use pppoe connection you may want to replace eth0 by ppp0 for IF_EXTERNAL constant.

Will show following output:

```
SETTING UP IPTABLES NAT
  Loading required stateful/NAT kernel modules...
  Configurating system parameters...
  External interface: eth0 (172.30.1.38)
  Internal interface: eth1 (172.19.255.254)
  Loading iptables rule sets...

  DONE.
