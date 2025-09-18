## DuckDuckgo search -> Tenda poc Execute arbitrary code
`2025-09-17`

* https://detailed-stetson-767.notion.site/Tenda-AX1806-Buffer-Overflow-in-getIptvInfo-d15d44b770e24213a8dcb13a4812e3f4?pvs=4

<blockquote>
 TendaAX1806BufferOverflowingetIptvInfo
</blockquote>
<blockquote>
The first time call formSetIptv , SetValue with a string whose length longer than v16 (64), the second time call getIptvInfo will Use the Getvalue to assign the string value to the local variable v16 .In the end,it will cause buffer overflow or even allows a remote attacker to execute arbitrary code.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Execute arbitrary code
`2025-09-17`

* https://securityvulnerability.io/vulnerability/CVE-2025-7417

<blockquote>
 StackbasedBufferOverflowinTendaO3V2RouterCVE20257417
</blockquote>
<blockquote>
A vulnerability has been identified in Tenda O3V2 version 1.0.0.12 (3880), where improper handling of the 'ip' argument in the fromNetToolGet function of the /goform/setPingInfo component can lead to a stack-based buffer overflow. This flaw allows remote attackers to potentially execute arbitrary code, posing significant risks to device security.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Execute arbitrary code
`2025-09-17`

* https://github.com/Cpppq43/Tenda/blob/main/Tenda_AC20_V16.03.08.05.md

<blockquote>
 TendaTendaAC20V16030805mdatmainCpppq43Tenda
</blockquote>
<blockquote>
The Tenda AC20 is a wireless router manufactured by Tenda, a Chinese company. The Tenda AC20 contains a buffer overflow vulnerability stemming from the failure to properly validate the length of input data in the parameter wanMTU in the file /goform/fromAdvSetMacMtuWan. An attacker could exploit this vulnerability to execute arbitrary code on the system.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Execute arbitrary code
`2025-09-17`

* https://redteamnews.com/red-team/cve/tenda-w12-and-i24-httpd-stack-based-buffer-overflow-vulnerability-cve-2025-4007-technical-analysis-and-mitigation/

<blockquote>
 TendaW12andi24HTTPdStackBasedBufferOverflowVulnerabilityCVE
</blockquote>
<blockquote>
A critical stack-based buffer overflow vulnerability (CVE-2025-4007) has been identified in Tenda W12 and i24 routers, affecting firmware versions 3.0.0.4 (2887) and 3.0.0.5 (3644). The flaw resides in the HTTPd module's `cgidhcpsCfgSet` function, which mishandles the `json` argument, allowing remote attackers to execute arbitrary code. With a CVSSv3 score of 8.8 (High), this vulnerability ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc Execute arbitrary code
`2025-09-17`

* https://cve.imfht.com/poc_detail/3843a814a81d73c19cb785ca8620af830726e427

<blockquote>
 POC详情3843a814a81d73c19cb785ca8620af830726e427
</blockquote>
<blockquote>
This vulnerability allows **unauthenticated remote attackers** to crash the router's web server (**Denial-of-Service, DoS**) and potentially execute arbitrary code (**Remote Code Execution, RCE**).
</blockquote>

---

## DuckDuckgo search -> Tenda poc Execute arbitrary code
`2025-09-17`

* https://github.com/ZZ2266/.github.io/blob/main/AC20/fromSetIpMacBind/readme.md

<blockquote>
 githubioAC20fromSetIpMacBindreadmemdatmainZZ2266githubio
</blockquote>
<blockquote>
A stack-based buffer overflow vulnerability in the Tenda AC20 router (firmware V16.03.08.12) allows unauthenticated remote attackers to execute arbitrary code or cause denial of service (DoS) via the list parameter in the /goform/SetIpMacBind endpoint. The flaw resides in the sub_48E628 function, which processes the list input using the unsafe strcpy function without bounds checking, leading ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc Auth Bypass
`2025-09-17`

* https://vuldb.com/?id.320788

<blockquote>
 CVE202524496TendaAC6getproductInfoauthenticationbypassTALOS
