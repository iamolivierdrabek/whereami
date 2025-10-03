# ORL Triangulation Station Terminal Client
Use the AMI's [Triangulation Station](https://whereami.bestpoint.institute) in your terminal to quickly pinpoint your location on the internet. Outputs IPv4 &amp; IPv6 connection info. Useful for proxy and VPN testing.

## Installation
First, make sure curl is installed. Then copy [bin/whereami](bin/whereami) to `~/.local/bin` (or any other directory in `$PATH`) and grant it "executable" privileges. Then restart your shell.

## Usage
Just run `whereami` to retrieve your public-facing IP & hostmask from our [IPv4](https://ipv4.whereami.bestpoint.institute) & [IPv6](https://ipv6.whereami.bestpoint.institute) triangulation beacons.

Use `whereami full` to get a more detailed readout.
