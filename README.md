###### List of OS/distros I've spent a lot time on or got pretty fimiliar with
 - **Android** 4, 6, 9, 10
 - **Windows** 7, 10
   - MS SQL Server
 - **Cisco IOS**
   - Enterprise networking, I've spent more time using it than all non-Android Linux distros combined
 - **Ubuntu** LTS 18.04, 20.04
    - Libre Office impressivly opened my x264 tutorials correctly, given the complexity and advanced formattings were used inside
    - Tried out Docker, the docker account registration was a tune down
    - Deployed a high availably website stack for school project
    - phpMyAdmin feels better designed than Microsoft IIS
 - **Red Hat / RHEL** 7, 8
    - Wrote a bunch of shells
    - Ansible & its playbook
    - Git server, GPG
    - nftable, nmap
    - Kickstart
  - **OpenWRT**
    - QoS perVLAN / SQM load balancing (it works but my home internet is Canadian so I can't tell if it has performance issues)
    - ACL (not working, no module found, too)
    - Zone based firewall (ZPF, it works)
    - NTP to Windows & Ubuntu
    - True DMZ (yes it works)
    
###### Enterprise networking joke 1, should be decent:
 1. Separate LANs with VLAN
 2. Implement inter-VLAN routing which puts them back together
 3. Congratulations, you've achieved NOTHING

###### Enterprise networking joke 2, should be more than decent:
 - The term "high-availability" is basically:
   1. another one (DRBD)
   2. another one (heartbeat)
   3. another one (HSRP)
   4. annnnd another one (IPMI or redundant PSU)  ——DJ Khaled

###### AAA stands for Authenticaion, Authorization, Accounting... MUST REMEMBER
 - Forgetting this may cause serious trouble

###### Idea for a DHCP trap security measure:
 - For extra-secure organizations
 - New device (ID-ed by MAC address occurance counter VS average occurance):
   - Gets assigned to a trap-like address pool
   - Where ex-ACL (extended access list) blocks most of protocols and access to organization devices
 - This should be a low cost measure that just work without special software or hardware, but some tuning is needed
 - The networking specialist / Operator needs to check the trap address pool at work
 - This idea could turn to be a facepalm, or someone probably would already have it implemented and it's just that me not knowing

###### My Desktop Computer:
 - Motherboard: *MPG B650 EDGE WIFI* (MS-7E10)
 - Porcessor:   *Ryzen 7 7700X* (PBO -21 OC)
 - CPU cooler:  *Le Grand Macho RT w/ AM5 kit* the oldest possible AM5 cooler
 - Memory:      *F5-6400J3239G16G*    6200MT/s with subtiming OC
 - Display:     *LU28R55*             Broken and then warranty repaired
 - GPU:         *RTX 3070 ti* (planning to sell it since I've spent no time on FPS gaming anymore)
 - PC Case      *Corsair 4000D White* 2nd handed
 - PSU:         *Corsair RM1000x*     2nd handed
 - Drive:       *Crucial CT1000P3P*   NVME 1TB  PCIE Gen4 QLC
 - Drive:       *Crucial MX500SSD*    SATA 500G
 - Drive:       *Micron  1100-SSD*    SATA 2TB  second handed
 - Drive:       *Segate  ST4000NE*    SATA 4TB  emergency purchase
 - Drive:       *HGST    HUH728080*   SATA 8TB  second handed
 - Drive:       *Segate  ST10000NM*   SATA 10TB second handed
 - Drive:       *Intel   SC1NA400G*   SATA 400GB
 - Drive:       *Samsung T5*          USBC 500GB
 - Mouse:       *G502 Proteus Core*   You can buy replacement for every single part of it on Aliexpress, this means that it will NEVER die and always ready for endless re-try for modifications, and not forget to mention that it supports the lighter G903 mouse wheel, and various grip stickers, extra sleek bottom pads, ZERO-SCREW shell mounting that allows you to open it's shell under 10 seconds with bare hands (after removing the bottom screws once), it is also one of the rare being that comes with a switchable free-rotating wheel, which allows a smooth viewing of massive research papers, code bases, video projects, FL Studio with ease, AND because of it's price drops each year. You don't deny its omnisigmapeakprime ultras the homo-sapien computer industry
 - Controller:  *Microsoft QAU-00021*
 - Keyboard:    *FL eSports wired + Gatreon G Pro 3pin Milky + Some scissor-cut foams inside keyboard's body*

###### Reads:
  - CVE-2019-3753, CVE-2018-8641, CVE-2019-14615, CVE-2019-1378, CVE-2021-27070, CVE-2021-36945, CVE-2021-42297, CVE-2021-43211
  - Don't read CVE-2022-31501~31588


  - I've made music recompositions at https://www.youtube.com/channel/UCfvTs_azeQE-dlFsHMDZhHw
