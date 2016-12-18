## tzn-daemon

[![CircleCI](https://circleci.com/gh/NebTex/tzn-daemon.svg?style=svg)](https://circleci.com/gh/NebTex/tzn-facts) [![Go Report Card](https://goreportcard.com/badge/github.com/NebTex/tzn-daemon)](https://goreportcard.com/report/github.com/NebTex/tzn-daemon) [![codecov](https://codecov.io/gh/NebTex/tzn-daemon/branch/master/graph/badge.svg)](https://codecov.io/gh/NebTex/tzn-daemon)

Small tool for coordinate mesh vpns (initially tinc) using consul as backend
 
 1. Continuously push node information to the consul backend
 
 - Interfaces ip
 - Geo-ip info (thanks to https://freegeoip.net)
 - Check if the node is a bare-metal or lxc container
 - Tinc public key of the node
 
 2. Automatically assign an ip to the node 
 
 3. maintain updated the `/etc/hosts` file, with a entry for each node, 
 with its respective vpn address 
 
### Vendoring 

trash was used  https://github.com/rancher/trash

### Licence

Copyright (c) 2016 NebTex

MIT 
