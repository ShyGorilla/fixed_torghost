## What is TorGhost ?
TorGhost is an anonymization script. TorGhost redirects all internet traffic through SOCKS5 tor proxy. DNS requests are also redirected via tor, thus preventing DNSLeak. The scripts also disables unsafe packets exiting the system. Some packets like ping request can compromise your identity.

## Build and install from source
`git clone https://github.com/ShyGorilla/fixed_torghost.git`

`cd torghost`

`chmod +x build.sh`

`sudo ./build.sh`


## Usage
Torghost v3.0 usage:

`  -s      --start        Start Torghost`

`  -r      --switch       Request new tor exit node`

`  -x      --stop         Stop Torghost`

`  -h      --help         Print this help and exit`

`  -u      --update       Checks for updates`





