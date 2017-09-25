# go-ipfs LifeMesh fork
This is the official fork of IPFS used in LifeMesh, which in turn was forked for use in OpenBazaar (https://github.com/OpenBazaar/go-ipfs)

Issues:
- "ipfs swarm peers" command won't work, return type was changed into []string from a private struct (inherited from openbazaar ipfs fork)