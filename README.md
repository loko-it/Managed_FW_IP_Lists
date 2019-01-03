# Managed FW IP Lists
IP Lijsten t.b.v URL Alias

RL Table Aliases
A URL table alias is a URL that points to a plain text file containing IP and/or CIDR masked network addresses. The URL will be periodically downloaded and refreshed. The contents of the file would look like so:

192.0.2.0/24
172.22.59.49
192.168.0.128/26
URL Alias
Similar to a URL table in that the file format is the same. However, the content is only requested once and is immediately turned into a traditional alias.

https://www.netgate.com/docs/pfsense/firewall/aliases.html
