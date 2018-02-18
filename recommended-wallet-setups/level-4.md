### Level 4

This level has very complex setup options, using advanced software/hardware wallets, an [offline computer](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/building-your-offline-air-gapped-computer.html), and a [Gnosis Multi-Signature Wallet](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/gnosis-multi-signature-wallet.html). This section is only recommended for expert users who are very technical or have a lot of funds to protect.

#### 3 of 5 [Gnosis Multi-Signature Wallet](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/gnosis-multi-signature-wallet.html), Using an "Offline Computer" 🌨

1. Setup/boot your [Air-Gapped Offline Computer](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/building-your-offline-air-gapped-computer.html).
 
2. Boot [Tails OS](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/tails-os.html)  via USB on your Offline Computer.
 
3. Setup [5 *Level 2* software or hardware wallets](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/recommended-wallet-setups/level-2.html). Record those 5 account addresses offline.
 
4. Boot your Online Computer.
 
5. Open https://wallet.gnosis.pm/ in a secured browser.
 
6. Use your Ledger Nano S to activate the wallet dApp.
 
7. Select “new”.
 
8. Specify your 5 account addresses as the owners of the wallet.
 
9. Specify a daily limit. Keep it reasonable.
 
10. Deploy the Wallet contract.
 
11. Test a small `submitTransaction` transaction withdrawal with all 5 accounts, with the destination set to the account used.
   - By following this withdrawal process, hackers can see that you have potentially read this article and are following these instructions.
<p></p>

12. Once all accounts successfully have withdrawn a small amount of funds from the wallet, deposit an amount slightly larger than the Daily Limit.
  
13. Attempt a 3-signature withdrawal from the multi-signature wallet.
 
14. Now you can use that multi-signature wallet as your cold wallet.