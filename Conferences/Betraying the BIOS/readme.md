# Betraying the BIOS: Where the Guardians of the BIOS are Failing
For UEFI firmware, the barbarians are at the gate -- and the gate is open. On the one hand, well-intentioned researchers are increasingly active in the UEFI security space; on the other hand, so are attackers. Information about UEFI implants -- by HackingTeam and state-sponsored actors alike -- hints at the magnitude of the problem, but are these isolated incidents, or are they indicative of a more dire lapse in security? Just how breachable is the BIOS?

In this presentation, I'll explain UEFI security from the competing perspectives of attacker and defender. I'll cover topics including how hardware vendors have left SMM and SPI flash memory wide open to rootkits; how UEFI rootkits work, how technologies such as Intel Boot Guard and BIOS Guard (and the separate Authenticated Code Module CPU) aim to kill them; and weaknesses in these protective technologies. There are few public details; most of this information has been extracted by reverse engineering.

This talk is a revisited version of the Black Hat Vegas 2017 research with new details about Intel BIOS Guard and Intel ACM’s including new vulnerabilities.

## Conferences:
* **Black Hat Vegas 2017** [slides](https://github.com/REhints/BlackHat_2017/blob/master/Betraying%20the%20BIOS.pdf) [video](https://www.youtube.com/watch?v=Dfl2JI2eLc8)
* **H2HC 2017** [video](https://www.youtube.com/watch?v=jQyzhXQexrQ)
* **Blue Hat 2017 (Revisited Version)** [video](https://www.youtube.com/watch?v=a2A-iuAGkSM)
* **ZeroNights (Revisited Version)** [slides](https://github.com/REhints/Publications/blob/master/Conferences/Betraying%20the%20BIOS/ZeroNights_17%5Bv1.5%5D.pdf) [video](https://www.youtube.com/watch?v=mTuA68JHJdw)
* **Offensivecon 2018 (Updated and Revisited Version)** [slides](https://github.com/REhints/Publications/blob/master/Conferences/Betraying%20the%20BIOS/Offensivecon_18%5Bv2.0%5D.pdf) [video](https://www.youtube.com/watch?v=kSQVGFbTfqE)

## References:
* **Who Watch BIOS Watchers?** [link](https://medium.com/@matrosov/bypass-intel-boot-guard-cc05edfca3a9)
