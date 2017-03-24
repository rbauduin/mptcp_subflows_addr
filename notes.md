# Address Types

## ipv4

* multicast 224.0.0.0/4: 224.0.0.0 to 239.255.255.255, see https://en.wikipedia.org/wiki/Multicast_address#IPv4
* link local 169.254.0.0/16
* private 10.0.0.0/8, 172.16.0.0/12, 192.168.0.0/16
* loopback 127.0.0.0/8



## ipv6

reference: https://www.ripe.net/participate/member-support/lir-basics/ipv6_reference_card.pdf

* site local: fec0::/10
* loopback: ::1/128
* ipv4-mapped: ::FFFF:xxxx:xxxx/96
* unique local address: fc00::/7
* link local: fe80::/10
* teredo, benchmarking, orchid, 6to4
* documentation: 2001:db8::/32
* global unicast 2000::/3
* multicast ff00::/8, https://en.wikipedia.org/wiki/Multicast_address#IPv6

* IPv4-compatible IPv6 Addresses: ::ip.add.re.ss



## General

* Appearing/disappearing interface (with address)
* Appearing/disappearing address on interface

## Actions

* Advertise new address to peers
* Open subflow with new source address
