# Million Channels Project: Generated Data

The Million Channels Project produces quite a bit of data: for your
convenience we've prepared some already so you don't have to reproduce
it.

## v0.1/gossip

This contains a compressed gossip dump `1M.gossip` which is a
concatenation of gossip messages, each prepended by a 2-byte
big-endian length.

It also contains a compressed CSV file `scidSatoshis.csv` which has
the capacities for each channel.

## v0.1/bitcoin

This contains the compressed `.bitcoin/regtest/block` files for
bitcoind's regtest mode.  Uncompressing this into an empty
`.bitcoin/regtest` directory will cause bitcoind to regenerate indexes
for the blockchain containing all the funding transactions for the
million channels project.

Happy stress-testing!

Rusty & Joe.
