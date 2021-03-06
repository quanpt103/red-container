## Usage
```bash
docker run --rm -it nbtscan
nbtscan 1.0.35 - 2008-04-08 - http://www.unixwiz.net/tools/

usage: nbtscan [options] target [targets...]

   Targets are lists of IP addresses, DNS names, or address
   ranges. Ranges can be in /nbits notation ("192.168.12.0/24")
   or with a range in the last octet ("192.168.12.64-97")

   -V        show Version information
   -f        show Full NBT resource record responses (recommended)
   -H        generate HTTP headers
   -v        turn on more Verbose debugging
   -n        No looking up inverse names of IP addresses responding
   -p <n>    bind to UDP Port <n> (default=0)
   -m        include MAC address in response (implied by '-f')
   -T <n>    Timeout the no-responses in <n> seconds (default=2 secs)
   -w <n>    Wait <n> msecs after each write (default=10 ms)
   -t <n>    Try each address <n> tries (default=1)
   -P        generate results in perl hashref format
```