</blockquote>
<blockquote>
A product requires authentication, but the product has an alternate path or channel that does not require authentication. As an impact it is known to affect confidentiality. CVE summarizes: An information disclosure vulnerability exists in the /goform/getproductInfo functionality of Tenda AC6 V5.0 V02.03.01.110.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Auth Bypass
`2025-09-17`

* https://book.hacktricks.wiki/en/linux-hardening/privilege-escalation/android-rooting-frameworks-manager-auth-bypass-syscall-hook.html

<blockquote>
 AndroidRootingFrameworksManagerAuthBypassSyscallHookHackTricks
</blockquote>
<blockquote>
Rooting frameworks like KernelSU, APatch, SKRoot and Magisk frequently patch the Linux/Android kernel and expose privileged functionality to an unprivileged userspace &quot;manager&quot; app via a hooked syscall. If the manager-authentication step is flawed, any local app can reach this channel and escalate privileges on already-rooted devices.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-09-17`

* https://0reg.dev/blog/tenda-ac8-rop

<blockquote>
 Retr0sRegister0regdev
</blockquote>
<blockquote>
At this point, executing arbitrary commands on the Tenda Ac8v4 Router will a easy-peasy task for us. Nevertheless, if you ever logged into the QEMU VM that was created for this router's file system, you will there's pretty nothing we can run, even scp and wget don't exist in busybox, then how can we create a reverse-shell back to our machine?
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-09-17`

* https://docs.sekoia.io/integration/categories/network_security/netskope_transaction/

<blockquote>
 NetskopeTransactionEventsSekoiaioDocumentation
</blockquote>
<blockquote>
A remote, authenticated attacker can execute arbitrary commands on the system hosting a vulnerable FortiWeb WAF by sending a POST request with the command in the name field.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-09-17`

* https://gist.github.com/Swind1er/c8e4369c7fdfd750c8ad01a276105c57

<blockquote>
 tendaAX9AX12V10setMacFilterCfgCommandExecutionVulnerabilityPoC
</blockquote>
<blockquote>
The web server in the firmware's file system processes the /goform/setMacFilterCfg request without filtering the content of the incoming macFilterType string. This allows an attacker to write a restricted number of illegal characters into the file system under the macFilterType field, leading to arbitrary command execution.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-09-17`

* https://github.com/Thir0th/Thir0th-CVE/blob/main/Tenda_AC20_V16.03.08.05_has_a_stack_overflow.md

<blockquote>
 Thir0thCVETendaAC20V16030805hasastackoverflowmdatGitHub
</blockquote>
<blockquote>
Tenda AC20 is a wireless router from China's Tenda company. Tenda AC20 has a buffer overflow vulnerability. The vulnerability is caused by the parameter list in the file /goform/SetStaticRouteCfg failing to correctly verify the length of the input data. Attackers can exploit this vulnerability to execute arbitrary code on the system.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote arbitrary command
`2025-09-17`

* https://medium.com/@frostbyte1122/analysis-of-traffic-and-payload-extracted-froby-tenda-router-honeypot-5bd9867176e6

<blockquote>
 AnalysisoftrafficandpayloadextractedfromTendaRouterHoneypot
</blockquote>
<blockquote>
The goform/setUsbUnload endpoint of Tenda AC15 AC1900 version 15.03.05.19 allows remote attackers to execute arbitrary system commands via the deviceName parameter.
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://www.reddit.com/r/kingdomcome/comments/wijq8l/a_while_back_there_was_a_discussion_about_lack_of/

<blockquote>
 AwhilebacktherewasadiscussionaboutlackofPOCbutiReddit
</blockquote>
<blockquote>
A while back there was a discussion about lack of POC, but i found one. The charlatan met one in Vienna. And he was not covered in charcoal
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://tendacn.com/product/SG110PC.html

<blockquote>
 SG110PC10PortGigabitLitePoESwitchwith8PortPoETenda
