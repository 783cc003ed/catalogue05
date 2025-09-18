## DuckDuckgo search -> SMB overflow
`2025-08-21`

* https://stackoverflow.com/questions/78238441/cause-of-excessive-smb2-find-requests-when-writing-files-to-a-windows-server

<blockquote>
 CauseofExcessiveSMB2FINDRequestsWhenWritingStackOverflow
</blockquote>
<blockquote>
The problem turned out to be that when we created new files on the server, we created them with a temporary filename, then validated them before renaming the file to its permanent name. It was this renaming that was causing the excessive SMB2_FIND_ID_BOTH_DIRECTORY_INFO pattern: * messages, and when we stopped renaming the file, the messages ceased.
</blockquote>

---

## DuckDuckgo search -> SMB overflow
`2025-08-21`

* https://stackoverflow.com/questions/78238441/cause-of-excessive-smb2-find-requests-when-writing-files-to-a-windows-server

<blockquote>
 CauseofExcessiveSMB2FINDRequestsWhenWritingStackOverflow
</blockquote>
<blockquote>
The problem turned out to be that when we created new files on the server, we created them with a temporary filename, then validated them before renaming the file to its permanent name. It was this renaming that was causing the excessive SMB2_FIND_ID_BOTH_DIRECTORY_INFO pattern: * messages, and when we stopped renaming the file, the messages ceased.
</blockquote>

---

