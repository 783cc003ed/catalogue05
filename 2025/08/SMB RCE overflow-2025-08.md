## DuckDuckgo search -> SMB RCE overflow
`2025-08-22`

* https://techienotes.blog/2023/10/20/cve-2020-0796-smbghost-rce-vulnerability/

<blockquote>
 CVE20200796SMBGhostRCEVulnerabilityJustSomeTechieNotes
</blockquote>
<blockquote>
Description and Impact Also known as CoronaBlue, EternalDarkness and SMBleedingGhost, this critical buffer-overflow pre-authentication RCE vulnerability affects Microsoft SMB version 3.1.1 that have SMBv3 Compression enabled. It occurs when the server attempts to decompress a data packet with malformed header, causing a memory buffer overflow. That overflow can cause memory corruption ...
</blockquote>

---

