
# MultiWalletTransfer

Contract Address : 0x581305496A783A666a7bb9383B13c9a14C20578F

It is a smart contract on bsc. You can transfer your wallet balance to multiple wallets in one go AKA batch transfer your balance



## Example

 ![Example](https://i.postimg.cc/JhGGY8XK/example1.png)
 
 
## Standard Information

```javascript

WALLET1 -> AMOUNT1 
WALLET2 -> AMOUNT2 
WALLET3 -> AMOUNT3 
....... -> .......

_.transferToWallets([WALLET1, WALLET2, WALLET3,.....], [AMOUNT1,AMOUNT2,AMOUNT3,...], {
        value: TOTALAMOUNT
});
```
 
## Points To Remember

- Contract does not recieve or store any tokens.
- Always use staticcall first to check if your transaction works or not


## Warning

I've tried with wbnb balance and it is working smoothly. But I've not tried with other tokens. Please use it on your own risk. I'm not responsible if any of your tokens lost during the transaction.


## Authors

- [@0xdaebak](https://www.github.com/0xdaebak)



## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
