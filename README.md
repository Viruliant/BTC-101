# BTC-101
_________

Code@[github.com/Viruliant/BTC-101](http://github.com/Viruliant/BTC-101)  

Bitcoin is a protocol on how to send BTC between Account Numbers(aka public address number). Each Account Number has a corresponding Account Signature Keys(aka private key number). "You have the private key number you have the money." --AAntonopoulos

At the heart of bitcoin is Transactions - messages consisting of receiving Account Numbers and how much to send to each one, the remaining unspent funds are the transaction fee. A VALID Pending Transaction needs to have an Account Key signature that matches an public Account Numbers with enough funds in it. Multisig Accounts require multiple signatures.

Once a VALID Pending Transaction is broadcast to the WWW all the miners are constantly using difficulty adjusted dice(aka checksuming with an incrementing nonce added to checksum input to roll again) until they get a low enough roll() to win the block reward(some bitcoins) by securing the block which adds all the current pending transactions(together as a checksum secured block) into the Master Secured Ledger of ALL BTC Transactions of all time(blockchain). Until a Transaction is secured into the blockchain it is worthless.

Address Reuse(Using a single account # for all transactions) is so dangerous that could be in violation of reasonable consumer protection laws, it is dangerous because anyone you trade with can see a complete history of the finances of a single address. You need to use an HD Account that has rolling Account Numbers(addresses) none of which exceeding a certain value.

The Signature algorithm works similar to the RSA encryption algorithm in the video below:

<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe src=
"//www.youtube.com/embed/IY8BXNFgnyI?list=PLjgrsP5Vg40mVUj2cmzUyb6Ik1IiCj8P9&loop=1&autoplay=1"
frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

[Here is how to do a RSA signature instead of encryption.](http://crypto.stackexchange.com/a/9897)


