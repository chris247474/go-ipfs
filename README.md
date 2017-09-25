# go-ipfs LifeMesh fork
This is the official fork of IPFS used in LifeMesh, which in turn was forked for use in OpenBazaar (https://github.com/OpenBazaar/go-ipfs)

# Diff
- The /openbazaar/dht, /openbazaar/bitswap/, and /openbazaar/supernoderouting/ protocol strings have been changed to /lifemesh/dht, /lifemesh/bitswap/, and /lifemesh/supernoderouting/ respectively, to further separate the LifeMesh IPFS network from OpenBazaar and the main IPFS network
- refracted code that interrupted build scripts (function signature mismatches)

# Issues:
- "ipfs swarm peers" command won't work, return type was changed into []string from a private struct (inherited from openbazaar ipfs fork)