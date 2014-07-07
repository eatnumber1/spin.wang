---
layout: default
---
## What

PrankDNS is an [OpenDNS] style open DNS resolver which hijacks NXDOMAIN
responses instead returning prank websites.

You can play pranks on your friends by setting their DNS server to
PrankDNS. Then whenever they try to go to a domain that doesn't exist,
they'll instead arrive at a suitable prank website.

## Where

The websites currently served by PrankDNS are:

 * [Meatspin]

Also see the safe for work [version][prank.domains]!

## How

Just configure your friend's DNS server to the following addresses:

|---------------+--------------------|
|      IPv4     |        IPv6        |
|:-------------:|:------------------:|
| 50.116.14.180 | 2600:3c01::31:d00d |
|---------------+--------------------|

For convenience, the domain `ns.spin.wang` points at these addresses.

## Contribute

I'm [@eatnumber1] and I'd love to hear what you think, especially if you have
suggestions for additional suitable prank websites to add to the rotation.

[OpenDNS]: http://opendns.com
[Meatspin]: http://meatspin.com
[prank.domains]: http://prank.domains
[@eatnumber1]: http://rus.har.mn
