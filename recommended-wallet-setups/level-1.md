### Level 1

This level is intended for more novice users of Ethereum --- people who have some funds and want to protect them better than leaving them in a Coinbase account.

#### Basic [Hardware Wallet](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/hardware-wallets.html)

 1\. Setup a single Ledger Nano S.
 
 2\. Safely backup and record seeds.

#### Basic Software Wallet with MyEtherWallet
 1\. Download/Setup [Tails 3.0 OS](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/tails-os.html) on a USB.
 
 2\. Download/unzip/copy MyEtherWallet (MEW) onto a fresh [SD card](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/why-sd-cards-over-usb-keys.html).
 
 3\. Shutdown/boot into Tails OS on USB.
 
 4\. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”
 
 5\. Copy MEW off the SD Card into the “Tor Browser” folder, open the dist folder
 
 6\. Unplug SD card.
 
 7\. Right-click `index.html` -> “Open with Tor Browser”
 
 8\. Enter a [strong passphrase](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/password-management.html), save the wallet file in Tor Browser folder, restore wallet with passphrase to get the address, and record the address in a text document.
 
 9\. Plugin the SD card and copy the address text file and wallet backup onto SD card.
 
 10\. Shutdown Tails.

#### Basic Software Wallet with [Ian Coleman’s Bip39 Tool](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/ethereum-wallet-basics/ian-colemans-bip39-tool.html)

 1\. Download/Setup [Tails 3.0 OS](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/tails-os.html) on a USB.
 
 2\. Download/unzip/copy Ian Coleman's Bip39 Tool onto a fresh [SD card](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/why-sd-cards-over-usb-keys.html).
 
 3\. Shutdown/boot into Tails OS on USB.
 
 4\. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”.
 
 5\. Copy the Bip39 Tool off SD Card into the “Tor Browser” folder, right-click the html file “Open With Tor Browser”.
 
 6\. Unmount/Unplug SD card.
 
 7\. Select “Supply your own source of entropy” and then input very strong entropy.
 
 8\. Generate your Bip39 passphrase with [KeePassX](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/password-management/using-keepassx-to-generate-and-store-secure-passphrases.html).
 
 9\. Safely record and backup your seed and passphrase.
  <ul>
   <li>I do not recommend recording on flash memory or SD, but if you do, make sure to encrypt this data before plugging in and saving on SD card.</li>
  </ul>
  
 10\. Copy first 5 addresses to a text document.
 
 11\. Plug in SD card, copy the text document onto the SD card, and then unplug SD card.
 
 12\. Shutdown and then reboot into Tails Offline.
 
 13\. Plug in the SD card, copy Bip39 tool off SD card into Tor Browser folder, and then right-click html file “Open with Tor Browser”.
 
 14\. Re-enter your recorded Bip39 seed and passphrase, and check the addresses generated are the ones you recorded.