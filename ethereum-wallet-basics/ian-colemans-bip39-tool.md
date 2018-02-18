## Ian Coleman's Bip39 Tool

Ian Coleman is a cryptocurrency expert and developer who has made an awesome Bip39 utility. The tool allows you to generate and recover Bip39 seed phrases and derive Ethereum account key pairs from it. The tool is well tested, and simple by design.

It also has:
- Support for Bip32 settings, allowing you specify unique HD paths.

- Good use of clear, reliable and safe system entropy generation that is to be paired with user inserted entropy.

  - Entropy is just another word for randomness, and the more randomness you have, the harder it will be for someone to guess your seed or password.

If we know the password and our Bip39 seed phrase, we can  recover our private key with Ian Coleman's tool. Let's try it out with the example password and Bip39 seed phrase we used in the last chapter.

The Bip39 seed phrase is:

    gravity trophy shrimp suspect sheriff
    avocado label trust dove tragic pitch title
    network myself spell task protect smooth 
    sword diary brain blossom under bulb

And the password is:

    fJF*(SDF*(*@J!)(SU*(D*F&^&TYSDFHL#@HO*&O

We want to recover this address...

        0x02941ca660485Ba7Dc196B510D9A6192c2648709

And this private key...
    
    0xb1b3dcf4a200ab01c7aeafb8b4cda3fd03401dd2413d169846959a8f7915fd2f

1. Go to https://iancoleman.io/bip39/
2. Enter the Bip39 seed phrase and the password.
3. Set “Coin” to “Ethereum”.
4. Scroll down. You will see the first address is the address we want to recover.
5. Scroll over and you will find the private key of that address (which matches the private key we want to withdraw).

Note that the hex prefix “0x” is not included in the Bip39 tool’s private and public keys. It should always be added when handling addresses or private keys, if not presented. While it is a minor matter of formatting and is usually not a problem...it is good practice to add it if you don't see it.