</blockquote>
<blockquote>
SG110PC is a gigabit dual-port uplink unmanaged PoE switch independently designed by Tenda. Compatible with AF/AT standard PoE power supply mode, intelligent identification of powered devicesprepare. - SG110PC - Feature - Tenda Global (English)
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://nvd.nist.gov/vuln/detail/CVE-2025-7418

<blockquote>
 NvdCve20257418
</blockquote>
<blockquote>
Information Technology Laboratory National Vulnerability DatabaseVulnerabilities
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://vulmon.com/vulnerabilitydetails?qid=CVE-2025-9298

<blockquote>
 Cve20259298
</blockquote>
<blockquote>
Vulnerability Summary A flaw has been found in Tenda M3 1.0.0.12. Affected is the function formQuickIndex of the file /goform/QuickIndex. Executing manipulation of the argument PPPOEPassword can lead to stack-based buffer overflow. The attack can be launched remotely. The exploit has been published and may be used. Subscribe to Tenda
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://securityvulnerability.io/vulnerability/CVE-2025-10442

<blockquote>
 OSCommandInjectioninTendaAC9andAC15Routers
</blockquote>
<blockquote>
Learn about the OS command injection vulnerability affecting Tenda AC9 and AC15 routers that can be exploited remotely. CVE-2025-10442.
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://nvd.nist.gov/vuln/detail/CVE-2025-7793

<blockquote>
 NvdCve20257793
</blockquote>
<blockquote>
Information Technology Laboratory National Vulnerability DatabaseVulnerabilities
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://github.com/xiaobor123/tenda-vul-i22

<blockquote>
 Detailsofthevulnerabilityfoundinthetendarouteri22V1GitHub
</blockquote>
<blockquote>
The following vulnerability analysis and explanation are based on the i22 router with firmware version V1.0.0.3(4687). Due to conditions such as nbytes &#61; 0 being met, wp-&gt;state([wp[0x35]]) &#61; 8 is finally set in the websGetInput function at address 0x24c00. At the address 0x24524 of the websReadEvent ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://nvd.nist.gov/vuln/detail/CVE-2025-9297

<blockquote>
 NvdCve20259297
</blockquote>
<blockquote>
Information Technology Laboratory National Vulnerability DatabaseVulnerabilities
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://securityvulnerability.io/vulnerability/CVE-2025-9298

<blockquote>
 CVE20259298StackbasedBufferOverflowinTendaM3Router
</blockquote>
<blockquote>
What is CVE-2025-9298? A vulnerability has been identified in the Tenda M3 router version 1.0.0.12 that impacts the function formQuickIndex within the /goform/QuickIndex file. This flaw allows an attacker to manipulate the PPPOEPassword argument, potentially leading to a stack-based buffer overflow. This remote exploit can compromise the router's functionality, making it imperative for users ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://securityvulnerability.io/vulnerability/CVE-2025-10120

<blockquote>
 BufferOverflowVulnerabilityinTendaAC20Router
</blockquote>
<blockquote>
Discover the buffer overflow vulnerability affecting Tenda AC20 routers, exposing users to remote attacks. Learn more about CVE-2025-10120.
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://nvd.nist.gov/vuln/detail/CVE-2025-7551

<blockquote>
 NvdCve20257551
</blockquote>
<blockquote>
Information Technology Laboratory National Vulnerability DatabaseVulnerabilities
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://github.com/dumitory-dev/CVE-2020-35391-POC

<blockquote>
 GitHubdumitorydevCVE202035391POCTendaN300Authentication
</blockquote>
<blockquote>
dumitory-dev / CVE-2020-35391-POC Public Notifications You must be signed in to change notification settings Fork 2 Star 2
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://nvd.nist.gov/vuln/detail/CVE-2025-9299

<blockquote>
 NvdCve20259299
</blockquote>
<blockquote>
Information Technology Laboratory National Vulnerability DatabaseVulnerabilities
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://github.com/SunnyYANGyaya/IOT-Vulnerable_POC--

<blockquote>
 SunnyYANGyayaIOTVulnerablePOCGitHub
