## DuckDuckgo search -> SMB use after free vulnerability
`2025-09-17`

* https://www.techmonitor.ai/technology/cybersecurity/openai-o3-model-linux-security-threat

<blockquote>
 OpenAIso3modelhelpsidentifysignificantLinuxsecuritythreat
</blockquote>
<blockquote>
This vulnerability was brought to light by cybersecurity researcher Sean Heelan, who leveraged the capabilities of OpenAI's o3 model. Officially confirmed on 20 May 2025, the vulnerability reveals a use-after-free issue in the SMB 'logoff' command handler, posing significant security risks.
</blockquote>

---

## DuckDuckgo search -> SMB use after free vulnerability
`2025-09-17`

* https://linuxsecurity.com/news/security-vulnerabilities/remote-zero-day-linux-kernel-flaw-discovered-using-ai

<blockquote>
 RemoteZerodayLinuxKernelFlawDiscoveredUsingAI
</blockquote>
<blockquote>
At the heart of CVE-2025-37899 is a use-after-free (UAF) flaw—a well-known category of memory safety issues with devastating potential. The bug resides in the ksmbd module, the kernel-space implementation of the SMB protocol introduced in modern Linux distributions to handle SMB3 communications more efficiently than user-space counterparts like Samba. Specifically, the flaw emerges in the ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free Protocol
`2025-09-17`

* https://learn.microsoft.com/en-us/windows-server/storage/file-server/troubleshoot/smbv1-not-installed-by-default-in-windows

<blockquote>
 SMBv1notinstalledbydefaultinWindowsServerandWindows
</blockquote>
<blockquote>
The Server Message Block version 1 (SMBv1) protocol is deprecated and no longer installed by default in modern versions of Windows and Windows Server. This article provides an overview of SMBv1's removal, its behavior in various Windows editions, and alternatives for legacy compatibility.
</blockquote>

---

## DuckDuckgo search -> SMB use after free Protocol
`2025-09-17`

* https://www.action1.com/patch-tuesday/patch-tuesday-september-2025/

<blockquote>
 PatchTuesdaySeptember2025Action1
</blockquote>
<blockquote>
The first zero-day vulnerability, CVE-2025-55234, is a serious flaw in the Windows Server Message Block (SMB) protocol related to authentication relay attacks. It arises from improper authentication (CWE-287), allowing attackers to intercept and relay legitimate credentials between services.
</blockquote>

---

## DuckDuckgo search -> SMB use after free Protocol
`2025-09-17`

* https://hoploninfosec.com/ksmbd-use-after-free-exploit-technique/

<blockquote>
 CVE202537899ksmbduseafterfreeexploittechnique
</blockquote>
<blockquote>
Those updates remain the central defensive action against the CVE-2025-378997899 ksmbd use-after-free exploit technique. Detection signals and forensic clues to hunt for Know what to look for. Kernel oops messages, unusual log messages from the ksmbd service, and repeated crashes tied to SMB session events are all red flags.
</blockquote>

---

## DuckDuckgo search -> SMB use after free Protocol
`2025-09-17`

* https://windowsforum.com/threads/cve-2025-54101-remediation-for-windows-smbv3-client-use-after-free-rce.380225/

<blockquote>
 CVE202554101RemediationforWindowsSMBv3ClientUseAfterFreeRCE
</blockquote>
<blockquote>
Background SMB (Server Message Block) is a decades‑old protocol used for file, printer, and IPC services on Windows networks. Its ubiquity — present on endpoints, servers, appliances, and many third‑party products — makes any remotely exploitable SMB flaw inherently high‑risk.
</blockquote>

---

## DuckDuckgo search -> SMB use after free Protocol
`2025-09-17`

* https://www.bodhost.com/kb/steps-to-enable-and-disable-smbv1-smbv2-and-smbv3-in-windows-servers/

<blockquote>
 EnableorDisableSMBv1SMBv2SMBv3onWindowsServersbodHOST
</blockquote>
<blockquote>
The following post shows detailed steps to enable and disable the Server Message Block (SMB) versions SMBv1, SMBv2 &amp; SMBv3 on the SMB server and SMB client. The SMBv2 protocol was introduced in Windows Vista &amp; Windows Server 2008 and the SMBv3 was introduced in Windows 8 and Windows Server 2012.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://www.bleepingcomputer.com/news/microsoft/microsoft-says-windows-september-updates-break-smbv1-shares/

<blockquote>
 MicrosoftsaysWindowsSeptemberupdatesbreakSMBv1shares
</blockquote>
<blockquote>
Microsoft has confirmed that the September 2025 Windows security updates are causing connection issues to Server Message Block (SMB) v1 shares.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://lkml.org/lkml/2025/4/18/943

<blockquote>
 LKMLSteveFrenchGITPULLksmbdserverfixes
