# Kali Tools

This repo gives access to **all kali tools**, on every Linux distributions. More specifically, it clones the source repo of the packages (and install them if needed).

Additionnally, it allows **searching** for tools, a feature I was dearly missing. Searching works on packages name **and descriptions** (which were curated, then hardcoded in this repo to avoid unneeded net access).

Author: Ludovic Barman

# searching for SQL injection

```
$ ./kali.py "sql injection"
 _  _    __    __    ____     ____  _____  _____  __    ___ 
( )/ )  /__\  (  )  (_  _)___(_  _)(  _  )(  _  )(  )  / __)
 )  (  /(__)\  )(__  _)(_(___) )(   )(_)(  )(_)(  )(__ \__ 
(_)\_)(__)(__)(____)(____)    (__) (_____)(_____)(____)(___/

Searching for sql injection 

 N°|  Name         | Installed | Description
---|---------------|-----------|-----------------------------------------------------------------------------------------------------
 1)  sqlmap         YES, git     sqlmap is an open source penetration testing tool that automates the process of detecting and exp...
 2)  fimap                       fimap is a little python tool which can find, prepare, audit, exploit and even google automaticly...
 3)  proxystrike                 ProxyStrike is an active Web Application Proxy. It’s a tool designed to find vulnerabilities whil...
 4)  vega                        Vega is a free and open source scanner and testing platform to test the security of web applicati...
 5)  bbqsql                      Blind sql injection can be a pain to exploit. When the available tools work they work well, but w...
 6)  sqlninja                    Fancy going from a sql injection on Microsoft SQL Server to a full GUI access on the DB? Take a f...
 7)  jsql                        jsql injection is a lightweight application used to find database information from a distant serv...
 8)  siparmyknife                SIP Army Knife is a fuzzer that searches for cross site scripting, sql injection, log injection, ...
 9)  paros                       A Java based HTTP/HTTPS proxy for assessing web application vulnerability. It supports editing/vi...
10)  grabber                     Grabber is a web application scanner. Basically it detects some kind of vulnerabilities in your w...
11)  sqlsus                      sqlsus is an open source Mysql injection and takeover tool, written in perl. Via a command line i...

Package No: 
1

----------------------------------------------------------------------------------------------------
| Package sqlmap 
----------------------------------------------------------------------------------------------------
| Description:
| sqlmap is an open source penetration testing tool that automates the process of detecting and
| exploiting sql injection flaws and taking over of database servers. It comes with a
| powerful detection engine, many niche features for the ultimate penetration tester and a broad
| range of switches lasting from database fingerprinting, over data fetching from the database, to
| accessing the underlying file system and executing commands on the operating system via out-of-band
| connections.
----------------------------------------------------------------------------------------------------
This package is already installed (and will not be downloaded).
Would you like to run it ? [Y/n] 
...
```

## If no search term is given, it displays the kali menu:

```
$ ./kali.py
 _  _    __    __    ____     ____  _____  _____  __    ___ 
( )/ )  /__\  (  )  (_  _)___(_  _)(  _  )(  _  )(  )  / __)
 )  (  /(__)\  )(__  _)(_(___) )(   )(_)(  )(_)(  )(__ \__ 
(_)\_)(__)(__)(____)(____)    (__) (_____)(_____)(____)(___/

PROTIP: use ./kali.py TERM to directly search for TERM

Please select a category:

1) Information Gathering            8) Exploitation Tools
2) Vulnerability Analysis           9) Forensics Tools
3) Wireless Attacks                 10) Stress Testing
4) Web Applications                 11) Password Attacks
5) Sniffing & Spoofing              12) Reverse Engineering
6) Maintaining Access               13) Hardware Hacking
7) Reporting Tools                  14) Extra

Category: 
13

 N°|  Name        | Installed | Description
---|--------------|-----------|-----------------------------------------------------------------------------------------------------
 1)  android-sdk                The Android SDK provides you the API libraries and developer tools necessary to build, test, and ...
 2)  apktool                    It is a tool for reverse engineering 3rd party, closed, binary Android apps. It can decode resour...
 3)  arduino                    Arduino is an open-source electronics prototyping platform based on flexible, easy-to-use hardwar...
 4)  dex2jar                    dex2jar contains following compments: (1) dex-reader is designed to read the Dalvik Executable (....
 5)  sakis3g                   
 6)  smali                      smali/baksmali is an assembler/disassembler for the dex format used by dalvik, Android’s Java VM ...
```