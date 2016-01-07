# iptables

> Command line front-end for the Linux netfilter firewall

- flush all iptables rules

`iptables -F`

- list all rules in the filter table

`iptables --list`

- list rules from a specific table (filter, nat, mangle or raw)

`iptables -t {{table_name}} --list
