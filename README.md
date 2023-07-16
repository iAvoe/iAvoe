### Hi there 👋

<!--
**iAvoe/iAvoe** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

List of OS/distributions I've used or got fimiliar with
 - Android 4, 6, 9, 10
 - Windows 7, 10
 - Ubuntu LTS 18.04
    - Deployed a high availably website stack for school project, with OpenWRT with true DMZ
    - Tried out Docker and 
 - Red Hat / RHEL 7, 8
    - Kickstart (with enough configurations you may actually clone your RHEL OS with it)
      - The idea that you could configure things without needing a restart like:
      - "echo 10.0.1.100 thatmachine>>/etc/hosts", "echo PREFIX=24>>/etc/sysconfig/network-scripts/ifcfg-enp0s3" (network setting)
      - is kind of mindblowing, whereas Windows Deployment Server is Windows-Server exclusive and clunky for home users
    - nftable
      - Unintuitive and easy to make configuration mistakes
      - Kind of difficult to troubleshoot, meh
    - nmap & nessus scanners
    - Git server
    - Ansible & its playbook
    - GPG encryption & decryption
    - Bash scripts
      - Created some cool scripts such as:
        - Change tracking over time (record MD5 hash for fiels in a folder to text, then track hash change over time for these text files)
 - Cisco IOS
   - Enterprise networking, the real deal
 - Kali Linux
   - Anti-networking, the deal breaker, used for a lab only


I believe the "high-availability" industry term in sometimes can be a fancy-ed up for "buy another one", kindly change my mind



####Enterprise networking joke 1 that should be functional:
 1. Separate LANs with VLAN
 2. Implement inter-VLAN routing which puts them back together
 3. Congratulations, you've achieved NOTHING!!
 - Baldi's Basics SFX can be inserted, too

####A really good enterprise networking joke that really should be good:
 - The term "high-availability" is basically:
 - "another one (DRBD), another one (heartbeat)... another one (HSRP)... annnnd another one (IPMI) ——DJ Khaled"
 - Edit the original meme video is likely to double the fun

####AAA stands for Authenticaion, Authorization, Accounting... MUST REMEMBER...
 - If ever, failing to recall when someone asked you about it, your career is going to a down spiral

I may have invented a networking security measure called DHCP trap for secure organization, where a new device (ID-ed by MAC address occurance counter being much less than average occurance), gets assigned to a trap-like address pool where extended ACL (access list) blocks most of protocols and access to organization devices, this should just work without special software or hardware and can be implemented very quickly in SOHO environments.
 - The networking specialist / Operator needs to check the trap address pool at work
 - This idea could turn to be a facepalm, or someone probably would already have it implemented and it's just that me not knowing
