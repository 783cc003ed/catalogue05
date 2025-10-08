## DuckDuckgo search -> SMB CVE overflow
`2025-07-07`

* https://www.mcafee.com/blogs/other-blogs/mcafee-labs/smbghost-analysis-of-cve-2020-0796/

<blockquote>
 SMBGhostAnalysisofCVE20200796McAfeeBlog
</blockquote>
<blockquote>
The flaw is present in the SMB Compression Transform Header, prior to any kind of authentication. We can see the very large OriginalSize used for attacker-controlled data (4294967295 is 0xFFFFFFFF in hex which is also -1 if viewed as a signed long). This is copied into a smaller fixed buffer and results in a classic buffer overflow.
</blockquote>

---

## DuckDuckgo search -> SMB CVE overflow
`2025-07-04`

* https://securityvulnerability.io/vulnerability/CVE-2025-32718

<blockquote>
 CVE202532718IntegerOverflowVulnerabilityinWindowsSMBAffects
</blockquote>
<blockquote>
What is CVE-2025-32718? A vulnerability exists in Windows SMB that can be exploited through integer overflow or wraparound conditions, enabling an authorized attacker to gain elevated privileges locally. This flaw could allow the attacker to execute arbitrary code with elevated rights, potentially compromising system integrity and data confidentiality. Regular updates and security practices ...
</blockquote>

---

