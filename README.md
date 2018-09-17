# jsonrpcproxy

Provides JSON-RPC-over-HTTP <-> JSON-RPC-over-IPC "translation" for
Ethereum node implementations that don't have a native HTTP server.

Extracted from [`ethereum/aleth`](https://github.com/ethereum/aleth) -
at [commit `0eb14b`][script-source]. (The original code has had many
improvements since then.)

Modified to work with Trinity, an
[`ethereum/py-evm`](https://github.com/ethereum/py-evm) implementation -
in particular, to interface with `eth-net-intelligence-api`, as it
exists in [branch `break-to-work-with-trinity`][enia-branch] of my
repo fork.

PROVIDED AS-IS. No, seriously - this is not a license warning; what
can be seen here is a dirty commit I didn't think I'd publish.

[script-source]: https://raw.githubusercontent.com/ethereum/aleth/0eb14b2b7aea2431f3661690e7d8edb004eae26a/scripts/jsonrpcproxy.py
[enia-branch]: https://github.com/veox/eth-net-intelligence-api/tree/break-to-work-with-trinity
