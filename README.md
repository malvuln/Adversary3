# Adversary3

Malware Vulnerability Bedazzler -
By John Page (aka malvuln/hyp3rlinx) Copyright (C) TM 2022

www.malvuln.com
twitter.com/malvuln
twitter.com/hyp3rlinx
malvuln13@gmail.com
ISR: ApparitionSec
hyp3rlinx.altervista.org

Adversary3.py navigates the vast www.malvuln.com malware vulnerability dataset.
Need a way in but no 0day?, choose the path of least resistance and
work off the backs of others (virus) flaws.
Yes, shot in the dark... but vuln backdoors, trojans and virus exist.
Redteam? look for infected hosts with unsecured backdoors, BoF or RCE.
On a system with low privs? look for infections with weak permissions
you get the idea third-party adversary!

NOTE: Tested on Windows 10 Python3 / Kali (Python3)
Requirements: Windows OS > 7 and Python 3
Run on Kali: python3 Adversary3.py

Adversary3 Commands:
===================
repos: Lists repositories, vulns and amount of each vuln class.\n
credz: Malware backdoors [PASSWORD] list.\n
familia: Search number of [VULNS] for all or specific malware [FAMILY].
ports: Lists vuln backdoor malware ports.
md5: Search vulns based on a MD5 malware hash.
mvid: Search vulns based on a MVID malware advisory.
vulns: Browse vuln categories and advisorys, based on the latest downloaded .Zip archive.
md5family: Returns malware [FAMILY][MD5] by family, MD5 or *.
shodan: Crawl the internet for a vuln malware port. Requires a Shodan Enterprise Data license.
scan: Basic port scan for vuln malware ports using half open SYN packet.
 (Note: scan networks or systems for which you have permission to scan)
update: Download and update lastest Adversary3 .Zip from github.com/malvuln.
id: Get MVID, MD5 by MVID, MD5 or wildcard *
cls: Clears the [CONSOLE] window.
about: Explanation of Adversary3.

DISCLAIMER:
Author is NOT responsible for any damages whatsoever by using this software,
by using Adversary3 you assume and accept all risk implied or otherwise.

MIT License - Copyright (c) 2022 malvuln
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Permission is also explicitly given for insertion in vulnerability databases and similar,
provided that due credit is given to the author John Page (aka malvuln/hyp3rlinx) Copyright (C)(TM) 2022
