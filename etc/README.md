**dhcpcd.conf**

Change whitelist and static routers to your default gateway address.

**nftables.conf**

This is a basic firewall configuration that only accepts packets from connections that are established within the system, connections from outside are dropped.

ARP packets are only accepted from the router configured by the /etc/sysctl.d/local.conf file (net.ipv4.conf.all.arp_ignore = 3)