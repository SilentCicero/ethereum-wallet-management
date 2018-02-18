### Using EthOffline to sign Ethereum Transactions on an Offline Computer

**Preface**: In ["Risks of Hardware Wallets"](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/hardware-wallets/risks-of-hardware-wallets.html), we discussed the development of air-gapped hardware wallets and their use of QR codes to allow users to interact with the blockchain. In this section, we provide instructions of how to use this same "QR scanning" process when using an offline computer. 

These instructions are provided only as an additional learning tool, and is not necessary as a requirement for learning.
<hr>

It is possible to sign Ethereum transactions offline using EthOffline, and to then broadcast those transactions to the blockchain by using EthScanner. This approach allows you to conduct transactions securely without ever allowing your private key to leave your offline computer.

Both applications (EthOffline and EthScanner) are located online at https://ethjs.github.io/.

Here's some step-by-step instructions on how to use both tools.

1. Download EthOffline (from https://ethjs.github.io/offline).

2. Notate the address or addresses you want to send to in a text document.

2. Load EthOffline and any other required tools and the text document onto an SD card.

3. Boot into your offline computer with the SD card, copy all files over, then unplug the SD card.

4. Recover your Ethereum Private Key from your Bip39 seed and passphrase offline.

5. Open the EthOffline tool and paste your private key in.

6. Scan the QR code prompted with EthScanner (on an Android/PC Laptop via Chrome or FireFox).

7. Notate your account nonce, and gas values (higher for contract transactions like multisig wallets, lower for just sending to accounts).

8. Click “I know my Nonce and Gas Values”.

9. Select your nonce and gas values.

10. Copy in your to address and select any data or transaction value if necessary.

12. Click Sign Transaction, scan the QR code prompted with the EthScanner app.

13. On the EthScanner app, click “Broadcast Transaction to Mainnet”.

**Note**: EthOffline is not compliant with [EIP155](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-155.md). This means that if you have both ETH and ETC (or any other fork of Ethereum), then your funds may be vulnerable to a "replay attack". Please use another tool for now, until this is resolved.