
# MultiWalletTransfer

Contract Address : 0xD1143818f9979A10B3f44C1d19745ab232C482c7

It is a smart contract on bsc. You can transfer your wallet balance to multiple wallets in one go AKA batch transfer your balance



## Example

 ![Example](https://i.postimg.cc/dVLMrCqD/example.png)
 
 
## Points To Remember

- If you are sending 1 bnb as total amount and distributing this amount to 5 wallets then make sure to use value (client side)/msg.value as 1 bnb. And transfer everything to wallets because if you transfer lets say total of 0.9 bnb to 5 wallets and 0.1 bnb remains then transaction will revert.
- Contract does not recieve or store any tokens.
- Always use staticcall first to check if your transaction works or not


## Warning

I've tried with wbnb balance and it is working smoothly. But I've not tried with other tokens. Please use it on your own risk. I'm not responsible if any of your tokens lost during the transaction.


## Authors

- [@0xdaebak](https://www.github.com/0xdaebak)



## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
