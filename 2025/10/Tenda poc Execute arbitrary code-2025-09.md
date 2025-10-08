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

