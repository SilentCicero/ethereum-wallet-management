### Downloading and Validating Ian Coleman's Bip39 Tool on Tails

#### Downloading

There are two ways to to download the tool: from the main site or from the Github release page.

##### Main Site
1. Go to https://iancoleman.github.io/bip39/

2. Right-click, “Save as…”

3. Select “Webpage [Complete]..”

4. Save the Webpage on to a SD card.

##### Github Repository
1. Go to Ian Coleman's Bip39 tool's Github release page (link: https://github.com/iancoleman/bip39/releases).

2. Go to releases and then download the latest version's .html file.

3. Save the Webpage on to a SD card.

#### Using The Tool On Tails

1. Boot into Tails Offline.

2. Select “Places” (top right on screen) → “Tor Browser”.

3. Copy the .html file off the SD card into the “Tor 
Browser” folder.

4. In the Tor Browser Folder, right click the file and “Open with Tor Browser”.

### Validating Ian Coleman’s Bip39 Tool

The process of validating the tool is the same no matter whether you downloaded it from the main site or the Github release page. 

1. In Linux or Tails, `cd ./path/to/bip39-standalone.html` then run `sha256sum ./bip39-standalone.html`.

4. Compare the result with the one listed on the release in Github.

5. Compare the result with the tweet on twitter by Ian Coleman: `https://twitter.com/bip39tool`

6. If all hashes match up, you have the right file.

7. (Optional) On a phone or separate connection, check to see if the Github hash and Twitter hash all are the same. Having multiple points of reference from multiple connections are a way to validate the tools integrity (GPG and Bittorrent are also good methods if available).