</blockquote>
<blockquote>
&amp;quot;Collection of IoT vulnerability research and exploits, focusing on unauthorized access, CVEs, and popular devices like TP-LINK, Tenda, D-Link, and more. Perfect for penetration testing and Io...
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://github.com/SolitaryGrass/IoT_vuln/blob/main/tenda/AC6/AC6V2.0RTL_V15.03.06.23/formSetMacFilterCfg/poc.md

<blockquote>
 IoTvulntendaAC6AC6V20RTLV15030623formSetMacFilterCfgpocmd
</blockquote>
<blockquote>
Firmware download website: AC6V2.0升级软件_腾达 (Tenda)官方网站 In the function formSetMacFilterCfg, user-supplied parameters macFilterType and deviceList are passed to a function without input validation, ultimately leading to an overflow. formSetMacFilterCfg-》set_macfilter_rules-》set_macfilter_rules_by_one-》parse_macfilter_rule-》strcpy poc
</blockquote>

---

## DuckDuckgo search -> Tenda poc
`2025-09-17`

* https://blog.csdn.net/weixin_48539059/article/details/135084950

<blockquote>
 Tenda账号密码泄露漏洞复现附POCCSDN博客
</blockquote>
<blockquote>
文章浏览阅读917次，点赞8次，收藏10次。本文详细介绍了Tenda路由器存在的信息泄露漏洞，攻击者可通过特定接口获取到后台账号密码。文章提供了影响版本、漏洞环境的FOFA查询语法，并展示了两种GET方式的POC，用于漏洞复现。
</blockquote>

---

## DuckDuckgo search -> Tenda poc OS Command injection
`2025-09-17`

* https://securityvulnerability.io/vulnerability/CVE-2025-5606

<blockquote>
 CommandInjectionVulnerabilityinTendaAC18Router
</blockquote>
<blockquote>
A command injection vulnerability exists in the Tenda AC18 router, specifically in the function formSetIptv located in the /goform/SetIPTVCfg file. This security flaw allows an attacker to manipulate the argument list, potentially leading to unauthorized command execution.
</blockquote>

---

## DuckDuckgo search -> Tenda poc OS Command injection
`2025-09-17`

* https://github.com/DaDong-G/Vulnerability_info/blob/main/ac10_command_injection/Readme.md

<blockquote>
 Vulnerabilityinfoac10commandinjectionReadmemdatmainGitHub
</blockquote>
<blockquote>
The Tenda AC10 (V15.03.06.26) was found to contain a command insertion vulnerability in formWriteFacMac.This vulnerability allows an attacker to execute arbitrary commands through the &quot;mac&quot; parameter.
</blockquote>

---

## DuckDuckgo search -> Tenda poc OS Command injection
`2025-09-17`

* https://github.com/z1r00/IOT_Vul/blob/main/Tenda/W6-S/exeCommand/readme.md

<blockquote>
 IOTVulTendaW6SexeCommandreadmemdatmainGitHub
</blockquote>
<blockquote>
In /goform/exeCommand, cmdinput is controlled by the user, it will be copied to s by vos_strcpy, and finally tpi_get_ping_output will be called to execute the command, which is not restricted, resulting in a command injection vulnerability
</blockquote>

---

## DuckDuckgo search -> Tenda poc Authentication Bypass
`2025-09-17`

* https://www.censys.com/advisory/cve-2025-1851

<blockquote>
 March7AdvisoryTendaAC7StackedBasedBufferOverflowVulnerability
</blockquote>
<blockquote>
Successful exploitation may allow an attacker to obtain a root shell on the device - however, based on the PoC, this appears to require authentication to the device to successfully exploit, which mitigates the potential impact. The assigned CVSS score of 8.7 seems relatively high given that authentication is needed to exploit.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Authentication Bypass
`2025-09-17`

* https://dec-solutions.com/cve-2025-27129-tenda-ac6-authentication-bypass-risk/

<blockquote>
 CVE202527129TendaAC6AuthenticationBypassRisk
