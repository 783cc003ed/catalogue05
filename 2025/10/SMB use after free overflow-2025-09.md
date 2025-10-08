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

