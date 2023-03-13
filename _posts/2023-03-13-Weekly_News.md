
---

I have been waiting for a cost-effective RISC-V-based development for several years. The VisionFive 2 SBC seems to be coming close at $90 for a 4GB SBC that is currently available for retail. Based on what I have seen so far, they seem to do a good job of making the documentation and source code available.

The biggest issue that I have seen so far has been managing expectations about the user experience with the new VisionFive 2 boards. StarFive is a very small organization compared to some of the other System on a Chip Vendors and Single Board Computer manufacturers. At the end of the day, they have to generate enough profit selling chips and boards to pay their engineering and development staff to continue doing post-sale software development.

**Current state**

**Getting started** 

For those just interested in getting Linux up and running on their board, the best place to start is the Quick Start Guides at https://doc-en.rvspace.org/VisionFive2/Quick_Start_Guide/index.html and https://doc-en.rvspace.org/VisionFive2/PDF/VisionFive2_QSG.pdf. It is a surprisingly complete document.

I must admit that I found the online content management system rather clunky. The PDF was straightforward but does need to be kept up-to-date with the current shipping boards and software. 

**Operating System**

The current support Operating system is located at https://github.com/starfive-tech/VisionFive2/releases/tag/VF2_v2.10.4. It is based on Debian Linux with some board and chip-specific patches.

VisionStar is building its Operating System on version 5.15 of the Linux Kernel, released in October of 2021. It would be great to hear from VisionStar why they settled on the release and what their plans are moving forward. I guess that it is a matter of assigning developer time to the job of porting the Linux kernel 6.1.

One issue that seems to be catching users off guard is the fact that you can not use the Debian upgrade process of ‘apt-get upgrade’ to upgrade your operating system on the VisionFive 2. All of the plumbing does not yet seem to be in place for an onboard upgrade, so you must currently download and burn a new OP image manually.

I look forward to seeing what kind of release cadence is used for operating system upgrades.
 
**In the media**

Jeff Geerling did a great review at https://www.youtube.com/watch?v=aFze0XVhHZA&t=2s I highly recommend it to anyone interested in starting with a RISC-V board. He is critical yet fair. 

Two other channels worth noting are https://www.youtube.com/@LivingLinux/videos and https://www.youtube.com/@CyReVolt/videos. Both @LivingLinux and @CyReVolt are smaller channels. However, they are creating some very interesting content for new ‘hardware hacker’ who wants to look a bit deeper under the covers.

**Resources**

The best current resource list is https://forum.rvspace.org/t/visionfive-2-faq-quick-links/1376 thanks, @selina and @mzs.

**Development** 

For the week of March 5, 2023, to March 12, 2023

VisionFive OS image https://github.com/starfive-tech/VisionFive2/pulse

2 Merged pull requests, 0 Open pull requests, 0 Closed issues, and 1 new issue.

VisionFive Kernel https://github.com/starfive-tech/linux/pulse

0 Merged pull requests, 4 Open pull requests, 0 Closed issues, and 0 new issues.

**Future updates**

If anyone finds this interesting or valuable, please provide links and suggestions for additional information, topics, and corrections.