</blockquote>
<blockquote>
CVE-2025-27129 vulnerability affects the Tenda AC6 router, enabling HTTP authentication bypass and potential unauthorized access.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Authentication Bypass
`2025-09-17`

* https://github.com/dumitory-dev/CVE-2020-35391-POC/blob/main/README.md

<blockquote>
 CVE202035391POCREADMEmdatmainGitHub
</blockquote>
<blockquote>
Tenda N300 Authentication Bypass via Malformed HTTP Request Header - dumitory-dev/CVE-2020-35391-POC
</blockquote>

---

## DuckDuckgo search -> Tenda poc Authentication Bypass
`2025-09-17`

* https://docs.vulncheck.com/initial-access/2025-08-29

<blockquote>
 ThreeauthbypasseswalkintoabarNewexploitsandsignaturesontap
</blockquote>
<blockquote>
CVE-2025-54309: CrushFTP Authentication Bypass, CVE-2025-52970: FortiWeb Authentication Bypass, CVE-2025-57788: Commvault API Key Retrieval via Authentication Bypass, CVE-2025-9090: Tenda AC20 Remote Telnet Enable, CVE-2025-27007: OttoKit (formerly SureTriggers) WordPress Plugin Incorrect Privilege Assignment
</blockquote>

---

## DuckDuckgo search -> Tenda poc Authentication Bypass
`2025-09-17`

* https://www.ameeba.com/blog/cve-2025-27129-authentication-bypass-vulnerability-in-tenda-ac6-v5-0-v02-03-01-110/

<blockquote>
 CVE202527129AuthenticationBypassVulnerabilityinTendaAC6V50
</blockquote>
<blockquote>
CVE-2025-27129 is one such security flaw that poses significant risks to users of the Tenda AC6 V5.0 V02.03.01.110. This vulnerability allows an attacker to bypass the HTTP authentication mechanism, leading to potential arbitrary code execution.
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://www.tendacn.com/product/TES7001

<blockquote>
 TES7001SinglePortGPONOLTTES7001FeatureTenda
</blockquote>
<blockquote>
TES7001 is a small volume, low density box GPON OLT access device, which provides GPON-based passive optical network for ISP, government ，park，hotel，schooland enterprise users. - TES7001 - Feature - Tenda Global (English)
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://www.bleepingcomputer.com/news/security/whatsapp-patches-vulnerability-exploited-in-zero-day-attacks/

<blockquote>
 WhatsApppatchesvulnerabilityexploitedinzerodayattacks
</blockquote>
<blockquote>
WhatsApp has patched a security vulnerability in its iOS and macOS messaging clients that was exploited in targeted zero-day attacks.
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://www.youtube.com/watch?v=OgKPjBs-P5Y

<blockquote>
 RepairingaTendaSmartPlugFixingtheRelayClickNoYouTube
</blockquote>
<blockquote>
In this video, I'm diagnosing and fixing a common issue with the Tenda Smart Plug, which has stopped working. The only sign of life is a clicking sound from the relay, but there's no Wi-Fi ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://www.tendacn.com/product/TES7002

<blockquote>
 TES70022PortGPONOLTTES7002FeatureTendaGlobalEnglish
</blockquote>
<blockquote>
TES7002 is a small volume, low density box GPON OLT access device, which provides GPON-based passive optical network for ISP, government ，park，hotel，schooland enterprise users. - TES7002 - Feature - Tenda Global (English)
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://github.com/b1n4r1b01/n-days/blob/main/CVE-2025-43300.md

<blockquote>
 ndaysCVE202543300mdatmainb1n4r1b01ndaysGitHub
</blockquote>
<blockquote>
Contribute to b1n4r1b01/n-days development by creating an account on GitHub.
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://www.tendacn.com/us/product/TES7002.html

<blockquote>
 TES70022PortGPONOLTTendaUS
</blockquote>
<blockquote>
TES7002 is a small volume, low density box GPON OLT access device, which provides GPON-based passive optical network for ISP, government ，park，hotel，schooland enterprise users.
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://zeropath.com/blog/cve-2025-9605-tenda-ac21-ac23-stack-buffer-overflow-summary

