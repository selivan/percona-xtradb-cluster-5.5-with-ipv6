PXC 5.5 work does not work with IPv6 out-of-the-box. It can not parse IPv6 addresses from config and SST does not work. 

Here is config example that avoids this problems. It forces usage of IPv6 for SST, so won't work on IPv4-only hosts. Hostnames should be used in config instead of IPv6 addresses, so you need this names in DNS or in /etc/hosts.

This setup should also work with later versions of PXC.
