## DuckDuckgo search -> SMB use after free
`2025-07-08`

* https://lkml.iu.edu/2507.0/08526.html

<blockquote>
 PATCHV2smbclientfixuseafterfreeincifsoplockbreak
</blockquote>
<blockquote>
inodes under RCU. However, cifs_oplock_break () continues to access the cinode after this point, resulting in use-after-free.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-07-08`

* https://cyberalerts.io/vulnerability/CVE-2024-53095

<blockquote>
 CVE202453095smbclientFixuseafterfreeofnetworknamespace
</blockquote>
<blockquote>
In the Linux kernel, the following vulnerability has been resolved: smb: client: Fix use-after-free of network namespace. Recently, we got a customer report that CIFS triggers oops while reconnecting to a server. [0] The workload runs on Kubernetes, and some pods mount CIFS servers in non-root network namespaces. The problem rarely happened, but it was always while the pod was dying. The root ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-07-07`

* https://lkml.org/lkml/2025/7/7/31

<blockquote>
 LKMLWangZhaolongPATCHV2smbclientfixuseafterfreeincifs
</blockquote>
<blockquote>
A race condition can occur in cifs_oplock_break() leading to a use-after-free of the cinode structure when unmounting: cifs_oplock_break() _cifsFileInfo_put(cfile) cifsFileInfo_put_final() cifs_sb_deactive() [last ref, start releasing sb] kill_sb() kill_anon_super() generic_shutdown_super() evict_inodes() dispose_list() evict() destroy_inode() call_rcu(&amp;inode-&gt;i_rcu, i_callback) spin_lock ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free Protocol
`2025-07-04`

* https://www.packetsafari.com/blog/2020/06/09/smbv1-vs-smbv2-vs-smbv3/

<blockquote>
 SMBv1vsSMBv2vsSMBv3UnderstandingtheDifferencesandSecuring
</blockquote>
<blockquote>
⚠️ Also checkout our article on how to identify legacy SMBv1 traffic using advanced filters ⚠️ SMB (Server Message Block) is a critical network protocol that enables file and printer sharing services on Windows networks. Over the years, SMB has evolved through three major versions - SMBv1, SMBv2, and SMBv3 - each bringing significant improvements in performance, scalability, and ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-07-04`

* https://cybersecuritynews.com/linux-6-16-rc4/

<blockquote>
 Linux616rc4ReleasedWithFixesforFilesystemDriverHardware
</blockquote>
<blockquote>
4. Fixed overflow vulnerabilities, memory issues, and use-after-free conditions across kernel subsystems. With contributions from 157 developers, this release demonstrates the collaborative nature of Linux kernel development and includes significant fixes for bcachefs, device drivers, and various hardware platforms.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-07-04`

* https://curl.se/docs/CVE-2022-43552.html

<blockquote>
 curlHTTPProxydenyuseafterfreeCVE202243552
</blockquote>
<blockquote>
The SMB part was introduced in 2014. The Common Vulnerabilities and Exposures (CVE) project has assigned the name CVE-2022-43552 to this issue. CWE-416: Use After Free Severity: Low AFFECTED VERSIONS Affected versions: curl 7.16.0 to and including 7.86.0 Not affected versions: curl &lt; 7.16.0 and curl &gt;&#61; 7.87.0
</blockquote>

---

## DuckDuckgo search -> SMB use after free vulnerability
`2025-07-04`

* https://linuxiac.com/chatgpt-o3-model-found-remote-zeroday-in-linux-kernel-code/

<blockquote>
 ChatGPTso3ModelFoundRemoteZerodayinLinuxKernelCode
</blockquote>
<blockquote>
The vulnerability occurs because one thread frees an object while another thread may still access it without proper synchronization, leading to use-after-free conditions that could allow kernel memory corruption and arbitrary code execution. Before this breakthrough, Heelan used another vulnerability, CVE-2025-37778, as a benchmark.
</blockquote>

---

## DuckDuckgo search -> SMB use after free vulnerability
`2025-07-04`

* https://www.cve.news/cve-2025-37899/

<blockquote>
 CVE202537899DeepDiveIntoAksmbdUseAfterFreeVulnerability
</blockquote>
<blockquote>
What is &quot;ksmbd&quot;? ksmbd is a relatively new kernel-level SMB (Server Message Block) server for Linux. SMB allows file sharing across the local network and is widely used in enterprises—think Windows File Sharing. Since ksmbd runs in kernel-space, vulnerabilities here can be especially severe.
</blockquote>

---

## DuckDuckgo search -> SMB use after free vulnerability
`2025-07-04`

* https://dailycve.com/linux-kernel-use-after-free-vulnerability-cve-2025-22041-critical/

<blockquote>
 LinuxKernelUseAfterFreeVulnerabilityCVE202522041Critical
</blockquote>
<blockquote>
This vulnerability occurs in the ksmbd (kernel SMB server) component of Linux kernel when operating in multichannel mode. The use-after-free bug triggers when a second channel establishes a session through the first channel's connection.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-07-04`

* https://answers.microsoft.com/en-us/feedback/forum/all/remediation-for-171859-use-after-free-787-cve-2022/d52854d8-19df-4ded-9e54-8706e342ac22

<blockquote>
 Remediationfor171859UseAfterFree787CVE202243552
</blockquote>
<blockquote>
Remediation for 171859 - Use-After-Free &lt; 7.87 (CVE-2022-43552) Hi Everyone, Nessus scanner found a vulnerability with Curl on Windows Server 2019 uses version 7.83.1.0 which is vulnerable. Below is the vulnerability details: ... Can you please suggest the remediation process to fix it. Thanks In advance.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-07-03`

* https://vuldb.com/?id.306897

<blockquote>
 CVE202537750LinuxKernelsmbuseafterfreevuldbcom
</blockquote>
<blockquote>
In the Linux kernel, the following vulnerability has been resolved: smb: client: fix UAF in decryption with multichannel After commit f7025d861694 (&quot;smb: client: allocate crypto only for primary server&quot;) and commit b0abcd65ec54 (&quot;smb: client: fix UAF in async decryption&quot;), the channels started reusing AEAD TFM from primary channel to perform ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-07-01`

* https://learn.microsoft.com/en-us/windows-server/storage/file-server/troubleshoot/troubleshooting-smb

<blockquote>
 AdvancedTroubleshootingServerMessageBlockSMB
</blockquote>
<blockquote>
The SMB Client (CLI) refers to the system that is trying to access the file system, regardless of the OS version or edition. For example, if you use Windows Server 2016 to reach an SMB share that is hosted on Windows 10, Windows Server 2016 is the SMB Client and Windows 10 the SMB Server.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-07-01`

* https://www.cve.news/cve-2023-52752/

<blockquote>
 CVE202352752LinuxKernelSMBClientUseAfterFreeVulnerabilityFixed
</blockquote>
<blockquote>
A vulnerability found in the Linux kernel has been addressed, which resolves a use-after-free bug pertaining to the SMB client. This post contains details about the vulnerability, the code snippet illustrating the fix, and links to the original references.
</blockquote>

---

