## Bip39 Seeds and Ethereum Keys

Some accounts are created using Bip seed phrases - special kinds of phrases that can generate private keys.  The tool I recommend generates a type of Bip phrase called a Bip39 seed phrase. Bip39 seed phrases are a standard in the cryptocurrency community and are used across a number of software and hardware wallets (including MyEtherWallet and Ledger Nano S).

You can think of Bip39 seed phrases like this:

```
seed + password + HD Path => private key
private key => public key
public key => public address
```

A single Bip39 24 word seed phrase with a Bip39 password/passphrase, along a particular path (called an HD path) will produce a particular private key.

That private key will then produce a public key.

*That* public key will then produce the public address.

#### Example
Here is a standard 24 word Bip39 seed phrase.

    gravity trophy shrimp suspect sheriff   
    avocado label trust dove tragic pitch title 
    network myself spell task protect smooth 
    sword diary brain blossom under bulb

Using this password:

	fJF*(SDF*(*@J!)(SU*(D*F&^&TYSDFHL#@HO*&O

And this HD path:

	m/44'/60'/0'/0/0

We will derive this Ethereum private key:

	0xb1b3dcf4a200ab01c7aeafb8b4cda3fd03401dd2413d169846959a8f7915fd2f

Which will then derive to this Ethereum public key:

	0x0322b7e67644956f7672891f92b6d41e8ecab3b8990f0257eb167baf81737f3f7d

Which will derive to this public Ethereum address:
		
		0x02941ca660485Ba7Dc196B510D9A6192c2648709

(Do not use this account for any real funds...you will lose everything you put in there.)

In order to steal the funds out of a wallet, someone needs to know the Bip39 seed phrase, and the password. Then they can just guess all the various HD paths (there are not that many options) until they get the private key.

Once they have the private key, then and only then can they attempt to take all the funds within the wallet.