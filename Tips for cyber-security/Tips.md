# Tips for cyber-security

***
## 1. Core knowledge
> **Basic security knowledge**
> - Embeded systems security and Trust Zone [[book]](https://embeddedsecurity.io/introduction)
> - Introduction to ARM Trusted Execution Environment [[blog]](https://sergioprado.blog/introduction-to-trusted-execution-environment-tee-arm-trustzone/)
> - Memory protection [[report]](https://cyber-itl.org/2019/08/26/iot-data-writeup.html)

> **Penetration testing**
> - Practical Guide To Penetration Testing [[Book]](https://gbhackers.com/wp-content/uploads/2022/08/The-Hacker-Playbook-2_-Practical-Guide-To-Penetration-Testing-PDFDrive-.pdf)

> **Vulnerabilities**
> - Buffer overflow

***
## 2. Tips for component security
## ***Hardware***
### ***Hardware security***
### ***Hardware hacking***
> **Tutorial** [[blog]](https://ivanorsolic.github.io/tags/hardware-hacking/ "Hardware Hacking")

> **JTAG** [[paper]](https://www.researchgate.net/publication/329373688_Exploiting_JTAG_and_its_mitigation_in_IOT_A_survey "Exploiting JTAG and its mitigation in IOT: A survey")

> **UART** 
> - [[UART hacking]](https://web.archive.org/web/20210116054244/https://techblog.mediaservice.net/2019/03/a-journey-into-iot-hardware-hacking-uart/ "A journey into IoT – Hardware hacking: UART") 
> - Practical Reverse Engineering [[1]](https://jcjc-dev.com/2016/04/08/reversing-huawei-router-1-find-uart/)

> **I2C** [[blog]](https://security.humanativaspa.it/a-journey-into-iot-chip-identification-busside-and-i2c/ "A journey into IoT – Chip identification, BUSSide, and I2C")

> **SPI** [[blog]](https://www.iotpentest.com/2019/06/dumping-firmware-from-device-using.html?m=1) [[2]](https://jcjc-dev.com/2016/04/29/reversing-huawei-router-2-scouting-firmware/) [[3]](https://jcjc-dev.com/2016/05/23/reversing-huawei-3-sniffing/) [[4]](https://jcjc-dev.com/2016/06/08/reversing-huawei-4-dumping-flash/) [[5]](https://jcjc-dev.com/2016/12/14/reversing-huawei-5-reversing-firmware/)
### ***Hardware hacking tools***


***

## ***Software***
### ***Boot***
> **Security**
>   

### ***Linux***
> **Security & hardening**
Introduction to Linux security [[blog #1]](https://sergioprado.blog/introduction-embedded-linux-security-part-1/) [[blog #2]](https://sergioprado.blog/introduction-embedded-linux-security-part-2/)
> - Linux kernel security [[codeblog]](https://outflux.net/blog/archives/category/kernel/ "codeblog") [[Programming guide]](https://sysprog21.github.io/lkmpg/)
> - Anti-debugging & anti-analysis [[github:Rust lib]](https://github.com/0xor0ne/debugoff)
> - Learning Linux internals & reverse engineering [[github]](https://github.com/michalmalik/linux-re-101 "A collection of resources for linux reverse engineering")
> - Linux debugging & tracing [[traning]](https://bootlin.com/doc/training/debugging/debugging-slides.pdf)

> **Exploitation**
> - Linux kernel #1 [[Github]](https://github.com/xairy/linux-kernel-exploitation "xairy/linux-kernel-exploitation") 
> - Linux kernel #2 [[debug]](https://blog.k3170makan.com/2020/11/linux-kernel-exploitation-0x0-debugging.html?m=1) [[stack overflow]](http://blog.k3170makan.com/2020/11/linux-kernel-exploitation-0x1-smashing.html?m=1) [[privilage escalatoon]](https://blog.k3170makan.com/2021/01/linux-kernel-exploitation-0x2.html?m=1)


### Examples of reverse engineering & Exploit
> [[Examples]](https://github.com/updf83/Public-directly/blob/main/Tips%20for%20cyber-security/Reverse%20engineering%20and%20exploit.md)

### ***Tools***
> **Hacking tools**
> - Debugger [[gef]](https://github.com/bata24/gef "bata24/gef")
> - Reversing [[frida-Ghidra]](https://security.humanativaspa.it/ghidra2frida-the-new-bridge-between-ghidra-and-frida/)

***

## ***Communication***
### ***Cellular***
> **Security**
>

> **Exploit**
>

> **Tools**
>

### ***Wi-Fi***
> **Security**
> - Wi-Fi security [[Web]](https://tbhaxor.com/offensive-wifi-security/ "Offensive Wi-Fi Security")

> **Exploit**
> - Mind maps & cheatsheets [[Github]](https://github.com/koutto/pi-pwnbox-rogueap "koutto/pi-pwnbox-rogueap") [[Wiki]](https://github.com/koutto/pi-pwnbox-rogueap/wiki "koutto/pi-pwnbox-rogueap")

> **Tools**
>

### ***Bluetooth***
> **Security**
>

> **Exploit**
> - Bluetooth Attack & Defence [[Github]](https://github.com/Charmve/BLE-Security-Attack-Defence "Charmve/BLE-Security-Attack-Defence")
> - SweynTooth vulnerabilities [[Web]](https://asset-group.github.io/disclosures/sweyntooth/ "Unleashing Mayhem over Bluetooth Low Energy") [[Github]](https://github.com/Matheus-Garbelini/sweyntooth_bluetooth_low_energy_attacks "Matheus-Garbelini/sweyntooth_bluetooth_low_energy_attacks")

> **Tools**


### ***NFC***
> **Security**
>

> **Exploit**
>

> **Tools**
>

### ***USB***
> **Security**
> - USB Threats & best practices [[paper]](https://honeywellprocess.blob.core.windows.net/public/Marketing/White-Paper-USB-Security-Myths-vs-Reality.pdf "Latest USB Security Threats & Best Practices to Follow")

> **Exploit**
> - USB cyber attack [[paper]](https://www.sciencedirect.com/science/article/pii/S0167404817301578 "USB-based attacks") [[Article]](https://www.bleepingcomputer.com/news/security/heres-a-list-of-29-different-types-of-usb-attacks/ "Here's a List of 29 Different Types of USB Attacks")

> **Tools**
> - USB Fuzzer [[paper]](https://nebelwelt.net/publications/files/20SEC3.pdf "USBFuzz: A Framework for Fuzzing USB Drivers by Device Emulation") 


### ***CAN(Contoller Area Network)***
> **Security**
>

> **Exploit**
>

> **Tools**
>

### ***Others***
> **Security**
>

> **Exploit**
>

> **Tools**
>

***

## ***Programming & CTF***
### **Programming**
> - Competitive programming [[Book's Appendix]](https://github.com/updf83/private-work/blob/main/Intelligence/Collection%20source.md "競技プログラミングの鉄則 ～アルゴリズムと思考力を高める 77 の技術～")

### ***CTF***
> - CTF [[ImaginaryCTF]](https://imaginaryctf.org "Daily CTF Challenges For Everyone:")

### **OSINT**
> - Tool Collection [[Github]](https://github.com/cipher387/osint_stuff_tool_collection "cipher387/osint_stuff_tool_collection")
