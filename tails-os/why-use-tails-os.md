## Why Use Tails OS For Wallet Creation/Management

Tails OS is designed with privacy in mind, and security a close second. It is among the best choices I can find of the available Linux distros for sensitive data handling and management. It has the following security features:

- It can be run in offline, in a no networking enabled mode, upon boot.

- AppArmour enabled by design and root terminal required for execution (meaning it’s hard to run any sort of bin or executable without going through a few steps), making it even harder to attract and run malware.

- Is stateless by default (meaning all files copied to the “amnesia” directory or subdirectories will be forgotten and wiped upon successful shutdown).

- It has basic cryptographic tools like GtkHash MD5 hashing utilities (Applications → Accessories → GtkHash) to hash verify files or software was downloaded properly and intact (less chance of tampering).

- Comes equipped (like many Linux distros) with KeePassX, for password management/creation/encryption/storage.

- Contains Safe Browsing/execution environment by-default.

      - All local, offline JS/HTML apps/webpages must be safely copied to the safe “Tor Browser” folder before being executed.


- A firm, irreversible “Wipe” function can be used to delete sensitive files (right-click...“Wipe”), such as files containing seeds or passphrases.

- Comes equipped with default compression with strong encryption options, like .7z via AES (to use, simply right-click “Compress”.. .7z).

- Contains enough browsing capability to run some basic HTML/JS offline Ethereum Tools.

The Tails USB is also simple and cannot be written to once formatted when setup with the Tails Installer.