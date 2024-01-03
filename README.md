# flipperzerophone
Why buy the 'flipper zero' if you have your old smartphone?

![photo1704247773](https://github.com/francescofusca/FlipperZeroPhone/assets/118103038/f68dc573-0577-4adc-92f9-33d4055eb91a)


# Description
Hello to all the GitHub community! This is the first project I'm publishing here. It's a project I abandoned a few years ago, but now I want to complete it entirely beyond its current state by running all the necessary tests.

Since the release of the Flipper Zero, I've always wanted to have one after seeing many viral videos showcasing its capabilities, especially being passionate about cybersecurity. However, I wasn't keen on spending all that money (around 300/400$ ~). So, I decided to take my "old" Redmi Note 7 and transform it as much as possible into a Flipper Zero, not in terms of physical appearance, but in functionality.

In short, I rooted the device using (TWRP) Magisk and downloaded its modules (Kali-Nethunter, Systemless Hosts, Wireless Firmware for Nethunter). Fortunately, I found its kernel to enable functionalities like Bad USB and a WiFi adapter. Of course, I installed Kali Nethunter, which was already in the ROM. If you can't find Magisk modules, you can find them on Fox MMM.

**Quick Tip:** For quickly inserting and removing microSD cards, I use a TF/SD USB adapter. This makes the process smoother and more efficient.

Trying to replicate all the tools present in the Flipper Zero:
- RFID: I'm still looking for a better solution, but the quickest ones that come to mind are mfkey32 (a valid RFID solution or another read/writer with software connected to the phone) and Mifare Attack (an outdated solution due to NFC and RFID differences).
- NFC, Bluetooth: My phone has NFC and Bluetooth. I plan to test attacks, especially with Bluetooth, even though some may not be supported with the internal Bluetooth (VHCI or bt_smd). For the rest, these are things that need to be activated in the kernel or in devices with the mentioned driver.
- Infrared Transmitter: My phone has infrared trasm, but there are many inexpensive ones on web.
- Hardware Exploration: I found little for this part, but on web, there are countless modules like Raspberry Pi GPIO. Writing code can be done using Termux or the terminal provided in the ROM.
- iButton: If interested, you can find online resources with GPIO or through hardware exploration or using separate modules (although the latter is not widely used in Europe, depending on the region).
- RF Attack: Modules with attached transceivers can be found online, making them easy to use.
- Bad usb: I use Racky (Kernel Attention!).

And of course, with Kali Linux, the possibilities are endless. You can explore a myriad of tools by referring to the guide or conducting research online about the latest trends in attacks.

I conceived this project out of passion, not to launch attacks on anyone. All the tests I've conducted were on my local network and my own devices! If you want to contribute to the project in any way, even just with an idea, I'll be ready to invest time and welcome it with pleasure. I'll communicate any additions or plans immediately!

**Fun Fact:** I managed to test everything on 3 devices, one of which is quite beat up, lol. If you see the phone tilted to the left with half the screen, it's because I changed the resolution.

Certainly, I won't be here publishing all the ROMs, recoveries, and basic stuff like everyone does on GitHub, or providing commands on how to download or implement such things. This project was intended to inspire ideas and encourage individuals to explore beyond the basics. For anything you're unsure about, educate yourself—there's a wealth of information available online. However, I'm still here and available to assist you!

PS: It's not always guaranteed that things found online are secure and functional. I assume no responsibility; <strong>be cautious!</strong> For any information, I'm here!
