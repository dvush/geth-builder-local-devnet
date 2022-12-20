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
`dc5a15972116d30544019f651d900a33cf5e28f9dc81300e480de96bd28cb055` - priave key
2. `0x8ec1237b1e80a6adf191f40d4b7d095e21cdb18f` - user
`c01dd3e4426ef5739c3cb2f08d0287c83172e33625e9d3f21b73e32144fa62eb` - private key
`panic keen way shuffle post attract clever country juice point pulp february` - mnemonic
`m/44'/60'/0'/0/0` - path