<blockquote>
 TendaAC21AC23CVE20259605StackBufferOverflowzeropathcom
</blockquote>
<blockquote>
A brief summary of CVE-2025-9605, a critical stack-based buffer overflow in Tenda AC21 and AC23 routers (firmware 16.03.08.16), including affected versions, technical details, proof of concept, detection methods, and vendor security history.
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://click.gos.pk/tender

<blockquote>
 CLICKCompetitiveLivableCityofKarachi
</blockquote>
<blockquote>
Tenders2025 2024 2023 2022 2021
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://github.com/b1n4r1b01/n-days/blob/main/CVE-2025-43300.md

<blockquote>
 ndaysCVE202543300mdatmainGitHub
</blockquote>
<blockquote>
iOS 18.6.1 0-click RCE POC The vulnerability seems to be in the Apple's implementation of JPEG Lossless Decompression code which is used inside Adobe's DNG file format.
</blockquote>

---

## DuckDuckgo search -> Tenda poc zero-click
`2025-09-17`

* https://undercodetesting.com/the-zero-click-nightmare-how-cve-2025-53772-turns-your-iis-server-into-a-hackers-playground/

<blockquote>
 TheZeroClickNightmareHowCVE202553772TurnsYourIISServerinto
</blockquote>
<blockquote>
We predict the emergence of cryptomining and ransomware payloads within 72 hours of a public Proof-of-Concept (PoC) exploit being released, forcing emergency patching cycles and widespread firewall reconfigurations across global enterprises.
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://gh.mlsub.net/mansploit/CVE-2024-29197-exploit

<blockquote>
 GitHubmansploitCVE202429197exploitTENDAROUTERAC10RCE
</blockquote>
<blockquote>
TENDA ROUTER AC10 - RCE (full research). Contribute to mansploit/CVE-2024-29197-exploit development by creating an account on GitHub.
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://www.censys.com/advisory/cve-2025-1851

<blockquote>
 March7AdvisoryTendaAC7StackedBasedBufferOverflowVulnerability
</blockquote>
<blockquote>
Date of Disclosure (source): February 22, 2025 CVE-2025-1851 is a high severity vulnerability affecting Tenda AC7 routers running firmware versions up to 15.03.06.44, with a CVSS score of 8.7. CVE-2025-1851 is a stack-based buffer overflow vulnerability within the formSetFirewallCfg function and allows a remote attacker to send a specially crafted payload to the router's web interface ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://www.wu.ac.at/star/about-us/rce-vienna/

<blockquote>
 RCEViennaAboutUsSTaRwuacat
</blockquote>
<blockquote>
The Regional Centre of Expertise on Education for Sustainable Development Vienna (RCE Vienna) is a project-based network for research, education and knowledge interactions on questions related to regional and transregional sustainable development and socioecological transformations. The RCE Vienna was founded in 2011 and is one of more than 190 RCEs worldwide. Since 2019 it has been associated ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://gist.github.com/win3zz/da5f1fb6e872c8ba50fcc5ed2dc0a82f

<blockquote>
 CVE20259523StackBasedBufferOverflowinTendaWiFi5Router
</blockquote>
<blockquote>
A stack-based buffer overflow vulnerability exists in the Tenda Wi-Fi 5 Router AC1206 running firmware AC1206V1.0RTL_V15.03.06.23. The issue lies in the /goform/GetParentControlInfo endpoint, where the mac parameter is copied into a fixed-size stack buffer using strcpy() without boundary checks. This flaw allows unauthenticated remote attackers to send a crafted payload and cause a Denial of ...
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://medium.com/@frostbyte1122/analysis-of-traffic-and-payload-extracted-froby-tenda-router-honeypot-5bd9867176e6

<blockquote>
 AnalysisoftrafficandpayloadextractedfromTendaRouterMedium
</blockquote>
<blockquote>
An online example of a PoC related to the exploitation of the authentication bypass to perform a Command Injection exploiting CVE-2023-37144 is present at the following blog post.
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://blog.csdn.net/user_hs/article/details/145599296

