# Note
This is a messy list of links I'm picking up in course of a security training. I will structure it when I got time, so please be patient.
# Security Sources
* [Grayhat Warfare](https://grayhatwarfare.com/)
* [Common Vulnerability Scoring System SIG](https://www.first.org/cvss/) The CVSS SIG continues to work on gathering feedback and updating CVSS v4.0. The CVSS documentation, including the User Guide, FAQ, and Examples have seen updates since the initial release in November 2023. Currently, the CVSS SIG is developing a roadmap for future updates to the standard. To that end, the CVSS SIG has created a survey to understand the usage of CVSS in general and the new CVSS v4.0 in particular.
  * [CVSS Vector Strings](https://qualysguard.qg2.apps.qualys.com/qwebhelp/fo_portal/setup/cvss_vector_strings.htm) CVSS Base and Temporal scores are represented as a numeric value and also as a vector string. The vector string is a textual representation of the metric values used to determine the score.


* [CVE](https://cve.mitre.org/)
* [National Vulnerability Database](https://nvd.nist.gov/) The NVD is the U.S. government repository of standards based vulnerability management data represented using the Security Content Automation Protocol (SCAP). This data enables automation of vulnerability management, security measurement, and compliance. The NVD includes databases of security checklist references, security-related software flaws, product names, and impact metrics. For information on how to cite the NVD, including the database's Digital Object Identifier (DOI), please consult NIST's Public Data Repository.
* [Common Weaknes Enumeration](https://cwe.mitre.org/) The 2024 CWE Top 25 is here! Often easy to find and exploit, these can lead to exploitable vulnerabilities that allow adversaries to completely take over a system, steal data, or prevent applications from working. The Top 25 highlights the most severe and prevalent weaknesses behind the 31,770 CVE® Records in this year’s dataset.
* [IBM X-Force Exchange](https://exchange.xforce.ibmcloud.com/search/%23c2)

# Vulnerability Scanners
* [OpenVAS](https://tryhackme.com/r/room/openvas) OpenVAS, an application used to scan endpoints and web applications to identify and detect vulnerabilities. It is commonly used by corporations as part of their mitigation solutions to quickly identify any gaps in their production or even development servers or applications. This is not an end all be all solution but can help to get rid of any common vulnerabilities that may have slipped through the cracks.  
  * [OpenVAS on Github](https://github.com/greenbone/) This repository contains the scanner component for Greenbone Community Edition.
  * [Greenbone Community Documentation[https://greenbone.github.io/docs/latest/background.html]
* [Tenable Nessus® Essentials](https://www.tenable.com/products/nessus/nessus-essentials) As part of the Tenable Nessus family, Tenable Nessus Essentials allows you to scan your environment (up to 16 IP addresses per scanner) with the same high-speed, in-depth assessments and agentless scanning convenience that Nessus subscribers enjoy.
  * [Nessus for Education](https://www.tenable.com/tenable-for-education/nessus-essentials?edu=true) To register to use Nessus Essentials for education, please complete the following form. There is no cost for students and instructors.
* [GFI LanGuard](https://gfi.ai/products-and-solutions/network-security-solutions/languard) Patch management, vulnerability scanning, and network auditing - GFI LanGuard enables you to manage and maintain end-point protection across your network. It provides visibility into all the elements in your network, helps you assess where there may be potential vulnerabilities, and enables you to patch them. The patch management and network auditing solution is easy-to-use and easy-to-deploy.
* [nikto](https://github.com/sullo/nikto) Nikto is an Open Source (GPL) web server scanner which performs comprehensive tests against web servers for multiple items, including over 6700 potentially dangerous files/programs, checks for outdated versions of over 1250 servers, and version specific problems on over 270 servers. It also checks for server configuration items such as the presence of multiple index files, HTTP server options, and will attempt to identify installed web servers and software. Scan items and plugins are frequently updated and can be automatically updated.
* [Arachne](https://webgate.ec.europa.eu/arachneweb/) Arachne is a risk scoring tool developed by the European Commission, represented by the DirectorateGeneral for Employment, Social Affairs and Inclusion and the Directorate General for Regional Policy and Urban Development (hereinafter: the Commission services) in close cooperation with some Member States. The Commission services aim at supporting managing authorities responsible for the European Structural and Investment Funds (hereinafter: ESIF1 by providing the Arachne Risk Scoring Tool to identify effectively and efficiently most risky projects, contracts, contractors and beneficiaries, necessary for their management verifications under point (c) of Article 125 (4) of Common Provision Regulation (EU) No 1303/2013 (hereinafter: the CPR).
* [Skipfish (unofficial mirror)](https://github.com/spinkham/skipfish) [Skipfish](https://code.google.com/archive/p/skipfish/) Skipfish is an active web application security reconnaissance tool. It prepares an interactive sitemap for the targeted site by carrying out a recursive crawl and dictionary-based probes. The resulting map is then annotated with the output from a number of active (but hopefully non-disruptive) security checks. The final report generated by the tool is meant to serve as a foundation for professional web application security assessments.
* [Acunetix](https://www.acunetix.com/) Introducing API Security with discovery: cover more ground by finding and testing APIs without breaking development workflows. Discover, test and patch vulnerabilities in your web applications and APIs from a single solution, helping you stay continuously secure with ease.
* [Zed Attack Proxy (ZAP)](https://www.zaproxy.org/) [ZAP at Github](https://github.com/zaproxy/zaproxy) The Zed Attack Proxy (ZAP) by Checkmarx is the world’s most widely used web app scanner. Free and open source. A community based GitHub Top 1000 project that anyone can contribute to. It can help you automatically find security vulnerabilities in your web applications while you are developing and testing your applications. It's also a great tool for experienced pentesters to use for manual security testing.
* [Quark Engine](https://quark-engine.readthedocs.io/en/latest/) [Github repository](https://github.com/quark-engine/quark-engine) Quark Engine is an open source software for automating analysis of suspicious Android application. To do so it makes use of custom Dalvik Bytecode Loader and unique scoring system that detect malicious behaviors and calculate threat level within seconds.
* [THC - The Hacker's Choice](https://www.thc.org/) We are a group of international hackers. We do IT security work. We are not for hire. All of our work is for the public. We research and publish tools and academic papers to expose fishy IT security that just isn’t secure. We also develop and publish tools to help the IT Security movement.


# Enumeration
* [smtp-user-enum](https://github.com/cytopia/smtp-user-enum) SMTP user enumeration via VRFY, EXPN and RCPT with clever timeout, retry and reconnect functionality.
* [RPCScan](https://github.com/hegusung/RPCScan) Tool to communicate with RPC services and check misconfigurations on NFS shares
* [TCP Idle Scan (-sI)](https://nmap.org/book/idlescan.html)
* [Sysinternals Active Directory Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/adexplorer) Active Directory Explorer (AD Explorer) is an advanced Active Directory (AD) viewer and editor. You can use AD Explorer to easily navigate an AD database, define favorite locations, view object properties and attributes without having to open dialog boxes, edit permissions, view an object's schema, and execute sophisticated searches that you can save and re-execute.
* [Softerra LDAP Administrator](https://www.ldapadministrator.com/) LDAP Administrator allows you to manage multiple directories with ease. Quick navigation, handy attribute editors, bulk object modification, and plenty of other features provide for an intuitive and efficient LDAP server management experienc
* [Python LDAP 3](https://ldap3.readthedocs.io/en/latest/) ldap3 is a pure Python LDAP 3 client library strictly conforming to RFC4510 and is released under the LGPL v3 open source license. RFC4510 is the current LDAP specification (June 2006) from IETF and obsoletes the previous LDAP RFCs 2251, 2830, 3771 (December 1997).
* https://nmap.org/book/scan-methods-null-fin-xmas-scan.html
* https://www.geeksforgeeks.org/tcp-3-way-handshake-process/
* http://www.visualroute.com/
* [Unicornscan](https://www.kali.org/tools/unicornscan/) Unicornscan is a new information gathering and correlation engine built for and by members of the security research and testing communities. It was designed to provide an engine that is Scalable, Accurate, Flexible, and Efficient. It is released for the community to use under the terms of the GPL license.
* [MASSCAN: Mass IP port scanner](https://github.com/robertdavidgraham/masscan) TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.
* [hping3](https://www.kali.org/tools/hping3/) hping3 is a network tool able to send custom ICMP/UDP/TCP packets and to display target replies like ping does with ICMP replies. It handles fragmentation and arbitrary packet body and size, and can be used to transfer files under supported protocols. Using hping3, you can test firewall rules, perform (spoofed) port scanning, test network performance using different protocols, do path MTU discovery, perform traceroute-like actions under different protocols, fingerprint remote operating systems, audit TCP/IP stacks, etc. hping3 is scriptable using the Tcl language.
* [Metasploit](https://www.metasploit.com/) The world’s most used penetration testing framework. Knowledge is power, especially when it’s shared. A collaboration between the open source community and Rapid7, Metasploit helps security teams do more than just verify vulnerabilities, manage security assessments, and improve security awareness; it empowers and arms defenders to always stay one step (or two) ahead of the game.
  * [About the Metasploit Meterpreter](https://www.offsec.com/metasploit-unleashed/about-meterpreter/) Meterpreter is an advanced, dynamically extensible payload that uses in-memory DLL injection stagers and is extended over the network at runtime. It communicates over the stager socket and provides a comprehensive client-side Ruby API. It features command history, tab completion, channels, and more.
* [Angry IP Scanner](https://angryip.org/) Angry IP Scanner (or simply ipscan) is an open-source and cross-platform network scanner designed to be fast and simple to use. It scans IP addresses and ports as well as has many other features. It is widely used by network administrators and just curious users around the world, including large and small enterprises, banks, and government agencies. It runs on Linux, Windows, and Mac OS X, possibly supporting other platforms as well.
* [OSINT Framework](https://osintframework.com/) OSINT framework focused on gathering information from free tools or resources. The intention is to help people find free OSINT resources. Some of the sites included might require registration or offer more data for $$$, but you should be able to get at least a portion of the available information for no cost. I originally created this framework with an information security point of view. Since then, the response from other fields and disciplines has been incredible. I would love to be able to include any other OSINT resources, especially from fields outside of infosec. Please let me know about anything that might be missing!
* [ReconDog](https://github.com/s0md3v/ReconDog) Reconnaissance Swiss Army Knife
* [The Recon-ng Framework](https://github.com/lanmaster53/recon-ng) Open Source Intelligence gathering tool aimed at reducing the time spent harvesting information from open sources.
  * [econ-NG Tutorial](https://hackertarget.com/recon-ng-tutorial/) In this recon-ng tutorial, discover open source intelligence and easily pivot to new results. Using a modular approach, collect and dig deeper into extracted data.
 
# Monitoring
* [PRTG Network Monitor](https://www.paessler.com/prtg) NetScanTools Pro is an integrated collection of internet information gathering and network troubleshooting utilities for Network Professionals. Research IPv4 addresses, IPv6 addresses, hostnames, domain names, email addresses and URLs automatically** or with manual tools. It is designed for the Windows operating system GUI. **Automated tools are started interactively by the user.
* [Omnipeek](https://www.liveaction.com/products/omnipeek/) Get network protocol analyzer capabilities, on your Windows machine, to quickly conduct deep packet analysis to resolve network and security issues.
* [NetScanTools® Pro](https://www.netscantools.com/nstpromain.html) 

# Tracking Links
* https://linklyhq.com/create-tracking-links
* https://bitly.com/blog/tracking-link/
  
# "Darknets"
* https://staging.freenetproject.org/index.html
* https://retroshare.cc/
* [Whonix](https://www.whonix.org/)
* [Tails](https://tails.net/) Tails is a portable operating system that protects against surveillance and censorship.
  
# Social Engineering
* [theHarvester](https://github.com/laramies/theHarvester) theHarvester is a simple to use, yet powerful tool designed to be used during the reconnaissance stage of a red
team assessment or penetration test. It performs open source intelligence (OSINT) gathering to help determine
a domain's external threat landscape. The tool gathers names, emails, IPs, subdomains, and URLs by using
multiple public resources
* [Sherlock](https://github.com/sherlock-project/sherlock) Hunt down social media accounts by username across 400+ social networks
* [Infoga - Email OSINT](https://github.com/GiJ03/Infoga) Infoga is a tool gathering email accounts informations (ip,hostname,country,...) from different public source (search engines, pgp key servers and shodan) and check if emails was leaked using haveibeenpwned.com API. Is a really simple tool, but very effective for the early stages of a penetration test or just to know the visibility of your company in the Internet.
* [Maltego](https://www.maltego.com/) The all-in-one investigation platform that accelerates complex cyber investigations from hours to minutes
* [FOCA (Fingerprinting Organizations with Collected Archives)](https://github.com/ElevenPaths/FOCA) FOCA is a tool used mainly to find metadata and hidden information in the documents it scans. These documents may be on web pages, and can be downloaded and analysed with FOCA.

* https://de.indeed.com

# Subdomain Enumeration
* https://www.netcraft.com/
* [Sublist3r](https://github.com/aboul3la/Sublist3r) Sublist3r is a python tool designed to enumerate subdomains of websites using OSINT. It helps penetration testers and bug hunters collect and gather subdomains for the domain they are targeting. Sublist3r enumerates subdomains using many search engines such as Google, Yahoo, Bing, Baidu and Ask. Sublist3r also enumerates subdomains using Netcraft, Virustotal, ThreatCrowd, DNSdumpster and ReverseDNS.
* https://www.social-searcher.com/
* https://www.shodan.io/
* https://who.is/
* [subfinder](https://github.com/projectdiscovery/subfinder) ast passive subdomain enumeration tool.
* [gobuster](https://github.com/OJ/gobuster) Gobuster is a tool used to brute-force: URIs (directories and files) in web sites, DNS subdomains (with wildcard support), Virtual Host names on target web servers, Open Amazon S3 buckets, Open Google Cloud buckets, TFTP servers
# 
* [ATT&CK](https://attack.mitre.org/) MITRE ATT&CK® is a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations. The ATT&CK knowledge base is used as a foundation for the development of specific threat models and methodologies in the private sector, in government, and in the cybersecurity product and service community.
  * [Software](https://attack.mitre.org/software/) Software is a generic term for custom or commercial code, operating system utilities, open-source software, or other tools used to conduct behavior modeled in ATT&CK. Some instances of software have multiple names associated with the same instance due to various organizations tracking the same set of software by different names. The team makes a best effort to track overlaps between names based on publicly reported associations, which are designated as “Associated Software” on each page (formerly labeled “Aliases”), because we believe these overlaps are useful for analyst awareness.
* https://www.pcisecuritystandards.org/standards/
  
# Standards and Laws
* https://www.itgovernance.co.uk/iso27001
* https://www.hhs.gov/hipaa/index.html
* https://en.wikipedia.org/wiki/Sarbanes%E2%80%93Oxley_Act
* https://www.copyright.gov/dmca/
* https://security.cms.gov/learn/federal-information-security-modernization-act-fisma
* https://www.cisa.gov/topics/cyber-threats-and-advisories/federal-information-security-modernization-act
* https://gdpr-info.eu/
* https://www.gov.uk/data-protection
* [S.2521 - Federal Information Security Modernization Act of 2014](https://www.congress.gov/bill/113th-congress/senate-bill/2521) Federal Information Security Modernization Act of 2014 - Amends the Federal Information Security Management Act of 2002 (FISMA) to: (1) reestablish the oversight authority of the Director of the Office of Management and Budget (OMB) with respect to agency information security policies and practices, and (2) set forth authority for the Secretary of Homeland Security (DHS) to administer the implementation of such policies and practices for information systems.
* [Digital Millenium Copyright Act](https://www.congress.gov/105/plaws/publ304/PLAW-105publ304.pdf) To amend title 17, United States Code, to implement the World Intellectual Property Organization Copyright Treaty and Performances and Phonograms Treaty, and for other purposes
* [Payment Card Industry Data Security Standard](https://docs-prv.pcisecuritystandards.org/PCI%20DSS/Standard/PCI-DSS-v4_0_1.pdf) The Payment Card Industry Data Security Standard (PCI DSS) was developed to encourage and enhance payment account data security and facilitate the broad adoption of consistent data security measures globally. PCI DSS provides a baseline of technical and operational requirements designed to protect account data. While specifically designed to focus on environments with payment account data, PCI DSS can also be used to protect against threats and secure other elements in the payment ecosystem. 

# Threat Modeling
* [Cyber Threat Modeling](https://www.eccouncil.org/threat-modeling/) 

# Forensic
* https://www.opentext.com/products/forensic
* [Autopsy Digital Forensics](https://www.autopsy.com/download/) Autopsy® is the premier end-to-end open source digital forensics platform. Built by Sleuth Kit Labs with the core features you expect in commercial forensic tools, Autopsy is a fast, thorough, and efficient hard drive investigation solution that evolves with your needs.
* https://www.exterro.com/digital-forensics-software/forensic-toolkit
* https://medium.com/@kryptologyst/incident-response-preparation-6f24d776d8ee
* https://www.softwaresecured.com/post/comparison-of-stride-dread-pasta
* https://cis.temple.edu/~qzeng/cis4360-spring17/papers/Praetorian_Threat_Modeling_Presentation.pdf
* https://www.itsecurityguru.org/2015/06/10/risk-analysis-how-to/
* https://www.eccouncil.org/cybersecurity-exchange/ethical-hacking/what-is-ethical-hacking/
* https://apps.dtic.mil/sti/citations/ADA586960
* https://apps.dtic.mil/sti/pdfs/ADA586960.pdf
* [REMnux: A Linux Toolkit for Malware Analysis](https://remnux.org/) REMnux® is a Linux toolkit for reverse-engineering and analyzing malicious software. REMnux provides a curated collection of free tools created by the community. Analysts can use it to investigate malware without having to find, install, and configure the tools.
* [C.A.IN.E. Computer Aided Investigative Environment](https://www.caine-live.net/) CAINE (Computer Aided INvestigative Environment) is an Italian GNU/Linux live distribution created as a Digital Forensics project Currently the project manager is Nanni Bassetti (Bari - Italy). CAINE offers a complete forensic environment that is organized to integrate existing software tools as software modules and to provide a friendly graphical interface
* [Best Digital Forensics Software](https://www.g2.com/categories/digital-forensics) Digital forensics software is used to investigate and examine IT systems after security incidents or for security-related preventive maintenance. These tools help businesses perform in-depth analysis of IT systems to identify the cause of security incidents, outline vulnerabilities, and assist security teams in facilitating incident response processes. These tools aggregate security information from hardware, network logs, and files to present security professionals with a full picture of the likely causes of security incidents. From there, many tools identify the steps necessary to remediate the vulnerability and update policies and configurations to prevent the situation from arising again.
  
# Google Dorks
* https://www.boxpiper.com/posts/google-dork-list
* https://gbhackers.com/latest-google-dorks-list/
* https://www.exploit-db.com/
* https://search.censys.io/

# Attack types
* DDOS
  * [Slow Loris](https://www.cloudflare.com/learning/ddos/ddos-attack-tools/slowloris/)
  * [Pulsewave](https://www.keysight.com/blogs/en/tech/nwvs/2024/08/01/pulsewave-ddos-attacks)
* [Smashing the Stack for Fun and Profit](https://inst.eecs.berkeley.edu/~cs161/fa08/papers/stack_smashing.pdf)
* [Heyoka Backdoor](https://attack.mitre.org/software/S1027/) Heyoka Backdoor is a custom backdoor--based on the Heyoka open source exfiltration tool--that has been used by Aoqin Dragon since at least 2013.
* [Evil twin (wireless networks)](https://en.wikipedia.org/wiki/Evil_twin_(wireless_networks)) An evil twin is a fraudulent Wi-Fi access point that appears to be legitimate but is set up to eavesdrop on wireless communications.[1] The evil twin is the wireless LAN equivalent of the phishing scam.
* [LLMNR poisoning](https://www.prosec-networks.com/en/blog/llmnr-poisoning/) Link-local multicast name resolution (LLMNR) Poisoning causes data traffic on a network to be intercepted and modified. This can be done using various tools without much knowledge and can lead to great damage. The goal is usually to collect information, obtain password hashes or exploit other gaps in the network. The whole thing falls under Man-In-The-Middle attack techniques and opens up many new attack vectors.
* [Pass the hash](https://en.wikipedia.org/wiki/Pass_the_hash) In computer security, pass the hash is a hacking technique that allows an attacker to authenticate to a remote server or service by using the underlying NTLM or LanMan hash of a user's password, instead of requiring the associated plaintext password as is normally the case. It replaces the need for stealing the plaintext password to gain access with stealing the hash.
* [Internal Monologue Attack: Retrieving NTLM Hashes without Touching LSASS](https://github.com/eladshamir/Internal-Monologue) Mimikatz, developed by Benjamin Delpy (@gentilkiwi), is a well-regarded post-exploitation tool, which allows adversaries to extract plain text passwords, NTLM hashes and Kerberos tickets from memory, as well as perform attacks such as pass-the-hash, pass-the-ticket or build a golden ticket. Arguably, the primary use of Mimikatz is retrieving user credentials from LSASS process memory for use in post exploitation lateral movement.

# DNS tunnel 
* [Ron Bowes iagox86](https://github.com/iagox86)
  * [dnscat2](https://github.com/iagox86/dnscat2) This tool is designed to create an encrypted command-and-control (C&C) channel over the DNS protocol, which is an effective tunnel out of almost every network.
* [yarrick](https://github.com/yarrick)
  * iodine DNS tunnel
  * pingfs stores your data in ICMP packets
  * turbomem incomplete Linux driver for Intel Turbo Memory Controller ("Robson") PCIe card
  * scsniff Linux tool for sniffing smartcard communication between card and reader using season interface
  * lwip-tcpip/lwip lwIP mirror from http://git.savannah.gnu.org/cgit/lwip.git
  * scsniff Linux tool for sniffing smartcard communication between card and reader using season interface.

# Pentest
* [BlackArch Linux](https://github.com/BlackArch) lackArch Linux is an Arch Linux-based distribution for penetration testers and security researchers.
* [Kali Linux](https://www.kali.org/) Kali Linux is an open-source, Debian-based Linux distribution geared towards various information security tasks, such as Penetration Testing, Security Research, Computer Forensics and Reverse Engineering.
* [Parrot](https://parrotsec.org/) Parrot Security provides a huge arsenal of tools, utilities and libraries that IT and security professionals can use to test and assess the security of their assets in a reliable, compliant and reproducible way. From information gathering to the final report. The Parrot system gets you covered with the most flexible environment.

# Password recovery
* [Cain and Abel](https://web.archive.org/web/20190603235413/http://www.oxid.it/cain.html) Cain and Abel (often abbreviated to Cain) was a password recovery tool for Microsoft Windows. It could recover many kinds of passwords using methods such as network packet sniffing, cracking various password hashes by using methods such as dictionary attacks, brute force and cryptanalysis attacks.[1] Cryptanalysis attacks were done via rainbow tables which could be generated with the winrtgen.exe program provided with Cain and Abel.[2] Cain and Abel was maintained by Massimiliano Montoro[3] and Sean Babcock.
* [John the Ripper password cracker](https://www.openwall.com/john/) John the Ripper is an Open Source password security auditing and password recovery tool available for many operating systems. John the Ripper jumbo supports hundreds of hash and cipher types, including for: user passwords of Unix flavors (Linux, *BSD, Solaris, AIX, QNX, etc.), macOS, Windows, "web apps" (e.g., WordPress), groupware (e.g., Notes/Domino), and database servers (SQL, LDAP, etc.); network traffic captures (Windows network authentication, WiFi WPA-PSK, etc.); encrypted private keys (SSH, GnuPG, cryptocurrency wallets, etc.), filesystems and disks (macOS .dmg files and "sparse bundles", Windows BitLocker, etc.), archives (ZIP, RAR, 7z), and document files (PDF, Microsoft Office's, etc.) These are just some of the examples - there are many more.
* [mimikatz](https://github.com/gentilkiwi/mimikatz) It's now well known to extract plaintexts passwords, hash, PIN code and kerberos tickets from memory. mimikatz can also perform pass-the-hash, pass-the-ticket or build Golden tickets.
  * [mimikatz](https://github.com/ParrotSec/mimikatz)
* https://crack.sh/
* [selfhash](https://github.com/snowytoxa/selfhash) SyScan'14 release - Selfhash allows you to get password hashes of the current user. This tool doesn't requere high privileges i.e. SYSTEM, but on another hand it returns NTLM Challenge Response, so you could crack it later.
* https://hashcat.net/hashcat/
* [thc-hydra](https://github.com/vanhauser-thc/thc-hydra) Number one of the biggest security holes are passwords, as every password security study shows. This tool is a proof of concept code, to give researchers and security consultants the possibility to show how easy it would be to gain unauthorized access from remote to a system.
* [ncrack](https://github.com/nmap/ncrack) Ncrack network authentication tool - [Deprecation Notice](https://nmap.org/ncrack/)
* [responder](https://github.com/lgandx/Responder) Responder is a LLMNR, NBT-NS and MDNS poisoner, with built-in HTTP/SMB/MSSQL/FTP/LDAP rogue authentication server supporting NTLMv1/NTLMv2/LMv2, Extended Security NTLMSSP and Basic HTTP authentication.
  * [Kali responder tool documentation](https://www.kali.org/tools/responder/)
* [Ettercap](https://www.ettercap-project.org/) Ettercap is a comprehensive suite for man in the middle attacks. It features sniffing of live connections, content filtering on the fly and many other interesting tricks. It supports active and passive dissection of many protocols and includes many features for network and host analysis.
* [Bettercap](https://www.bettercap.org/) The Swiss Army knife for WiFi, Bluetooth Low Energy, wireless HID hijacking, CAN-bus and IPv4 and IPv6 networks reconnaissance and MITM attacks.
* [Wireshark](https://www.wireshark.org/) Wireshark is the world's foremost network protocol analyzer. It lets you see what's happening on your network at a microscopic level. It is the de facto (and often de jure) standard across many industries and educational institutions.
* [tcpdump](https://www.tcpdump.org/) tcpdump prints out a description of the contents of packets on a network interface that match the Boolean expression (see pcap-filter(7) for the expression syntax); the description is preceded by a time stamp, printed, by default, as hours, minutes, seconds, and fractions of a second since midnight. It can also be run with the -w flag, which causes it to save the packet data to a file for later analysis, and/or with the -r flag, which causes it to read from a saved packet file rather than to read packets from a network interface. It can also be run with the -V flag, which causes it to read a list of saved packet files. In all cases, only packets that match expression will be processed by tcpdump
* [Ophcrack](https://ophcrack.sourceforge.io/) also offers rainbow tables for download
* [L0phtcrack](https://www.l0phtcrack.com/)
* [pwdump](https://www.openwall.com/passwords/windows-pwdump) This handy utility dumps the password database of an NT machine that is held in the NT registry (under HKEY_LOCAL_MACHINE\SECURITY\SAM\Domains\Account\Users) into a valid smbpasswd format file (which is understood by practically all Windows password security auditing tools).
* [fgdump](https://sectools.org/tool/fgdump/) fgdump is a newer version of the pwdump tool for extracting NTLM and LanMan password hashes from Windows. It is also capable of displaying password histories if they are available. It outputs the data in L0phtCrack-compatible form, and can write to an output file. fgdump attempts to disable antivirus software before running. It then runs pwdump, cachedump (cached credentials dump), and pstgdump (protected storage dump). For downloads and more information, visit the [fgdump homepage](http://swamp.foofus.net/fizzgig/fgdump/).


    
# Webshell
* [BlackArch Webshells](https://github.com/BlackArch/webshells) Various webshells. We accept pull requests for additions to this collection.

# Assessment
* [tenable one}(https://www.tenable.com/products/tenable-one) The world’s only AI-powered exposure management platform - Tenable One radically unifies security visibility, insight and action across the attack surface, equipping modern organizations to isolate and eradicate priority cyber exposures from IT infrastructure to cloud environments to critical infrastructure and everywhere in between.
* [Redscan](https://www.redscan.com/)


# (Windows) Authentication
* [Kerberos Authentication Explained | A deep dive](https://www.youtube.com/watch?v=5N242XcKAsM) Kerberos explained in easy to understand terms with intuitive diagrams. Starting with a high-level overview and then a deep dive into all the messages that are passed between the User, Authentication Server, Ticket Granting Server and the Service. Including the contents of messages, Authenticators, the encryption used and the validation that is performed to achieve mutual authentication. 
