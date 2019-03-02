![IQR Tokens](logo.jpg "IQR Token")

# IQR Token smart contract

* _Standard_        : [ERC20](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md)
* _[Name](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md#name)_            : IQR
* _[Ticker](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md#symbol)_        : IQ RISES SYSTEM
* _[Decimals](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md#decimals)_    : 18
* _Emission_        : As sale
* _Crowdsales_      : 1
* _Fiat dependency_ : Yes
* _Price_           : 0.06 USD
* _Tokens locked_   : 6 month
* _Token issue_     : 200 000 000

## Smart-contracts description

There is a special function to return 3rd party tokens that were sent by mistake (function retrieveTokens()).  
Each stage has a direct minting function in wei. This is made to support the external payment gateways.

### Contracts contains
1. _IQRToken_ - IQR Token
2. _IQRSaleFirst_ - IQR contract for crowdsale

### How to manage contract
To start working with contract you should follow next steps:
1. Compile it in Remix with enamble optimization flag and compiler 0.4.18
2. Deploy bytecode with MyEtherWallet. Gas 5100000 (actually 5073514).
3. Call 'deploy' function on addres from (3). Gas 4000000 (actually 3979551).

Contract manager must call finishMinting after each crowdsale milestone!

### How to invest
To purchase tokens investor should send ETH (more than minimum 0.1 ETH) to corresponding crowdsale contract.
Recommended GAS: 250000, GAS PRICE - 21 Gwei.

### Wallets with ERC20 support
1. MyEtherWallet - https://www.myetherwallet.com/
2. Parity
3. Mist/Ethereum wallet

EXODUS not support ERC20, but have way to export key into MyEtherWallet - http://support.exodus.io/article/128-how-do-i-receive-unsupported-erc20-tokens

Investor must not use other wallets, coinmarkets or stocks. Can lose money.


## Tokens distribution for IQR

* _Manual_          : ?
* _For sale agent_  : ?
* _Founders_        : ?



### Links
1. _IQR Token_ - https://etherscan.io/token/0x63ff24f4a41a4bb40e7ca5e46530560c251eb1f1
2. _IQR Smart contract_ - https://etherscan.io/address/0xbd034b87f1e92757e4bcd5c9a9ea178e317a4abf


### ITO
* _Minimal insvested limit_     : 0.1 ETH
* _Base price_                  : 6 USD = 1000 Tokens
* _Hardcap_                     : ... ETH
* _Softcap_                     : ... ETH
* _Period_                      : ... days
* _Start_                       : ...
* _Wallet_                      :

#### Features
No

## rinkeby test

### Links
1. _IQR Token_ - https://rinkeby.etherscan.io/token/0x0ceebef652067ee3382f2949a8f46b2d26f2a90e#readContract
2. _IQR Smart contract_ - https://rinkeby.etherscan.io/address/0xa4b3c58897d8c6f89492bc84eebfcd689e7351dc#readContract
