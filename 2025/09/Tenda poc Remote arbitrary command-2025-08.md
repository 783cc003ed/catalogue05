## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-08-21`

* https://github.com/wshidamowang/Router/blob/main/Tenda/AC18/RCE_1.md?cve=title

<blockquote>
 RouterTendaAC18RCE1mdatmainGitHub
</blockquote>
<blockquote>
I found an Arbitrary Command Execution vulnerability in the router's web server-- /bin/httpd of squashfs filesystem. While processing the mac parameters for a post request (when an attacker accesses ip/goform/WriteFacMac), the value is directly passed to doSystem, which causes a RCE.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-08-21`

* https://cve.imfht.com/poc_detail/8765a73bec77d8586b6a4ccd06c73730786c41e8

<blockquote>
 POC详情8765a73bec77d8586b6a4ccd06c73730786c41e8
</blockquote>
<blockquote>
The goform/setUsbUnload endpoint of Tenda AC15 AC1900 version 15.03.05.19 allows remote attackers to execute arbitrary system commands via the deviceName POST parameter.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-08-21`

* https://securityvulnerability.io/vulnerability/CVE-2025-7415

<blockquote>
 CommandInjectionVulnerabilityinTendaO3V2Router
</blockquote>
<blockquote>
What is CVE-2025-7415? A serious command injection vulnerability exists in the Tenda O3V2 router's /goform/getTraceroute component, specifically affecting the fromTraceroutGet function. By manipulating the dest argument, attackers can execute arbitrary commands on the device remotely. This vulnerability has been publicly disclosed, making it crucial for users to patch their devices promptly to ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-08-21`

* https://securityvulnerability.io/exploits/latest

<blockquote>
 LatestCyberSecurityExploitPoCs
</blockquote>
<blockquote>
A command injection vulnerability has been discovered in the Tenda AC20 router's Telnet Service, specifically within the websFormDefine function of the /goform/telnet file. This flaw allows an attacker to execute arbitrary commands remotely, leading to unauthorized system access and potential com...
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-08-21`

* https://github.com/ZZ2266/.github.io/blob/main/AC20/telnet/readme.md

<blockquote>
 githubioAC20telnetreadmemdatmainZZ2266githubio
</blockquote>
<blockquote>
A remote command execution vulnerability exists in the Tenda AC20 router (firmware V16.03.08.12), allowing attackers to activate the telnet service via a specific HTTP endpoint. The vulnerability resides in the TendaTelnet function, which directly executes system commands to start the telnet service without proper input sanitization, enabling attackers to gain interactive shell access to the ...
</blockquote>

---

