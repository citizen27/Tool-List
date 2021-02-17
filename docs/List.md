# Open Source-ish Tool List

## Database Analysis

- [DB Browser for SQLite](https://sqlitebrowser.org/)
  - Visual tool to create and edit database files with SQlite databases
  - Plug and play SQL commands for indexing and searching

## Deletion Utilities

- [CCleaner](https://www.ccleaner.com/)
  - Free version does standard cleaning, but there are much better utilities
- [Darik&#39;s Boot and Nuke (DBAN)](https://dban.org/)
  - Supports Gutmann Method, as well as DoD Short and 5220.22
  - Many options for network wide deployment or pass settings
- [Nwipe](https://github.com/martijnvanbrummelen/nwipe)
  - Link git?
  - Command line utility
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
- Dd
- FTK Imager
- Powershell

## Hashing

- [HashCheck](https://github.com/gurnec/HashCheck)
  - Calculate and verify checksums from Windows Explorer
- [HashMyFiles](https://www.nirsoft.net/utils/hash_my_files.html)
  - NirSofttool to calculate MD5 and SHA1 hashes

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

- Angry IP Scanner
- GNS3
  - Open Source Packet Tracer
- Nagios
  - Network Scanner for DevOps culture
- Network Miner
- NMAP
  - Zenmap
- OpenVAS
  - Open Source Nessus
- Wireshark

## Operating System Forensics

- Registry Tools
  - RECmd
  - RegShot
- Rifiuti
  - Vista and 2
- [Zimmerman Tools](https://ericzimmerman.github.io/#!index.md)
  - JLECmd
    - JumpList artifact parser
  - KAPE
    - Collection and processing of files, super fast
  - LECmd
    - LNK file parser
  - PECmd
    - Prefetch file parser
  - RBCmd
    - Recycle Bin parser
  - There are many more, I just have found these the most useful in my experience

## Packing and Compression

- 7zip
- Detect It Easy
- UPX

## Passwords

- Aircrack-ng
- Cain and abel
- Hashcat
- Hydra
- John the ripper
- Ncrack
- [NirSoft Password Utilities](https://www.nirsoft.net/password_recovery_tools.html)
  - Hyper-specific tools for niche password recovery / extractions

## Randomization

- ISAAC
- Mersenne Twister

## Removable Media

- Rufus
- USBDetective

## OSINT

- DNS Dumpster
- Intelx.io
- Metagoofil

- ophcrack
- rainbowcrack

- Spokeo
- Thatsthem.com
- Theharvester

## Vulnerability reference

- exploitdb
- MITRE
- OWASP
- VulnHub
