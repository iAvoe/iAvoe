I can do enterprise networking & security analytic things, video encoding via x264 and x265 (tutorials and tools development), PSScript/Shell/Batch development, music recomposition via FL Studio, and above junior level of After Effects, Premiere, PhotoShop
  - I've made a few dozen music recompositions at https://www.youtube.com/channel/UCfvTs_azeQE-dlFsHMDZhHw
  - TODO: Implement ACL/QoS speed limit for Windows/iOS updates, it appears that ASUS-Merlin along can't deal with this
  - AAA stands for Authenticaion, Authorization, Accounting
  - Currently studying: .NET programming with advanced Windows Forms (via PSScript)

###### Enterprise networking joke #1:
 1. Separate LANs with VLAN so the LAN splits
 2. Implement inter-VLAN routing so they reunites

###### Enterprise networking joke #2:
 - The term "high-availability" is basically a DJ Khaled meme:
   1. another one (IPMI / redundant PSU)
   2. another one (DRBD)
   3. another one (Heartbeat / failover)
   4. another one (HSRP / VRRP)
   5. another one (ISP Redundancy, Canadians actually needs this)
   6. an---d another one (Cross-Region or cloud disaster recovery backup)

###### Idea for a DHCP trap security measure:
 - For extra-secure organizations
 - New device (ID-ed by MAC address occurance counter VS average occurance):
   - Gets assigned to a trap-like address pool
   - Where ex-ACL (extended access list) blocks most of protocols and access to organization devices
 - This should be a low cost measure that just work without special software or hardware, but some tuning is needed
 - The networking specialist / Operator needs to check the trap address pool at work
 - This idea could turn to be a facepalm, or someone probably would already have it implemented and it's just that me not knowing

###### Reads:
  - CVE-2019-3753, CVE-2018-8641, CVE-2019-14615, CVE-2019-1378, CVE-2021-27070, CVE-2021-36945, CVE-2021-42297, CVE-2021-43211

###### List of OSes I've spent a LOT of time with
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
    - True DMZ
   
###### My Desktop Computer:
| Type        | Model                          | Info                                                                                                                      |
|-------------|--------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| Motherboard | *MPG B650 EDGE WIFI*           | MS-7E10                                                                                                                   |
| Porcessor   | *Ryzen 7 7700X*                | PBO -21 OC                                                                                                                |
| CPU cooler  | *Le Grand Macho RT w/ AM5 kit* | the oldest possible AM5 cooler                                                                                            |
| Memory:     | *F5-6400J3239G16G*             | 6200MT/s w/ subtiming OC                                                                                                  |
| Display:    | *LU28R55*                      | Broken, then warranty repaired                                                                                            |
| GPU:        | *RTX 3070 ti*                  | planning to sell it                                                                                                       |
| PSU:        | *Corsair RM1000x*              | 2nd handed                                                                                                                |
| Drive:      | *Crucial CT1000P3P*            | NVME 1TB PCIE Gen4 QLC                                                                                                    |
| Drive:      | *Crucial MX500SSD*             | SATA 500G                                                                                                                 |
| Drive:      | *Micron  1100 SATA*            | SATA 2TB second handed                                                                                                    |
| Drive:      | *Segate  ST4000NE*             | SATA 4TB emergency purchase                                                                                               |
| Drive:      | *HGST    HUH728080*            | SATA 8TB second handed                                                                                                    |
| Drive:      | *Segate  ST10000NM*            | SATA 10TB second handed                                                                                                   |
| Drive:      | *Samsung T5*                   | USBC 500GB                                                                                                                |
| Mouse:      | *G502 Proteus Core*            | You can buy replacement for every single part of it on Aliexpress, this means it will never die, incredibly high in value |