<blockquote>
 tenda路由器WriteFacMac存在远程命令执行漏洞CVE202410697CSDN博客
</blockquote>
<blockquote>
文章浏览阅读794次。tenda路由器WriteFacMac存在远程命令执行漏洞。_tenda路由器writefacmac存在远程命令执行漏洞
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://www.iotsec-zone.com/article/119

<blockquote>
 TendaAC15CVE202010987漏洞分析IOTsecZone
</blockquote>
<blockquote>
IOTsec-Zone是信睿网络创办的一个技术性社区，专注于物联网安全领域，秉承&quot;专业、创新、自由、开放&quot;的精神，致力于分享顶尖的物联网安全技术文章、挖掘最新的安全资讯以及核心的物联网安全课程教学
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://www.wu.ac.at/en/star/about-us/rce-vienna

<blockquote>
 RCEViennaAboutUsSTaRWU
</blockquote>
<blockquote>
Home About Us RCE Vienna RCE Vienna The Regional Centre of Expertise on Education for Sustainable Development Vienna (RCE Vienna) is a project-based network for research, education and knowledge interactions on questions related to regional and transregional sustainable development and socioecological transformations.
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://blog.csdn.net/m0_55368674/article/details/128939608

<blockquote>
 从零复现CVE漏洞Tenda路由器栈溢出复现CVE201818708路由器漏洞复现及环境搭建CSDN博客
</blockquote>
<blockquote>
文章浏览阅读6.2k次，点赞10次，收藏40次。Tenda 路由器栈溢出复现 (CVE-2018-18708)_路由器漏洞复现及环境搭建
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://sechub.in/view/3062091

<blockquote>
 TendaRouterFlawCVSS98UnauthenticatedRCEFlawPoCNoPatch
</blockquote>
<blockquote>
A critical vulnerability in the Tenda W18Ev2 Enterprise Router allows unauthenticated attackers to remotely change the administrator password The post Tenda Router Flaw (CVSS 9.8): Unauthenticated RCE Flaw (PoC, No Patch) appeared first on Daily CyberSecurity.
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://www.censys.com/advisory/cve-2025-1851

<blockquote>
 March7AdvisoryTendaAC7StackedBasedBufferOverflowVulnerability
</blockquote>
<blockquote>
CVE-2025-1851 is a high severity vulnerability affecting Tenda AC7 routers running firmware versions up to 15.03.06.44, with a CVSS score of 8.7. CVE-2025-1851 is a stack-based buffer overflow vulnerability within the formSetFirewallCfg function and allows a remote attacker to send a specially crafted payload to the router's web interface.
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://blog.csdn.net/user_hs/article/details/145599296

<blockquote>
 tenda路由器WriteFacMac存在远程命令执行漏洞CVE202410697CSDN博客
</blockquote>
<blockquote>
文章浏览阅读789次。tenda路由器WriteFacMac存在远程命令执行漏洞。_tenda路由器writefacmac存在远程命令执行漏洞
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://xz.aliyun.com/news/13848

<blockquote>
 基于实战的MIPS路由器栈溢出利用寄存器指令与攻击思路的探究
</blockquote>
<blockquote>
将httpd程序导入ghidra后按住ctrl+shift+e，呼出搜索界面，搜索strcpy函数，除了strcpy函数，也可以搜索system函数寻找RCE漏洞 上图就是程序调用了strcpy的地方，点击就能看到对应函数伪代码
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://github.com/Momollax/CVE-2025-53772-IIS-WebDeploy-RCE

<blockquote>
 GitHubMomollaxCVE202553772IISWebDeployRCE
</blockquote>
<blockquote>
This repository contains a Proof-of-Concept (PoC) exploit for CVE-2025-53772, a Remote Code Execution vulnerability in IIS WebDeploy through unsafe deserialization.
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://forum.butian.net/share/1619

<blockquote>
 奇安信攻防社区TendaAX1806路由器多处栈溢出漏洞
