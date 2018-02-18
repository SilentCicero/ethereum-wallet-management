# What is An Ethereum Wallet?

Ethereum wallets are simply accounts on Ethereum that are not "smart contracts".

Every account has a public address (where ether can be sent to), a public key, and a private key (that only we have/control and see). The address can be derived from the public key and the public key can be derived from the private key. The private key is what is used for signing Ethereum transactions.

You cannot send an Ethereum transaction from an address without having the single private key to that address. If an attacker gets the private key, they can now be the signer of that account and can use and control the account forever.

Remember, funds are not sent to the private key, but to the public ethereum address - not to be confused with the public key. I know the wording is confusing.

For reference, this is what an Ethereum private key (in hexadecimal format) looks like:

     0xfdb32a9e7ecd6408c491d0db8f525597eca49abe6acad75a5d6ff28e9818347b

And this is its subsequent Ethereum public key (in hexadeimal format):

     0x0213555f283a98881b01eb0da53fb4569de723d1b7aae64b2a567508675e4d0835

And this is the Ethereum address derived from the public key above (in checksum format):

    0x1668A14aA2f99E3D406b6AF73fCa80EAba55E9AC

In the next section, we will discuss the Bip39 system for creating/storing and managing cryptographic key pairs like Ethereum accounts.