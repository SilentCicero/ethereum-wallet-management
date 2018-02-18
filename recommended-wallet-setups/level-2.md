### Level 2

This level requires the use of either a hardware wallet or an offline computer. These setup instructions are geared towards an intermediate user who is familiar with the Ethereum ecosystem.

#### Complex [Hardware Wallet](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/hardware-wallets.html) Wallet ([Air-Gapped](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/building-your-offline-air-gapped-computer.html) Setup with Bip39 Passphrase)

 1\. Setup a single Ledger Nano S. Plug into a plug (not a computer) when creating seed/accounts.
 
 2\. Upgrade/verify that your Ledger Nano S is at version 1.3.1.
 
 3\. Enable Shuffle Pin and set the Timeout.
 
 4\. Enable Pin with Bip39 Passphrase (generate passphrase offline with [KeePassX](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/password-management/using-keepassx-to-generate-and-store-secure-passphrases.html)).
 
 5\. Backup and encrypt passphrase with KeePassX database on a [SD card](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/why-sd-cards-over-usb-keys.html).
 
 6\. Safely backup and record your seed, passphrase and accounts.
 
 7\. Reset the Ledger S Nano wallet device.
 
 8\. Restore the reset device to the seed and passphrase you recorded.
 
 9\. Verify the accounts you recorded are the same as the ones from the newly restored hardware wallet.
 
#### Basic [Offline Air-Gapped Software Wallet](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/building-your-offline-air-gapped-computer.html) with MyEtherWallet 🌨

 1\. Download/Setup [Tails 3.0 OS](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/tails-os.html) on a USB.
 
 2\. Download/unzip/copy MyEtherWallet (MEW) onto a fresh [SD card](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/why-sd-cards-over-usb-keys.html).
 
 3\. Setup an [Offline Air-Gapped Computer](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/building-your-offline-air-gapped-computer.html).
 
 4\. Shutdown/boot into Tails OS on USB on the Offline Air-Gapped Computer.
 
 5\. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”.
 
 6\. Copy MEW off the SD Card into the “Tor Browser” folder, and then open the dist folder.
 
 7\. Unplug SD card.
 
 8\. Right-click `index.html` -> “Open with Tor Browser”.
 
 9\. Enter a strong passphrase, save the wallet file in the Tor Browser folder, restore wallet with passphrase to get the address, and record the address in a text document.
 
 10\. Shutdown the Tor Browser.
 
 11\. Plug in the SD card and copy the address text file and wallet backup onto the SD card.
 
 12\. Shutdown Tails.
 
#### Basic [Offline Air-Gapped Software Wallet](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/building-your-offline-air-gapped-computer.html) with [Ian Coleman’s Bip39 Tool](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/ethereum-wallet-basics/ian-colemans-bip39-tool.html) 🌨

  1\. Download/Setup [Tails 3.0 OS](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/tails-os.html) on a USB.
  
  2\. Download/unzip/copy [Ian Coleman’s Bip39 Tool](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/ethereum-wallet-basics/ian-colemans-bip39-tool.html) onto a fresh [SD card](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/why-sd-cards-over-usb-keys.html).
  
 3\. Setup an [Offline Air-Gapped Computer](https://tra38.gitbooks.io/pro-tips-for-ethereum-wallet-management/content/offline-computing/building-your-offline-air-gapped-computer.html).
 
 4\. Shutdown/boot into Tails OS on USB on your Air-Gapped Offline Computer.
 
 5\. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”.
 
 6\. Copy the Bip39 Tool off SD Card into the “Tor Browser” folder, right-click the html file “Open With Tor Browser”.
 
 7\. Unmount/Unplug the SD card.
 
 8\. Select “Supply your own source of entropy”, and input very strong entropy.
 
 9\. Generate your Bip39 passphrase with KeePassX.
 
 10\. Safely record and backup your seed and passphrase.
<ul><li>I do not recommend recording on flash memory or SD, but if you do, make sure to encrypt this data before plugging in and saving on SD card.</li></ul>

 11\. Copy first 5 addresses to a text document.
 
 12\. Plug in SD card, copy the text document onto the SD card, and then unplug the SD card.
 
 13\. Shutdown and then reboot into Tails Offline.
 
 14\. Plug in the SD card, copy Bip39 tool off SD card into Tor Browser folder, and then right-click html file “Open with Tor Browser”.
 
 15\. Re-enter your recorded Bip39 seed and passphrase, and then check the addresses generated are the ones you recorded.