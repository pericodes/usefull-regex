# Cryptocurrency-regex
## Regex (regular expression) for matching cryptocurrencies in a text.

| Name       | Regex           | Description     |Source          |
| ---------- |:---------------:| :--------------:| :--------------:|
| Bitcoin | [13][a-km-zA-HJ-NP-Z1-9]{25,34} | Regular expression for matching Bitcoin Cash (BCH) addresses. | http://mokagio.github.io/tech-journal/2014/11/21/regex-bitcoin.html |
| Monero address | 4[0-9AB][1-9A-HJ-NP-Za-km-z]{93} | Regular expression for matching Monero (XMR) addresses. | https://github.com/k4m4/monero-regex/blob/master/index.js |
| Monero payment ID | ([0-9a-fA-F]{16}\|[0-9a-fA-F]{64}) | Regular expression for matching Monero (XMR)payment ID. | https://monero.stackexchange.com/questions/2554/what-is-the-regex-for-a-monero-address-or-payment-id |
| Ripple address | r[0-9a-zA-Z]{24,34} | Regular expression for matching Ripple (XRP) addresses. | https://github.com/k4m4/ripple-regex |
| Ethereum address | 0x[a-fA-F0-9]{40 | Regular expression for matching Ethereum (ETH) addresses. | https://github.com/k4m4/ethereum-regex/blob/master/index.js |
| Litecoin address | [LM3][a-km-zA-HJ-NP-Z1-9]{26,33} | Regular expression for matching Litecoin (LTC) addresses. | https://github.com/k4m4/litecoin-regex/blob/master/index.js |
| Dash address | X[1-9A-HJ-NP-Za-km-z]{33} | Regular expression for matching Dash addresses. | https://github.com/k4m4/dash-regex/blob/master/index.js |
| Neo address | A[0-9a-zA-Z]{33} | Regular expression for matching NEO addresses. | https://github.com/k4m4/neo-regex/blob/master/index.js |
| Dogecoin adress | D{1}[5-9A-HJ-NP-U]{1}[1-9A-HJ-NP-Za-km-z]{32} | Regular expression for matching Dogecoin (DOGE) addresses. | https://github.com/k4m4/dogecoin-regex/blob/master/index.js |
