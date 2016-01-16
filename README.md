decompose environment for safe-transmission project.

# Usage

``` bash
decompose --init https://github.com/dmp1ce/decompose-safe-transmission.git

# Modify .decompose/elements
vim .decompose/elements

# (OPTIONAL) Add openvpn configuration to the `./vpn/vpn.conf` file.
vim vpn/vpn.conf

# Build and start project
decompose --build && docker-compose up -d
```
