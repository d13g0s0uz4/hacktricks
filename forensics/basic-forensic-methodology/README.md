# Basic Forensic Methodology

*Do you use **Hacktricks every day**? Did you find the book **very** **useful**? Would you like to **receive extra help** with cybersecurity questions? Would you like to **find more and higher quality content on Hacktricks**?\
[**Support Hacktricks through github sponsors**](https://github.com/sponsors/carlospolop) **so we can dedicate more time to it and also get access to the Hacktricks private group where you will get the help you need and much more!***

If you want to know about my **latest modifications**/**additions** or you have **any suggestion for HackTricks** or **PEASS**, **join the** [**💬**](https://emojipedia.org/speech-balloon/)[**telegram group**](https://t.me/peass), or **follow** me on **Twitter** [**🐦**](https://github.com/carlospolop/hacktricks/tree/7af18b62b3bdc423e11444677a6a73d4043511e9/\[https:/emojipedia.org/bird/README.md)[**@carlospolopm**](https://twitter.com/carlospolopm)**.**\
If you want to **share some tricks with the community** you can also submit **pull requests** to [**https://github.com/carlospolop/hacktricks**](https://github.com/carlospolop/hacktricks) that will be reflected in this book and don't forget to **give ⭐** on **github** to **motivate** **me** to continue developing this book.



In this section of the book we are going to learn about some **useful forensics tricks**.\
We are going to talk about partitions, file-systems, carving, memory, logs, backups, OSs, and much more.

So if you are doing a professional forensic analysis to some data or just playing a CTF you can find here useful interesting tricks.

## Creating and Mounting an Image

- [image-adquisition-and-mount.md](image-adquisition-and-mount.md)

## Malware Analysis

This **isn't necessary the first step to perform once you have the image**. But you can use this malware analysis techniques independently if you have a file, a file-system image, memory image, pcap... so it's good to **keep these actions in mind**:

- [malware-analysis.md](malware-analysis.md)

## Inspecting an Image

if you are given a **forensic image** of a device you can start **analyzing the partitions, file-system** used and **recovering** potentially **interesting files** (even deleted ones). Learn how in:

- [partitions-file-systems-carving](partitions-file-systems-carving/)

Depending on the used OSs and even platform different interesting artifacts should be searched:

- [windows-forensics](windows-forensics/)

- [linux-forensics.md](linux-forensics.md)

- [docker-forensics.md](docker-forensics.md)

## Deep inspection of specific file-types and Software

If you have very **suspicious** **file**, then **depending on the file-type and software** that created it several **tricks** may be useful.\
Read the following page to learn some interesting tricks:

- [specific-software-file-type-tricks](specific-software-file-type-tricks/)

I want to do a special mention to the page:

- [browser-artifacts.md](specific-software-file-type-tricks/browser-artifacts.md)

## Memory Dump Inspection

- [memory-dump-analysis](memory-dump-analysis/)

## Pcap Inspection

- [pcap-inspection](pcap-inspection/)

## **Anti-Forensic Techniques**

Keep in mind the possible use of anti-forensic techniques:

- [anti-forensic-techniques.md](anti-forensic-techniques.md)

## Threat Hunting

- [file-integrity-monitoring.md](file-integrity-monitoring.md)

