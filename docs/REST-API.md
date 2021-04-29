## Supported Endpoints
### Address
```
/address/details/{address}
/address/details
/address/utxo/{address}
/address/utxo
/address/unconfirmed/{address}
/address/unconfirmed
/address/fromXPub/{xpub}
/address/transactions
```

### Block
```
/block/detailsByHash/{hash}
/block/detailsByHeight/{height}
```

### BlockChain
```
/blockchain/getBestBlockHash
/blockchain/getBlockchainInfo
/blockchain/getBlockCount
/blockchain/getBlockHeader/{hash}
/blockchain/getBlockHeader
/blockchain/getChainTips
/blockchain/getDifficulty
/blockchain/getMempoolEntry/{txid}
/blockchain/getMempoolEntry
/blockchain/getMempoolInfo
/blockchain/getRawMempool
/blockchain/getTxOut/{txid}/{n}
/blockchain/getTxOutProof/{txid}
/blockchain/getTxOutProof
/blockchain/verifyTxOutProof/{proof}
/blockchain/verifyTxOutProof
```

### Control
```
/control/getInfo
/control/getNetworkInfo
```

### Mining
```
/mining/getMiningInfo
/mining/getNetworkHashps
```

### RawTransactions
```
/rawtransactions/decodeRawTransaction/{hex}
/rawtransactions/decodeRawTransaction
/rawtransactions/decodeScript/{hex}
/rawtransactions/decodeScript
/rawtransactions/getRawTransaction/{txid}
/rawtransactions/getRawTransaction
/rawtransactions/sendRawTransaction/{hex}
/rawtransactions/sendRawTransaction
```

### Transaction
```
/transaction/details/{txid}
/transaction/details
```
### Util
```
/util/validateAddress/{address}
/util/validateAddress
```

### SLP
```
/slp/list GET
/slp/list POST
/slp/list/{tokenId} GET
/slp/convert/{address} GET
/slp/convert POST
/slp/balancesForAddress/{address} GET
/slp/balancesForAddress POST
/slp/balancesForToken/{tokenId} GET
/slp/balancesForToken POST
/slp/balance/{address}/{tokenId}
/slp/balance POST
/slp/validateTxid/{txid} GET
/slp/validateTxid POST
/slp/tokenStats/{tokenId} GET
/slp/tokenStats POST
/slp/txDetails/{txid} GET
/slp/transactions/{tokenId}/{address} GET
/slp/transactions POST
/slp/transactionHistoryAllTokens/{address} GET
/slp/transactionHistoryAllTokens POST
/slp/burnTotal/{transactionId} GET
/slp/burnTotal POST
```
___

## Currently Unsupported Endpoints

### CashAccounts
```
/cashAccounts/lookup/{account}/{number}/{collision} GET
/cashAccounts/check/{account}/{number} GET
/cashAccounts/reverselookup/{address} GET
```