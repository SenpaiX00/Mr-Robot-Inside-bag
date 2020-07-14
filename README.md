DeepSound
If you’re wondering why someone who’d fry his computer’s memory chip in the microwave would be careless enough to store evidence of people he’s hacked on CD-ROMs disguised as CDs, then Elliot’s one step ahead of you. He used DeepSound, an audio converter tool, to hide all of the files on everyone he’s hacked—as well as his own old family photos—within WAV and FLAC audio files. And yes, the real files are encrypted and password protected, as we saw in episode 9. DeepSound is a modern example of steganography, the art of concealing information within plain sight.

ProtonMail
If you assumed Elliot would run his own server or be an early adopter of Pond , episode 8’s revelation that he has a ProtonMail account may have come as a surprise. ProtonMail is a browser-based email service incorporated in Switzerland created by researchers who met at a CERN research facility. (Yes, that CERN: the one where the World Wide Web was born.)

“One of the benefits of ProtonMail is that it’s end-to-end encryption, and it’s in a way that even the owners of ProtonMail can’t see your content, and there’s no IP logging,” says Michael Bazzell, one of the technical advisers on the show. It even lets you set expiration dates for your emails, after which they’ll self-destruct (provided the recipient hasn’t made a copy of them, that is). ProtonMail is free, though there’s a wait list for invitations to create an account. Beta versions of iOS and Android mobile apps were just announced, and it’s possible to jump the queue with a $29 donation. The next batch will be released Thursday.

Raspberry Pi
A Raspberry Pi is that tiny and delightfully inexpensive computer that helps you learn programming and build your own digital toys. Turns out, it can also be used to gain remote access to HVAC systems. On the show, Elliot’s plot was to gain access using the Pi and then raise the temperature in Evil Corp’s storage room where tape backups are stored, thus destroying the records of much of the consumer debt in the world.

Tastic RFID Thief
Fsociety wouldn’t even think of trying to penetrate the most secure facility in the country without a plan for stealing badge information from employees. Luckily, when visiting Steel Mountain, fSociety member Mobley was armed with Bishop Fox’s Tastic RFID Thief, a long-range radio frequency identification (RFID) reader that saves your score on a microSD card as a text file so you can clone the badge later. It’s completely portable and fits neatly into a messenger bag or a briefcase.

RSA SecurID
Two-factor authentication can definitely foil your average fraudster’s plans. Like 25,000 actual organizations worldwide, Allsafe, the cybersecurity firm where Elliot works, uses RSA SecurID. RSA SecurID's two-factor authentication adds a layer of security to a company's protected resources by requiring users to not only enter their RSA SecurID pin, but a one-time password generated within the app—which lasts only 60 seconds. This is why Elliot needed a multi-faceted plan to get ahold of Gideon’s phone in episode 8. First he texted him large MMS files to try to drain some of his boss’ battery, then he snagged the phone to enter that temporary authentication code at the end of the password with nary a second to spare. He certainly raised suspicion from Gideon with the clever ruse, but at least he got the job done.

Kali Linux
Kali Linux, BackTrack’s Linux’s successor, is a Debian-based version of Linux that’s specifically built for penetration testing and security auditing and is used in multiple episodes of Mr. Robot. It’s free, open source, and pre-installed with hundreds of pen testing programs, so it’s perfect for cracking Wi-Fi passwords, bypassing anti-virus software, and testing security vulnerabilities on your network. Many of the tools used in Mr. Robot are utilized within Kali. “That’s the benefit of Kali is that all the tools are built in,” says Bazzell. “It’s got a distribution system with everything you need.”

John the Ripper
John the Ripperis a tool that Elliot used in the second episode of the show to crack Tyrell’s password. Its primary purpose is to detect weak Unix passwords, but it can crack weak passwords with several thousand (or even several million) attempts per second. John the Ripper is available within the Kali Linux platform.

Metasploit and Meterpreter
Episode 6 features Rapid7’s Metasploit Framework. Metasploit is an exploit development and delivery system that allows users to create and execute exploits, typically for penetration testing. It saves hackers time because they don’t have to learn a new tool each time they want to run an exploit. Meterpreter is just one of several hundred payloads that can be used within Metasploit. It resides entirely in memory and writes nothing to disk, but can give an attacker control of their target’s system and parts of the network. It’s often used within Kali Linux on a virtual machine in Windows, or on Windows itself.

Social-Engineer Toolkit
TrustedSec’s Social-Engineer Toolkit is an open-source pen testing framework designed specifically for simulating social engineering attacks, such as phishing, spear phishing, credential harvesting, and more. Elliot used SMS spoofing from within SET, a module that’s unavailable on the newer versions, but Mr. Robot tech adviser Michael Bazzell said that it’s possible for users to add that package back in within the new version.

FlexiSPY
This list would be remiss without the inclusion of a tool used by one of the show’s less sympathetic characters. In the third episode of Mr. Robot, Tyrell Wellick secretly installs mobile monitoring software on a lover’s Android phone. After gaining root privilege by using SuperSU, he installs FlexiSPY, a tool that lets you monitor other people’s device activities with an online portal. FlexiSPY doesn’t recover past data, but can show you anything still stored on their phone’s memory or SIM card, as well as any future. It also hides SuperSU as part of its installation.
