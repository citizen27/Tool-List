# Open Source-ish Tool List

## Database Browsing and Analysis

- [DB Browser for SQLite](https://sqlitebrowser.org/)
  - Visual tool to create and edit database files with SQlite databases
  - Plug and play SQL commands for indexing and searching
- [DBeaver](https://dbeaver.io/)
  - A versatile database tool that supports multiple databases and provides a user-friendly interface for viewing, querying, and managing database systems.
  - Supports SQL Variants and Apache Family databases
  - Licensed version supports more databses (MongoDB, BigQuery)
- [DBVisualizer](https://www.dbvis.com/)
  - Database management and analyiss tool, offers a pleasing visual interface
  - Supports an immense amount of database structures
- [pgAdmin](https://www.pgadmin.org/)
  - A comprehensive administration and management platform specifically designed for PostgreSQL databases. It offers advanced features for database development and maintenance.
- [MySQL Workbench](https://www.mysql.com/products/workbench/)
  - An official graphical tool provided by MySQL for database design, development, and administration. It supports MySQL databases and offers visual modeling features.

## Deletion Utilities


- [CCleaner](https://www.ccleaner.com/)
  - Free version does standard cleaning, but there are much better utilities
- [Darik&#39;s Boot and Nuke (DBAN)](https://dban.org/)
  - Supports Gutmann Method, as well as DoD Short and 5220.22
  - Many options for network wide deployment or pass settings
- [Nwipe](https://github.com/martijnvanbrummelen/nwipe)
  - Command line utility for wiping
- [WinDirStat](https://windirstat.net/)
  - Disk usage statistic viewer and cleanup tool

## Exploitation

- [Bloodhound](https://github.com/BloodHoundAD/BloodHound)
  - Windows domain pen-testing suite
  - Uses graph theory to link relationships in an AD environment
- [BeEF](https://beefproject.com/)
  - Penetration testing tool for web browsers
  - Uses client side attack vectors
- [Metasploit](https://www.metasploit.com/)
  - Vulnerability tester and exploiter
  - Lots and lots of modules and exploits
- [Mimikatz](https://github.com/gentilkiwi/mimikatz/wiki)
  - Getting windows passwords from memory
  - Build Golden Tickets and pass-the-hash
- [Mitmproxy](https://mitmproxy.org/)
  - HTTP traffic interception utility
  - Debugging and pentesting tool
- [Nikto](https://cirt.net/Nikto2)
  - Web server scanner
- [Impacket](https://github.com/SecureAuthCorp/impacket)
  - Python classes for packet analysis over the wire
- [OWASP ZAP](https://www.zaproxy.org/)
  - Web spider and penetration testing suite

## File System Forensics

## Full Forensic Suites

- [Autopsy](https://www.autopsy.com/)
  - Full forensic suite with lots of functionality
  - File carving and registry hive extraction
  - Linux, Windows, Android and iOS image support

## General Tools

- Command Line
- [Dc3dd](https://tools.kali.org/forensics/dc3dd)
  - On the fly hashing
  - Pattern wiping
  - Writing errors to file
- dd
- [FTK Imager](https://accessdata.com/products-services/forensic-toolkit-ftk/ftkimager#:~:text=FTK%C2%AE%20Imager%20is%20a,%C2%AE%20(FTK)%20is%20warranted.)
  - Imaging software of creating disk images with hash validation
  - Also useful for recovering simple deleted files from personal machine or image
- Powershell

## Hashing

- [HashCheck](https://github.com/gurnec/HashCheck)
  - Calculate and verify checksums from Windows Explorer
- [HashMyFiles](https://www.nirsoft.net/utils/hash_my_files.html)
  - NirSoft tool to calculate MD5 and SHA1 hashes

## Hex Editors

- [HxD](https://mh-nexus.de/en/hxd/)
  - Fast and lightweight
  - Raw disk and memory editing
  - Supports files of any size
- [wxHexEditor](https://www.wxhexeditor.org/)
  - For Linux, Windows and MacOS

## Image and Video Tools

## Malware Tools

- [APIMonitor](http://www.rohitab.com/apimonitor)
  - Monitor and control API calls from apps and services
  - Very useful form malware call analysis
- [CFF Explorer](https://ntcore.com/?page_id=388)
  - Built in hex editor and unpacker
  - Portable Executable / Executable analysis
  - Useful for DLL viewing, Imported Libraries
- [Detect It Easy](https://github.com/horsicq/Detect-It-Easy)
  - File type and information detector
  - Checks entropy, strings and built in hex editor
- [PEStudio](https://www.winitor.com/)
  - Malware assessment tool
  - MITRE and VirusTotal built in to check against known hashsets
- [Resource Hacker](http://www.angusj.com/resourcehacker/)
  - Compiler and Decompiler for Windows applications
  - Useful for stepping through malware resource usage and processes
- [X64dbg](https://github.com/x64dbg/x64dbg)
  - Debugger for Windows systems
  - Useful for stepping through malware or patching

## Memory Forensics

- Memory Analysis
  - [Volatility](https://www.volatilityfoundation.org/releases)
    - V2.5 for Workbench
    - V2.6 for CLI
    - Can pull DLLs, previous commands and connections from a memory image
  - [YARA](https://github.com/virustotal/yara)
    - User defined rule sets to find files matching parameters on disk or in memory
- Memory Capture
  - [Belkasoft Live RAM Capturer](https://belkasoft.com/ram-capturer)
    - Windows
    - Extract entire dump of all volatile memory
    - Only requires sign up for use and download
  - [Magnet Ram Capture](https://www.magnetforensics.com/resources/magnet-ram-capture/)
    - Windows
    - Extract entire dump of all volatile memory
    - Only requires sign up for use and download
  - [WinPMem](https://winpmem.velocidex.com/)
    - Windows
    - RAM capture with three different acquisition modes

## Monitoring Tools

- Event Viewer
  - Built-in to Windows
- [SNORT](https://www.snort.org/downloads)
  - Open Source IDS
  - Network traffic analyzer with multiple configuration options
- [SysInternals](https://docs.microsoft.com/en-us/sysinternals/)
  - Full published suite by Microsoft
  - Most useful tools for monitoring or ProcMon and SysMon
- [Zabbix](https://www.zabbix.com/)
  - Open Source SIEM for many forms of monitoring

## Network Tools

- [Angry IP Scanner](https://angryip.org/)
  - Scans any specified IP range or network by network mask
  - Runs on Linux, MacOS and Windows
- [GNS3](https://www.gns3.com/software)
  - Build and deploy test networks that are completely virtualized
  - Similar to Cisco Packet Tracer
- [Network Miner](https://www.netresec.com/?page=NetworkMiner)
  - Passive network scanner / network forensic tool
  - Intuitive UI
- [NMAP](https://nmap.org/)
  - Network discovery and basic vulnerability scanner
  - Full suite includes Zenmap, Ncat, Ndiff and Nping
- [OpenVAS](https://www.openvas.org/)
  - Full featured vulnerability scanner across networks
  - Can run large scale scans and has internal programming language
- [Wireshark](https://www.wireshark.org/)
  - Network protocol analyzer
  - Supports both live capture and offline analysis
  - Widely used in all IT industries

## Operating System Forensics

- [RegShot](https://sourceforge.net/projects/regshot/)
  - Registry comparison utility
- [Rifiuti](https://abelcheung.github.io/rifiuti2/)
  - Recycle Bin analysis
  - Supported through multiple versions of Windows (95 to 10)
- [Zimmerman Tools](https://ericzimmerman.github.io/#!index.md)
  - All of Eric Zimmerman&#39;s tools are absolutely wonderful, and the full list is linked above, but below are the tools I have found most useful.
  - [JLECmd](https://github.com/EricZimmerman/JLECmd)
    - JumpList artifact parser
  - [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape)
    - Collection and processing of files, super fast
  - [LECmd](https://github.com/EricZimmerman/LECmd)
    - LNK file parser
  - [PECmd](https://github.com/EricZimmerman/PECmd)
    - Prefetch file parser
  - [RBCmd](https://github.com/EricZimmerman/RBCmd)
    - Recycle Bin parser
  - [RECmd](https://github.com/EricZimmerman/RECmd)
    - Windows Registry modifier and examiner

## Packing and Compression

- [7-Zip](https://www.7-zip.org/)
  - Compression utility widely used
- [Detect It Easy](https://github.com/horsicq/Detect-It-Easy)
  - File type determiner
  - Also finds out entropy, strings and hashes
- [UPX](https://upx.github.io/)
  - Compression and decompression of files with no memory overhead

## Passwords

- [Aircrack-NG](https://www.aircrack-ng.org/)
  - Wi-Fi network security tester with monitoring, attacking, testing and cracking modes
- [Hashcat](https://hashcat.net/hashcat/)
  - Password cracker
  - Very fast and robust supporting over 300 hashing algorithms
- [Hydra](https://tools.kali.org/password-attacks/hydra)
  - Kali Linux built in program for password and login breaking based off of wordlists
- [John](https://www.openwall.com/john/)
  - John and John The Ripper
  - Password security auditing and recovery
- [Ncrack](https://nmap.org/ncrack/)
  - Fast network authentication cracking tool
- [NirSoft Password Utilities](https://www.nirsoft.net/password_recovery_tools.html)
  - Hyper-specific tools for niche password recovery / extractions
- [Ophcrack](https://ophcrack.sourceforge.io/)
  - Rainbow table based password cracker for Windows
- [Rainbowcrack](http://project-rainbowcrack.com/)
  - Hash cracker based off of rainbow tables
  - Supports AMD and NVIDIA GPU acceleration

## Randomization

- [ISAAC](https://en.wikipedia.org/wiki/ISAAC_(cipher))
  - Pseudorandom number generator and stream cipher
- [Mersenne Twister](https://en.wikipedia.org/wiki/Mersenne_Twister)
  - Pseudorandom number generator
  - More widely used than ISAAC

## Removable Media

- [Rufus](https://rufus.ie/)
  - Create bootable disk images from ISOs
- [USBDetective](https://usbdetective.com/)
  - Process USB artifacts for all versions of Windows

## OSINT

- [DNS Dumpster](https://dnsdumpster.com/)
  - Discovers hosts related to domains
  - Only shows visible hosts for the domain
- [Intelx.io](https://intelx.io/)
  - Search engine for darknet, private servers and more
- [Metagoofil](https://github.com/laramies/metagoofil)
  - Metadata extractor for public documents from target websites
- [Spokeo](https://www.spokeo.com/)
  - People finder
  - Essentially open source White Pages
- [Thatsthem.com](https://thatsthem.com/)
  - Similar to Spokeo
- [TheHarvester](https://github.com/laramies/theHarvester)
  - Early stage red team engagement for assessing threat landscape

## Vulnerability reference

- [Exploit-db](https://www.exploit-db.com/)
  - Exploit database for pentesters and researchers
- [MITRE](https://attack.mitre.org/)
  - Attack framework for enterprise, personal, and virtual networks
- [OWASP](https://owasp.org/)
  - Open Web Application Security Project
  - Identifies most common vulnerabilities for web applications
- [VulnHub](https://www.vulnhub.com/)
  - Purposely vulnerable virtual machines for practice and testing
