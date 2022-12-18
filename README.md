Run builder as a local devnet

1. Get https://github.com/flashbots/builder and run `make`
2. Set path to builder executable
```
export GETH=$(realpath ./build/bin/geth)
```
3. Use `./devnet run` to start local node (or `./devnet clean` to reset chain)

Now you can send bundles / txs to "http://localhost:8545".

### Prefunded accounts

1. `0x8691735873b058e9c9959cd1ae11e0df941bb063` - validator
`dc5a15972116d30544019f651d900a33cf5e28f9dc81300e480de96bd28cb055` priave key
2. `0x9194d8ab69737ecec59632d9964272864b7e5d92` - user
`ea14b05f4419f1dd22081c213b67b11164296e607373445ce972419eb895ce17` private key

