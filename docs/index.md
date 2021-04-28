# Welcome to ActorForth Docs

[Contact Us](www.actorforth.org)

[REST API](rest.bch.actorforth.org)

___	

## Currently Unsupported REST APIs
### SLP
* /slp/list GET
* /slp/list POST
* /slp/list/{tokenId} GET
* /slp/convert/{address} GET
* /slp/convert POST
* /slp/balancesForAddress/{address} GET
* /slp/balancesForAddress POST
* /slp/balancesForToken/{tokenId} GET
* /slp/balancesForToken POST
* /slp/balance/{address}/{tokenId}
* /slp/balance POST
* /slp/validateTxid/{txid} GET
* /slp/validateTxid POST
* /slp/tokenStats/{tokenId} GET
* /slp/tokenStats POST
* /slp/txDetails/{txid} GET
* /slp/transactions/{tokenId}/{address} GET
* /slp/transactions POST
* /slp/transactionHistoryAllTokens/{address} GET
* /slp/transactionHistoryAllTokens POST
* /slp/burnTotal/{transactionId} GET
* /slp/burnTotal POST

### CashAccounts
* /cashAccounts/lookup/{account}/{number}/{collision} GET
* /cashAccounts/check/{account}/{number} GET
* /cashAccounts/reverselookup/{address} GET