# docker-bind9-debian-jessie
Docker container with JUST /usr/sbin/named and its library dependancies.

docker run -d -v /path/to/base/config:/etc/bind kpeiruza/standalone-bind9

It's based on Debian Jessie's bind9 for maximum compatibility and updates.

There's nothing else inside, no shell, no commands, nothing. Not tested with DNS-SEC but it probably works (all DNSSEC and Unicode libs are there).

Enjoy!
