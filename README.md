# Active-Directory


![Predator-AD](https://github.com/user-attachments/assets/e72e39c4-b900-4930-a179-aa2fdcc90670)


List of tools and resources for pentesting Microsoft Active Directory
===========

<br>

+ Create Vulnerable AD Lab 
  - [Medium Tutorial by Logan Hugli](https://medium.com/@lhugli/constructing-a-vulnerable-active-directory-hacking-lab-environment-6e7cc7fd55c6)
  - [Medium article by Justin Duru](https://medium.com/@jduru213/cybersecurity-homelab-building-an-on-premise-domain-environment-with-splunk-windows-and-active-840ba325f3ee)
  - [Vulnerable-AD Script](https://github.com/safebuffer/vulnerable-AD/tree/master)
  - [BadBlood Script](https://github.com/davidprowe/BadBlood)
  - [DetectionLab](https://www.detectionlab.network/introduction/)
  - [Game of Active Directory - GOAD](https://github.com/Orange-Cyberdefense/GOAD)

<br>

+ AD Pentesting Cheat Sheets
  - [AD Pentesting Cheat-Sheets](https://swisskyrepo.github.io/InternalAllTheThings/)
    - This one contains an AMAZING amount of info on AD for Pentesters and Red Teams
  - [S1ckB0y1337 Active Directory Exploitation Cheat-Sheet](https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet)
  - [HackTheBox AD Pentesting Cheat-Sheet](https://www.hackthebox.com/blog/active-directory-penetration-testing-cheatsheet-and-guide)
  - [HackTricks AD Methodology](https://book.hacktricks.xyz/windows-hardening/active-directory-methodology)
  - [The Hacker Recipes](https://www.thehacker.recipes/)
  - [ired.team AD and Kerberos Cheat Sheets](https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse)

<br>

+ [BloodHound CE](https://github.com/SpecterOps/BloodHound)
  - BloodHound uses graph theory to reveal the hidden and often unintended relationships within an Active Directory or Azure environment
  - Attackers can use BloodHound to quickly identify highly complex attack paths that would otherwise be impossible to find
  - Defenders can use BloodHound to identify and eliminate those same attack paths
  - Both red and blue teams can use BloodHound to better understand privileged relationships in an Active Directory or Azure environment

<br>
      
+ [GoodHound](https://github.com/idnahacks/GoodHound?tab=readme-ov-file)
  - GoodHound operationalises Bloodhound by determining the busiest paths to high value targets and creating actionable output to prioritise remediation of attack paths

<br>

+ [ADalanche](https://github.com/lkarlslund/Adalanche)
  - Adalanche instantly reveals what permissions users and groups have in an Active Directory
  - It is useful for visualizing and exploring
    + Who can take over accounts, machines or the entire domain
    + Find and show misconfigurations
   
<br>
     
+ [Hardening Kitty](https://github.com/scipag/HardeningKitty)
  - Intended use is for Windows system hardening
  - Can be used to <u>**test for weak configurations**</u>

<br>
 
+ [Delinea Weak Password Finder](https://delinea.com/resources/weak-password-finder-tool-active-directory)
  - Free tool to quickly <u>**discover weak passwords in AD**</u>

<br>

+ [Rubeus](https://github.com/GhostPack/Rubeus)
  - A C# toolset for raw Kerberos interaction and abuses

<br>

+ [Seatbelt](https://github.com/GhostPack/Seatbelt)
  - A C# project that performs a number of security oriented host-survey "safety checks" relevant from both offensive and defensive security perspectives

<br>

+ [Microsoft Security Compliance Toolkit](https://www.microsoft.com/en-us/download/details.aspx?id=55319)
  - This set of tools allows enterprise security administrators to download, analyze, test, edit and store Microsoft-recommended security configuration baselines for Windows and other Microsoft products, while comparing them against other security configurations

<br>
 
+ [Semperis Forest Druid](https://www.semperis.com/forest-druid/)
  - Focuses on attack paths leading into the Tier 0 perimeter in hybrid identity environments—saving time by prioritizing your most critical assets

<br>

+ [Semperis Purple Knight](https://www.semperis.com/purple-knight/)
  - A free AD, Entra ID, and Okta security assessment tool—to help you discover indicators of exposure (IoEs) and indicators of compromise (IoCs) in your hybrid AD environment

<br>
 
+ [Group3r](https://github.com/Group3r/Group3r)
  - A tool for pentesters and red teamers to rapidly <u>**enumerate relevant settings in AD Group Policy**</u>, and to identify exploitable misconfigurations
 
<br>

+ [LockSmith](https://github.com/TrimarcJake/Locksmith)
  - A tool built to find and fix common misconfigurations in <u>**Active Directory Certificate Services**</u>

<br>

+ [BlueTuxedo](https://github.com/TrimarcJake/BlueTuxedo)
  - A tool built to find and fix common misconfigurations in <u>**Active Directory-Integrated DNS**</u>
    + Also a little bit of DHCP
   
<br>

+ [Empire](https://github.com/BC-SECURITY/Empire)
  - A post-exploitation and adversary emulation <u>**C2 framework**</u> that is used to aid Red Teams and Penetration Testers

<br>

+ [Starkiller](https://github.com/BC-SECURITY/Starkiller)
  - Frontend for Empire
 
<br>

+ [PowerSploit](https://github.com/PowerShellMafia/PowerSploit)
  - A collection of Microsoft PowerShell modules that can be used to aid penetration testers during all phases of an assessment
 
<br>

+ [SharpSploit](https://github.com/cobbr/SharpSploit)
  - A .NET post-exploitation library written in C# that aims to highlight the attack surface of .NET and make the use of offensive .NET easier for red teamers
 
<br>

+ [Ping Castle](https://www.pingcastle.com/)
  - An Active Directory health and security audit tool
  - Specifically designed to assess the security posture of an AD environment and provides a report with detailed findings
 
<br>

+ [ADRecon](https://github.com/sense-of-security/ADRecon)
  - Extracts and combines various artefacts out of an AD environment
