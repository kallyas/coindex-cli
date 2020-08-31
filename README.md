# Coindex CLI

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0996803e8fa24d43bb6a9ff12eab22e6)](https://app.codacy.com/manual/kallyasmedia/coindex-cli?utm_source=github.com&utm_medium=referral&utm_content=kallyas/coindex-cli&utm_campaign=Badge_Grade_Dashboard)

Command line interface written in Node.js to check cryptocurrency prices

Register an API key at https://nomics.com
## Usage

```
npm install

npm link
```

## Commands
```
# Help & Commands
coindex -h

# Version
coindex -V

# API Key Commands
coindex key set
coindex key show
coindex key remove

# Crypto Check Commands
coindex check price

# Check Specific Coins (default: BTN,ETH,XRP)
coindex check --coin=BTC,ETH

# Choose Currency (Default: USD)
coindex check --cur=EUR
```

Version

1.0.0
License

GNU General Public License v3.0