</blockquote>
<blockquote>
Denis Arefev (1): ksmbd: Prevent integer overflow in calculation of deadtime Namjae Jeon (4): ksmbd: fix WARNING &quot;do not call blocking ops when !TASK_RUNNING&quot; ksmbd: fix use-after-free in __smb2_lease_break_noti() ksmbd: fix use-after-free in smb_break_all_levII_oplock() ksmbd: fix the warning from __kernel_write_iter Sean Heelan (1):
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-smb2/d64e0451-64a2-425a-848e-52a7dddab7b9

<blockquote>
 MSSMB2HandlingSMB20INFOFILEMicrosoftLearn
</blockquote>
<blockquote>
If the underlying object store returns only a portion of the variable-length data, the server MUST construct a response as described below but set the Status field in the SMB2 header to STATUS_BUFFER_OVERFLOW.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://www.tenable.com/plugins/nessus/238080

<blockquote>
 KB5060531Windows10version1809WindowsServer2019SecurTenable
</blockquote>
<blockquote>
It is, therefore, affected by multiple vulnerabilities - Heap-based buffer overflow in Windows Routing and Remote Access Service (RRAS) allows an unauthorized attacker to execute code over a network. (CVE-2025-33066) - Improper access control in Windows SMB allows an authorized attacker to elevate privileges over a network. (CVE-2025-33073)
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://lkml.org/lkml/2025/5/17/411

<blockquote>
 RePATCHV202smbclientFixuseafterfreeinreaddir
</blockquote>
<blockquote>
&gt; &gt; &gt; &gt; This patch series addresses a use-after-free vulnerability in the SMB/CIFS &gt; &gt; client readdir implementation that can be triggered during concurrent &gt; &gt; directory reads when a signal interrupts directory enumeration. &gt; &gt; &gt; &gt; The root cause is in the operation sequence in find_cifs_entry(): &gt; &gt; 1.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://marc.info/?l=linux-cifs&m=175448979225906

<blockquote>
 RePATCHnextsmbclientFixuseafterfreeinsenddoneMARC
</blockquote>
<blockquote>
Don't free the request &gt; &gt; &gt; until after smbd_disconnect_rdma_connection () to avoid a use after free &gt; &gt; &gt; bug. &gt; &gt; &gt; &gt; &gt; &gt; Fixes: 5e65668c75c0 (&quot;smb: client: let send_done () cleanup before calling \ &gt; &gt; &gt; smbd_disconnect_rdma_connection ()&quot;) &gt; &gt; &gt; Signed-off-by: Dan Carpenter &lt;dan.carpenter@linaro.org&gt; &gt; &gt; &gt; --- &gt; &gt; &gt; fs/smb/client/smbdirect ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://PDF

<blockquote>
 PDFEternalBlueExploitDepartmentofComputerScienceUniversityofToronto
</blockquote>
<blockquote>
EternalBlue is best known for it's use in 2017's WannaCry, a ransomware which would encrypt a victim's files and ask for a ransom for the files to be decrypted. Using the TCP through port 45 it would spread to other computers, sending malformed data which would be handled by the SMB protocol, wherein the exploit can be found.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://www.cvedetails.com/cve/CVE-2025-54101/

<blockquote>
 CVE202554101UseafterfreeinWindowsSMBv3Clientallowsan
</blockquote>
<blockquote>
CVE-2025-54101 : Use after free in Windows SMBv3 Client allows an authorized attacker to execute code over a network.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://feedly.com/cve/CVE-2025-54101

<blockquote>
 CVE202554101ExploitsSeverityFeedly
</blockquote>
<blockquote>
CVE-2025-54101 is an RCE vulnerability caused by a use-after-free in Windows SMB v3 Client/Server that allows an authorized attacker to execute code over a network. CVE-2025-54916 is an RCE vulnerability caused by a stack-buffer overflow in Windows NTFS that allows an authorized attacker to execute code over the network.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://cvefeed.io/vuln/detail/CVE-2025-54101

<blockquote>
 CVE202554101WindowsSMBClientRemoteCodeExecutionVulnerability
</blockquote>
<blockquote>
Use after free in Windows SMBv3 Client allows an authorized attacker to execute code over a network.
</blockquote>

---

## DuckDuckgo search -> SMB use after free overflow
`2025-09-17`

* https://vuldb.com/?id.323264

<blockquote>
 CVE202554101MicrosoftWindowsSMBClientuseafterfree
</blockquote>
<blockquote>
Details info A vulnerability, which was classified as problematic, has been found in Microsoft Windows. Affected by this issue is an unknown code of the component SMB Client. The manipulation with an unknown input leads to a use after free vulnerability. Using CWE to declare the problem leads to CWE-416. Referencing memory after it has been freed can cause a program to crash, use unexpected ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://securityvulnerability.io/vulnerability/CVE-2023-32256

<blockquote>
 UseAfterFreeFlawinLinuxKernelsksmbdComponentAffects
