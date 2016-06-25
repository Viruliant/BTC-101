# BTC-101
_________

Code@[github.com/Viruliant/BTC-101](http://github.com/Viruliant/BTC-101)  

__________
##Accounts

Bitcoin is a protocol on how to send BTC between Account Numbers(aka public address number). Each Account Number has a corresponding Account Signature Keys(aka private key number). "You have the private key number you have the money." --AAntonopoulos in a JRE interview

Address Reuse(Using a single account # for all transactions) is VERY dangerous, because anyone you trade with would see a complete history of the finances of a single address. You need to use an HD Account that has rolling Account Numbers(addresses) none of which exceeding a certain value.

______________
##Transactions
At the heart of bitcoin is Transactions - messages consisting of receiving Account Numbers and how much to send to each one, the remaining unspent funds are the transaction fee. A VALID Pending Transaction needs to have an Account Key signature that matches an public Account Numbers with enough funds in it. Multisig Accounts require multiple signatures.

Once a VALID Pending Transaction is broadcast to the WWW all the miners are constantly using difficulty adjusted dice(aka checksuming with an incrementing nonce added to checksum input to roll again) until they get a low enough roll() to win the block reward(some bitcoins) by securing the block which adds all the current pending transactions(together as a checksum secured block) into the Master Secured Ledger of ALL BTC Transactions of All Time(blockchain). Until a Transaction is secured in the blockchain the money you are going to receive can still be spent before it gets to you.

____________
##Signatures

Transactions cannot take place without valid signatures, The DSA-Signature algorithm works semantically similar to the RSA-Encryption algorithm in the video below:  
[Here is how to do a RSA signature instead of encryption.](http://crypto.stackexchange.com/a/9897)

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src=
"//www.youtube.com/embed/IY8BXNFgnyI?list=PLjgrsP5Vg40mVUj2cmzUyb6Ik1IiCj8P9&loop=1&autoplay=0"
frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

___
##Debit Cards
For dealing with traditional money with BTC:  
For use in the US [Here is my Shameless Coinbase Plug(we each get $10 if you make an account at that link an buy over $100usd worth of btc from them)](https://www.coinbase.com/join/57537a120dd5607fe400025a)
