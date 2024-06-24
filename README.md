##  Require Foundry

### Setup

```sh
forge install
```

### Deploy

forge create --rpc-url <RPC-URL> --private-key <YOUR-PRIVATE-KEY> src/Permit2.sol:Permit2
forge create --rpc-url https://l1testnet.trustkeys.network --private-key 0x387030e12125537380d3a5f8365c03f2a6443aecbca4044cf115ecf7a6bb4c63 src/Permit2.sol:Permit2