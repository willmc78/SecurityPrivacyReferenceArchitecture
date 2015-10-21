OSS Security Applications
-------------------------

American fuzzy lop

**SBB Description**

*American fuzzy lop* is a security-oriented [fuzzer](https://en.wikipedia.org/wiki/Fuzz_testing) that employs a novel type of compile-time instrumentation and genetic algorithms to automatically discover clean, interesting test cases that trigger new internal states in the targeted binary. This substantially improves the functional coverage for the fuzzed code.

These tool can be very productive in determining security flaws: The famous SSL Heartbleed bug was found in record time using this software. See <https://blog.hboeck.de/archives/868-How-Heartbleed-couldve-been-found.html>.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

C

**Project URL**

<http://lcamtuf.coredump.cx/afl/>

**Source Location**

<http://lcamtuf.coredump.cx/afl/releases/>

***Tag(s)***

Security, Test Tool

Bokken (Open Source Reverse Code Engineering)

**SBB Description**

Bokken is an Open Source Reverse Code Engineering tool.

Bokken is a **GUI for the Pyew and Radare projects** so it offers almost all the same features that Pyew has and and some of the Radare’s ones. It’s intended to be a **basic disassembler**, mainly, to analyze malware and vulnerabilities.

Currently Bokken **is neither** an hexadecimal editor **nor** a full featured disassembler **YET**, so it should not be used for deep code analysis or to try to modify files with it.

Bokken has the ability to detect and analyze **PE/Elf/mach0** files so, when one of those file formats is detected, the GUI shows all the information found on the analysis and offers many additional options to study the file.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

Python

**Project URL**

<http://bokken.re>

**Source Location**

<https://inguma.eu/projects/bokken/repository>

***Tag(s)***

Code Analyzer, Security

Bosun

**SBB Description**

Bosun is an open-source, MIT licensed, monitoring and alerting system by Stack Exchange. It has an expressive domain specific language for evaluating alerts and creating detailed notifications. It also lets you test your alerts against history for a faster development experience.

Collecting metrics about our systems is fun but what makes a monitoring system useful is alerting when anomalies arise. This is the real strength of Bosun.

Bosun encourages a particular workflow that makes it easy to design, test, and deploy an alert. If you look at the top of the Bosun display, the tabs include Items, Graph, Expression, Rule, and Test config in left-to-right order; that reflects the phases you go through as you create an alert. In general, first you’ll select an item (metric) that is the basis of the alert.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

GO

**Project URL**

<http://bosun.org/>

**Source Location**

<https://github.com/bosun-monitor/bosun>

***Tag(s)***

Security, SIEM

Bro

**SBB Description**

Bro is a powerful network analysis framework. Bro is a passive, open-source network traffic analyzer. It is primarily a security monitor that inspects all traffic on a link in depth for signs of suspicious activity. Bro supports a wide range of traffic analysis tasks even outside of the security domain, including performance measurements and helping with trouble-shooting.

The most immediate benefit that a site gains from deploying Bro is an extensive set of *log files* that record a network’s activity in high-level terms. These logs include not only a comprehensive record of every connection seen on the wire, but also application-layer transcripts such as, e.g., all HTTP sessions with their requested URIs, key headers, MIME types, and server responses; DNS requests with replies; SSL certificates; key content of SMTP sessions; and much more. By default, Bro writes all this information into well-structured tab-separated log files suitable for post-processing with external software. Users can however also chose from a set of alternative output formats and backends to interface directly with, e.g., external databases.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

C

**Project URL**

<https://www.bro.org>

**Source Location**

<https://github.com/bro>

***Tag(s)***

IDS, Security

Data Seal

**SBB Description**

Data Seal is a lightweight, UELMA-compliant data authentication service.

Data Seal is a project of [U.S. Open Data](http://usopendata.org/) to provide a system where open data released by governments can be authenticated by end users—whether or not the data was most recently downloaded from the official source.

Government data releases need to abide by local laws (for example, the District of Columbia Official Code) and should also abide by the [Uniform Electronic Legal Material Act (UELMA)](https://github.com/unitedstates/data-seal/wiki/UELMA). Part of the UELMA provisions state that “legal material be…authenticated, by providing a method to determine that it is unaltered”.

Data Seal provides agencies with a web-based interface to provide this functionality.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

Django/Python

**Project URL**

<https://github.com/unitedstates/data-seal/wiki>

**Source Location**

<https://github.com/unitedstates/data-seal>

***Tag(s)***

data authentication, Security

FIDO (Fully Integrated Defense Operation)

**SBB Description**

FIDO (Fully Integrated Defense Operation – apologies to the FIDO Alliance for acronym collision) is developed by NetFlix and now OSS. This system is for automatically analyzing security events and responding to security incidents.

The premise of FIDO is simple… each year companies are receiving an ever increasing amount of security related alerts. Instead of hiring more analyst to comb through the endless stream of alerts we automate the analysis to combat the barrage of information. Simply put, we integrate and then automate the manual human processes by codifying the logic and process used by threat analysts to provide consistent and reliable results.

The typical process for investigating security-related alerts is labor intensive and largely manual. To make the situation more difficult, as attacks increase in number and diversity, there is an increasing array of detection systems deployed and generating even more alerts for security teams to investigate.

FIDO is a NetFlix OSS project, see: <http://techblog.netflix.com/2015/05/introducing-fido-automated-security.html>

**SBB License**

Apache License 2.0

**Core Technology**

C\#

**Project URL**

<https://github.com/Netflix/Fido/wiki>

**Source Location**

<https://github.com/Netflix/Fido>

***Tag(s)***

Security, SIEM

Gryffin

**SBB Description**

Gryffin is a large scale web security scanning platform. Created by Yahoo, and since September 2015 available as open source.

It is not yet another scanner. It was written to solve two specific problems with existing scanners: coverage and scale. Better coverage translates to fewer false negatives. Inherent scalability translates to capability of scanning, and supporting a large elastic application infrastructure. Simply put, the ability to scan 1000 applications today to 100,000 applications tomorrow by straightforward horizontal scaling.

**SBB License**

MIT License

**Core Technology**

Go

**Project URL**

<https://github.com/yahoo/gryffin>

**Source Location**

<https://github.com/yahoo/gryffin>

***Tag(s)***

IDS, Security, Vulnerability scanning

Kali

**SBB Description**

Kali is the most complete ‘Penetration Testing Linux Distribution’ around. Everything you need for penetration testing is collected, tested and made available on this linux distribution. Of course all tools are OSS.

The complete list of tools can be found here:<http://tools.kali.org/tools-listing>

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

N.A. (OSS Tool collection)

**Project URL**

<https://www.kali.org/>

**Source Location**

<http://git.kali.org/gitweb/>

***Tag(s)***

Security, Sniffer, Vulnerability scanning

Kismet

**SBB Description**

Kismet is an 802.11 layer2 wireless network detector, sniffer, and intrusion detection system. Kismet will work with any wireless card which supports raw monitoring (rfmon) mode, and (with appropriate hardware) can sniff 802.11b, 802.11a, 802.11g, and 802.11n traffic. Kismet also supports plugins which allow sniffing other media such as DECT.

Kismet identifies networks by passively collecting packets and detecting standard named networks, detecting (and given time, decloaking) hidden networks, and inferring the presence of non beaconing networks via data traffic. The great feature of Kismet is that this tool works working passively, so detection by IDS is prevented when scanning WLAN’s.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

C++

**Project URL**

<http://www.kismetwireless.net/>

**Source Location**

<https://www.kismetwireless.net/code/>

***Tag(s)***

IDS, Security, Sniffer

Libreswan

**SBB Description**

Libreswan is an IPsec implementation for Linux. Libreswan is a free software implementation of the most widely supported and standarized VPN protocol based on (“IPsec”) and the Internet Key Exchange (“IKE”).

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

**Project URL**

<https://libreswan.org/>

**Source Location**

<https://github.com/libreswan/libreswan>

***Tag(s)***

communication, Cryptography, Security

Lynis

**SBB Description**

Lynis is a suite of tools (shell scripts) for security auditing, compliance and hardening for Linux, Mac OS, and Unix based systems. Of course many (better) audit tools are available, but this one is simple and straightforward. So easy to extend and to improve. Especially if you like shell-scripting.

Michael Boelen from the Netherlands (owner of company cisofy.com ) created this software.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

unix-shell scripts

**Project URL**

<https://cisofy.com>

**Source Location**

<https://github.com/CISOfy/lynis/>

***Tag(s)***

Audit, Security

Mantra

**SBB Description**

**OWASP Mantra** is a collection of free and open source tools integrated into a web browser, which can become handy for students, penetration testers, web application developers,security professionals etc. It is portable, ready-to-run, compact and follows the true spirit of free and open source software.

**Mantra** is lite, flexible, portable and user friendly with a nice graphical user interface. You can carry it in memory cards, flash drives, CD/DVDs, etc. It can be run natively on Linux, Windows and Mac platforms. It can also be installed on to your system within minutes. Mantra is absolutely free of cost and takes no time for you to set up.

Mantra is a browser especially designed for web application security testing. By having such a product, more people will come to know the easiness and flexibility of being able to follow basic testing procedures within the browser. Mantra believes that having such a portable, easy to use and yet powerful platform can be helpful for the industry.

Mantra has many built in tools to modify headers, manipulate input strings, replay GET/POST requests, edit cookies, quickly switch between multiple proxies, control forced redirects etc. This makes it a good software for performing basic security checks and sometimes, exploitation. Thus, Mantra can be used to solve basic levels of various web based CTFs, showcase security issues in vulnerable web applications etc.

**SBB License**

GNU General Public License (GPL) 3.0

**Core Technology**

javascript

**Project URL**

<http://www.getmantra.com>

**Source Location**

<https://code.google.com/p/getmantra/>

***Tag(s)***

Security, Test Tool

OpenVAS

**SBB Description**

OpenVAS is a framework of several services and tools offering a comprehensive and powerful vulnerability scanning and vulnerability management solution.

The core of this SSL-secured service-oriented architecture is the **OpenVAS Scanner**. The scanner very efficiently executes the actual Network Vulnerability Tests (NVTs) which are served with daily updates via the [OpenVAS NVT Feed](http://www.openvas.org/openvas-nvt-feed.html) or via a commercial feed service.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

C

**Project URL**

<http://www.openvas.org>

**Source Location**

[https://scm.wald.intevation.org/svn/openvas/trunk](%20https://scm.wald.intevation.org/svn/openvas/trunk)

***Tag(s)***

Security, Vulnerability scanning

OWASP ZCR Shellcoder

**SBB Description**

OWASP ZCR Shellcoder is an open source software in python language which lets you generate customized shellcodes for various operation systems. Shellcodesare small codes in assembly which could be use as the payload in software exploiting. Other usages are in malwares, bypassing antiviruses, obfuscated codes and etc.

**SBB License**

GNU General Public License (GPL) 3.0

**Core Technology**

Python

**Project URL**

<https://www.owasp.org/index.php/OWASP_ZSC_Tool_Project>

**Source Location**

<https://github.com/Ali-Razmjoo/OWASP-ZSC/>

***Tag(s)***

Security, Test Tool

OWASP Zed Attack Proxy (ZAP)

**SBB Description**

The OWASP Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications.

It is designed to be used by people with a wide range of security experience and as such is ideal for developers and functional testers who are new to penetration testing as well as being a useful addition to an experienced pen testers toolbox.

**SBB License**

Apache License 2.0

**Core Technology**

Java

**Project URL**

<https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project#tab=Main>

**Source Location**

<https://github.com/zaproxy/zaproxy>

***Tag(s)***

Security

Phpseclib (PHP Secure Communications Library)

**SBB Description**

Php<span class="red">sec</span>lib is designed to be ultra-compatible. It works on PHP4+ (PHP4, assuming the use of [PHP\_Compat](http://pear.php.net/package/PHP_Compat)) and doesn’t require any extensions. For purposes of speed, **mcrypt is used** if it’s available **as is gmp or bcmath** (in that order), but they are not required. Php<span class="red">sec</span>lib is designed to be fully interoperable with OpenSSL and other standardized cryptography programs and protocols.

Php<span class="red">sec</span>lib is a pure-PHP implementations of:

-   BigIntegers
-   RSA
-   SSH2
-   SFTP
-   X.509
-   Symmetric key encryption
    -   AES
    -   Rijndael
    -   Twofish
    -   Blowfish
    -   DES
    -   3DES
    -   RC4
    -   RC2

**SBB License**

MIT License

**Core Technology**

PHP

**Project URL**

<http://phpseclib.sourceforge.net/>

**Source Location**

<https://github.com/phpseclib/phpseclib>

***Tag(s)***

Cryptography, Security

RIPS (code analyser)

**SBB Description**

<span class="vulntitle">RIPS is a tool written in PHP to find vulnerabilities in PHP applications using static code analysis. By tokenizing and parsing all source code files RIPS is able to transform PHP source code into a program model and to detect sensitive sinks (potentially vulnerable functions) that can be tainted by userinput (influenced by a malicious user) during the program flow. Besides the structured output of found vulnerabilities RIPS also offers an integrated code audit framework for further manual analysis.</span>

RIPS was released during the Month of PHP Security ([www.php-security.org](http://www.php-security.org)).

**Features**

-   detect XSS, SQLi, File disclosure, LFI/RFI, RCE vulnerabilities and more
-   5 verbosity levels for debugging your scan results
-   mark vulnerable lines in source code viewer
-   highlight variables in the code viewer
-   user-defined function code by mouse-over on detected call
-   active jumping between function declaration and calls
-   list of all user-defined functions (defines and calls), program entry points (user input) and scanned files (with includes) connected to the source code viewer
-   graph visualization for files and includes as well as functions and calls
-   create CURL exploits for detected vulnerabilities with few clicks
-   visualization, description, example, PoC, patch and securing function list for every vulnerability
-   7 different syntax highlighting colour schemata
-   display scan result in form of a top-down flow or bottom-up trace
-   only minimal requirement is a local webserver with PHP and a browser (tested with Firefox)
-   regex search function

**SBB License**

GNU General Public License (GPL) 3.0

**Core Technology**

PHP

**Project URL**

<http://rips-scanner.sourceforge.net/>

**Source Location**

<http://sourceforge.net/projects/rips-scanner/>

***Tag(s)***

Code Analyzer, Security

Security Monkey

**SBB Description**

Security Monkey monitors policy changes and alerts on insecure configurations in an AWS account. While Security Monkey’s main purpose is security, it also proves a useful tool for tracking down potential problems as it is essentially a change tracking system.

More information: <http://techblog.netflix.com/2014/06/announcing-security-monkey-aws-security.html>

**SBB License**

Apache License 2.0

**Core Technology**

Python

**Project URL**

<http://securitymonkey.readthedocs.org/en/latest/>

**Source Location**

<https://github.com/Netflix/security_monkey>

***Tag(s)***

Security, SIEM

SIMP (The System Integrity Management Platform)

**SBB Description**

SIMP is a framework that aims to provide a reasonable combination of security compliance and operational flexibility. Fundamentally, SIMP is a framework that is designed to be secure from a practical point of view out of the box. As a framework, SIMP is designed to be flexed to meet the needs of the end user.

The ultimate goal of the project is to provide a complete management environment focused on compliance with the various profiles in the [SCAP Security Guide Project](https://fedorahosted.org/scap-security-guide/) and industry best practice.

Though it is fully capable out of the box, the intent of SIMP is to be molded to your target environment in such a way that deviations are easily identifiable to both Operations Teams and Security Officers. This project is released to the public by the US <span class="author">National Security Agency.</span>

**SBB License**

MIT License

**Core Technology**

**Project URL**

<https://github.com/NationalSecurityAgency/SIMP>

**Source Location**

<https://github.com/simp>

***Tag(s)***

Audit, Security

Simplify

**SBB Description**

Simplify uses a virtual machine to understand what an app does. Then, it applies optimizations to create code that behaves identically, but is easier for a human to understand. Specifically, it takes Smali files as input and outputs a Dex file with (hopefully) identical semantics but less complicated structure.

For example, if an app’s strings are encrypted, Simplify will interpret the app in its own virtual machine to determine semantics. Then, it uses the apps own code to decrypt the strings and replaces the encrypted strings and the decryption method calls with the decrypted versions. It’s a **generic** deobfuscator because Simplify doesn’t need to know how the decryption works ahead of time. This technique also works well for eliminating different types of white noise, such as no-ops and useless arithmetic.

**SBB License**

MIT License

**Core Technology**

**Project URL**

[]()

**Source Location**

<https://github.com/CalebFenton/simplify>

***Tag(s)***

Code Analyzer, Security

Streisand

**SBB Description**

Streisand is software for setting up secure connections with your friends. A bit like TOR. Communication can be sets up over L2TP/IPsec, OpenSSH, OpenVPN, Shadowsocks, sslh, Stunnel, and a Tor bridge.

**SBB License**

GNU General Public License (GPL) 3.0

**Core Technology**

Python

**Project URL**

<https://github.com/jlund/streisand>

**Source Location**

<https://github.com/jlund/streisand>

***Tag(s)***

Privacy, Security

Stunnel

**SBB Description**

Stunnel is a proxy designed to add TLS encryption functionality to existing clients and servers without any changes in the programs’ code. Its architecture is optimized for security, portability, and scalability (including load-balancing), making it suitable for large deployments.

Stunnel uses the OpenSSL library for cryptography, so it supports whatever cryptographic algorithms are compiled into the library. It can benefit from the FIPS 140-2 validation of the OpenSSL FIPS Object Module, as long as the building process meets its Security Policy.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

C

**Project URL**

<https://www.stunnel.org/index.html>

**Source Location**

<http://www.usenix.org.uk/mirrors/stunnel/>

***Tag(s)***

Cryptography, Security

Suricata

**SBB Description**

Suricata is a high performance Network IDS, IPS and Network Security Monitoring engine. [Open Source](http://suricata-ids.org/about/open-source/ "Open Source") and owned by a community run non-profit foundation, the Open Information Security Foundation ([OISF](http://idsips.wordpress.com/about/oisf/ "OISF")). Suricata is developed by the OISF and its [supporting vendors](http://suricata-ids.org/about/consortium/ "Consortium Members").

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

C

**Project URL**

<http://suricata-ids.org>

**Source Location**

<https://github.com/inliniac/suricata>

***Tag(s)***

IDS, Security

SWAMP (Software Assurance Marketplace)

**SBB Description**

This security application is a SAAS solution. However it is built of OSS building blocks and available to be use under an friendly OSS license for everyone.

-   Capabilities of the SWAMP
-   Static analysis
-   Operates on the original source code
-   Tracks problems down to the location in the original code
-   Relatively quick and easy to use
-   Provides complete code coverage
-   Compare results from multiple tools
-   Find and visualize overlaps
-   Correlate results

Languages supported: C/C++,Java source, Java bytecode, Python, Ruby. PHP and Javascript are on the roadmap for end 2015 to be supported.

**SBB License**

GNU General Public License (GPL) 3.0

**Core Technology**

**Project URL**

<https://www.mir-swamp.org>

**Source Location**

[]()

***Tag(s)***

Code Analyzer, Security

Tor

**SBB Description**

Tor is free software and an open network that helps you defend against traffic analysis, a form of network surveillance that threatens personal freedom and privacy, confidential business activities and relationships, and state security. Creating your own Tor network is easy with this software, or use existing Tor nodes.

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

**Project URL**

<https://www.torproject.org>

**Source Location**

<https://www.torproject.org/dist/>

***Tag(s)***

Cryptography, Privacy, Security

Vault

**SBB Description**

Vault is a tool for securely accessing secrets. A secret is anything that you want to tightly control access to, such as API keys, passwords, certificates, and more. Vault provides a unified interface to any secret, while providing tight access control and recording a detailed audit log.

<span class="strong">Vault</span> secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets in modern computing. Vault handles leasing, key revocation, key rolling, and auditing. Vault presents a unified API to access multiple backends: HSMs, AWS IAM, SQL databases, raw key/value, and more.

A modern system requires access to a multitude of secrets: database credentials, API keys for external services, credentials for service-oriented architecture communication, etc. Understanding who is accessing what secrets is already very difficult and platform-specific. Adding on key rolling, secure storage, and detailed audit logs is almost impossible without a custom solution. This is where Vault steps in.

**SBB License**

Mozilla Public License (MPL) 1.1

**Core Technology**

GO

**Project URL**

<https://vaultproject.io>

**Source Location**

<https://github.com/hashicorp/vault>

***Tag(s)***

Security

w3af (Web Application Attack and Audit Framework)

**SBB Description**

w3af is a Web Application Attack and Audit Framework. The project’s goal is to create a framework to help you secure your web applications by finding and exploiting all web application vulnerabilities.

The w3af framework is divided into three main sections:

1.  The core, which coordinates the whole process and provides libraries for using in plugins.
2.  The user interfaces, which allow the user to configure and start scans
3.  The plugins, which find links and vulnerabilities

**SBB License**

GNU General Public License (GPL) 2.0

**Core Technology**

Phython

**Project URL**

<http://w3af.org/>

**Source Location**

<https://github.com/andresriancho/w3af/>

***Tag(s)***

Audit, Security, Test Tool

