# Modern Secure Boot Attacks: Bypassing Hardware Root of Trust from Software
Many hardware vendors are armoring modern Secure Boot by moving Root of Trust to the hardware. While it is definitely the right direction to create more difficulties for the attacker, many layers of code exist between hardware and firmware. Also, hardware vendors are always fighting for boot performance, which creates interesting security issues in actual implementations.

In this presentation, I'll explain new security issues to bypass a specific implementation of Intel Boot Guard technology in one of the most common enterprise vendors. The actual vulnerability allows the attacker to bypass Intel Boot Guard security checks from OS without physical access to the hardware. Also, I'll cover topics including Embedded Controller (EC) with focus on UEFI Firmware cooperation and Authenticated Code Module (ACM) runtime environment. It is brand new research not based on my previous Boot Guard discoveries.


## Conferences:
* [Offensivecon 2019](https://www.offensivecon.org/speakers/2019/alex-matrosov.html) [video](https://www.youtube.com/watch?v=Ap-2CnoyBek)
* Amazon Red Team Summit [RTS 2019](https://redteamsummit.com)
* [BHASIA 2019](https://www.blackhat.com/asia-19/briefings/schedule/#modern-secure-boot-attacks-bypassing-hardware-root-of-trust-from-software-13950)
* [OPCDE 2019](https://emirates.opcde.com/speaker/alex-matrosov/) [video](https://www.youtube.com/watch?v=TuaP7fG4_rk)
* [Ekoparty 15](http://ekoparty.org/editions/eko15/charlas/bypassing-root-trust.php)
