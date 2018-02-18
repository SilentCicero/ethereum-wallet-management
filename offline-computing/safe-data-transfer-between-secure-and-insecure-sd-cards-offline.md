### Safe Data Transfer Between Secure and Insecure SD Cards Offline

You may want to transfer data between sensitive and nonsensitive SD cards. This should be done through Tails, preferably with encryption. Here is a quick process flow for doing a safe transfer.

Note that this does not protect against SD card reader malware. It is purely just to create some distance between cards that will touch your Air-Gapped machine and your online day-to-day computer.

Ideally, data should flow one-way (from your online machine to your offline machine). Data flowing the other way (from your offline machine to your online machine) is very dangerous as it could expose your secrets to the online machine in question. Any data transfer from the offline machine to the online machine needs to be done very cautiously.

#### Transfer Steps:

1. Plug in fresh SD card to online computer.

2. Copy tools/data/files onto the SD card.

3. Plug in Tails USB, boot into Tails Offline

4. Copy tools/data/files off the insecure SD card onto the Desktop or Home folder.

5. Unplug the insecure SD card.

6. Plugin the sensitive SD card.

7. Safely transfer files onto the secure SD card.

8. Plug in SD card to Air-Gapped machine.