</blockquote>
<blockquote>
Tenda AX1806路由器固件版本 v1.0.0.1，存在多处栈溢出漏洞，漏洞点在 tdhttpd 二进制文件中，使用了危险函数 strcpy 前未对参数长度进行判断，导致拒绝服务漏洞。
</blockquote>

---

## DuckDuckgo search -> Tenda poc RCE
`2025-09-17`

* https://sc.rce-vienna.at

<blockquote>
 HomeSustainabilityChallenge
</blockquote>
<blockquote>
RCE - Regional Centre of Expertise on Education for Sustainable Development &quot;Die Teilnahme an der Sustainability Challenge war für mich eine bereichernde Erfahrung.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote Code Execution
`2025-09-17`

* https://dailycve.com/tenda-fh451-stack-overflow-vulnerability-cve-2025-45514-critical/

<blockquote>
 TendaFH451StackOverflowVulnerabilityCVE202545514Critical
</blockquote>
<blockquote>
An attacker can send an oversized payload to the vulnerable endpoint, corrupting the stack and potentially executing arbitrary code with root privileges. The lack of input validation allows overwriting critical memory addresses, leading to remote code execution (RCE) or a denial-of-service (DoS) condition.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote Code Execution
`2025-09-17`

* https://cvetodo.com/cve/CVE-2025-10120

<blockquote>
 CVE202510120CVEDetailsCVETodo
</blockquote>
<blockquote>
CVE-2025-10120 is a critical remote code execution vulnerability affecting Tenda AC20 routers, specifically versions up to 16.03.08.12. The core issue lies in the improper handling of user-supplied input within the /goform/GetParentControlInfo endpoint, where the strcpy function is used unsafely.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote Code Execution
`2025-09-17`

* https://www.redpacketsecurity.com/cve-alert-cve-2025-9791-tenda-ac20/

<blockquote>
 CVEAlertCVE20259791TendaAC20RedPacketSecurity
</blockquote>
<blockquote>
High risk of remote code execution on affected Tenda AC20 devices due to a stack-based overflow, with a publicly available exploit increasing likelihood; prioritise if the device is network-reachable.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote Code Execution
`2025-09-17`

* https://www.cve.news/cve-2024-50852/

<blockquote>
 CVE202450852RemoteCommandInjectioninTendaG3v3Routers
</blockquote>
<blockquote>
A recent vulnerability, CVE-2024-50852, impacts the Tenda G3 v3. router (version v15.11..20) and demonstrates just how critical security hygiene is for home and business networks. What is CVE-2024-50852? This vulnerability was discovered in the formSetUSBPartitionUmount function of the router's web management interface.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote Code Execution
`2025-09-17`

* https://cvefeed.io/vuln/detail/CVE-2024-46628

<blockquote>
 CVE202446628TendaG3RouterRemoteCodeExecutionVulnerability
</blockquote>
<blockquote>
Tenda G3 Router firmware v15.03.05.05 was discovered to contain a remote code execution (RCE) vulnerability via the usbPartitionName parameter in the formSetUSBPartitionUmount function.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote Code Execution
`2025-09-17`

* https://medium.com/@frostbyte1122/analysis-of-traffic-and-payload-extracted-froby-tenda-router-honeypot-5bd9867176e6

<blockquote>
 AnalysisoftrafficandpayloadextractedfromTendaRouterMedium
</blockquote>
<blockquote>
We then analysed the attempts to exploit remote code execution to force the download from an IP controlled by attacker using installed binaries like wget or curl commands.
</blockquote>

---

## DuckDuckgo search -> Tenda poc Remote Code Execution
`2025-09-17`

* https://securityvulnerability.io/vulnerability/CVE-2025-9443

<blockquote>
 BufferOverflowVulnerabilityinTendaCH22byTenda
</blockquote>
<blockquote>
A buffer overflow vulnerability exists in the Tenda CH22 router, specifically in the editUserName function found in the /goform/editUserName file. This flaw allows an attacker to manipulate the 'new_account' argument, potentially leading to unauthorized remote code execution.
</blockquote>

---