</blockquote>
<blockquote>
What is CVE-2023-32256? A vulnerability has been identified in the ksmbd component of the Linux kernel, where a race condition occurs between the SMB2 close operation and logoff actions in multichannel connections. This flaw may create conditions that lead to a use-after-free issue, potentially allowing attackers to execute arbitrary code or cause system disruptions. It is crucial for users ...
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://vulert.com/vuln-db/debian-11-linux-196580

<blockquote>
 UseAfterFreeVulnerabilityinLinuxKernelsSMBClientCVE202538488
</blockquote>
<blockquote>
Learn about CVE-2025-38488, a use-after-free vulnerability in the Linux kernel's SMB client, its impact, and how to fix it.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://lists.samba.org/archive/samba-technical/2024-November/139211.html

<blockquote>
 PATCHv2smbclientFixuseafterfreeofnetworknamespace
</blockquote>
<blockquote>
The problem rarely happened, but &gt; it was always while the pod was dying. &gt; &gt; The root cause is wrong reference counting for network namespace. Saw your similar fix in the NFS client, thanks for attending to the SMB client as well. Question below... &gt; CIFS uses kernel sockets, which do not hold refcnt of the netns that &gt; the socket belongs to.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://cvefeed.io/vuln/detail/CVE-2024-53179

<blockquote>
 CVE202453179LinuxSMBClientUseAfterFreeVulnerability
</blockquote>
<blockquote>
CVE-2024-53179 has a 4 public PoC/Exploit available at Github. Go to the Public Exploits tab to see the list.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://cpanel.ogma.in/understanding-cve-2024-53186-addressing-use-after-free-in-linux-kernel-smb-request-handling

<blockquote>
 UnderstandingCVE202453186AddressingUseAfterFreeinLinuxKernel
</blockquote>
<blockquote>
Explore CVE-2024-53186, a Linux Kernel vulnerability, and learn how to mitigate use-after-free issues in SMB request handling for improved security.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://windowsforum.com/threads/cve-2025-54101-remediation-for-windows-smbv3-client-use-after-free-rce.380225/

<blockquote>
 CVE202554101RemediationforWindowsSMBv3ClientUseAfterFreeRCE
</blockquote>
<blockquote>
Vulnerability: Use‑after‑free in the Windows SMBv3 Client. Impact: Remote code execution — an attacker could execute code over a network. Attack model: Network‑accessible; exploitation typically involves a crafted SMB response from a malicious or attacker‑controlled SMB server provoked by a client‑initiated connection.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://vulert.com/vuln-db/debian-11-linux-179391

<blockquote>
 UseAfterFreeVulnerabilityinLinuxKernelSMBPackage
</blockquote>
<blockquote>
It includes various subsystems, one of which is the SMB (Server Message Block) protocol, used for sharing files and printers over a network. The vulnerability in question arises from a flaw in the open_cached_dir function, which can lead to a use-after-free condition, potentially compromising system stability and security.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://ogma.in/cve-2024-53095-resolving-use-after-free-vulnerability-in-linux-kernel-smb-client

<blockquote>
 CVE202453095ResolvingUseAfterFreeVulnerabilityinogmain
</blockquote>
<blockquote>
Learn about CVE-2024-53095, a critical use-after-free vulnerability in the Linux Kernel SMB client, and discover effective mitigation strategies.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://nvd.nist.gov/vuln/detail/CVE-2025-37899

<blockquote>
 NvdCve202537899
</blockquote>
<blockquote>
Information Technology Laboratory National Vulnerability DatabaseVulnerabilities
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://hoploninfosec.com/ksmbd-use-after-free-exploit-technique/

<blockquote>
 CVE202537899ksmbduseafterfreeexploittechnique
</blockquote>
<blockquote>
CVE-2025-37899 ksmbd use-after-free exploit technique explained. Learn risk, impact, mitigation, and how to protect Linux servers now.
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://cvefeed.io/vuln/detail/CVE-2023-52752

<blockquote>
 CVE202352752LinuxCIFSSMBUseAfterFreeVulnerability
</blockquote>
<blockquote>
In the Linux kernel, the following vulnerability has been resolved: smb: client: fix use-after-free bug in cifs_debug_data_proc_show() Skip SMB sessions that are being teared down (e.g. @ses-&gt;ses_status &#61;&#61; SES_EXITING) in cifs_debug_data_proc_show() to avoid use-after-free in @ses. This fixes the following GPF when reading from /proc/fs/cifs/DebugData while mounting and umounting [ …
</blockquote>

---

## DuckDuckgo search -> SMB use after free
`2025-09-17`

* https://www.cve.news/cve-2023-52752/

<blockquote>
 CVE202352752UseAfterFreeinLinuxSMBClientDebugInterface
</blockquote>
<blockquote>
CVE-2023-52752 is a classic example of a race condition in kernel debug code, resulting in a use-after-free scenario. Any user on a system could easily crash the machine.
</blockquote>

---

