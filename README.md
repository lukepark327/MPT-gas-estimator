# MPT-gas-estimator
gas estimating code about Merkle Patricia Trie verification on smart contract.

# How to Use

```
$ node txProof.js
```

# Troubleshooting

* Go `./node_modules/ethereumjs-block/node_modules/ethereumjs-tx/dist/transaction.js`

* Comment out `L#308`-`L#311`.

```js
        // var isValidEIP155V = vInt === this.getChainId() * 2 + 35 || vInt === this.getChainId() * 2 + 36;
        // if (!isValidEIP155V) {
        //     throw new Error("Incompatible EIP155-based V " + vInt + " and chain id " + this.getChainId() + ". See the second parameter of the Transaction constructor to set the chain id.");
        // }
```

# References

### eth-proof
https://github.com/zmitton/eth-proof
