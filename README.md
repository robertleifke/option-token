## Option ERC-20 Token

A liquidity providing position in Numo repersents a covered call position that earns premiums from buyers call options. To maximize composability, a modified ERC-20 has been created to implement custom logic that deals with expiries, minting and burning with premium accrual, and strikes.

## Build

```shell
$ forge build
```

## Deploy

```shell
$ forge script script/Option.s.sol:DeployScript --rpc-url <ALCHEMY_RPC_URL> --private-key <PRIVATE_KEY>
```

