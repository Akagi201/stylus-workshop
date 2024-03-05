# Counter

## Init

```sh
cargo stylus new counter
```

## Build

```sh
cargo build
```

## Generate ABI

```sh
cargo stylus export-abi
```

## Check wasm

```sh
cargo stylus check
```

## Deploy

estimate gas

```sh
cargo stylus deploy --private-key xxx --estimate-gas-only
```

true deploy

```sh
cargo stylus deploy --private-key xxx
```

```sh
Uncompressed WASM size: 24.9 KB
Compressed WASM size to be deployed onchain: 9.0 KB
Connecting to Stylus RPC endpoint: https://stylus-testnet.arbitrum.io/rpc
Program succeeded Stylus onchain activation checks with Stylus version: 1
Deployer address: 0x00000000001b00B15f85Ce4ed62381510c4ec86f

====DEPLOYMENT====
Deploying program to address 0x069537550E0a050464d74aA81AaBE201f5B987cD
Base fee: 0.100000000 gwei
Estimated gas for deployment: 3149627 gas units
Submitting deployment tx...
Confirmed deployment tx 0x279d219ee7d8a0efd22b5d3beabd6d9aafd4de19e48b60370b53f9fac4bbc56d
Gas units used 3031615, effective gas price 0.100000000 gwei
Transaction fee: 0.000303161500000000 ETH

====ACTIVATION====
Activating program at address 0x069537550E0a050464d74aA81AaBE201f5B987cD
Base fee: 0.100000000 gwei
Estimated gas for activation: 14067075 gas units
Submitting activation tx...
Confirmed activation tx 0xc6a4142d438c1ca1b9eb39ef865eb5d24c803879efc70a5c92efa9f3085a2fdf
Gas units used 14062113, effective gas price 0.100000000 gwei
Transaction fee: 0.001406211300000000 ETH
```
