## DuckDuckgo search -> SMB double free overflow
`2025-07-04`

* https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-smb2/a9d1d0f9-0614-49f9-bf2e-021ce5cfcb2e

<blockquote>
 MSSMB2HandlingaDFSReferralInformationRequest
</blockquote>
<blockquote>
When the server receives a request with an SMB2 header with a Command value equal to SMB2 IOCTL, and a CtlCode of FSCTL_DFS_GET_REFERRALS or FSCTL_DFS_GET_REFERRALS_EX, message handling proceeds as follows: If IsDfsCapable is set to FALSE, the server MUST return STATUS_FS_DRIVER_REQUIRED to the client. The server MUST invoke the event as specified in [MS-DFSC] section 3.2.4.2 and pass the ...
</blockquote>

---

## DuckDuckgo search -> SMB double free overflow
`2025-07-04`

* https://wiki.wireshark.org/SMB2

<blockquote>
 SMB2WiresharkWiki
</blockquote>
<blockquote>
SMB2 Server Message Block version 2 and 3 SMB2 is a new version of the old Windows filesharing protocol SMB and is used for filesharing on modern and future Windows hosts. Windows 8 introduced several new features, so Microsoft has decided to bump the revision number up to SMB v3.
</blockquote>

---

