### Why SD Cards over USB Keys

- SD Cards are simply a leaner and simpler flash memory chip than USBs (meaning they have less firmware and less accessible firmware, from what I’ve researched).

- By design they contain simpler hardware than USBs, but still none the less have firmware of some kind. They are slightly less complex than microSDs, but virtually the same from a vulnerabilities perspective.

- They are not good for medium to long term storage as the memory is not intended for long term storage use. Their life span ranges anywhere from 3 to 20 years depending on the chip quality, how often it is used, and if you win the factory lottery of having a chip with 20%+ good data storage blocks.

- They should only be used for data transfer and short to medium term storage. Recording important data should be done on more reliable mediums (e.g. whatever has lasted historically) within reliable environments (with little to no fluctuating temperature, moisture, static etc).

- Also remember to turn the lock write protection on, once you are done writing data to them (no need to have it off unless you are swapping data).

- Assume 80%+ of the memory blocks inside portable flash memory (i.e. SD, microSD, USB) to be bad/invalid/corrupt within the hardware, and the little micro-controller inside (that can be infected or reprogrammed as loggers etc) trying to present to you a guess of what is on the good/bad blocks within the flash (I know...it's insane).

- They can be infected with malware (as most contain a tiny microprocessor to fix their bad block management).

- Redundancy among multiple storage mediums (digital and analog) is probably a good choice for longer term data storage and protection

- Only writing to the cards once and locking them to Offline Air-Gapped computers helps protect the data being transferred.

- Follow the guide for safe data transfer on and off these cards. Using offline computers also goes a long way as well in protecting against malware or infected SD cards.

### Further Reading:
- http://bunniefoo.com/bunnie/sdcard-30c3-pub.pdf

- https://techcrunch.com/2013/12/29/sd-cards-arent-as-secure-as-we-think/

- https://www.dpreview.com/forums/thread/2006174

- https://www.infosecurity-magazine.com/news/the-ubiquitous-sd-cards-can-be-hacked-to-deliver/ 

- https://www.bunniestudios.com/blog/?p=3554

- https://www.apotelyt.com/photo-memory/sd-card-reliability