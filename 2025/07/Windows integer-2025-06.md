## DuckDuckgo search -> Windows integer Protocol
`2025-06-30`

* https://learn.microsoft.com/en-us/windows/win32/api/winnt/

<blockquote>
 WinnthheaderWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The LARGE_INTEGER structure represents a 64-bit signed integer value. (LARGE_INTEGER union (winnt.h)) LDT_ENTRY Describes an entry in the descriptor table. This structure is valid only on x86-based systems. LUID Describes a local identifier for an adapter. (LUID) LUID_AND_ATTRIBUTES Represents a locally unique identifier (LUID) and its attributes.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://opentechtips.com/integer8/

<blockquote>
 WindowsTimestampConverterOnlineandinPowerShellInteger8
</blockquote>
<blockquote>
The Windows Time Stamp Format - aka Integer8 Microsoft Windows environments use the Integer8 timestamp format. A 64-bit value representing the number of 100-nanoseconds elapsed since January 1, 1601 (UTC).
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://devblogs.microsoft.com/oldnewthing/20080325-00/?p=23013

<blockquote>
 WhatsthedifferencebetweenintandINTlongandLONGetc
</blockquote>
<blockquote>
An int is always a 32-bit signed integer, as is a long. As a result, the distinction between language types and platform types is now pretty much academic, and the two can be used interchangeably. New Windows functions tend to be introduced with language types, leaving platform types behind only for compatibility.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://win32.pub/docs/guides-concepts/integer-types

<blockquote>
 IntegerTypeswin32
</blockquote>
<blockquote>
Integer Types Unlike Dart, which has a single integer type for storing values between -263-1 and 263, the Win32 API utilizes various integer types in both signed and unsigned forms. The following table lists the common integer types encountered when working with Win32 APIs:
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://learn.microsoft.com/en-us/windows/win32/winprog/windows-data-types

<blockquote>
 WindowsDataTypesBaseTsdhWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The data types supported by Windows are used to define function return values, function and message parameters, and structure members. They define the size and meaning of these elements. For more information about the underlying C/C++ data types, see Data Type Ranges. The following table contains the following types: character, integer, Boolean, pointer, and handle. The character, integer, and ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://stackoverflow.com/questions/384502/what-is-the-bit-size-of-long-on-64-bit-windows

<blockquote>
 Whatisthebitsizeoflongon64bitWindowsStackOverflow
</blockquote>
<blockquote>
There is an intptr_t type - a signed integer type for holding pointers; you should plan on not using it, or only using it as the result of a subtraction of two uintptr_t values (ptrdiff_t). But, as the question points out (in disbelief), there are different systems for the sizes of the integer data types on 64-bit machines.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://learn.microsoft.com/en-us/windows/win32/winprog/large-integers

<blockquote>
 LargeIntegersWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The large integer functions and structures originally provided support for 64-bit values on 32-bit Windows. Now, your C compiler may support 64-bit integers natively. For example, Microsoft Visual C++ supports the __int64 sized integer type. For more information, see the documentation included with your C compiler. For information on 64-bit integers on 64-bit Windows, see The New Data Types.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://learn.microsoft.com/en-us/windows/win32/api/winnt/ns-winnt-large_integer-r1

<blockquote>
 LARGEINTEGERWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The LARGE_INTEGER structure is actually a union. If your compiler has built-in support for 64-bit integers, use the QuadPart member to store the 64-bit integer.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://en.cppreference.com/w/cpp/language/types.html

<blockquote>
 Fundamentaltypescppreferencecom
</blockquote>
<blockquote>
It has the same size, signedness, and alignment as one of the integer types, but is a distinct type. In practice, it is 32 bits and holds UTF-32 on Linux and many other non-Windows systems, but 16 bits and holds UTF-16 code units on Windows. The standard used to require wchar_t to be large enough to represent any supported character code point.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-30`

* https://learn.microsoft.com/en-us/windows/win32/winrt/base-data-types

<blockquote>
 WindowsRuntimebasedatatypesWin32appsMicrosoftLearn
</blockquote>
<blockquote>
This table lists the base data types that are supported by the Windows Runtime, and indicates the corresponding type in C\&#35;, Visual Basic, and C++.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-27`

* https://en.wikibooks.org/wiki/Windows_Programming/Handles_and_Data_Types

<blockquote>
 WindowsProgrammingHandlesandDataTypesWikibooks
</blockquote>
<blockquote>
Windows, buttons, icons, mouse pointers, menus, and so on, all get an entry in the table, and each entry is assigned a unique address known as a HANDLE. If you want to pick a particular entry out of that table, you need to give Windows the HANDLE value, and Windows will return the corresponding table entry.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-27`

* https://learn.microsoft.com/en-us/windows-hardware/drivers/kernel/avoiding-misalignment-of-fixed-precision-data-types

<blockquote>
 AvoidingMisalignmentofFixedPrecisionDataTypesWindowsdrivers
</blockquote>
<blockquote>
For example, __int64, LARGE_INTEGER, and KFLOATING_SAVE must be aligned on a 4-byte boundary on x86 platforms. However, on Itanium-based machines, they must be aligned on an 8-byte boundary. To determine the alignment requirement for a given data type on a particular platform, use the TYPE_ALIGNMENT macro on that platform.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-27`

* https://stackoverflow.com/questions/1395361/manipulating-large-integers

<blockquote>
 cmanipulatingLARGEINTEGERSStackOverflow
</blockquote>
<blockquote>
The LARGE_INTEGER structure is actually a union. If your compiler has built-in support for 64-bit integers, use the QuadPart member to store the 64-bit integer. Otherwise, use the LowPart and HighPart members to store the 64-bit integer. So if your compiler supports 64 bit integers use quadPart like this :
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-27`

* https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-dtyp/e904b1ba-f774-4203-ba1b-66485165ab1a

<blockquote>
 MSDTYPLARGEINTEGERMicrosoftLearn
</blockquote>
<blockquote>
The LARGE_INTEGER structure is used to represent a 64-bit signed integer value. typedef struct _LARGE_INTEGER {Skip to main content Skip to Ask Learn chat experience This browser is no longer supported. Upgrade to Microsoft Edge to take advantage of the latest features, security updates, and technical support. Download ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-27`

* https://learn.microsoft.com/en-us/cpp/cpp/integer-limits?view=msvc-170

<blockquote>
 IntegerLimitsMicrosoftLearn
</blockquote>
<blockquote>
The limits for integer types are listed in the following table. Preprocessor macros for these limits are also defined when you include the standard header file &lt;climits&gt;. Limits on Integer Constants. Constant Meaning Value; CHAR_BIT: Number of bits in the smallest variable that is not a bit field. 8:
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-26`

* https://stackoverflow.com/questions/5254330/reserve-a-tcp-port-in-windows

<blockquote>
 ReserveaTCPportinWindowsStackOverflow
</blockquote>
<blockquote>
The port number needn't be determined in advance. It's OK for the first process to acquire a random port number, and pass it to the requesting process. EDIT: It occurs to me that my question is somewhat poorly stated. What I really want is to separate the allocation of a dynamic port number from the bind-to-port-zero operation.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-26`

* https://learn.microsoft.com/en-us/powershell/module/nettcpip/get-netipv4protocol?view=windowsserver2025-ps

<blockquote>
 GetNetIPv4ProtocolNetTCPIPMicrosoftLearn
</blockquote>
<blockquote>
Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell. Skip to main content Skip to in-page navigation Skip to Ask Learn chat experience This browser is no longer supported. Upgrade to Microsoft Edge to take advantage of the latest features, security updates, and technical support. ...
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-26`

* https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers

<blockquote>
 ListofTCPandUDPportnumbersWikipedia
</blockquote>
<blockquote>
This is a list of TCP and UDP port numbers used by protocols for operation of network applications. The Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP) only need one port for bidirectional traffic. TCP usually uses port numbers that match the services of the corresponding UDP implementations, if they exist, and vice versa. The Internet Assigned Numbers Authority (IANA ...
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-26`

* https://PDF

<blockquote>
 PDFMSWPOWindowsProtocolsOverview
</blockquote>
<blockquote>
This document can also be used in conjunction with the Windows Protocols Documentation Roadmap [MS-DOCO], which describes the protocol documentation set, the types of protocol documents provided by Microsoft, and how to find the documents online. Detailed technical specifications for
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-26`

* https://github.com/advisories/GHSA-vf6f-gpmv-93m4

<blockquote>
 IntegeroverfloworwraparoundinWindowsFastFATDriverGitHub
</blockquote>
<blockquote>
This score calculates overall vulnerability severity from 0 to 10 and is based on the Common Vulnerability Scoring System (CVSS). Attack vector: More severe the more the remote (logically and physically) an attacker can be in order to exploit the vulnerability. Attack complexity: More severe for the ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-26`

* https://vuldb.com/?id.291780

<blockquote>
 MicrosoftWindowsuptoServer2025GDIintegeroverflow
</blockquote>
<blockquote>
A vulnerability classified as critical has been found in Microsoft Windows. Affected is some unknown processing of the component GDI+. The manipulation with an unknown input leads to a integer overflow vulnerability. CWE is classifying the issue as CWE-190.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-24`

* https://www.ibm.com/docs/el/ibm-mq/9.2.x?topic=platforms-standard-data-types-aix-linux-windows

<blockquote>
 StandarddatatypesonAIXLinuxandWindowsIBM
</blockquote>
<blockquote>
Table 3. Data type names and lengths for Windows 64-bit applications; Name Length; char: 1 byte: short: 2 bytes: int: 4 bytes: long: 4 bytes: float: 4 bytes: double ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-24`

* https://learn.microsoft.com/en-us/cpp/cpp/int8-int16-int32-int64?view=msvc-170

<blockquote>
 int8int16int32int64MicrosoftLearn
</blockquote>
<blockquote>
Microsoft-specific. Microsoft C/C++ features support for sized integer types. You can declare 8-, 16-, 32-, or 64-bit integer variables by using the __intN type specifier, where N is 8, 16, 32, or 64.. The following example declares one variable for each of these types of sized integers:
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-23`

* https://PDF

<blockquote>
 PDFLecture7SlidingWindowsUniversityofCaliforniaSanDiego
</blockquote>
<blockquote>
CSE$123:$Computer$Networks Geoff Voelker (guest$lecture) Lecture 7: Sliding Windows
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-23`

* https://learn.microsoft.com/en-us/windows/win32/secauthn/protocols-in-tls-ssl--schannel-ssp-

<blockquote>
 ProtocolsinTLSSSLSchannelSSPWin32apps
</blockquote>
<blockquote>
The following sections describe the support of TLS, DTLS, and SSL protocols in different Windows versions. TLS protocol version support. The following table displays the Microsoft Schannel Provider support of TLS protocol versions. Important.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-23`

* https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-dtyp/262627d8-3418-4627-9218-4ffe110850b2

<blockquote>
 MSDTYPDWORDMicrosoftLearn
</blockquote>
<blockquote>
A DWORD is a 32-bit unsigned integer (range: 0 through 4294967295 decimal). Because a DWORD is unsigned, its first bit (Most Significant Bit (MSB)) is not reserved for signing. This type is declared as follows: typedef unsigned long DWORD, *PDWORD, *LPDWORD; Additional resources In this article.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-23`

* https://PDF

<blockquote>
 PDFTheWindows10randomnumbergenerationinfrastructure
</blockquote>
<blockquote>
The Windows 10 random number generation infrastructure practice. (Very large machines tend to have very large memories, and they tend to run a few very large processes rather than thousands of smaller ones.) Reseeding the tree All PRNG states in Windows 10 are reseeded on a regular schedule. The root PRNG keeps a seed version.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-23`

* https://learn.microsoft.com/en-us/troubleshoot/windows-server/networking/install-configure-ip-version-6

<blockquote>
 InstallandconfigureIPversion6WindowsServer
</blockquote>
<blockquote>
delete route [prefix&#61;] ipv6address / integer [interface&#61;] string This command uses the following values: [prefix &#61;] ipv6address / **integer: Specifies the prefix for which to delete a route. Ipv6address is an IPv6 address and integer is the prefix length of the route to delete. [interface &#61;] string: Specifies the interface name.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-23`

* https://learn.microsoft.com/en-us/windows/win32/winsock/ipproto-tcp-socket-options

<blockquote>
 IPPROTOTCPsocketoptionsWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The following table describes IPPROTO_TCP socket options that apply to sockets created for the IPv4 and IPv6 address families (AF_INET and AF_INET6) with the protocol parameter to the socket function specified as TCP (IPPROTO_TCP). See the getsockopt and setsockopt function reference pages for more information on getting and setting socket options.. To enumerate protocols and discover ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-23`

* https://www.secwest.net/cansecwest2023-presentations/an-insiders-perspective-on-integer-overflow-vulnerabilities-challenges-and-solutions-from-identification-to-mitigation-at-microsoft

<blockquote>
 AnInsidersPerspectiveonIntegerOverflowVulnerabilities
</blockquote>
<blockquote>
Challenges and Solutions from Identification to Mitigation at Microsoft This talk will delve deep into one of the most prevalent memory safety issues on Windows: Integer Overflows. Over the past few years, MSRC has seen hundreds of Integer Overflow vulnerabilities, ranging from size overflows, integer truncations, overflows in checks, and reference counting overflows. We will cover the ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-23`

* https://undercodenews.com/urgent-cybersecurity-alert-microsoft-windows-fast-fat-vulnerability-cve-2025-24985/

<blockquote>
 UrgentCybersecurityAlertMicrosoftWindowsFastFATVulnerability
</blockquote>
<blockquote>
The CVE-2025-24985 vulnerability is rooted in a dangerous integer overflow issue within Microsoft's Fast FAT driver, a legacy component that manages the FAT and FAT32 file systems on Windows systems. The flaw enables attackers to execute arbitrary code on affected systems, but the catch is that physical access to the target machine is required.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-22`

* https://serverfault.com/questions/1045527/how-do-i-find-out-why-certain-ports-are-excluded-and-delete-the-exclusion

<blockquote>
 windowsHowdoIfindoutwhycertainportsareexcludedanddelete
</blockquote>
<blockquote>
PS C:\Windows\system32&gt; netsh int ipv4 delete excludedportrange protocol&#61;tcp 1414 1000 Element not found. How can I find out why those ports are excluded and &quot;un-exclude&quot; them? I have Windows 10 Home 2004.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-22`

* https://learn.microsoft.com/en-us/troubleshoot/windows-client/networking/tcpip-addressing-and-subnetting

<blockquote>
 TCPIPaddressingandsubnettingWindowsClient
</blockquote>
<blockquote>
This article is intended as a general introduction to the concepts of Internet Protocol (IP) networks and subnetting. A glossary is included at the end of article. Applies to: Supported versions of Windows Server and Windows Client Original KB number: 164015. Summary
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-22`

* https://learn.microsoft.com/en-us/cpp/cpp/data-type-ranges?view=msvc-170

<blockquote>
 DataTypeRangesMicrosoftLearn
</blockquote>
<blockquote>
A variable of __wchar_t designates either a wide-character type or multibyte-character type. Use the L prefix before a character or string constant to designate the wide-character-type constant.. signed and unsigned are modifiers that you can use with any integral type except bool.Note that char, signed char, and unsigned char are three distinct types for the purposes of mechanisms like ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-22`

* https://www.infosecinstitute.com/resources/secure-coding/what-is-is-integer-overflow-and-underflow/

<blockquote>
 UnderstandingExploitingIntegerOverflowVulnerabilitiesInfosec
</blockquote>
<blockquote>
What is an Integer Int, short for &quot;integer,&quot; is a variable type used to represent real numbers without fractional part. An integer on a 32 bit system is 32 bits long and it is 64 bits long on 64 bit systems. For example, the decimal value 2 on a 64 bit system is represented as follows in binary.
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-22`

* https://www.cvedetails.com/cve/CVE-2025-24985/

<blockquote>
 CVE202524985IntegeroverfloworwraparoundinWindowsFastFAT
</blockquote>
<blockquote>
CVE-2025-24985 : Integer overflow or wraparound in Windows Fast FAT Driver allows an unauthorized attacker to execute code locally.
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-22`

* https://fuzzysecurity.com/tutorials/expDev/18.html

<blockquote>
 FuzzySecurityWindowsExploitDevPart14
</blockquote>
<blockquote>
Part 14: Kernel Exploitation -&gt; Integer Overflow Hola, and welcome back to part 14 of the Windows exploit development tutorial series. Today we have another post on pwning @HackSysTeam's extreme vulnerable driver. This time we will take a look at the integer overflow; barring the GS stack overflow (we will cover this later) and the type confusion (too easy to cover but exploit on GitHub) this ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-22`

* https://learn.microsoft.com/en-us/windows-hardware/drivers/kernel/ntintsafe-design-guide

<blockquote>
 UsingSafeIntegerFunctionsWindowsdriversMicrosoftLearn
</blockquote>
<blockquote>
The ntintsafe library provides a set of C functions that perform safe integer arithmetic operations with bounds checking to prevent overflows and underflows in kernel-mode code.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://securityvulnerability.io/vulnerability/CVE-2025-24985

<blockquote>
 IntegerOverflowVulnerabilityinMicrosoftWindowsFastFATDriver
</blockquote>
<blockquote>
CVE-2025-24985 is a vulnerability in the Microsoft Windows Fast FAT Driver, a critical component responsible for managing file operations within the Windows operating system. This vulnerability involves an integer overflow, which permits an unauthorized attacker to execute code locally on affected systems.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-22`

* https://learn.microsoft.com/zh-cn/windows/win32/winprog/windows-data-types

<blockquote>
 Windows数据类型BaseTsdhWin32appsMicrosoftLearn
</blockquote>
<blockquote>
指向以 null 结尾的 8 位 Windows （ANSI） 字符字符串的指针。 有关详细信息，请参阅 字体使用的字符集。 此类型在 WinNT.h 中声明，如下所示： typedef CHAR *LPSTR; LPTSTR: 如果定义了 UNICODE ，则为 LPW STR;否则为 LPSTR。 有关详细信息，请参阅 字符串的 Windows 数据类型。
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-22`

* https://learn.microsoft.com/en-us/dotnet/api/system.net.securityprotocoltype?view=net-9.0

<blockquote>
 SecurityProtocolTypeEnumSystemNetMicrosoftLearn
</blockquote>
<blockquote>
The TLS 1.1 protocol is defined in IETF RFC 4346. On Windows systems, this value is supported starting with Windows 7. Tls12 3072: Specifies the Transport Layer Security (TLS) 1.2 security protocol. The TLS 1.2 protocol is defined in IETF RFC 5246. On Windows systems, this value is supported starting with Windows 7. Tls13 12288
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-22`

* https://learn.microsoft.com/en-us/troubleshoot/windows-client/printing/windows-11-rpc-connection-updates-for-print

<blockquote>
 Windows11RPCconnectionupdatesforprintWindowsClient
</blockquote>
<blockquote>
Windows 11, version 22H2 introduces changes to print components that modify how Windows machines communicate with each other during printing or print related operations. ... To set a dynamic/excluded port range, run the netsh int commands. To use IPSec with netsh, run the netsh ipsec commands. To use Windows Firewall to block a range of ports ...
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-22`

* https://en.wikipedia.org/wiki/List_of_IP_protocol_numbers

<blockquote>
 ListofIPprotocolnumbersWikipedia
</blockquote>
<blockquote>
This is a list of the IP protocol numbers found in the 8-bit Protocol field of the IPv4 header and the 8-bit Next Header field of the IPv6 header. It is an identifier for the encapsulated protocol and determines the layout of the data that immediately follows the header. ... Protocol Number Keyword Protocol References/RFC; 0x00 0 HOPOPT IPv6 ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-22`

* https://windowsforum.com/threads/critical-vulnerability-in-windows-fast-fat-driver-cve-2025-24985-explained.356271/

<blockquote>
 CriticalVulnerabilityinWindowsFastFATDriverCVE202524985
</blockquote>
<blockquote>
At its core, the vulnerability stems from an integer overflow or wraparound issue within the Windows Fast FAT File System Driver. In simpler terms, when the driver processes values—often related to file operations—a miscalculation occurs if the number exceeds the maximum value that can be stored.
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-22`

* https://www.cvedetails.com/cve/CVE-2025-24985/

<blockquote>
 CVE202524985IntegeroverfloworwraparoundinWindowsFastFAT
</blockquote>
<blockquote>
Integer overflow or wraparound in Windows Fast FAT Driver allows an unauthorized attacker to execute code locally. Published 2025-03-11 16:59:19 Updated 2025-05-29 16:31:56 Source Microsoft Corporation. View at NVD, CVE.org. Vulnerability category: Overflow Execute code.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://windowsforum.com/threads/cve-2025-29974-critical-windows-kernel-integer-underflow-vulnerability-explained.366060/

<blockquote>
 CVE202529974CriticalWindowsKernelIntegerUnderflowVulnerability
</blockquote>
<blockquote>
The sudden emergence of CVE-2025-29974—a critical Windows Kernel Information Disclosure Vulnerability—has triggered intense scrutiny among IT professionals, security researchers, and enterprise administrators alike. Characterized by an integer underflow (also known as wrap or wraparound), this security flaw enables adjacent network attackers to extract sensitive information from the ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://nvd.nist.gov/vuln/detail/CVE-2025-24985

<blockquote>
 NvdCve202524985
</blockquote>
<blockquote>
CVE-2025-24985 Detail Description Integer overflow or wraparound in Windows Fast FAT Driver allows an unauthorized attacker to execute code locally.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://securityvulnerability.io/vulnerability/CVE-2025-24985

<blockquote>
 CVE202524985IntegerOverflowVulnerabilityinMicrosoftWindows
</blockquote>
<blockquote>
Learn about the integer overflow vulnerability in Windows Fast FAT Driver and its potential impact on system security.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://cybersecuritynews.com/windows-11-integer-overflow-vulnerability/

<blockquote>
 NewWindows11IntegerOverflowVulnerabilityLetsAttackersElevate
</blockquote>
<blockquote>
A critical security flaw in Windows 11 has been discovered, allowing attackers to gain elevated system privileges through an integer overflow vulnerability.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://whiteknightlabs.com/2025/05/27/understanding-integer-overflow-in-windows-kernel-exploitation/

<blockquote>
 UnderstandingIntegerOverflowinWindowsKernelExploitation
</blockquote>
<blockquote>
In this blog post, we will explore integer overflows in Windows kernel drivers and cover how arithmetic operations can lead to security vulnerabilities. We will analyze real-world cases, build a custom vulnerable driver, and demonstrate how these flaws can impact memory allocations and system stability.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://www.cve.news/cve-2025-24985/

<blockquote>
 CVE202524985LeveragingIntegerOverflowinWindowsFastFATDriver
</blockquote>
<blockquote>
The Vulnerability: Integer Overflow or Wraparound CVE-2025-24985 is classified as an &quot;Integer overflow or wraparound&quot; issue. In programming, an integer overflow happens when an arithmetic operation tries to create a numeric value outside the range that can be represented with a given number of bits.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://windowsforum.com/threads/critical-vulnerability-in-windows-fast-fat-driver-cve-2025-24985-explained.356271/

<blockquote>
 CriticalVulnerabilityinWindowsFastFATDriverCVE202524985
</blockquote>
<blockquote>
In a recent advisory, a critical vulnerability (CVE-2025-24985) has been identified in the Windows Fast FAT File System Driver. The flaw, triggered by an integer overflow or wraparound condition, could enable an attacker to execute code by exploiting the vulnerable driver. Although the vulnerability description hints at remote code execution capabilities, the technical breakdown primarily ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-22`

* https://www.cvedetails.com/cve/CVE-2025-24985/

<blockquote>
 CVE202524985IntegeroverfloworwraparoundinWindowsFastFAT
</blockquote>
<blockquote>
Vulnerability Details : CVE-2025-24985 Integer overflow or wraparound in Windows Fast FAT Driver allows an unauthorized attacker to execute code locally.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-21`

* https://whiteknightlabs.com/2025/05/27/understanding-integer-overflow-in-windows-kernel-exploitation/

<blockquote>
 UnderstandingIntegerOverflowinWindowsKernelExploitation
</blockquote>
<blockquote>
In Windows, ULONG is a 32-bit unsigned integer, meaning it can hold values from 0x00000000 (0 in decimal) to 0xFFFFFFFF (4,294,967,295 in decimal). Since it cannot store negative values, any arithmetic operation that exceeds 0xFFFFFFFF causes an integer overflow, wrapping the value back to a much smaller number instead of continuing to increase ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-21`

* https://renenyffenegger.ch/notes/Windows/development/WinAPI/data-types/index

<blockquote>
 WinAPIdatatypesandconstantsRenéNyffenegger
</blockquote>
<blockquote>
C/C++: managed type : Notes (mainly in conjunction with P/Invoke): VOID: void: System.Void: Applied to a function that does not return a value. HANDLE: void * System.IntPtr or System.UIntPtr: 32 bits on 32-bit Windows operating systems, 64 bits on 64-bit Windows operating systems.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-21`

* https://PDF

<blockquote>
 PDFMSDOCOWindowsProtocolsDocumentationRoadmap
</blockquote>
<blockquote>
This document describes the Windows protocols documentation set and provides a roadmap for navigating it. This document set includes detailed technical specifications for Windows protocols and extensions to industry-standard or other published protocols. These protocols and extensions provide a wide variety of services to Windows Workgroup ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-21`

* https://windowsforum.com/threads/critical-vulnerability-in-windows-fast-fat-driver-cve-2025-24985-explained.356271/

<blockquote>
 CriticalVulnerabilityinWindowsFastFATDriverCVE202524985
</blockquote>
<blockquote>
In a recent advisory, a critical vulnerability (CVE-2025-24985) has been identified in the Windows Fast FAT File System Driver. The flaw, triggered by an integer overflow or wraparound condition, could enable an attacker to execute code by exploiting the vulnerable driver.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-21`

* https://learn.microsoft.com/en-us/cpp/cpp/data-type-ranges?view=msvc-170

<blockquote>
 DataTypeRangesMicrosoftLearn
</blockquote>
<blockquote>
The int and unsigned int types have a size of 4 bytes. However, portable code shouldn't depend on the size of int because the language standard allows this to be implementation-specific. C/C++ in Visual Studio also supports sized integer types. For more information, see __int8, __int16, __int32, __int64 and Integer Limits.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-21`

* https://learn.microsoft.com/en-us/windows/win32/api/winnt/ns-winnt-large_integer-r1

<blockquote>
 LARGEINTEGERWin32appsMicrosoftLearn
</blockquote>
<blockquote>
A signed 64-bit integer. Remarks. The LARGE_INTEGER structure is actually a union. If your compiler has built-in support for 64-bit integers, use the QuadPart member to store the 64-bit integer. Otherwise, use the LowPart and HighPart members to store the 64-bit integer. Requirements
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-20`

* https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-doco/20f47ec5-c33c-40a1-b7cb-1667501d2eee

<blockquote>
 MSDOCOWindowsProtocolsOverviewMicrosoftLearn
</blockquote>
<blockquote>
[MS-WPO]: Windows Protocols Overview provides a conceptual overview of Windows protocols, including their functionality, how they interact, and their relationships to Windows technologies. Each technology is further broken down into subsystems with information about the technology overviews (section 2.1.3) and technical specifications (section 2.2) that pertain to each subsystem.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-20`

* https://learn.microsoft.com/en-us/windows/win32/winprog/windows-data-types

<blockquote>
 WindowsDataTypesBaseTsdhWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The data types supported by Windows are used to define function return values, function and message parameters, and structure members. ... character, integer, Boolean, pointer, and handle. The character, integer, and Boolean types are common to most C compilers. Most of the pointer-type names begin with a prefix of P or LP. Handles refer to a ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-20`

* https://feedly.com/cve/CVE-2025-24985

<blockquote>
 CVE202524985ExploitsSeverityFeedly
</blockquote>
<blockquote>
Integer overflow vulnerability in the Windows Fast FAT Driver that can be exploited when users mount specially-crafted VHD files, enabling local code execution. Impact. An attacker can execute arbitrary code locally with user interaction, potentially leading to: - Complete system compromise - Malware installation - Data manipulation - Creation ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-20`

* https://nvd.nist.gov/vuln/detail/CVE-2025-24985

<blockquote>
 Cve202524985Nvd
</blockquote>
<blockquote>
Integer overflow or wraparound in Windows Fast FAT Driver allows an unauthorized attacker to execute code locally. Metrics ... Microsoft Windows Fast FAT File System Driver Integer Overflow Vulnerability: 03/11/2025: 04/01/2025: Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-20`

* https://www.cvedetails.com/cve/CVE-2025-24985/

<blockquote>
 CVE202524985IntegeroverfloworwraparoundinWindowsFastFAT
</blockquote>
<blockquote>
Microsoft Windows Fast FAT File System Driver Integer Overflow Vulnerability CISA required action: Apply mitigations per vendor instructions, follow applicable BOD 22-01 guidance for cloud services, or discontinue use of the product if mitigations are unavailable.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-20`

* https://stack.watch/vuln/CVE-2025-24985/

<blockquote>
 CVE202524985vulnerabilityinMicrosoftProducts
</blockquote>
<blockquote>
Known Exploited Vulnerability. This Microsoft Windows Fast FAT File System Driver Integer Overflow Vulnerability is part of CISA's list of Known Exploited Vulnerabilities. Microsoft Windows Fast FAT File System Driver contains an integer overflow or wraparound vulnerability that allows an unauthorized attacker to execute code with a physical ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-20`

* https://stackoverflow.com/questions/384502/what-is-the-bit-size-of-long-on-64-bit-windows

<blockquote>
 Whatisthebitsizeoflongon64bitWindowsStackOverflow
</blockquote>
<blockquote>
For information about Windows API types like INT, LONG etc. there is a page on MSDN: Windows Data Types. The information is also available in various Windows header files like WinDef.h. I have listed a few relevant types here:
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-20`

* https://docwiki.embarcadero.com/RADStudio/Alexandria/en/64-bit_Windows_Data_Types_Compared_to_32-bit_Windows_Data_Types

<blockquote>
 64bitWindowsDataTypesComparedto32bitWindowsDataTypes
</blockquote>
<blockquote>
C++Builder 32-bit and 64-bit Windows built-in type sizes The following tables summarize the differences and similarities between 64-bit OS data types and 32-bit OS data types in C++Builder. Note: In order to use members of the System unit (such as System::Byte), you need to &#35;include &lt;System.hpp&gt; .
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://PDF

<blockquote>
 PDFMSWPOWindowsProtocolsOverview
</blockquote>
<blockquote>
FASOD] Protocols Overview Access Services (FAS) protocols, which enable network file access and sharing in Windows and allow a client computer to discover, access, and share files that are hosted on, and made available by,
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://www.winsocketdotnetworkprogramming.com/winsock2programming/winsock2advancedcode1a.html

<blockquote>
 TheIPv4andIPv6protocoladdressingwinsock2functionsandstepson
</blockquote>
<blockquote>
On Windows Vista and later, the RtlIpv4StringToAddress() and RtlIpv4StringToAddressEx() functions can be used to convert a text representation of an IPv4 address in Internet standard dotted-decimal notation to a numeric binary address represented as an IN_ADDR structure. ... int type, int protocol); The first parameter, af, is the protocol's ...
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-socket

<blockquote>
 socketfunctionwinsock2hWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The socket function creates a socket that is bound to a specific transport service provider. Syntax SOCKET WSAAPI socket( [in] int af, [in] int type, [in] int protocol ); Parameters [in] af. The address family specification. Possible values for the address family are defined in the Winsock2.h header file.. On the Windows SDK released for Windows Vista and later, the organization of header ...
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-winprotlp/92b33e19-6fff-496b-86c3-d168206f9845

<blockquote>
 MSWINPROTLPWindowsProtocolsMicrosoftLearn
</blockquote>
<blockquote>
Windows Protocols Preview Documents. Provides preliminary versions of new or updated Open Specifications technical documents for community review and feedback. Windows Protocols Errata . Provides clarifications and adjustments of content issues in published versions of protocol documents that could impact an implementation.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://en.wikipedia.org/wiki/List_of_IP_protocol_numbers

<blockquote>
 ListofIPprotocolnumbersWikipedia
</blockquote>
<blockquote>
This is a list of the IP protocol numbers found in the 8-bit Protocol field of the IPv4 header and the 8-bit Next Header field of the IPv6 header. It is an identifier for the encapsulated protocol and determines the layout of the data that immediately follows the header. ... Protocol Number Keyword Protocol
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://petri.com/smb-port-445-139-138-137/

<blockquote>
 WindowsFileSharingwithSMBPort445139138and137
</blockquote>
<blockquote>
SMB is the most prevalent protocol for sharing files on Windows. This article examines how Windows file sharing works over ports 445, 139, 138, and 137.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://learn.microsoft.com/en-us/troubleshoot/windows-server/networking/service-overview-and-network-port-requirements

<blockquote>
 ServiceoverviewandnetworkportrequirementsforWindows
</blockquote>
<blockquote>
No port number: Lightweight Directory Access Protocol (LDAP) Server: TCP: 389: LDAP Server: UDP: 389: LDAP SSL: TCP: 636: ... SMB, and RPC protocols. Windows XP and Windows Server 2003 additionally require the ICMP protocol. If any one of these protocols is unavailable or blocked between the client and a relevant domain controller, Group Policy ...
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://answers.microsoft.com/en-us/windows/forum/all/protocol-numbers-setting-in-windows-firewall-what/1382bf65-0353-45be-8c85-4ca68dec9be9

<blockquote>
 ProtocolnumberssettinginWindowsFirewallWhatarethey
</blockquote>
<blockquote>
In Windows Firewall 'Outbound Rules', 'Thunderbird Properties', _/Protocols and Ports\_, 'Protocol type: [Custom]' &amp; 'Protocol number: [?]': What are the Protocol numbers for SMTP &amp; POP? for SMTPv2? for SMTPv3? for POP3? (...Actually, I didn't know there was such a thing as protocol number...) Regarding POP, if ports are used instead of ...
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://PDF

<blockquote>
 PDFMSWMODWindowsManagementProtocolsOverview
</blockquote>
<blockquote>
Provides an overview of the functionality and relationship of the Windows Management protocols, which are specified in [MS-WMI], [MS-WSMAN], [MS-WSMV], and [MS-PSRP]. The Windows Management protocols provide the ability to control settings and to collect data for a set of client and server computers.
</blockquote>

---

## DuckDuckgo search -> Windows integer Protocol
`2025-06-19`

* https://learn.microsoft.com/en-us/openspecs/windows_protocols/ms-wpo/c5f54a77-65be-40a0-bb82-9e4181d8ab67

<blockquote>
 MSWPOWindowsProtocolsOverviewMicrosoftLearn
</blockquote>
<blockquote>
A preview version of this document may be available on the Windows Protocols - Preview Documents page. After the preview period, the most current version of the document is available on this page. Development Resources. Find resources for creating interoperable solutions for Microsoft software, services, hardware, and non-Microsoft products:
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://en.wikipedia.org/wiki/Integer_overflow

<blockquote>
 IntegeroverflowWikipedia
</blockquote>
<blockquote>
An integer overflow can cause the value to wrap and become negative, which violates the program's assumption and may lead to unexpected behavior (for example, 8-bit integer addition of 127 + 1 results in −128, a two's complement of 128). (A solution for this particular problem is to use unsigned integer types for values that a program expects ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://learn.microsoft.com/en-us/windows-hardware/drivers/kernel/ntintsafe-design-guide

<blockquote>
 UsingSafeIntegerFunctionsWindowsdriversMicrosoftLearn
</blockquote>
<blockquote>
These functions correspond to the Windows IntSafe functions that are used by application code. You use these functions to calculate an index or buffer size, or to compute some other form of bounds check. ... (STATUS_INTEGER_OVERFLOW). The ntintsafe library has two categories of functions: Conversion functions—These functions perform ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://fuzzysecurity.com/tutorials/expDev/18.html

<blockquote>
 FuzzySecurityWindowsExploitDevPart14
</blockquote>
<blockquote>
Part 14: Kernel Exploitation -&gt; Integer Overflow. Hola, and welcome back to part 14 of the Windows exploit development tutorial series. Today we have another post on pwning @HackSysTeam's extreme vulnerable driver. This time we will take a look at the integer overflow; barring the GS stack overflow (we will cover this later) and the type confusion (too easy to cover but exploit on GitHub) this ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://www.comparitech.com/blog/information-security/integer-overflow-attack/

<blockquote>
 WhatisanIntegerOverflowAttackwithExamplesComparitech
</blockquote>
<blockquote>
Examples of integer overflow attacks. Integer overflows have been a component in a range of prominent attacks. Some of these include: An integer overflow led to Pegasus spyware on a Saudi activist's phone. In March 2021, Citizen Lab examined the phone of a Saudi Arabian activist. Citizen Lab is a Canadian organization that conducts research ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://cybersecuritynews.com/windows-11-integer-overflow-vulnerability/

<blockquote>
 NewWindows11IntegerOverflowVulnerabilityLetsAttackersElevate
</blockquote>
<blockquote>
This security issue is particularly concerning as it affects Windows 11 23H2, one of the latest versions of Microsoft's flagship operating system, reads SSD Disclosure advisory. The exploit takes advantage of an integer overflow that occurs during the calculation of buffer sizes.
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://www.infosecinstitute.com/resources/secure-coding/what-is-is-integer-overflow-and-underflow/

<blockquote>
 WhatisisintegeroverflowandunderflowInfosecInstitute
</blockquote>
<blockquote>
What is integer overflow? As we noticed in the table above, the maximum size for a variable of type Signed char is 127 and it is 255 for unsigned char. Storing a value greater than maximum supported value will lead to integer overflow. Integer overflows by themselves do not lead to code execution.
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://infosecwriteups.com/exploring-integer-overflow-the-realm-of-exploiting-binaries-706d4f7f174e

<blockquote>
 ExploringIntegerOverflowTherealmofexploitingbinaries
</blockquote>
<blockquote>
Image Source: Comic Historical Perspective of Integer Overflow Vulnerability. Integer overflow has been an issue since the early days of computing due to the fixed-size nature of data types in programming languages. In older systems, developers often worked with limited hardware, meaning data types like int and short were used to conserve memory. As a result, overflows became a common problem ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://www.welivesecurity.com/2022/02/21/integer-overflow-how-it-occur-can-be-prevented/

<blockquote>
 IntegeroverflowHowdoesitoccurandhowcanitbeprevented
</blockquote>
<blockquote>
An integer overflow or wraparound happens when an attempt is made to store a value that is too large for an integer type. The range of values that can be stored in an integer type is better ...
</blockquote>

---

## DuckDuckgo search -> Windows integer overflow
`2025-06-19`

* https://www.secwest.net/cansecwest2023-presentations/an-insiders-perspective-on-integer-overflow-vulnerabilities-challenges-and-solutions-from-identification-to-mitigation-at-microsoft

<blockquote>
 AnInsidersPerspectiveonIntegerOverflowVulnerabilities
</blockquote>
<blockquote>
Challenges and Solutions from Identification to Mitigation at Microsoft This talk will delve deep into one of the most prevalent memory safety issues on Windows: Integer Overflows. Over the past few years, MSRC has seen hundreds of Integer Overflow vulnerabilities, ranging from size overflows, int
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-19`

* https://advisory.eventussecurity.com/advisory/security-flaw-in-windows-11-allows-privilege-escalation/

<blockquote>
 SecurityFlawinWindows11AllowsPrivilegeEscalation
</blockquote>
<blockquote>
CVE-2024-38144: This integer overflow vulnerability in the CKSAutomationThunk::ThunkEnableEventIrp function of the ksthunk.sys driver, with a CVSS score of 9.1, enables local attackers to manipulate buffer sizes, causing heap overflow and allowing privilege escalation through arbitrary code execution. The discovered vulnerability in Windows 11 poses significant risks, with the potential for ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-19`

* https://www.hendryadrian.com/integer-overflow-vulnerability-in-windows-driver-enables-privilege-escalation-poc-published/

<blockquote>
 IntegerOverflowVulnerabilityinWindowsDriverEnablesPrivilege
</blockquote>
<blockquote>
&#35;&#35;&#35; &#35;KernelExploitation &#35;PrivilegeEscalation &#35;WindowsVulnerability. Summary: A critical vulnerability in the ksthunk.sys driver of Windows allows local attackers to exploit an integer overflow for privilege escalation, demonstrated at the TyphoonPWN 2024 event. Despite Microsoft's claims of resolution, the flaw remains exploitable in Windows 11 23H2.
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-19`

* https://windowsforum.com/threads/cve-2025-29974-critical-windows-kernel-integer-underflow-vulnerability-explained.366060/

<blockquote>
 CVE202529974CriticalWindowsKernelIntegerUnderflowVulnerability
</blockquote>
<blockquote>
The sudden emergence of CVE-2025-29974—a critical Windows Kernel Information Disclosure Vulnerability—has triggered intense scrutiny among IT professionals, security researchers, and enterprise administrators alike. Characterized by an integer underflow (also known as wrap or wraparound), this...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-19`

* https://www.cisa.gov/news-events/alerts/2025/03/11/cisa-adds-six-known-exploited-vulnerabilities-catalog

<blockquote>
 CISAAddsSixKnownExploitedVulnerabilitiestoCatalog
</blockquote>
<blockquote>
CISA has added six new vulnerabilities to its Known Exploited Vulnerabilities Catalog, based on evidence of active exploitation.. CVE-2025-24983 Microsoft Windows Win32k Use-After-Free Vulnerability; CVE-2025-24984 Microsoft Windows NTFS Information Disclosure Vulnerability; CVE-2025-24985 Microsoft Windows Fast FAT File System Driver Integer Overflow Vulnerability
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-19`

* https://vuldb.com/?id.291780

<blockquote>
 MicrosoftWindowsuptoServer2025GDIintegeroverflow
</blockquote>
<blockquote>
A vulnerability classified as critical has been found in Microsoft Windows. Affected is some unknown processing of the component GDI+. The manipulation with an unknown input leads to a integer overflow vulnerability. CWE is classifying the issue as CWE-190. The product performs a calculation that can produce an integer overflow or wraparound ...
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-19`

* https://www.cvedetails.com/cve/CVE-2025-29974/

<blockquote>
 CVE202529974IntegerunderflowwraporwraparoundinWindows
</blockquote>
<blockquote>
Integer underflow (wrap or wraparound) in Windows Kernel allows an unauthorized attacker to disclose information over an adjacent network. Published 2025-05-13 17:15:58 Updated 2025-05-19 14:20:27
</blockquote>

---

## DuckDuckgo search -> Windows integer vulnerability
`2025-06-19`

* https://www.cve.news/cve-2025-24985/

<blockquote>
 CVE202524985LeveragingIntegerOverflowinWindowsFastFATDriver
</blockquote>
<blockquote>
A new vulnerability tracked as CVE-2025-24985 has been discovered in the Windows Fast FAT (File Allocation Table) Driver. This vulnerability involves an integer overflow, also known as &quot;wraparound,&quot; which allows local attackers to escalate their privileges and potentially execute arbitrary code on affected Windows systems.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://learn.microsoft.com/en-us/windows-hardware/drivers/kernel/the-new-data-types

<blockquote>
 TheNewDataTypesWindowsdriversMicrosoftLearn
</blockquote>
<blockquote>
There are three classes of new data types: fixed-precision integer types, pointer-precision integer types, and specific-precision pointer types. These types were added to the Windows environment (specifically, to Basetsd.h) to allow developers to prepare for 64-bit Windows well before its introduction. These new types were derived from the ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://learn.microsoft.com/en-us/cpp/cpp/data-type-ranges?view=msvc-170

<blockquote>
 DataTypeRangesMicrosoftLearn
</blockquote>
<blockquote>
Learn more about: Data Type Ranges. A variable of __wchar_t designates either a wide-character type or multibyte-character type. Use the L prefix before a character or string constant to designate the wide-character-type constant.. signed and unsigned are modifiers that you can use with any integral type except bool.Note that char, signed char, and unsigned char are three distinct types for ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://devblogs.microsoft.com/oldnewthing/20080325-00/?p=23013

<blockquote>
 WhatsthedifferencebetweenintandINTlongandLONGetc
</blockquote>
<blockquote>
In the intervening years, most if not all compilers which target Windows have aligned their native types with Windows' platform types. An int is always a 32-bit signed integer, as is a long. As a result, the distinction between language types and platform types is now pretty much academic, and the two can be used interchangeably. ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://win32.pub/docs/guides-concepts/integer-types

<blockquote>
 IntegerTypeswin32
</blockquote>
<blockquote>
Integer Types. Unlike Dart, which has a single integer type for storing values between -2 63-1 and 2 63, the Win32 API utilizes various integer types in both signed and unsigned forms. The following table lists the common integer types encountered when working with Win32 APIs:
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://github.com/MicrosoftDocs/win32/blob/docs/desktop-src/WinProg/windows-data-types.md

<blockquote>
 win32desktopsrcWinProgwindowsdatatypesmdatdocsGitHub
</blockquote>
<blockquote>
You signed in with another tab or window. Reload to refresh your session. You signed out in another tab or window. Reload to refresh your session. You switched accounts on another tab or window.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://blog.thecoatlessprofessor.com/programming/cpp/differences-in-primitive-data-types-between-os-x-and-windows/index.html

<blockquote>
 DifferencesinPrimitiveDataTypesbetweenOSXandWindows
</blockquote>
<blockquote>
Size of int: 4; Size of long int: 8; Size of long: 8; Size of int32_t: 4 * Above given in bytes… Notice that a difference exist in the amount of bytes allocated to the long int type between OS X and Windows of 4 bytes. At long last, the reason was becoming clear what the issue was and what the solution is. Solution. Use portable integer types!
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://stackoverflow.com/questions/463299/how-do-i-make-a-textbox-that-only-accepts-numbers

<blockquote>
 HowdoImakeatextboxthatonlyacceptsnumbers
</blockquote>
<blockquote>
But I want to share a generalized form for the System.Windows.Forms.TextBox and System.Windows.Controls.TextBox. There is not available KeyPress event in System.Windows.Controls.TextBox. This answer is for those people who want to implement with the same logic for System.Windows.Forms.TextBox and System.Windows.Controls.TextBox.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://opentechtips.com/integer8/

<blockquote>
 WindowsTimestampConverterOnlineandinPowerShellInteger8
</blockquote>
<blockquote>
The Windows Time Stamp Format - aka Integer8. Microsoft Windows environments use the Integer8 timestamp format. A 64-bit value representing the number of 100-nanoseconds elapsed since January 1, 1601 (UTC). Conversion with PowerShell.
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://learn.microsoft.com/en-us/dotnet/standard/base-types/standard-numeric-format-strings

<blockquote>
 StandardnumericformatstringsNETMicrosoftLearn
</blockquote>
<blockquote>
Standard numeric format strings are used to format common numeric types. A standard numeric format string takes the form [format specifier][precision specifier], where:. Format specifier is a single alphabetic character that specifies the type of number format, for example, currency or percent. Any numeric format string that contains more than one alphabetic character, including white space ...
</blockquote>

---

## DuckDuckgo search -> Windows integer
`2025-06-19`

* https://learn.microsoft.com/en-us/windows/win32/winprog/windows-data-types

<blockquote>
 WindowsDataTypesBaseTsdhWin32appsMicrosoftLearn
</blockquote>
<blockquote>
The data types supported by Windows are used to define function return values, function and message parameters, and structure members. ... the underlying C/C++ data types, see Data Type Ranges. The following table contains the following types: character, integer, Boolean, pointer, and handle. The character, integer, and Boolean types are common ...
</blockquote>

---

# GitHub search -> Windows integer
# MortenSchenkb

https://github.com/hiperbolt9/MortenSchenkb
<blockquote>
Control Flow Guard bypass using LoadLibrary and IsBadCodePtr
</blockquote>

<table><tr>
<tr><td>Owner: <code>hiperbolt9</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2021-10-31 06:37:46+00:00</code></td>
    <td>Latest: <code>2028-01-14 22:47:37+08:00</code></td></tr>
<tr><td>Commits: <code>1155</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: control flow guard bypass

---

# GitHub search -> Windows integer
# TOP

https://github.com/GhostTroops/TOP
<blockquote>
TOP All bugbounty pentesting CVE-2023- POC Exp  RCE example payload  Things
</blockquote>

<table><tr>
<tr><td>Owner: <code>GhostTroops</code></td>
    <td>Language: <code>Shell</code></td>
    <td>Started: <code>2022-03-19 01:54:15+00:00</code></td>
    <td>Latest: <code>2025-07-03 01:17:05+00:00</code></td></tr>
<tr><td>Commits: <code>1233</code></td>
    <td>Stargazers: <code>699</code></td>
    <td>Watchers: <code>699</code></td>
    <td>Forks: <code>121</code></td></tr>
</table>
Keywords: rce exploit, rce poc, rce vulnerability

---

# GitHub search -> Windows integer
# mbanyamer-Microsoft-PowerPoint-Use-After-Free-Remote-Code-Execution-RCE

https://github.com/mbanyamer/mbanyamer-Microsoft-PowerPoint-Use-After-Free-Remote-Code-Execution-RCE
<blockquote>
This repository contains a Proof of Concept (PoC) exploit for the **CVE-2025-47175** vulnerability found in Microsoft PowerPoint.   The vulnerability is a Use-After-Free (UAF) bug that allows an attacker to execute arbitrary code by tricking a user into opening a specially crafted PPTX file.
</blockquote>

<table><tr>
<tr><td>Owner: <code>mbanyamer</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-07-02 12:17:25+00:00</code></td>
    <td>Latest: <code>2025-07-02 15:19:49+03:00</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Microsoft rce

---

# GitHub search -> Windows integer
# certificate-vuln1001-opensecuritytraining2

https://github.com/ngvtdanhh/certificate-vuln1001-opensecuritytraining2
<blockquote>
Deep-dive into C-family memory vulnerabilities — stack overflow, heap corruption, format strings, and more.
</blockquote>

<table><tr>
<tr><td>Owner: <code>ngvtdanhh</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2025-06-28 04:57:17+00:00</code></td>
    <td>Latest: <code>2025-07-02 12:14:55+07:00</code></td></tr>
<tr><td>Commits: <code>25</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow vulnerability

---

# GitHub search -> Windows integer
# jsoup

https://github.com/jhy/jsoup
<blockquote>
jsoup: the Java HTML parser, built for HTML editing, cleaning, scraping, and XSS safety.
</blockquote>

<table><tr>
<tr><td>Owner: <code>jhy</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2009-12-19 01:29:58+00:00</code></td>
    <td>Latest: <code>2025-06-23 14:43:41+10:00</code></td></tr>
<tr><td>Commits: <code>2710</code></td>
    <td>Stargazers: <code>11193</code></td>
    <td>Watchers: <code>11193</code></td>
    <td>Forks: <code>2238</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# smart-doc

https://github.com/TongchengOpenSource/smart-doc
<blockquote>
Smart-doc is a java restful api document generation tool. Smart-doc is based on interface source code analysis to generate interface documentation, completely zero-injection.
</blockquote>

<table><tr>
<tr><td>Owner: <code>TongchengOpenSource</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2019-09-10 01:23:13+00:00</code></td>
    <td>Latest: <code>2025-06-23 11:32:56+08:00</code></td></tr>
<tr><td>Commits: <code>2153</code></td>
    <td>Stargazers: <code>1492</code></td>
    <td>Watchers: <code>1492</code></td>
    <td>Forks: <code>292</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# sqlmap

https://github.com/sqlmapproject/sqlmap
<blockquote>
Automatic SQL injection and database takeover tool
</blockquote>

<table><tr>
<tr><td>Owner: <code>sqlmapproject</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2012-06-26 09:52:15+00:00</code></td>
    <td>Latest: <code>2025-06-22 13:47:48+02:00</code></td></tr>
<tr><td>Commits: <code>10417</code></td>
    <td>Stargazers: <code>34565</code></td>
    <td>Watchers: <code>34565</code></td>
    <td>Forks: <code>5934</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# dalfox

https://github.com/hahwul/dalfox
<blockquote>
🌙🦊 Dalfox is a powerful open-source XSS scanner and utility focused on automation.
</blockquote>

<table><tr>
<tr><td>Owner: <code>hahwul</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2020-04-12 07:04:10+00:00</code></td>
    <td>Latest: <code>2025-06-22 16:09:45+09:00</code></td></tr>
<tr><td>Commits: <code>1919</code></td>
    <td>Stargazers: <code>4345</code></td>
    <td>Watchers: <code>4345</code></td>
    <td>Forks: <code>474</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# hackerone-reports

https://github.com/reddelexc/hackerone-reports
<blockquote>
Top disclosed reports from HackerOne
</blockquote>

<table><tr>
<tr><td>Owner: <code>reddelexc</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-04-19 06:11:04+00:00</code></td>
    <td>Latest: <code>2025-06-21 21:21:52+04:00</code></td></tr>
<tr><td>Commits: <code>138</code></td>
    <td>Stargazers: <code>4613</code></td>
    <td>Watchers: <code>4613</code></td>
    <td>Forks: <code>836</code></td></tr>
</table>
Keywords: xxe, ssrf

---

# GitHub search -> Windows integer
# InjectionNext

https://github.com/johnno1962/InjectionNext
<blockquote>
Fourth evolution of Code Injection for Xcode
</blockquote>

<table><tr>
<tr><td>Owner: <code>johnno1962</code></td>
    <td>Language: <code>Swift</code></td>
    <td>Started: <code>2024-05-30 09:54:05+00:00</code></td>
    <td>Latest: <code>2025-06-20 19:36:40+02:00</code></td></tr>
<tr><td>Commits: <code>170</code></td>
    <td>Stargazers: <code>178</code></td>
    <td>Watchers: <code>178</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# lfi

https://github.com/zyedidia/lfi
<blockquote>
LFI: Practical, Efficient, and Secure Software-based Sandboxing
</blockquote>

<table><tr>
<tr><td>Owner: <code>zyedidia</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2023-05-31 02:24:53+00:00</code></td>
    <td>Latest: <code>2025-06-17 18:34:24-07:00</code></td></tr>
<tr><td>Commits: <code>996</code></td>
    <td>Stargazers: <code>79</code></td>
    <td>Watchers: <code>79</code></td>
    <td>Forks: <code>9</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# Exploit-Street

https://github.com/MzHmO/Exploit-Street
<blockquote>
Complete list of LPE exploits for Windows (starting from 2023)
</blockquote>

<table><tr>
<tr><td>Owner: <code>MzHmO</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2024-11-14 18:24:50+00:00</code></td>
    <td>Latest: <code>2025-06-16 21:27:29+05:00</code></td></tr>
<tr><td>Commits: <code>23</code></td>
    <td>Stargazers: <code>802</code></td>
    <td>Watchers: <code>802</code></td>
    <td>Forks: <code>105</code></td></tr>
</table>
Keywords: Windows lpe, lpe exploit, lpe exploitation, Windows lpe exploit, Windows lpe exploitation

---

# GitHub search -> Windows integer
# atdatabases

https://github.com/ForbesLindesay/atdatabases
<blockquote>
TypeScript clients for databases that prevent SQL Injection
</blockquote>

<table><tr>
<tr><td>Owner: <code>ForbesLindesay</code></td>
    <td>Language: <code>TypeScript</code></td>
    <td>Started: <code>2018-12-19 16:31:39+00:00</code></td>
    <td>Latest: <code>2025-06-11 12:07:21+01:00</code></td></tr>
<tr><td>Commits: <code>229</code></td>
    <td>Stargazers: <code>617</code></td>
    <td>Watchers: <code>617</code></td>
    <td>Forks: <code>46</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# one_gadget

https://github.com/david942j/one_gadget
<blockquote>
The best tool for finding one gadget RCE in libc.so.6
</blockquote>

<table><tr>
<tr><td>Owner: <code>david942j</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2017-02-07 08:03:34+00:00</code></td>
    <td>Latest: <code>2025-06-11 09:44:10+08:00</code></td></tr>
<tr><td>Commits: <code>319</code></td>
    <td>Stargazers: <code>2190</code></td>
    <td>Watchers: <code>2190</code></td>
    <td>Forks: <code>144</code></td></tr>
</table>
Keywords: rce exploit

---

# GitHub search -> Windows integer
# KEV

https://github.com/Ostorlab/KEV
<blockquote>
Ostorlab KEV: One-command to detect most remotely known exploitable vulnerabilities. Sourced from CISA KEV, Google's Tsunami, Ostorlab's Asteroid and Bug Bounty programs.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Ostorlab</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-04-19 08:58:42+00:00</code></td>
    <td>Latest: <code>2025-06-03 18:30:06+01:00</code></td></tr>
<tr><td>Commits: <code>704</code></td>
    <td>Stargazers: <code>574</code></td>
    <td>Watchers: <code>574</code></td>
    <td>Forks: <code>40</code></td></tr>
</table>
Keywords: 0day vulnerability, 0day exploitation, 0day exploit

---

# GitHub search -> Windows integer
# InputValidationProgram2

https://github.com/FotisDev/InputValidationProgram2
<blockquote>
This program ensures the user inputs valid integers or floating-point numbers. It checks for invalid characters, multiple decimal points, and improper placement of signs. The program keeps prompting the user until a valid input is entered, ensuring the correct format is maintained for both integer and floating-point values.
</blockquote>

<table><tr>
<tr><td>Owner: <code>FotisDev</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2025-05-13 17:49:31+00:00</code></td>
    <td>Latest: <code>2025-05-13 20:50:00+03:00</code></td></tr>
<tr><td>Commits: <code>1</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: improper input validation

---

# GitHub search -> Windows integer
# oSSRF

https://github.com/TheOSuite/oSSRF
<blockquote>
Server-Side Request Forgery Testing Utility
</blockquote>

<table><tr>
<tr><td>Owner: <code>TheOSuite</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-05-04 22:25:20+00:00</code></td>
    <td>Latest: <code>2025-05-13 12:12:14-05:00</code></td></tr>
<tr><td>Commits: <code>7</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: server side request forgery

---

# GitHub search -> Windows integer
# DillonAIPolyGlotDefender

https://github.com/mayd01/DillonAIPolyGlotDefender
<blockquote>
All in one AI and Rust based CyberSecurity tool to protect Windows and Linux OS systems from Zero Day threats 
</blockquote>

<table><tr>
<tr><td>Owner: <code>mayd01</code></td>
    <td>Language: <code>Rust</code></td>
    <td>Started: <code>2025-01-27 21:24:16+00:00</code></td>
    <td>Latest: <code>2025-05-09 13:17:01-04:00</code></td></tr>
<tr><td>Commits: <code>88</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows zero-day

---

# GitHub search -> Windows integer
# jsql-injection

https://github.com/ron190/jsql-injection
<blockquote>
jSQL Injection is a Java application for automatic SQL database injection.
</blockquote>

<table><tr>
<tr><td>Owner: <code>ron190</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2012-07-18 18:07:09+00:00</code></td>
    <td>Latest: <code>2025-05-09 01:37:35+02:00</code></td></tr>
<tr><td>Commits: <code>1547</code></td>
    <td>Stargazers: <code>1631</code></td>
    <td>Watchers: <code>1631</code></td>
    <td>Forks: <code>430</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# rcedit

https://github.com/electron/rcedit
<blockquote>
Command line tool to edit resources of exe
</blockquote>

<table><tr>
<tr><td>Owner: <code>electron</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2013-11-05 11:13:21+00:00</code></td>
    <td>Latest: <code>2025-05-01 00:20:35-07:00</code></td></tr>
<tr><td>Commits: <code>193</code></td>
    <td>Stargazers: <code>1911</code></td>
    <td>Watchers: <code>1911</code></td>
    <td>Forks: <code>202</code></td></tr>
</table>
Keywords: Windows rce

---

# GitHub search -> Windows integer
# Data-Injection

https://github.com/vimalAdithan/Data-Injection
<blockquote>
get Sales data from CSV file and inject in db
</blockquote>

<table><tr>
<tr><td>Owner: <code>vimalAdithan</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2025-04-25 08:07:45+00:00</code></td>
    <td>Latest: <code>2025-04-25 21:45:39+05:30</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: csv injection

---

# GitHub search -> Windows integer
# a2lfile

https://github.com/DanielT/a2lfile
<blockquote>
Create, edit and write a2l files with this rust crate
</blockquote>

<table><tr>
<tr><td>Owner: <code>DanielT</code></td>
    <td>Language: <code>Rust</code></td>
    <td>Started: <code>2021-05-26 18:08:46+00:00</code></td>
    <td>Latest: <code>2025-04-23 19:30:41+02:00</code></td></tr>
<tr><td>Commits: <code>182</code></td>
    <td>Stargazers: <code>26</code></td>
    <td>Watchers: <code>26</code></td>
    <td>Forks: <code>14</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# Commodity-Injection-Signatures

https://github.com/xsscx/Commodity-Injection-Signatures
<blockquote>
Commodity Injection Signatures, Malicious Inputs, XSS, HTTP Header Injection, XXE, RCE, Javascript, XSLT
</blockquote>

<table><tr>
<tr><td>Owner: <code>xsscx</code></td>
    <td>Language: <code>HTML</code></td>
    <td>Started: <code>2015-02-01 02:06:13+00:00</code></td>
    <td>Latest: <code>2025-04-21 11:07:40-04:00</code></td></tr>
<tr><td>Commits: <code>253</code></td>
    <td>Stargazers: <code>403</code></td>
    <td>Watchers: <code>403</code></td>
    <td>Forks: <code>118</code></td></tr>
</table>
Keywords: rce exploit, rce poc, xxe

---

# GitHub search -> Windows integer
# mcp-exploit-demo

https://github.com/Repello-AI/mcp-exploit-demo
<blockquote>
This repository demonstrates a security vulnerability in MCP (Model Context Protocol ) servers that allows for remote code execution and data exfiltration through tool poisoning.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Repello-AI</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-04-16 07:55:55+00:00</code></td>
    <td>Latest: <code>2025-04-21 18:08:32+05:30</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>11</code></td>
    <td>Watchers: <code>11</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: remote code execution vulnerability

---

# GitHub search -> Windows integer
# acra

https://github.com/cossacklabs/acra
<blockquote>
Database security suite. Database proxy with field-level encryption, search through encrypted data, SQL injections prevention, intrusion detection, honeypots. Supports client-side and proxy-side (&amp;quot;transparent&amp;quot;) encryption. SQL, NoSQL.
</blockquote>

<table><tr>
<tr><td>Owner: <code>cossacklabs</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2016-11-14 16:23:25+00:00</code></td>
    <td>Latest: <code>2025-04-17 13:21:23+03:00</code></td></tr>
<tr><td>Commits: <code>1403</code></td>
    <td>Stargazers: <code>1403</code></td>
    <td>Watchers: <code>1403</code></td>
    <td>Forks: <code>131</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# AMSI-WRITE-RAID-BYPASS

https://github.com/V-i-x-x/AMSI-WRITE-RAID-BYPASS
<blockquote>
&amp;quot;AMSI WRITE RAID&amp;quot; Vulnerability that leads to an effective AMSI BYPASS
</blockquote>

<table><tr>
<tr><td>Owner: <code>V-i-x-x</code></td>
    <td>Language: <code>PowerShell</code></td>
    <td>Started: <code>2024-05-03 21:27:59+00:00</code></td>
    <td>Latest: <code>2025-04-10 17:59:30+03:00</code></td></tr>
<tr><td>Commits: <code>24</code></td>
    <td>Stargazers: <code>290</code></td>
    <td>Watchers: <code>290</code></td>
    <td>Forks: <code>51</code></td></tr>
</table>
Keywords: 0day vulnerability

---

# GitHub search -> Windows integer
# AI-Based-Zero-Day-Vulnerability-Detection-System

https://github.com/PICT-Cyber-Cell/AI-Based-Zero-Day-Vulnerability-Detection-System
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>PICT-Cyber-Cell</code></td>
    <td>Language: <code>Jupyter Notebook</code></td>
    <td>Started: <code>2025-03-08 09:47:07+00:00</code></td>
    <td>Latest: <code>2025-04-06 10:47:06+05:30</code></td></tr>
<tr><td>Commits: <code>36</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: zero-day vulnerability

---

# GitHub search -> Windows integer
# zerodayf

https://github.com/0xHamy/zerodayf
<blockquote>
Zerodayf is an advanced code analysis platform that leverages artificial intelligence &amp;amp; SAST to identify vulnerabilities within source code. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>0xHamy</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-02-07 03:19:33+00:00</code></td>
    <td>Latest: <code>2025-04-05 09:35:56-04:00</code></td></tr>
<tr><td>Commits: <code>73</code></td>
    <td>Stargazers: <code>28</code></td>
    <td>Watchers: <code>28</code></td>
    <td>Forks: <code>4</code></td></tr>
</table>
Keywords: 0day vulnerability, 0day analysis

---

# GitHub search -> Windows integer
# caldera_pathfinder

https://github.com/center-for-threat-informed-defense/caldera_pathfinder
<blockquote>
Pathfinder is a plugin for mapping network vulnerabilities, scanned by CALDERA or imported by a supported network scanner, and translating those scans into adversaries for network traversal.
</blockquote>

<table><tr>
<tr><td>Owner: <code>center-for-threat-informed-defense</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2020-04-14 12:48:05+00:00</code></td>
    <td>Latest: <code>2025-04-03 08:25:51-04:00</code></td></tr>
<tr><td>Commits: <code>245</code></td>
    <td>Stargazers: <code>126</code></td>
    <td>Watchers: <code>126</code></td>
    <td>Forks: <code>23</code></td></tr>
</table>
Keywords: path traversal vulnerability

---

# GitHub search -> Windows integer
# GA-CustomerRevenuePrediction

https://github.com/PaolaGaray/GA-CustomerRevenuePrediction
<blockquote>
Predict customer revenue in the GStore using Google Analytics data by implementing a two-stage machine learning framework.  Classification identifies potential buyers, and Regression forecasts revenue by analyzing user behavior, session details, and acquisition channels.
</blockquote>

<table><tr>
<tr><td>Owner: <code>PaolaGaray</code></td>
    <td>Language: <code>Jupyter Notebook</code></td>
    <td>Started: <code>2024-10-28 11:09:47+00:00</code></td>
    <td>Latest: <code>2025-03-26 14:35:24+01:00</code></td></tr>
<tr><td>Commits: <code>105</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session prediction

---

# GitHub search -> Windows integer
# PathSeeker

https://github.com/praveenkavi5/PathSeeker
<blockquote>
PathSeeker is a Python-based tool designed to identify path traversal vulnerabilities in web applications. It uses a combination of multi-threading, random user agents, and a robust wordlist to efficiently test endpoints for potential security weaknesses.
</blockquote>

<table><tr>
<tr><td>Owner: <code>praveenkavi5</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-03-19 11:30:49+00:00</code></td>
    <td>Latest: <code>2025-03-22 01:30:38+00:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: path traversal vulnerability

---

# GitHub search -> Windows integer
# sessionHijackingPrevention

https://github.com/1Mike3/sessionHijackingPrevention
<blockquote>
A woking proof of concept for detecting session hijacking using browser fingerprinting.
</blockquote>

<table><tr>
<tr><td>Owner: <code>1Mike3</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2024-10-17 18:19:14+00:00</code></td>
    <td>Latest: <code>2025-03-16 15:40:31+01:00</code></td></tr>
<tr><td>Commits: <code>53</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# Go-Insecure-Web-APP

https://github.com/Emin-F/Go-Insecure-Web-APP
<blockquote>
insecure web application that has 8 vulnerability on it, such as RCE, Path Traversal, XSS, SQL Injection, SSTI, IDOR, Authentication and Authorization 
</blockquote>

<table><tr>
<tr><td>Owner: <code>Emin-F</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2024-08-01 15:07:34+00:00</code></td>
    <td>Latest: <code>2025-03-11 14:29:44+03:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: path traversal vulnerability

---

# GitHub search -> Windows integer
# dresscode

https://github.com/sensepost/dresscode
<blockquote>
Scan websites CSP policies and visualise their vunlnerabilities from a dashboard
</blockquote>

<table><tr>
<tr><td>Owner: <code>sensepost</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-08-07 17:12:46+00:00</code></td>
    <td>Latest: <code>2025-03-11 10:07:52+01:00</code></td></tr>
<tr><td>Commits: <code>19</code></td>
    <td>Stargazers: <code>13</code></td>
    <td>Watchers: <code>13</code></td>
    <td>Forks: <code>3</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# JavaRce

https://github.com/Whoopsunix/JavaRce
<blockquote>
Common Exploitation Techniques for Java RCE Vulnerabilities in Real-World Scenarios | 实战场景较通用的 Java Rce 相关漏洞的利用方式
</blockquote>

<table><tr>
<tr><td>Owner: <code>Whoopsunix</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2023-08-18 08:40:21+00:00</code></td>
    <td>Latest: <code>2025-03-06 13:21:37+08:00</code></td></tr>
<tr><td>Commits: <code>96</code></td>
    <td>Stargazers: <code>515</code></td>
    <td>Watchers: <code>515</code></td>
    <td>Forks: <code>61</code></td></tr>
</table>
Keywords: rce vulnerability, rce exploitation, rce exploit

---

# GitHub search -> Windows integer
# Web_Venerability_Scanner

https://github.com/Arya182-ui/Web_Venerability_Scanner
<blockquote>
A **Command-Line Web Vulnerability Scanner** built in Python to scan websites for **SQL Injection, XSS, Directory Traversal**, and **Subdomain Enumeration** with **Tor &amp;amp; Proxy support** for anonymous scanning. The tool also generates an **HTML report** with the results.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Arya182-ui</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-03-05 04:24:41+00:00</code></td>
    <td>Latest: <code>2025-03-05 10:00:17+05:30</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: directory traversal vulnerability

---

# GitHub search -> Windows integer
# Automated-Web-Vulnerability-Scanner

https://github.com/ayush-07-parajuli/Automated-Web-Vulnerability-Scanner
<blockquote>
This Python-based tool scans websites for common vulnerabilities like SQL Injection, Cross-Site Scripting (XSS), and Security Misconfigurations. It features a user-friendly GUI built with Tkinter, stores results in an SQLite database, and allows exporting to CSV for further analysis. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>ayush-07-parajuli</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-02-27 13:30:14+00:00</code></td>
    <td>Latest: <code>2025-02-27 19:20:34+05:45</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: csv injection

---

# GitHub search -> Windows integer
# dbi-dbrc

https://github.com/djberg96/dbi-dbrc
<blockquote>
A database resource control interface for Ruby that lets you avoid hard coding your passwords
</blockquote>

<table><tr>
<tr><td>Owner: <code>djberg96</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2010-01-09 15:15:28+00:00</code></td>
    <td>Latest: <code>2025-02-27 06:40:48-05:00</code></td></tr>
<tr><td>Commits: <code>152</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# MBP-Session-Hijacking

https://github.com/Ciarands/MBP-Session-Hijacking
<blockquote>
Writeup on session hijacking exploit for video streaming platform MovieBoxPro which exposed over 6 million Google accounts (15/05/2024)
</blockquote>

<table><tr>
<tr><td>Owner: <code>Ciarands</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2025-02-26 10:49:02+00:00</code></td>
    <td>Latest: <code>2025-02-26 12:19:43+00:00</code></td></tr>
<tr><td>Commits: <code>6</code></td>
    <td>Stargazers: <code>4</code></td>
    <td>Watchers: <code>4</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# ghauri

https://github.com/r0oth3x49/ghauri
<blockquote>
An advanced cross-platform tool that automates the process of detecting and exploiting SQL injection security flaws
</blockquote>

<table><tr>
<tr><td>Owner: <code>r0oth3x49</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2022-10-01 11:21:50+00:00</code></td>
    <td>Latest: <code>2025-02-26 00:09:45+05:00</code></td></tr>
<tr><td>Commits: <code>147</code></td>
    <td>Stargazers: <code>3580</code></td>
    <td>Watchers: <code>3580</code></td>
    <td>Forks: <code>374</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# bincat

https://github.com/airbus-seclab/bincat
<blockquote>
Binary code static analyser, with IDA integration. Performs value and taint analysis, type reconstruction, use-after-free and double-free detection
</blockquote>

<table><tr>
<tr><td>Owner: <code>airbus-seclab</code></td>
    <td>Language: <code>OCaml</code></td>
    <td>Started: <code>2017-05-29 15:31:22+00:00</code></td>
    <td>Latest: <code>2025-02-25 17:53:49+01:00</code></td></tr>
<tr><td>Commits: <code>4725</code></td>
    <td>Stargazers: <code>1811</code></td>
    <td>Watchers: <code>1811</code></td>
    <td>Forks: <code>167</code></td></tr>
</table>
Keywords: use after free analysis

---

# GitHub search -> Windows integer
# HackSysExtremeVulnerableDriver

https://github.com/hacksysteam/HackSysExtremeVulnerableDriver
<blockquote>
HackSys Extreme Vulnerable Driver (HEVD) - Windows &amp;amp; Linux
</blockquote>

<table><tr>
<tr><td>Owner: <code>hacksysteam</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2015-05-28 08:24:56+00:00</code></td>
    <td>Latest: <code>2025-02-24 17:49:16+05:30</code></td></tr>
<tr><td>Commits: <code>176</code></td>
    <td>Stargazers: <code>2702</code></td>
    <td>Watchers: <code>2702</code></td>
    <td>Forks: <code>552</code></td></tr>
</table>
Keywords: vulnerability, Windows uaf vulnerability, uaf exploitation, Windows uaf exploitation, uaf vulnerability, Windows uaf

---

# GitHub search -> Windows integer
# PPS_Project

https://github.com/jonschumaker/PPS_Project
<blockquote>
Consider  the  design  of  a  database  for  a  web  site  that  allow  people  to  buy  and  sell  a  cypto called PPS (see website testing.ppswap.org). Only registered users can buy and sell PPS. Each user is identified by a userid, which is an email, first name, last name, birthday, address (street number, street, city, state, and zip code), balance of PPS and balance of dollar.  Initially, both PPS and dollar balances are zero. A user can withdraw and deposit dollars. A special user root (this is the only user whose id is root and not an email) initially will have the whole supply of PPS, which is 1T. A user will sell and buy PPS only with this special user root (in real life, this special root might be just a smart contract). The price of the PPS is set to 1M/$ initially. For the simplicity of this project, we assume each buy will increase the price by a little: each dollar can buy 1 less PPS after each buy. In the same way, each sell will decrease the price a little bit:  each  d...
</blockquote>

<table><tr>
<tr><td>Owner: <code>jonschumaker</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2021-10-17 15:02:55+00:00</code></td>
    <td>Latest: <code>2025-02-21 20:40:55-05:00</code></td></tr>
<tr><td>Commits: <code>51</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>5</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# wxvl

https://github.com/20142995/wxvl
<blockquote>
复现|漏洞|CVE|CNVD|POC|EXP|0day|1day|nday等相关微信文章收集
</blockquote>

<table><tr>
<tr><td>Owner: <code>20142995</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-11-16 11:21:28+00:00</code></td>
    <td>Latest: <code>2025-02-20 04:13:29+00:00</code></td></tr>
<tr><td>Commits: <code>546</code></td>
    <td>Stargazers: <code>93</code></td>
    <td>Watchers: <code>93</code></td>
    <td>Forks: <code>19</code></td></tr>
</table>
Keywords: 0day poc

---

# GitHub search -> Windows integer
# Stack-Overflow-and-Input-Validation-Issues-in-Recursive-Factorial-Function-rswgq

https://github.com/Bug-Hunter-X/Stack-Overflow-and-Input-Validation-Issues-in-Recursive-Factorial-Function-rswgq
<blockquote>
This Hack code calculates the factorial of a number using recursion. It has two issues: stack overflow for large inputs and lack of input validation for negative or non-integer inputs. The solution involves adding input validation and using an iterative approach instead of recursion.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Bug-Hunter-X</code></td>
    <td>Language: <code>Hack</code></td>
    <td>Started: <code>2025-02-18 03:50:04+00:00</code></td>
    <td>Latest: <code>2025-02-18 04:50:06+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lack of input validation

---

# GitHub search -> Windows integer
# ronin-vulns

https://github.com/ronin-rb/ronin-vulns
<blockquote>
Tests URLs for Local File Inclusion (LFI), Remote File Inclusion (RFI),   SQL injection (SQLi), and Cross Site Scripting (XSS), Server Side Template Injection (SSTI), and Open Redirects.
</blockquote>

<table><tr>
<tr><td>Owner: <code>ronin-rb</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2022-09-03 03:57:17+00:00</code></td>
    <td>Latest: <code>2025-02-17 13:24:05-08:00</code></td></tr>
<tr><td>Commits: <code>296</code></td>
    <td>Stargazers: <code>78</code></td>
    <td>Watchers: <code>78</code></td>
    <td>Forks: <code>19</code></td></tr>
</table>
Keywords: local file inclusion, cross-side-scripting

---

# GitHub search -> Windows integer
# Stack-Overflow-in-Recursive-Factorial-Function-b7vs1

https://github.com/Bug-Hunter-X/Stack-Overflow-in-Recursive-Factorial-Function-b7vs1
<blockquote>
Stack overflow error in recursive function due to lack of input validation and a missing base case for negative integers.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Bug-Hunter-X</code></td>
    <td>Language: <code>Hack</code></td>
    <td>Started: <code>2025-02-16 09:08:03+00:00</code></td>
    <td>Latest: <code>2025-02-16 10:08:05+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lack of input validation

---

# GitHub search -> Windows integer
# ronin-code-sql

https://github.com/ronin-rb/ronin-code-sql
<blockquote>
A Ruby DSL for crafting SQL Injections
</blockquote>

<table><tr>
<tr><td>Owner: <code>ronin-rb</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2010-01-30 02:35:12+00:00</code></td>
    <td>Latest: <code>2025-02-14 23:52:21-08:00</code></td></tr>
<tr><td>Commits: <code>939</code></td>
    <td>Stargazers: <code>46</code></td>
    <td>Watchers: <code>46</code></td>
    <td>Forks: <code>5</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# Auto-SSRF

https://github.com/banchengkemeng/Auto-SSRF
<blockquote>
基于 BurpSuite 新版 MontoyaAPI 的 SSRF 漏洞自动探测插件
</blockquote>

<table><tr>
<tr><td>Owner: <code>banchengkemeng</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2024-10-26 11:22:01+00:00</code></td>
    <td>Latest: <code>2025-02-13 13:59:13+08:00</code></td></tr>
<tr><td>Commits: <code>27</code></td>
    <td>Stargazers: <code>103</code></td>
    <td>Watchers: <code>103</code></td>
    <td>Forks: <code>5</code></td></tr>
</table>
Keywords: ssrf

---

# GitHub search -> Windows integer
# SQL_Injection-Techniques

https://github.com/ifconfig-me/SQL_Injection-Techniques
<blockquote>
Advanced SQL Injection Techniques for Bug Bounty Hunters
</blockquote>

<table><tr>
<tr><td>Owner: <code>ifconfig-me</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2024-07-23 17:24:22+00:00</code></td>
    <td>Latest: <code>2025-02-10 23:30:03+03:00</code></td></tr>
<tr><td>Commits: <code>13</code></td>
    <td>Stargazers: <code>127</code></td>
    <td>Watchers: <code>127</code></td>
    <td>Forks: <code>75</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# Alfie

https://github.com/4wayhandshake/Alfie
<blockquote>
Automatic Local File Inclusion Enumerator. Scan websites for LFI vulnerabilities and path traversals.
</blockquote>

<table><tr>
<tr><td>Owner: <code>4wayhandshake</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-02-09 21:41:09+00:00</code></td>
    <td>Latest: <code>2025-02-10 02:34:02+02:00</code></td></tr>
<tr><td>Commits: <code>24</code></td>
    <td>Stargazers: <code>5</code></td>
    <td>Watchers: <code>5</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: path traversal vulnerability, local file inclusion

---

# GitHub search -> Windows integer
# ibm-sterling-b2b-integrator-poc

https://github.com/ReversecLabs/ibm-sterling-b2b-integrator-poc
<blockquote>
PoC code for the LPE and RCE (CVE-2024-31903) attacks against the IBM Sterling B2B Integrator
</blockquote>

<table><tr>
<tr><td>Owner: <code>ReversecLabs</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2025-02-18 19:08:04+00:00</code></td>
    <td>Latest: <code>2025-02-02 14:52:48+00:00</code></td></tr>
<tr><td>Commits: <code>6</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lpe poc

---

# GitHub search -> Windows integer
# YG2

https://github.com/Yonicodedemon/YG2
<blockquote>
This repository contains a kernel exploit for PlayStation 4 firmware 6.72. The exploit leverages a vulnerability in the system kernel to achieve privilege escalation, allowing execution of unsigned code and jailbreak functionalities.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Yonicodedemon</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2025-01-31 12:45:01+00:00</code></td>
    <td>Latest: <code>2025-01-31 17:21:40+03:00</code></td></tr>
<tr><td>Commits: <code>27</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges exploit

---

# GitHub search -> Windows integer
# Integer-Overflow-in-Assembly-mov-Instruction-5aq3i

https://github.com/Bug-Hunter-X/Integer-Overflow-in-Assembly-mov-Instruction-5aq3i
<blockquote>
Integer overflow in assembly instruction leading to potential memory corruption or crash.  The mov instruction with an address calculation is vulnerable if the ecx register value is unexpectedly large.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Bug-Hunter-X</code></td>
    <td>Language: <code>Assembly</code></td>
    <td>Started: <code>2025-01-31 11:46:09+00:00</code></td>
    <td>Latest: <code>2025-01-31 12:46:11+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow vulnerability

---

# GitHub search -> Windows integer
# Collabfiltrator

https://github.com/0xC01DF00D/Collabfiltrator
<blockquote>
Exfiltrate blind Remote Code Execution and SQL injection output over DNS via Burp Collaborator.
</blockquote>

<table><tr>
<tr><td>Owner: <code>0xC01DF00D</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2020-03-16 09:49:41+00:00</code></td>
    <td>Latest: <code>2025-01-28 03:11:15-05:00</code></td></tr>
<tr><td>Commits: <code>32</code></td>
    <td>Stargazers: <code>267</code></td>
    <td>Watchers: <code>267</code></td>
    <td>Forks: <code>56</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# xsshunter

https://github.com/trufflesecurity/xsshunter
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>trufflesecurity</code></td>
    <td>Language: <code>SCSS</code></td>
    <td>Started: <code>2023-01-25 12:36:07+00:00</code></td>
    <td>Latest: <code>2025-01-22 15:35:19-08:00</code></td></tr>
<tr><td>Commits: <code>221</code></td>
    <td>Stargazers: <code>462</code></td>
    <td>Watchers: <code>462</code></td>
    <td>Forks: <code>127</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# Ada-Input-Validation-and-Exception-Handling-Bug-48kg9

https://github.com/Bug-Hunter-X/Ada-Input-Validation-and-Exception-Handling-Bug-48kg9
<blockquote>
Ada exception handling and input validation. The provided code lacks proper input validation, potentially leading to exceptions if the user enters non-numeric input.  The exception handler is too broad, masking the root cause of potential errors.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Bug-Hunter-X</code></td>
    <td>Language: <code>Ada</code></td>
    <td>Started: <code>2025-01-05 01:08:06+00:00</code></td>
    <td>Latest: <code>2025-01-05 02:08:07+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lack of input validation

---

# GitHub search -> Windows integer
# CVE_Database

https://github.com/justakazh/CVE_Database
<blockquote>
The Common Vulnerabilities Exposures (CVE) Database
</blockquote>

<table><tr>
<tr><td>Owner: <code>justakazh</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2023-07-05 05:32:02+00:00</code></td>
    <td>Latest: <code>2024-12-19 10:15:20-08:00</code></td></tr>
<tr><td>Commits: <code>4657</code></td>
    <td>Stargazers: <code>30</code></td>
    <td>Watchers: <code>30</code></td>
    <td>Forks: <code>12</code></td></tr>
</table>
Keywords: 0day vulnerability

---

# GitHub search -> Windows integer
# Robust-Input-Handling-in-Ada-vo0g8

https://github.com/Bug-Hunter-X/Robust-Input-Handling-in-Ada-vo0g8
<blockquote>
Ada exception handling and input validation. The original code lacks robust input validation, potentially leading to Constraint_Error exceptions if the user provides input outside the range of Integer.  The improved version adds explicit exception handling to gracefully manage such errors.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Bug-Hunter-X</code></td>
    <td>Language: <code>Ada</code></td>
    <td>Started: <code>2024-12-17 06:44:05+00:00</code></td>
    <td>Latest: <code>2024-12-17 07:44:08+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lack of input validation

---

# GitHub search -> Windows integer
# Stack-Overflow-in-Recursive-Hack-Function-y6u18

https://github.com/Bug-Hunter-X/Stack-Overflow-in-Recursive-Hack-Function-y6u18
<blockquote>
Stack Overflow Error in Hack recursive function due to lack of input validation and exceeding recursion depth.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Bug-Hunter-X</code></td>
    <td>Language: <code>Hack</code></td>
    <td>Started: <code>2024-12-14 19:02:06+00:00</code></td>
    <td>Latest: <code>2024-12-14 20:02:08+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lack of input validation

---

# GitHub search -> Windows integer
# lfi

https://github.com/TomerAberbach/lfi
<blockquote>
🦥 A lazy functional iteration library supporting sync, async, and concurrent iteration.
</blockquote>

<table><tr>
<tr><td>Owner: <code>TomerAberbach</code></td>
    <td>Language: <code>TypeScript</code></td>
    <td>Started: <code>2020-12-17 22:57:06+00:00</code></td>
    <td>Latest: <code>2024-12-13 00:12:02-05:00</code></td></tr>
<tr><td>Commits: <code>255</code></td>
    <td>Stargazers: <code>341</code></td>
    <td>Watchers: <code>341</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# numerical

https://github.com/bueler/numerical
<blockquote>
Webpage for Bueler's course in numerical analysis (MATH 426) at UAF.
</blockquote>

<table><tr>
<tr><td>Owner: <code>bueler</code></td>
    <td>Language: <code>TeX</code></td>
    <td>Started: <code>2024-08-14 22:37:31+00:00</code></td>
    <td>Latest: <code>2024-12-10 17:42:12-09:00</code></td></tr>
<tr><td>Commits: <code>241</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: uaf analysis

---

# GitHub search -> Windows integer
# Stack-Overflow-in-Recursive-Factorial-Function-10o1r

https://github.com/Bug-Hunter-X/Stack-Overflow-in-Recursive-Factorial-Function-10o1r
<blockquote>
Stack overflow error in recursive function due to lack of input validation and a missing base case for negative numbers. The program crashes when a large number or a negative number is passed as input.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Bug-Hunter-X</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2024-12-09 17:24:06+00:00</code></td>
    <td>Latest: <code>2024-12-09 18:24:08+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lack of input validation

---

# GitHub search -> Windows integer
# RCE_Static_Analysis_Tool

https://github.com/rcmcphee/RCE_Static_Analysis_Tool
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>rcmcphee</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-11-11 23:16:31+00:00</code></td>
    <td>Latest: <code>2024-12-02 10:03:57-05:00</code></td></tr>
<tr><td>Commits: <code>27</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: rce analysis

---

# GitHub search -> Windows integer
# BSQLinjector

https://github.com/enjoiz/BSQLinjector
<blockquote>
Blind SQL injection exploitation tool written in ruby.
</blockquote>

<table><tr>
<tr><td>Owner: <code>enjoiz</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2015-12-20 19:39:08+00:00</code></td>
    <td>Latest: <code>2024-12-01 16:26:21+01:00</code></td></tr>
<tr><td>Commits: <code>14</code></td>
    <td>Stargazers: <code>98</code></td>
    <td>Watchers: <code>98</code></td>
    <td>Forks: <code>27</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# XXEinjector

https://github.com/enjoiz/XXEinjector
<blockquote>
Tool for automatic exploitation of XXE vulnerability using direct and different out of band methods.
</blockquote>

<table><tr>
<tr><td>Owner: <code>enjoiz</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2015-05-16 10:56:14+00:00</code></td>
    <td>Latest: <code>2024-12-01 16:25:27+01:00</code></td></tr>
<tr><td>Commits: <code>56</code></td>
    <td>Stargazers: <code>1645</code></td>
    <td>Watchers: <code>1645</code></td>
    <td>Forks: <code>318</code></td></tr>
</table>
Keywords: xxe

---

# GitHub search -> Windows integer
# zero-day

https://github.com/EmilGallajov/zero-day
<blockquote>
This repo contains found vulnerabilities from open-source projects. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>EmilGallajov</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2024-11-02 13:32:37+00:00</code></td>
    <td>Latest: <code>2024-11-20 17:45:47+04:00</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: zero-day vulnerability

---

# GitHub search -> Windows integer
# WindowsPrivilegeEscalation

https://github.com/ycdxsb/WindowsPrivilegeEscalation
<blockquote>
Collection of Windows Privilege Escalation (Analyse/PoC/Exploit)
</blockquote>

<table><tr>
<tr><td>Owner: <code>ycdxsb</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2021-04-22 03:29:20+00:00</code></td>
    <td>Latest: <code>2024-11-19 21:39:12+08:00</code></td></tr>
<tr><td>Commits: <code>40</code></td>
    <td>Stargazers: <code>415</code></td>
    <td>Watchers: <code>415</code></td>
    <td>Forks: <code>78</code></td></tr>
</table>
Keywords: Win escalation of privileges poc, escalation of privileges poc, Win escalation of privileges, Windows escalation of privileges, Windows escalation of privileges poc, escalation of privileges exploit

---

# GitHub search -> Windows integer
# secure-ebook-platform

https://github.com/rafalgajos/secure-ebook-platform
<blockquote>
A web application built with Flask for managing e-books, focusing on securing against vulnerabilities like SQL Injection, XSS, CSRF, Session Hijacking, and File Upload attacks. Features a user interface based on the &amp;quot;Ebook Landing&amp;quot; template and various security mechanisms for safe usage.
</blockquote>

<table><tr>
<tr><td>Owner: <code>rafalgajos</code></td>
    <td>Language: <code>CSS</code></td>
    <td>Started: <code>2024-10-10 12:26:09+00:00</code></td>
    <td>Latest: <code>2024-10-28 14:49:56+01:00</code></td></tr>
<tr><td>Commits: <code>26</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session vulnerability

---

# GitHub search -> Windows integer
# enzyme

https://github.com/camila314/enzyme
<blockquote>
iOS jailbreak-free code injection framework. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>camila314</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-01-28 08:00:28+00:00</code></td>
    <td>Latest: <code>2024-10-21 18:04:57-05:00</code></td></tr>
<tr><td>Commits: <code>14</code></td>
    <td>Stargazers: <code>114</code></td>
    <td>Watchers: <code>114</code></td>
    <td>Forks: <code>18</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# 0days-in-the-wild

https://github.com/googleprojectzero/0days-in-the-wild
<blockquote>
Repository for information about 0-days exploited in-the-wild.
</blockquote>

<table><tr>
<tr><td>Owner: <code>googleprojectzero</code></td>
    <td>Language: <code>HTML</code></td>
    <td>Started: <code>2021-02-23 15:16:11+00:00</code></td>
    <td>Latest: <code>2024-10-17 06:04:00+00:00</code></td></tr>
<tr><td>Commits: <code>132</code></td>
    <td>Stargazers: <code>800</code></td>
    <td>Watchers: <code>800</code></td>
    <td>Forks: <code>79</code></td></tr>
</table>
Keywords: 0day exploitation, 0day exploit

---

# GitHub search -> Windows integer
# import-cli-simple

https://github.com/techdivision/import-cli-simple
<blockquote>
This the meta package for Pacemaker Community, a Symfony based CLI application that provides import functionality for products, categories, attributes, and attribute-sets. The default format is CSV, adapters for XML are also available. The application can be declaratively extended by additional operations, which can be used to reassemble and execute the existing functionalities according to project-specific requirements. But also completely new commands can be integrated quickly and easily via dependency injection.
</blockquote>

<table><tr>
<tr><td>Owner: <code>techdivision</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2016-12-09 16:26:31+00:00</code></td>
    <td>Latest: <code>2024-10-14 11:53:52+02:00</code></td></tr>
<tr><td>Commits: <code>1193</code></td>
    <td>Stargazers: <code>70</code></td>
    <td>Watchers: <code>70</code></td>
    <td>Forks: <code>17</code></td></tr>
</table>
Keywords: csv injection

---

# GitHub search -> Windows integer
# CVE-2024-38077

https://github.com/mrmtwoj/CVE-2024-38077
<blockquote>
CVE-2024-38077: Remote Code Execution Vulnerability in Windows Remote Desktop Licensing Service
</blockquote>

<table><tr>
<tr><td>Owner: <code>mrmtwoj</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-10-09 06:39:21+00:00</code></td>
    <td>Latest: <code>2024-10-09 10:12:25+03:30</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>15</code></td>
    <td>Watchers: <code>15</code></td>
    <td>Forks: <code>3</code></td></tr>
</table>
Keywords: remote code execution vulnerability, Windows remote code execution poc, remote code execution poc, Windows rce

---

# GitHub search -> Windows integer
# CVE-2024-47176

https://github.com/l0n3m4n/CVE-2024-47176
<blockquote>
Unauthenticated RCE on cups-browsed (exploit and nuclei template)
</blockquote>

<table><tr>
<tr><td>Owner: <code>l0n3m4n</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-10-03 15:53:04+00:00</code></td>
    <td>Latest: <code>2024-10-04 01:11:16+08:00</code></td></tr>
<tr><td>Commits: <code>16</code></td>
    <td>Stargazers: <code>13</code></td>
    <td>Watchers: <code>13</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: unauthenticated rce

---

# GitHub search -> Windows integer
# WindowsRCE

https://github.com/SleepTheGod/WindowsRCE
<blockquote>
RCE PoC For Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>SleepTheGod</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-09-10 05:10:28+00:00</code></td>
    <td>Latest: <code>2024-09-09 22:16:00-07:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows rce

---

# GitHub search -> Windows integer
# Zebra_Session

https://github.com/stefangabos/Zebra_Session
<blockquote>
A drop-in replacement for PHP's default session handler which stores session data in a MySQL database, providing better performance, better security and protection against session fixation and session hijacking
</blockquote>

<table><tr>
<tr><td>Owner: <code>stefangabos</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2013-08-03 12:04:16+00:00</code></td>
    <td>Latest: <code>2024-09-09 21:11:15+03:00</code></td></tr>
<tr><td>Commits: <code>215</code></td>
    <td>Stargazers: <code>174</code></td>
    <td>Watchers: <code>174</code></td>
    <td>Forks: <code>86</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# Major-project-list

https://github.com/ManojKumarPatnaik/Major-project-list
<blockquote>
A list of practical projects that anyone can solve in any programming language (See solutions). These projects are divided into multiple categories, and each category has its own folder.  To get started, simply fork this repo.  CONTRIBUTING See ways of contributing to this repo. You can contribute solutions (will be published in this repo) to existing problems, add new projects, or remove existing ones. Make sure you follow all instructions properly.  Solutions You can find implementations of these projects in many other languages by other users in this repo.  Credits  Problems are motivated by the ones shared at:  Martyr2’s Mega Project List Rosetta Code Table of Contents Numbers Classic Algorithms Graph Data Structures Text Networking Classes Threading Web Files Databases Graphics and Multimedia Security Numbers Find PI to the Nth Digit - Enter a number and have the program generate PI up to that many decimal places. Keep a limit to how far the program will go.  Find e to the Nth Dig...
</blockquote>

<table><tr>
<tr><td>Owner: <code>ManojKumarPatnaik</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2021-09-04 11:17:44+00:00</code></td>
    <td>Latest: <code>2024-09-07 20:52:27+05:30</code></td></tr>
<tr><td>Commits: <code>12</code></td>
    <td>Stargazers: <code>164</code></td>
    <td>Watchers: <code>164</code></td>
    <td>Forks: <code>34</code></td></tr>
</table>
Keywords: Windows zero-day analysis, zero-day analysis, path traversal attack, Windows zero-day, directory traversal attack

---

# GitHub search -> Windows integer
# CVE-2024-38063

https://github.com/ynwarcs/CVE-2024-38063
<blockquote>
poc for CVE-2024-38063 (RCE in tcpip.sys)
</blockquote>

<table><tr>
<tr><td>Owner: <code>ynwarcs</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-08-24 18:25:46+00:00</code></td>
    <td>Latest: <code>2024-08-27 14:22:39+02:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>673</code></td>
    <td>Watchers: <code>673</code></td>
    <td>Forks: <code>121</code></td></tr>
</table>
Keywords: rce poc

---

# GitHub search -> Windows integer
# Microsoft.iOS.AVSemanticSegmentationMatte-memoryleak

https://github.com/MLB-BIOMETRIC/Microsoft.iOS.AVSemanticSegmentationMatte-memoryleak
<blockquote>
Reproducable memory leak
</blockquote>

<table><tr>
<tr><td>Owner: <code>MLB-BIOMETRIC</code></td>
    <td>Language: <code>C#</code></td>
    <td>Started: <code>2023-11-22 12:15:20+00:00</code></td>
    <td>Latest: <code>2024-08-19 13:26:50+02:00</code></td></tr>
<tr><td>Commits: <code>18</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Microsoft memory leak

---

# GitHub search -> Windows integer
# crun-evaluation-guide

https://github.com/iarsystems/crun-evaluation-guide
<blockquote>
Evaluation Guide for the IAR C-RUN - Runtime Analysis Tool
</blockquote>

<table><tr>
<tr><td>Owner: <code>iarsystems</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2023-03-08 07:01:56+00:00</code></td>
    <td>Latest: <code>2024-08-09 09:18:18+02:00</code></td></tr>
<tr><td>Commits: <code>32</code></td>
    <td>Stargazers: <code>4</code></td>
    <td>Watchers: <code>4</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: memory leak analysis

---

# GitHub search -> Windows integer
# WhatsApp-Exploit

https://github.com/SaumyajeetDas/WhatsApp-Exploit
<blockquote>
1-Click RCE via WhatsApp For Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>SaumyajeetDas</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2024-07-27 17:47:56+00:00</code></td>
    <td>Latest: <code>2024-07-28 00:35:24+05:30</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>7</code></td>
    <td>Watchers: <code>7</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: Windows rce

---

# GitHub search -> Windows integer
# CVE-2024-36991

https://github.com/sardine-web/CVE-2024-36991
<blockquote>
Path traversal vulnerability in Splunk Enterprise on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>sardine-web</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2024-07-06 17:15:39+00:00</code></td>
    <td>Latest: <code>2024-07-06 20:54:11+03:30</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: path traversal vulnerability

---

# GitHub search -> Windows integer
# java-sec-code

https://github.com/JoyChou93/java-sec-code
<blockquote>
Java web common vulnerabilities and security code which is base on springboot and spring security
</blockquote>

<table><tr>
<tr><td>Owner: <code>JoyChou93</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2017-12-26 06:54:35+00:00</code></td>
    <td>Latest: <code>2024-06-28 09:52:04+08:00</code></td></tr>
<tr><td>Commits: <code>162</code></td>
    <td>Stargazers: <code>2533</code></td>
    <td>Watchers: <code>2533</code></td>
    <td>Forks: <code>691</code></td></tr>
</table>
Keywords: rce vulnerability, xxe, ssrf

---

# GitHub search -> Windows integer
# memleak

https://github.com/zivgates/memleak
<blockquote>
Simple CLI Memory Leak Simulator for Microsoft Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>zivgates</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2024-06-18 00:08:30+00:00</code></td>
    <td>Latest: <code>2024-06-17 20:38:46-05:00</code></td></tr>
<tr><td>Commits: <code>7</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows memory leak

---

# GitHub search -> Windows integer
# purejin

https://github.com/jbee/purejin
<blockquote>
java dependency injection through code 
</blockquote>

<table><tr>
<tr><td>Owner: <code>jbee</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2012-04-22 13:57:50+00:00</code></td>
    <td>Latest: <code>2024-05-29 11:30:50+02:00</code></td></tr>
<tr><td>Commits: <code>863</code></td>
    <td>Stargazers: <code>86</code></td>
    <td>Watchers: <code>86</code></td>
    <td>Forks: <code>9</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# exploits

https://github.com/vs4vijay/exploits
<blockquote>
Exploits R&amp;amp;D
</blockquote>

<table><tr>
<tr><td>Owner: <code>vs4vijay</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2014-04-10 10:33:20+00:00</code></td>
    <td>Latest: <code>2024-05-25 19:50:17+00:00</code></td></tr>
<tr><td>Commits: <code>13274</code></td>
    <td>Stargazers: <code>20</code></td>
    <td>Watchers: <code>20</code></td>
    <td>Forks: <code>10</code></td></tr>
</table>
Keywords: lpe exploit

---

# GitHub search -> Windows integer
# apostille

https://github.com/sensepost/apostille
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>sensepost</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2017-10-16 12:58:56+00:00</code></td>
    <td>Latest: <code>2024-05-23 22:09:05+02:00</code></td></tr>
<tr><td>Commits: <code>29</code></td>
    <td>Stargazers: <code>73</code></td>
    <td>Watchers: <code>73</code></td>
    <td>Forks: <code>21</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# Trophies

https://github.com/Halcy0nic/Trophies
<blockquote>
Trophy list of zero-day vulnerabilities that I discovered
</blockquote>

<table><tr>
<tr><td>Owner: <code>Halcy0nic</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2022-07-01 14:32:22+00:00</code></td>
    <td>Latest: <code>2024-05-06 07:39:20-06:00</code></td></tr>
<tr><td>Commits: <code>141</code></td>
    <td>Stargazers: <code>11</code></td>
    <td>Watchers: <code>11</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: zero-day vulnerability

---

# GitHub search -> Windows integer
# Kamek

https://github.com/Treeki/Kamek
<blockquote>
a nice code injection engine for Wii games
</blockquote>

<table><tr>
<tr><td>Owner: <code>Treeki</code></td>
    <td>Language: <code>C#</code></td>
    <td>Started: <code>2015-06-29 01:23:07+00:00</code></td>
    <td>Latest: <code>2024-04-21 04:47:29-04:00</code></td></tr>
<tr><td>Commits: <code>79</code></td>
    <td>Stargazers: <code>81</code></td>
    <td>Watchers: <code>81</code></td>
    <td>Forks: <code>13</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# Memory-Leakage-Analysis-Tool

https://github.com/tanmay1155/Memory-Leakage-Analysis-Tool
<blockquote>
Memory Leakage Analysis Tool by go language
</blockquote>

<table><tr>
<tr><td>Owner: <code>tanmay1155</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2024-04-11 15:56:27+00:00</code></td>
    <td>Latest: <code>2024-04-11 21:54:44+05:30</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: memory leak analysis

---

# GitHub search -> Windows integer
# portal

https://github.com/skr0x1c0/portal
<blockquote>
LPE vulnerability in macOS
</blockquote>

<table><tr>
<tr><td>Owner: <code>skr0x1c0</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2022-07-21 14:15:03+00:00</code></td>
    <td>Latest: <code>2024-03-25 12:29:36+05:30</code></td></tr>
<tr><td>Commits: <code>63</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: lpe vulnerability

---

# GitHub search -> Windows integer
# assless-chaps

https://github.com/sensepost/assless-chaps
<blockquote>
Crack MSCHAPv2 challenge/responses quickly using a database of NT hashes
</blockquote>

<table><tr>
<tr><td>Owner: <code>sensepost</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2021-05-17 07:27:57+00:00</code></td>
    <td>Latest: <code>2024-03-19 13:59:18+02:00</code></td></tr>
<tr><td>Commits: <code>37</code></td>
    <td>Stargazers: <code>133</code></td>
    <td>Watchers: <code>133</code></td>
    <td>Forks: <code>18</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# ManageEngineRCE

https://github.com/tw0point/ManageEngineRCE
<blockquote>
ManageEngine Application Manager 12 suffers from a blind SQLi vulnerability that may be used to gain unauthenticated remote code execution.
</blockquote>

<table><tr>
<tr><td>Owner: <code>tw0point</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-02-25 23:16:18+00:00</code></td>
    <td>Latest: <code>2024-03-07 18:34:07-05:00</code></td></tr>
<tr><td>Commits: <code>14</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: unauthenticated remote code execution, unauthenticated rce

---

# GitHub search -> Windows integer
# Day--5-For-Loop-Range-and-Code-Project

https://github.com/Keshab0310/Day--5-For-Loop-Range-and-Code-Project
<blockquote>
This is my Day-5 of learning Python. Here I have learned about For loop and how to use the loop to run in range of numbers as well as I have solve 1 leetcode problem. Similarly the final project contains the code to generate the random password which is basically in easy and in hard level.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Keshab0310</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-03-01 23:09:54+00:00</code></td>
    <td>Latest: <code>2024-03-01 18:13:32-05:00</code></td></tr>
<tr><td>Commits: <code>7</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# not-secure

https://github.com/itay601/not-secure
<blockquote>
sql injection ,stored XSS -cross side scripting 
</blockquote>

<table><tr>
<tr><td>Owner: <code>itay601</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-02-29 16:55:00+00:00</code></td>
    <td>Latest: <code>2024-03-01 12:12:42+02:00</code></td></tr>
<tr><td>Commits: <code>50</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: cross-side-scripting

---

# GitHub search -> Windows integer
# Axiell-thesauri

https://github.com/cultureelerfgoed/Axiell-thesauri
<blockquote>
Data analysis of Axiell thesauri RCE (B&amp;amp;AC and KC)
</blockquote>

<table><tr>
<tr><td>Owner: <code>cultureelerfgoed</code></td>
    <td>Language: <code>R</code></td>
    <td>Started: <code>2023-09-29 12:40:39+00:00</code></td>
    <td>Latest: <code>2024-02-29 16:31:27+01:00</code></td></tr>
<tr><td>Commits: <code>36</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: rce analysis

---

# GitHub search -> Windows integer
# tn-tame-session-defaults

https://github.com/timnashcouk/tn-tame-session-defaults
<blockquote>
Taming your WordPress user sessions, to help reduce the chance of session hijacking
</blockquote>

<table><tr>
<tr><td>Owner: <code>timnashcouk</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2024-02-06 20:02:47+00:00</code></td>
    <td>Latest: <code>2024-02-17 21:28:15+00:00</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>7</code></td>
    <td>Watchers: <code>7</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# CVE-2023-24317

https://github.com/angelopioamirante/CVE-2023-24317
<blockquote>
Judging Management System v1.0 - Unrestricted File Upload + RCE (Unauthenticated)
</blockquote>

<table><tr>
<tr><td>Owner: <code>angelopioamirante</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-03-08 22:00:44+00:00</code></td>
    <td>Latest: <code>2024-01-22 11:17:43+01:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: unrestricted file upload, unauthenticated rce

---

# GitHub search -> Windows integer
# ESP32-UART_RCE

https://github.com/Jayers0/ESP32-UART_RCE
<blockquote>
Research work on implementing RCE in micro-python as proof of concept for research with Dr Sass
</blockquote>

<table><tr>
<tr><td>Owner: <code>Jayers0</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2024-01-14 09:39:22+00:00</code></td>
    <td>Latest: <code>2024-01-14 04:58:46-05:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: rce proof of concept

---

# GitHub search -> Windows integer
# BootloaderSpoofer

https://github.com/chiteroman/BootloaderSpoofer
<blockquote>
Spoof locked bootloader on local attestations
</blockquote>

<table><tr>
<tr><td>Owner: <code>chiteroman</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2023-09-18 15:12:07+00:00</code></td>
    <td>Latest: <code>2024-01-02 21:57:34+01:00</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>893</code></td>
    <td>Watchers: <code>893</code></td>
    <td>Forks: <code>94</code></td></tr>
</table>
Keywords: spoofing certificate

---

# GitHub search -> Windows integer
# scan4all

https://github.com/GhostTroops/scan4all
<blockquote>
Official repository  vuls Scan: 15000+PoCs; 23 kinds of application password crack; 7000+Web fingerprints; 146 protocols and 90000+ rules Port scanning; Fuzz, HW, awesome BugBounty( ͡° ͜ʖ ͡°)...
</blockquote>

<table><tr>
<tr><td>Owner: <code>GhostTroops</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2022-06-20 03:11:08+00:00</code></td>
    <td>Latest: <code>2023-12-21 22:03:12+08:00</code></td></tr>
<tr><td>Commits: <code>1152</code></td>
    <td>Stargazers: <code>5719</code></td>
    <td>Watchers: <code>5719</code></td>
    <td>Forks: <code>683</code></td></tr>
</table>
Keywords: 0day poc

---

# GitHub search -> Windows integer
# quarkus-memory-leak-analysis

https://github.com/a-simoes/quarkus-memory-leak-analysis
<blockquote>
A memory leak analysis
</blockquote>

<table><tr>
<tr><td>Owner: <code>a-simoes</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2021-04-02 14:42:52+00:00</code></td>
    <td>Latest: <code>2023-10-29 18:02:40+00:00</code></td></tr>
<tr><td>Commits: <code>14</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: memory leak analysis

---

# GitHub search -> Windows integer
# CVE-2023-44487

https://github.com/studiogangster/CVE-2023-44487
<blockquote>
A python based exploit to test out rapid reset attack (CVE-2023-44487)
</blockquote>

<table><tr>
<tr><td>Owner: <code>studiogangster</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-10-16 11:07:50+00:00</code></td>
    <td>Latest: <code>2023-10-16 18:02:50+05:30</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>19</code></td>
    <td>Watchers: <code>19</code></td>
    <td>Forks: <code>3</code></td></tr>
</table>
Keywords: zero-day exploit, zero-day exploitation

---

# GitHub search -> Windows integer
# Awesome-RCE-techniques

https://github.com/p0dalirius/Awesome-RCE-techniques
<blockquote>
Awesome list of step by step techniques  to achieve Remote Code Execution on various apps!
</blockquote>

<table><tr>
<tr><td>Owner: <code>p0dalirius</code></td>
    <td>Language: <code>Dockerfile</code></td>
    <td>Started: <code>2022-04-05 06:49:03+00:00</code></td>
    <td>Latest: <code>2023-10-07 10:54:45+02:00</code></td></tr>
<tr><td>Commits: <code>83</code></td>
    <td>Stargazers: <code>1905</code></td>
    <td>Watchers: <code>1905</code></td>
    <td>Forks: <code>223</code></td></tr>
</table>
Keywords: rce exploit, remote code execution exploit

---

# GitHub search -> Windows integer
# SmartBridgeTeam-2.4

https://github.com/prasannakumar227/SmartBridgeTeam-2.4
<blockquote>
This paper discusses the vulnerabilities and risks associated with session management in network security, particularly session hijacking. The project aimed to explore the techniques and countermeasures related to session hijacking to raise awareness and promote better security practices.
</blockquote>

<table><tr>
<tr><td>Owner: <code>prasannakumar227</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-07-25 14:43:08+00:00</code></td>
    <td>Latest: <code>2023-09-26 01:49:21+05:30</code></td></tr>
<tr><td>Commits: <code>64</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session hijacking vulnerability, session vulnerability

---

# GitHub search -> Windows integer
# godnslog

https://github.com/chennqqi/godnslog
<blockquote>
An exquisite dns&amp;amp;http log server for verify SSRF/XXE/RFI/RCE vulnerability 
</blockquote>

<table><tr>
<tr><td>Owner: <code>chennqqi</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2020-08-13 02:18:11+00:00</code></td>
    <td>Latest: <code>2023-09-16 22:39:13+08:00</code></td></tr>
<tr><td>Commits: <code>55</code></td>
    <td>Stargazers: <code>471</code></td>
    <td>Watchers: <code>471</code></td>
    <td>Forks: <code>75</code></td></tr>
</table>
Keywords: rce vulnerability, xxe, ssrf

---

# GitHub search -> Windows integer
# 0dayNotice

https://github.com/OverPotter/0dayNotice
<blockquote>
You can receive notifications about new exploits.
</blockquote>

<table><tr>
<tr><td>Owner: <code>OverPotter</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-01-10 19:03:04+00:00</code></td>
    <td>Latest: <code>2023-09-11 14:49:43+03:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: 0day exploitation

---

# GitHub search -> Windows integer
# GDA-android-reversing-Tool

https://github.com/charles2gan/GDA-android-reversing-Tool
<blockquote>
the fastest and most powerful android decompiler(native tool working without Java VM) for the APK, DEX, ODEX, OAT, JAR, AAR, and CLASS file. which supports malicious behavior detection, privacy leaking detection, vulnerability detection, path solving, packer identification, variable tracking, deobfuscation, python&amp;amp;java scripts, device memory extraction, data decryption, and encryption, etc. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>charles2gan</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2017-10-31 08:18:29+00:00</code></td>
    <td>Latest: <code>2023-09-11 12:59:51+08:00</code></td></tr>
<tr><td>Commits: <code>250</code></td>
    <td>Stargazers: <code>4481</code></td>
    <td>Watchers: <code>4481</code></td>
    <td>Forks: <code>544</code></td></tr>
</table>
Keywords: memory leak vulnerability

---

# GitHub search -> Windows integer
# wp-mu-plugin-anti-brute-squad

https://github.com/dashifen/wp-mu-plugin-anti-brute-squad
<blockquote>
A WordPress MU plugin that prevents brute force attacks by limiting the number of failed login attempts during a browser session.
</blockquote>

<table><tr>
<tr><td>Owner: <code>dashifen</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2020-04-03 20:48:14+00:00</code></td>
    <td>Latest: <code>2023-09-02 11:50:18-04:00</code></td></tr>
<tr><td>Commits: <code>18</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session attack

---

# GitHub search -> Windows integer
# go4Hacker

https://github.com/GhostTroops/go4Hacker
<blockquote>
Automated penetration and auxiliary systems, providing XSS, XXE, DNS log, SSRF, RCE, web netcat and other Servers,gin-vue-admin，online https://51pwn.com
</blockquote>

<table><tr>
<tr><td>Owner: <code>GhostTroops</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2022-03-20 02:50:02+00:00</code></td>
    <td>Latest: <code>2023-08-30 16:43:21+08:00</code></td></tr>
<tr><td>Commits: <code>49</code></td>
    <td>Stargazers: <code>148</code></td>
    <td>Watchers: <code>148</code></td>
    <td>Forks: <code>25</code></td></tr>
</table>
Keywords: xxe

---

# GitHub search -> Windows integer
# pghostile

https://github.com/Aiven-Open/pghostile
<blockquote>
Pghostile is a tool to automate the exploitation of PostgreSQL® specific vulnerabilities that could lead to privilege escalation. It can be used to identify security issues in PostgreSQL extensions, to test system hardening and for security research in general.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Aiven-Open</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2022-07-11 11:39:53+00:00</code></td>
    <td>Latest: <code>2023-08-17 11:21:11+02:00</code></td></tr>
<tr><td>Commits: <code>40</code></td>
    <td>Stargazers: <code>12</code></td>
    <td>Watchers: <code>12</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: escalation of privileges exploitation, escalation of privileges vulnerability, escalation of privileges exploit

---

# GitHub search -> Windows integer
# Java-Flight-Recorder-Showcase

https://github.com/AndreTh0mas/Java-Flight-Recorder-Showcase
<blockquote>
Flight recorder Analysis: Contains 5 applications comprising of Latency, HotMethods detection, Memory leak etc.
</blockquote>

<table><tr>
<tr><td>Owner: <code>AndreTh0mas</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2023-07-10 08:51:11+00:00</code></td>
    <td>Latest: <code>2023-08-04 16:27:34+05:30</code></td></tr>
<tr><td>Commits: <code>34</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: memory leak analysis

---

# GitHub search -> Windows integer
# Mass-CVE-2023-28121

https://github.com/im-hanzou/Mass-CVE-2023-28121
<blockquote>
CVE-2023-28121 -  WooCommerce Payments &amp;lt; 5.6.2 - Unauthenticated Privilege Escalation [ Mass Add Admin User ]  
</blockquote>

<table><tr>
<tr><td>Owner: <code>im-hanzou</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-07-12 02:41:26+00:00</code></td>
    <td>Latest: <code>2023-07-15 04:47:59+07:00</code></td></tr>
<tr><td>Commits: <code>22</code></td>
    <td>Stargazers: <code>11</code></td>
    <td>Watchers: <code>11</code></td>
    <td>Forks: <code>3</code></td></tr>
</table>
Keywords: unauthenticated user

---

# GitHub search -> Windows integer
# gd-rce

https://github.com/meltah/gd-rce
<blockquote>
A remote code execution exploit for Geometry Dash 2.1
</blockquote>

<table><tr>
<tr><td>Owner: <code>meltah</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-06-22 14:06:42+00:00</code></td>
    <td>Latest: <code>2023-07-07 19:18:36+03:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>30</code></td>
    <td>Watchers: <code>30</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: remote code execution exploitation, remote code execution exploit

---

# GitHub search -> Windows integer
# Exploit-Development

https://github.com/VoidSec/Exploit-Development
<blockquote>
Exploit Development - Weaponized Exploit and Proof of Concepts (PoC) 
</blockquote>

<table><tr>
<tr><td>Owner: <code>VoidSec</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-04-11 08:47:31+00:00</code></td>
    <td>Latest: <code>2023-06-22 22:49:44+02:00</code></td></tr>
<tr><td>Commits: <code>76</code></td>
    <td>Stargazers: <code>222</code></td>
    <td>Watchers: <code>222</code></td>
    <td>Forks: <code>51</code></td></tr>
</table>
Keywords: Windows rce exploitation, rce poc, Windows lpe poc, Windows lpe exploit, Windows rce poc, rce exploit, 0day poc, Windows rce, Windows lpe, 0day proof of concept, lpe poc, Windows 0day exploit, rce exploitation, 0day exploitation, Windows rce proof of concept, Windows lpe exploitation, lpe exploit, Windows 0day proof of concept, Windows 0day exploitation, Windows 0day poc, Windows 0day, lpe proof of concept, 0day exploit, rce proof of concept, Windows lpe proof of concept, Windows rce exploit, lpe exploitation

---

# GitHub search -> Windows integer
# ssrfproxy-node

https://github.com/henryoswald/ssrfproxy-node
<blockquote>
node package to use ssrfproxy.com for protection against server side request forgery
</blockquote>

<table><tr>
<tr><td>Owner: <code>henryoswald</code></td>
    <td>Language: <code>TypeScript</code></td>
    <td>Started: <code>2023-06-13 12:19:20+00:00</code></td>
    <td>Latest: <code>2023-06-14 10:53:29+01:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: server side request forgery

---

# GitHub search -> Windows integer
# CVE-2023-32353-PoC

https://github.com/86x/CVE-2023-32353-PoC
<blockquote>
Proof of Concept Code for CVE-2023-32353: Local privilege escalation via iTunes in Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>86x</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2023-06-08 20:43:03+00:00</code></td>
    <td>Latest: <code>2023-06-09 09:33:36+02:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>35</code></td>
    <td>Watchers: <code>35</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: escalation of privileges proof of concept, escalation of privileges poc, Windows escalation of privileges, Windows escalation of privileges proof of concept, Windows escalation of privileges poc

---

# GitHub search -> Windows integer
# CVE-2023-25157

https://github.com/win3zz/CVE-2023-25157
<blockquote>
CVE-2023-25157 - GeoServer SQL Injection - PoC
</blockquote>

<table><tr>
<tr><td>Owner: <code>win3zz</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-06-06 14:05:09+00:00</code></td>
    <td>Latest: <code>2023-06-08 14:35:21+05:30</code></td></tr>
<tr><td>Commits: <code>7</code></td>
    <td>Stargazers: <code>169</code></td>
    <td>Watchers: <code>169</code></td>
    <td>Forks: <code>34</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# revsuit

https://github.com/Li4n0/revsuit
<blockquote>
RevSuit is a flexible and powerful reverse connection platform designed for receiving connection from target host in penetration. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>Li4n0</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2021-04-21 10:39:44+00:00</code></td>
    <td>Latest: <code>2023-06-02 00:36:44+08:00</code></td></tr>
<tr><td>Commits: <code>102</code></td>
    <td>Stargazers: <code>545</code></td>
    <td>Watchers: <code>545</code></td>
    <td>Forks: <code>67</code></td></tr>
</table>
Keywords: xxe, ssrf

---

# GitHub search -> Windows integer
# EMITRACK

https://github.com/Raptor287/EMITRACK
<blockquote>
UAF Physics Capstone Project EMITRACK - Electromagnetic Wave-Meteor Interaction Tracking, Analysis, and Recording Kit
</blockquote>

<table><tr>
<tr><td>Owner: <code>Raptor287</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-02-06 21:48:18+00:00</code></td>
    <td>Latest: <code>2023-05-30 22:35:10-07:00</code></td></tr>
<tr><td>Commits: <code>57</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: uaf analysis

---

# GitHub search -> Windows integer
# the-road-to-zero

https://github.com/faisalmemon/the-road-to-zero
<blockquote>
How to develop your own zero day vulnerabilities for iOS
</blockquote>

<table><tr>
<tr><td>Owner: <code>faisalmemon</code></td>
    <td>Language: <code>TeX</code></td>
    <td>Started: <code>2021-03-27 11:17:28+00:00</code></td>
    <td>Latest: <code>2023-05-20 09:44:26+01:00</code></td></tr>
<tr><td>Commits: <code>392</code></td>
    <td>Stargazers: <code>29</code></td>
    <td>Watchers: <code>29</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: zero-day vulnerability

---

# GitHub search -> Windows integer
# GregsBestFriend

https://github.com/WKL-Sec/GregsBestFriend
<blockquote>
GregsBestFriend process injection code created from the White Knight Labs Offensive Development course
</blockquote>

<table><tr>
<tr><td>Owner: <code>WKL-Sec</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2023-04-30 23:58:52+00:00</code></td>
    <td>Latest: <code>2023-05-01 07:08:58-04:00</code></td></tr>
<tr><td>Commits: <code>34</code></td>
    <td>Stargazers: <code>193</code></td>
    <td>Watchers: <code>193</code></td>
    <td>Forks: <code>35</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# springshell-rce-poc

https://github.com/DDuarte/springshell-rce-poc
<blockquote>
CVE-2022-22965 - CVE-2010-1622 redux
</blockquote>

<table><tr>
<tr><td>Owner: <code>DDuarte</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2022-03-31 08:06:46+00:00</code></td>
    <td>Latest: <code>2023-04-18 13:54:56+00:00</code></td></tr>
<tr><td>Commits: <code>22</code></td>
    <td>Stargazers: <code>19</code></td>
    <td>Watchers: <code>19</code></td>
    <td>Forks: <code>12</code></td></tr>
</table>
Keywords: rce poc

---

# GitHub search -> Windows integer
# go-sec-code

https://github.com/cokeBeer/go-sec-code
<blockquote>
Go-sec-code is a  project for learning Go vulnerability code.
</blockquote>

<table><tr>
<tr><td>Owner: <code>cokeBeer</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2022-04-10 05:38:57+00:00</code></td>
    <td>Latest: <code>2023-03-11 22:28:31+08:00</code></td></tr>
<tr><td>Commits: <code>30</code></td>
    <td>Stargazers: <code>41</code></td>
    <td>Watchers: <code>41</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: xxe

---

# GitHub search -> Windows integer
# bluscreenofjeff.github.io

https://github.com/bluscreenofjeff/bluscreenofjeff.github.io
<blockquote>
My information security blog
</blockquote>

<table><tr>
<tr><td>Owner: <code>bluscreenofjeff</code></td>
    <td>Language: <code>HTML</code></td>
    <td>Started: <code>2015-04-03 02:05:07+00:00</code></td>
    <td>Latest: <code>2023-03-09 12:51:36-08:00</code></td></tr>
<tr><td>Commits: <code>219</code></td>
    <td>Stargazers: <code>7</code></td>
    <td>Watchers: <code>7</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# xRCE-Windows

https://github.com/x10m/xRCE-Windows
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>x10m</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2023-02-24 15:51:26+00:00</code></td>
    <td>Latest: <code>2023-02-24 17:29:26+01:00</code></td></tr>
<tr><td>Commits: <code>12</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Win rce, Windows rce

---

# GitHub search -> Windows integer
# CVE-2023-0705

https://github.com/Live-Hack-CVE/CVE-2023-0705
<blockquote>
Integer overflow in Core in Google Chrome prior to 110.0.5481.77 allowed a remote attacker who had one a race condition to potentially exploit heap corruption via a crafted HTML page. (Chromium security severity: Low) CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2023-02-16 16:06:50+00:00</code></td>
    <td>Latest: <code>2023-02-16 17:06:53+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow exploitation

---

# GitHub search -> Windows integer
# lfito_rce

https://github.com/roughiz/lfito_rce
<blockquote>
LFI to RCE via phpinfo() assistance or via controlled log file
</blockquote>

<table><tr>
<tr><td>Owner: <code>roughiz</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2020-01-29 20:21:53+00:00</code></td>
    <td>Latest: <code>2023-02-08 19:37:59+01:00</code></td></tr>
<tr><td>Commits: <code>24</code></td>
    <td>Stargazers: <code>68</code></td>
    <td>Watchers: <code>68</code></td>
    <td>Forks: <code>12</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# CVE-2017-17854

https://github.com/Live-Hack-CVE/CVE-2017-17854
<blockquote>
kernel/bpf/verifier.c in the Linux kernel through 4.14.8 allows local users to cause a denial of service (integer overflow and memory corruption) or possibly have unspecified other impact by leveraging unrestricted integer values for pointer arithmetic. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2023-02-07 23:25:18+00:00</code></td>
    <td>Latest: <code>2023-02-08 00:25:20+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow denial of service

---

# GitHub search -> Windows integer
# CVE-2022-2329

https://github.com/Live-Hack-CVE/CVE-2022-2329
<blockquote>
A CWE-190: Integer Overflow or Wraparound vulnerability exists that could cause heap-based buffer overflow, leading to denial of service and potentially remote code execution when an attacker sends multiple specially crafted messages. Affected Products: IGSS Data Server - IGSSdataServer.exe (Versions prior to V15.0.0.2 CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2023-02-01 07:02:30+00:00</code></td>
    <td>Latest: <code>2023-02-01 08:02:32+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: remote code execution denial of service

---

# GitHub search -> Windows integer
# Log4j-Vulnerability

https://github.com/demining/Log4j-Vulnerability
<blockquote>
Vulnerability CVE-2021-44228 allows remote code execution without authentication for several versions of Apache Log4j2 (Log4Shell). Attackers can exploit vulnerable servers by connecting over any protocol, such as HTTPS, and sending a specially crafted string.
</blockquote>

<table><tr>
<tr><td>Owner: <code>demining</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2023-01-31 20:29:26+00:00</code></td>
    <td>Latest: <code>2023-01-31 23:35:59+03:00</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>6</code></td>
    <td>Watchers: <code>6</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: remote code execution vulnerability

---

# GitHub search -> Windows integer
# vertx-statichandler-windows-traversal-path-vulnerability

https://github.com/adrien-aubert-drovio/vertx-statichandler-windows-traversal-path-vulnerability
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>adrien-aubert-drovio</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2023-01-31 09:12:22+00:00</code></td>
    <td>Latest: <code>2023-01-31 10:33:50+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: path traversal vulnerability

---

# GitHub search -> Windows integer
# CVE-2016-3135

https://github.com/Live-Hack-CVE/CVE-2016-3135
<blockquote>
Integer overflow in the xt_alloc_table_info function in net/netfilter/x_tables.c in the Linux kernel through 4.5.2 on 32-bit platforms allows local users to gain privileges or cause a denial of service (heap memory corruption) via an IPT_SO_SET_REPLACE setsockopt call. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2023-01-17 23:40:55+00:00</code></td>
    <td>Latest: <code>2023-01-18 00:40:58+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow denial of service

---

# GitHub search -> Windows integer
# CVE-2022-32636

https://github.com/Live-Hack-CVE/CVE-2022-32636
<blockquote>
In keyinstall, there is a possible out of bounds write due to an integer overflow. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation. Patch ID: ALPS07510064; Issue ID: ALPS07510064. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2023-01-04 00:07:33+00:00</code></td>
    <td>Latest: <code>2023-01-04 01:07:36+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges exploitation

---

# GitHub search -> Windows integer
# CVE-2020-10722

https://github.com/Live-Hack-CVE/CVE-2020-10722
<blockquote>
A vulnerability was found in DPDK versions 18.05 and above. A missing check for an integer overflow in vhost_user_set_log_base() could result in a smaller memory map than requested, possibly allowing memory corruption. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 23:43:35+00:00</code></td>
    <td>Latest: <code>2022-12-30 00:43:37+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow vulnerability

---

# GitHub search -> Windows integer
# CVE-2021-21860

https://github.com/Live-Hack-CVE/CVE-2021-21860
<blockquote>
An exploitable integer truncation vulnerability exists within the MPEG-4 decoding functionality of the GPAC Project on Advanced Content library v1.0.1. A specially crafted MPEG-4 input can cause an improper memory allocation resulting in a heap-based buffer overflow that causes memory corruption. The FOURCC code, 'trik CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 23:05:12+00:00</code></td>
    <td>Latest: <code>2022-12-30 00:05:14+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow exploit, corruption overflow exploitation, corruption overflow vulnerability

---

# GitHub search -> Windows integer
# CVE-2022-26466

https://github.com/Live-Hack-CVE/CVE-2022-26466
<blockquote>
In audio ipi, there is a possible out of bounds write due to an integer overflow. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation. Patch ID: ALPS06558777; Issue ID: ALPS06558777. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 21:37:13+00:00</code></td>
    <td>Latest: <code>2022-12-29 22:37:15+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges exploitation

---

# GitHub search -> Windows integer
# CVE-2022-26454

https://github.com/Live-Hack-CVE/CVE-2022-26454
<blockquote>
In teei, there is a possible memory corruption due to an integer overflow. This could lead to local escalation of privilege with System execution privileges needed. User interaction is not needed for exploitation. Patch ID: ALPS06664701; Issue ID: ALPS06664701. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 21:36:01+00:00</code></td>
    <td>Latest: <code>2022-12-29 22:36:03+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow exploit, corruption overflow exploitation

---

# GitHub search -> Windows integer
# CVE-2014-0144

https://github.com/Live-Hack-CVE/CVE-2014-0144
<blockquote>
QEMU before 2.0.0 block drivers for CLOOP, QCOW2 version 2 and various other image formats are vulnerable to potential memory corruptions, integer/buffer overflows or crash caused by missing input validations which could allow a remote user to execute arbitrary code on the host with the privileges of the QEMU process. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 10:33:28+00:00</code></td>
    <td>Latest: <code>2022-12-29 11:33:30+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow vulnerability

---

# GitHub search -> Windows integer
# CVE-2021-32687

https://github.com/Live-Hack-CVE/CVE-2021-32687
<blockquote>
Redis is an open source, in-memory database that persists on disk. An integer overflow bug affecting all versions of Redis can be exploited to corrupt the heap and potentially be used to leak arbitrary contents of the heap or trigger remote code execution. The vulnerability involves changing the default set-max-intset- CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 09:05:21+00:00</code></td>
    <td>Latest: <code>2022-12-29 10:05:23+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: memory leak exploit, memory leak exploitation, memory leak vulnerability

---

# GitHub search -> Windows integer
# CVE-2019-5820

https://github.com/Live-Hack-CVE/CVE-2019-5820
<blockquote>
Integer overflow in PDFium in Google Chrome prior to 74.0.3729.108 allowed a remote attacker to potentially exploit heap corruption via a crafted PDF file. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 06:58:27+00:00</code></td>
    <td>Latest: <code>2022-12-29 07:58:29+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow exploit, Chrome corruption overflow, Chrome corruption overflow exploitation, corruption overflow exploitation, Chrome corruption overflow exploit

---

# GitHub search -> Windows integer
# CVE-2019-5789

https://github.com/Live-Hack-CVE/CVE-2019-5789
<blockquote>
An integer overflow that leads to a use-after-free in WebMIDI in Google Chrome on Windows prior to 73.0.3683.75 allowed a remote attacker who had compromised the renderer process to execute arbitrary code via a crafted HTML page. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 06:58:16+00:00</code></td>
    <td>Latest: <code>2022-12-29 07:58:18+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows use after free

---

# GitHub search -> Windows integer
# CVE-2019-5806

https://github.com/Live-Hack-CVE/CVE-2019-5806
<blockquote>
Integer overflow in ANGLE in Google Chrome on Windows prior to 74.0.3729.108 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 06:57:09+00:00</code></td>
    <td>Latest: <code>2022-12-29 07:57:12+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow exploit, Windows corruption overflow exploit, Chrome corruption overflow, Chrome corruption overflow exploitation, Windows corruption overflow exploitation, Windows corruption overflow, corruption overflow exploitation, Chrome corruption overflow exploit

---

# GitHub search -> Windows integer
# CVE-2019-9278

https://github.com/Live-Hack-CVE/CVE-2019-9278
<blockquote>
In libexif, there is a possible out of bounds write due to an integer overflow. This could lead to remote escalation of privilege in the media content provider with no additional execution privileges needed. User interaction is needed for exploitation. Product: AndroidVersions: Android-10Android ID: A-112537774 CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 04:20:41+00:00</code></td>
    <td>Latest: <code>2022-12-29 05:20:43+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges exploitation

---

# GitHub search -> Windows integer
# CVE-2022-28197

https://github.com/Live-Hack-CVE/CVE-2022-28197
<blockquote>
NVIDIA Jetson Linux Driver Package contains a vulnerability in the Cboot ext4_mount function, where Insufficient validation of untrusted data may allow a highly privileged local attacker to cause an integer overflow. This difficult-to-exploit vulnerability may lead to code execution, escalation of privileges, limited d CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 04:19:35+00:00</code></td>
    <td>Latest: <code>2022-12-29 05:19:36+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges vulnerability

---

# GitHub search -> Windows integer
# CVE-2022-28195

https://github.com/Live-Hack-CVE/CVE-2022-28195
<blockquote>
NVIDIA Jetson Linux Driver Package contains a vulnerability in the Cboot ext4_read_file function, where insufficient validation of untrusted data may allow a highly privileged local attacker to cause a integer overflow, which may lead to code execution, escalation of privileges, limited denial of service, and some impa CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 04:14:35+00:00</code></td>
    <td>Latest: <code>2022-12-29 05:14:38+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges denial of service, escalation of privileges vulnerability

---

# GitHub search -> Windows integer
# CVE-2022-1116

https://github.com/Live-Hack-CVE/CVE-2022-1116
<blockquote>
Integer Overflow or Wraparound vulnerability in io_uring of Linux Kernel allows local attacker to cause memory corruption and escalate privileges to root. This issue affects: Linux Kernel versions prior to 5.4.189; version 5.4.24 and later versions. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-29 02:05:27+00:00</code></td>
    <td>Latest: <code>2022-12-29 03:05:29+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow vulnerability

---

# GitHub search -> Windows integer
# CVE-2022-32775

https://github.com/Live-Hack-CVE/CVE-2022-32775
<blockquote>
An integer overflow vulnerability exists in the web interface /action/ipcamRecordPost functionality of Abode Systems, Inc. iota All-In-One Security Kit 6.9X and 6.9Z. A specially-crafted HTTP request can lead to memory corruption. An attacker can make an authenticated HTTP request to trigger this vulnerability. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-28 20:43:06+00:00</code></td>
    <td>Latest: <code>2022-12-28 21:43:09+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow vulnerability

---

# GitHub search -> Windows integer
# CVE-2021-41099

https://github.com/Live-Hack-CVE/CVE-2021-41099
<blockquote>
Redis is an open source, in-memory database that persists on disk. An integer overflow bug in the underlying string library can be used to corrupt the heap and potentially result with denial of service or remote code execution. The vulnerability involves changing the default proto-max-bulk-len configuration parameter t CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-28 17:03:12+00:00</code></td>
    <td>Latest: <code>2022-12-28 18:03:14+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: remote code execution denial of service

---

# GitHub search -> Windows integer
# CVE-2022-42533

https://github.com/Live-Hack-CVE/CVE-2022-42533
<blockquote>
In shared_metadata_init of SharedMetadata.cpp, there is a possible out of bounds write due to an integer overflow. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android kernelAndroid ID: A-239415 CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-28 05:24:00+00:00</code></td>
    <td>Latest: <code>2022-12-28 06:24:02+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges exploitation

---

# GitHub search -> Windows integer
# CVE-2016-0797

https://github.com/Live-Hack-CVE/CVE-2016-0797
<blockquote>
Multiple integer overflows in OpenSSL 1.0.1 before 1.0.1s and 1.0.2 before 1.0.2g allow remote attackers to cause a denial of service (heap memory corruption or NULL pointer dereference) or possibly have unspecified other impact via a long digit string that is mishandled by the (1) BN_dec2bn or (2) BN_hex2bn function,  CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-27 18:19:52+00:00</code></td>
    <td>Latest: <code>2022-12-27 19:19:53+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow denial of service

---

# GitHub search -> Windows integer
# CVE-2016-2105

https://github.com/Live-Hack-CVE/CVE-2016-2105
<blockquote>
Integer overflow in the EVP_EncodeUpdate function in crypto/evp/encode.c in OpenSSL before 1.0.1t and 1.0.2 before 1.0.2h allows remote attackers to cause a denial of service (heap memory corruption) via a large amount of binary data. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-27 18:18:29+00:00</code></td>
    <td>Latest: <code>2022-12-27 19:18:31+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow denial of service

---

# GitHub search -> Windows integer
# CVE-2016-2106

https://github.com/Live-Hack-CVE/CVE-2016-2106
<blockquote>
Integer overflow in the EVP_EncryptUpdate function in crypto/evp/evp_enc.c in OpenSSL before 1.0.1t and 1.0.2 before 1.0.2h allows remote attackers to cause a denial of service (heap memory corruption) via a large amount of data. CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-27 18:17:18+00:00</code></td>
    <td>Latest: <code>2022-12-27 19:17:21+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: corruption overflow denial of service

---

# GitHub search -> Windows integer
# CVE-2022-20598

https://github.com/Live-Hack-CVE/CVE-2022-20598
<blockquote>
In sec_media_protect of media.c, there is a possible EoP due to an integer overflow. This could lead to local escalation of privilege of secure mode MFC Core with no additional execution privileges needed. User interaction is not needed for exploitation.Product: AndroidVersions: Android kernelAndroid ID: A-242357514Ref CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-27 12:48:38+00:00</code></td>
    <td>Latest: <code>2022-12-27 13:48:40+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: escalation of privileges exploitation

---

# GitHub search -> Windows integer
# CVE-2022-42898

https://github.com/Live-Hack-CVE/CVE-2022-42898
<blockquote>
PAC parsing in MIT Kerberos 5 (aka krb5) before 1.19.4 and 1.20.x before 1.20.1 has integer overflows that may lead to remote code execution (in KDC, kadmind, or a GSS or Kerberos application server) on 32-bit platforms (which have a resultant heap-based buffer overflow), and cause a denial of service on other platform CVE project by @Sn0wAlice
</blockquote>

<table><tr>
<tr><td>Owner: <code>Live-Hack-CVE</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-12-27 09:14:34+00:00</code></td>
    <td>Latest: <code>2022-12-27 10:14:36+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: remote code execution denial of service

---

# GitHub search -> Windows integer
# Hacking-a-Bluetooth-Device

https://github.com/falcnix/Hacking-a-Bluetooth-Device
<blockquote>
This repository contains all the slides, code and APK required to simulate the attacks demonstrated in the Null Kolkata session. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>falcnix</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2022-12-09 16:37:01+00:00</code></td>
    <td>Latest: <code>2022-12-10 13:43:29+05:30</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>8</code></td>
    <td>Watchers: <code>8</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session attack

---

# GitHub search -> Windows integer
# DSIN

https://github.com/shenweichen/DSIN
<blockquote>
Code for the IJCAI'19 paper  &amp;quot;Deep Session Interest Network for Click-Through Rate Prediction&amp;quot;
</blockquote>

<table><tr>
<tr><td>Owner: <code>shenweichen</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-05-17 09:44:07+00:00</code></td>
    <td>Latest: <code>2022-11-11 13:11:13+00:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>445</code></td>
    <td>Watchers: <code>445</code></td>
    <td>Forks: <code>132</code></td></tr>
</table>
Keywords: session prediction

---

# GitHub search -> Windows integer
# Inject_Dylib

https://github.com/cedowens/Inject_Dylib
<blockquote>
Swift code to programmatically perform dylib injection
</blockquote>

<table><tr>
<tr><td>Owner: <code>cedowens</code></td>
    <td>Language: <code>Swift</code></td>
    <td>Started: <code>2022-01-02 17:19:43+00:00</code></td>
    <td>Latest: <code>2022-10-29 16:13:52-04:00</code></td></tr>
<tr><td>Commits: <code>13</code></td>
    <td>Stargazers: <code>51</code></td>
    <td>Watchers: <code>51</code></td>
    <td>Forks: <code>9</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# Swagger-EZ

https://github.com/RhinoSecurityLabs/Swagger-EZ
<blockquote>
A tool geared towards pentesting APIs using OpenAPI definitions.
</blockquote>

<table><tr>
<tr><td>Owner: <code>RhinoSecurityLabs</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2018-10-25 19:26:50+00:00</code></td>
    <td>Latest: <code>2022-10-27 08:33:37-07:00</code></td></tr>
<tr><td>Commits: <code>14</code></td>
    <td>Stargazers: <code>177</code></td>
    <td>Watchers: <code>177</code></td>
    <td>Forks: <code>42</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# Windows

https://github.com/Hack-with-Github/Windows
<blockquote>
Awesome tools to exploit Windows !
</blockquote>

<table><tr>
<tr><td>Owner: <code>Hack-with-Github</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2016-07-26 15:15:32+00:00</code></td>
    <td>Latest: <code>2022-10-27 11:02:43+00:00</code></td></tr>
<tr><td>Commits: <code>22</code></td>
    <td>Stargazers: <code>1119</code></td>
    <td>Watchers: <code>1119</code></td>
    <td>Forks: <code>386</code></td></tr>
</table>
Keywords: exploitation

---

# GitHub search -> Windows integer
# 0x1D

https://github.com/strawbberrys/0x1D
<blockquote>
Roblox Studio Remote Code Execution (RCE) Vulnerability
</blockquote>

<table><tr>
<tr><td>Owner: <code>strawbberrys</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-10-26 01:11:52+00:00</code></td>
    <td>Latest: <code>2022-10-25 19:19:07-05:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>4</code></td>
    <td>Watchers: <code>4</code></td>
    <td>Forks: <code>5</code></td></tr>
</table>
Keywords: rce vulnerability, remote code execution vulnerability

---

# GitHub search -> Windows integer
# cmstplua-uac-bypass

https://github.com/tijme/cmstplua-uac-bypass
<blockquote>
Cobalt Strike Beacon Object File for bypassing UAC via the CMSTPLUA COM interface.
</blockquote>

<table><tr>
<tr><td>Owner: <code>tijme</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2022-10-06 20:28:22+00:00</code></td>
    <td>Latest: <code>2022-10-09 17:14:03+02:00</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>185</code></td>
    <td>Watchers: <code>185</code></td>
    <td>Forks: <code>27</code></td></tr>
</table>
Keywords: uac bypass

---

# GitHub search -> Windows integer
# shm_win_patch

https://github.com/amsikking/shm_win_patch
<blockquote>
Fix a memory leak in SharedMemory on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>amsikking</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2022-09-27 19:25:29+00:00</code></td>
    <td>Latest: <code>2022-09-29 09:35:55-07:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: Windows memory leak, Win memory leak

---

# GitHub search -> Windows integer
# Advanced-SQL-Injection-Cheatsheet

https://github.com/kleiton0x00/Advanced-SQL-Injection-Cheatsheet
<blockquote>
A cheat sheet that contains advanced queries for SQL Injection of all types.
</blockquote>

<table><tr>
<tr><td>Owner: <code>kleiton0x00</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2020-10-23 18:14:47+00:00</code></td>
    <td>Latest: <code>2022-09-04 17:36:34+02:00</code></td></tr>
<tr><td>Commits: <code>110</code></td>
    <td>Stargazers: <code>3017</code></td>
    <td>Watchers: <code>3017</code></td>
    <td>Forks: <code>684</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# ds3-nrssr-rce

https://github.com/tremwil/ds3-nrssr-rce
<blockquote>
Documentation and proof of concept code for CVE-2022-24125 and CVE-2022-24126.
</blockquote>

<table><tr>
<tr><td>Owner: <code>tremwil</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2022-01-28 20:37:14+00:00</code></td>
    <td>Latest: <code>2022-08-29 22:11:05-04:00</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>156</code></td>
    <td>Watchers: <code>156</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: rce proof of concept, rce exploit

---

# GitHub search -> Windows integer
# Discount-Hardware-Key

https://github.com/elliot-huffman/Discount-Hardware-Key
<blockquote>
Use an Arduino Micro as a hard coded password type. Like the static password functionality of the Yubikey, but less secure.
</blockquote>

<table><tr>
<tr><td>Owner: <code>elliot-huffman</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2022-07-30 00:23:09+00:00</code></td>
    <td>Latest: <code>2022-07-29 17:36:48-07:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# Exploits

https://github.com/forrest-orr/Exploits
<blockquote>
A personal collection of Windows CVE I have turned in to exploit source, as well as a collection of payloads I've written to be used in conjunction with these exploits.
</blockquote>

<table><tr>
<tr><td>Owner: <code>forrest-orr</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2021-05-24 15:53:40+00:00</code></td>
    <td>Latest: <code>2022-07-21 03:01:37-07:00</code></td></tr>
<tr><td>Commits: <code>130</code></td>
    <td>Stargazers: <code>120</code></td>
    <td>Watchers: <code>120</code></td>
    <td>Forks: <code>14</code></td></tr>
</table>
Keywords: uaf poc, uaf exploit, Windows uaf, uaf exploitation, Windows uaf exploitation, Windows uaf exploit, Windows uaf poc

---

# GitHub search -> Windows integer
# Havij

https://github.com/rezaJOY/Havij
<blockquote>
Automated SQL Injection tool
</blockquote>

<table><tr>
<tr><td>Owner: <code>rezaJOY</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2021-07-28 14:14:56+00:00</code></td>
    <td>Latest: <code>2022-07-20 23:32:52+06:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>68</code></td>
    <td>Watchers: <code>68</code></td>
    <td>Forks: <code>13</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# randy

https://github.com/sourceincite/randy
<blockquote>
A pre-authenticated RCE exploit for Inductive Automation Ignition
</blockquote>

<table><tr>
<tr><td>Owner: <code>sourceincite</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2022-07-14 17:28:21+00:00</code></td>
    <td>Latest: <code>2022-07-18 11:12:27-05:00</code></td></tr>
<tr><td>Commits: <code>18</code></td>
    <td>Stargazers: <code>45</code></td>
    <td>Watchers: <code>45</code></td>
    <td>Forks: <code>9</code></td></tr>
</table>
Keywords: rce exploitation, rce exploit

---

# GitHub search -> Windows integer
# Follina-Generator

https://github.com/maxgestic/Follina-Generator
<blockquote>
A simple Follina RTF and DOCX generator
</blockquote>

<table><tr>
<tr><td>Owner: <code>maxgestic</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2022-06-17 09:37:33+00:00</code></td>
    <td>Latest: <code>2022-07-12 14:42:59+01:00</code></td></tr>
<tr><td>Commits: <code>24</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: Windows rce, Windows rce poc, Windows rce vulnerability, Windows rce exploit

---

# GitHub search -> Windows integer
# PHP-SecureSessions

https://github.com/onassar/PHP-SecureSessions
<blockquote>
Secure session class (with Memcached extension class) that uses sha256 to generate signatures, preventing session hijacking.
</blockquote>

<table><tr>
<tr><td>Owner: <code>onassar</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2011-08-24 23:14:21+00:00</code></td>
    <td>Latest: <code>2022-07-03 12:00:21-04:00</code></td></tr>
<tr><td>Commits: <code>37</code></td>
    <td>Stargazers: <code>8</code></td>
    <td>Watchers: <code>8</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# Log4Shell

https://github.com/o7-Fire/Log4Shell
<blockquote>
Log4Shell Zero-Day Exploit Proof of Concept
</blockquote>

<table><tr>
<tr><td>Owner: <code>o7-Fire</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2021-12-11 10:40:33+00:00</code></td>
    <td>Latest: <code>2022-06-28 03:20:20+02:00</code></td></tr>
<tr><td>Commits: <code>18</code></td>
    <td>Stargazers: <code>24</code></td>
    <td>Watchers: <code>24</code></td>
    <td>Forks: <code>11</code></td></tr>
</table>
Keywords: rce proof of concept, zero-day proof of concept, zero-day exploitation, zero-day exploit

---

# GitHub search -> Windows integer
# UnicodeVisualSpoofing

https://github.com/rohankhayech/UnicodeVisualSpoofing
<blockquote>
Unicode visual spoofing demo program showcasing the vulnerability and a patch.
</blockquote>

<table><tr>
<tr><td>Owner: <code>rohankhayech</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2022-06-27 13:23:51+00:00</code></td>
    <td>Latest: <code>2022-06-27 23:33:45+08:00</code></td></tr>
<tr><td>Commits: <code>62</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: spoofing vulnerability

---

# GitHub search -> Windows integer
# CVE-2010-4502

https://github.com/expFlash/CVE-2010-4502
<blockquote>
Integer overflow in KmxSbx.sys 6.2.0.22 in CA Internet Security Suite Plus 2010 allows local users to cause a denial of service (pool corruption) and execute arbitrary code via crafted arguments to the 0x88000080 IOCTL, which triggers a buffer overflow.
</blockquote>

<table><tr>
<tr><td>Owner: <code>expFlash</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2022-06-17 02:39:13+00:00</code></td>
    <td>Latest: <code>2022-06-26 07:38:16-04:00</code></td></tr>
<tr><td>Commits: <code>16</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: corruption overflow denial of service

---

# GitHub search -> Windows integer
# BlueLotus_XSSReceiver

https://github.com/firesunCN/BlueLotus_XSSReceiver
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>firesunCN</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2015-10-12 06:37:45+00:00</code></td>
    <td>Latest: <code>2022-05-24 00:13:20+08:00</code></td></tr>
<tr><td>Commits: <code>46</code></td>
    <td>Stargazers: <code>1570</code></td>
    <td>Watchers: <code>1570</code></td>
    <td>Forks: <code>988</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# MySQL-UDF-Exploitation

https://github.com/koparmalbaris/MySQL-UDF-Exploitation
<blockquote>
MySQL User Defined Functions Exploitation to RCE or PrivEsc Simple Cheat Sheet.
</blockquote>

<table><tr>
<tr><td>Owner: <code>koparmalbaris</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-02-07 19:34:10+00:00</code></td>
    <td>Latest: <code>2022-05-13 10:10:25+03:00</code></td></tr>
<tr><td>Commits: <code>14</code></td>
    <td>Stargazers: <code>20</code></td>
    <td>Watchers: <code>20</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: rce exploitation

---

# GitHub search -> Windows integer
# Fullstack-Transferwise-Task

https://github.com/Edwardy221133/Fullstack-Transferwise-Task
<blockquote>
backend endpoint: https://transferwise-apitest.herokuapp.com/api/v1 Coding Project   Hints: Be smart, don’t repeat yourself or reinvent the wheel. Use as many packages/libraries as you can do. Use up-to-date software and bundles. Read the entire document here before jumping into action. Think twice. Model the application before you jump into coding.   Why? This coding challenge should give us a good understanding of  How well you can go from text to code, from requirements to product. How well you can execute on predefined requirements. How well you pay attention to detail so we can rely on you executing the work end to end. How creatively you execute on loose requirements (not defined in great detail). How well you can hack, organize, document, test, structure, and write your code. How well you can leverage existing things to build this app fast.   What (Objective):  The challenge is to create a web app where users can send virtual money in the currencies of (USD, EUR, NGN) to each ot...
</blockquote>

<table><tr>
<tr><td>Owner: <code>Edwardy221133</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2022-05-12 01:31:48+00:00</code></td>
    <td>Latest: <code>2022-05-11 19:50:14-07:00</code></td></tr>
<tr><td>Commits: <code>182</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# BrowserExploitation

https://github.com/MaherAzzouzi/BrowserExploitation
<blockquote>
Browser exploitation v8 and sandbox escape challenges with solutions.
</blockquote>

<table><tr>
<tr><td>Owner: <code>MaherAzzouzi</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2021-04-20 00:49:14+00:00</code></td>
    <td>Latest: <code>2022-05-10 23:15:36+01:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>27</code></td>
    <td>Watchers: <code>27</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: sandbox escape exploitation, sandbox escape exploit

---

# GitHub search -> Windows integer
# cyber_attack_simulation

https://github.com/seal9055/cyber_attack_simulation
<blockquote>
Attack simulation involving rce &amp;amp; kernel lpe exploits and malware + rootkit to exfil data
</blockquote>

<table><tr>
<tr><td>Owner: <code>seal9055</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2022-02-01 15:25:15+00:00</code></td>
    <td>Latest: <code>2022-05-04 17:26:36-04:00</code></td></tr>
<tr><td>Commits: <code>51</code></td>
    <td>Stargazers: <code>6</code></td>
    <td>Watchers: <code>6</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: lpe exploit, lpe exploitation

---

# GitHub search -> Windows integer
# zenith

https://github.com/0vercl0k/zenith
<blockquote>
Zenith exploits a memory corruption vulnerability in the NetUSB driver to get remote-code execution on the TP-Link Archer C7 V5 router for Pwn2Own Austin 2021.
</blockquote>

<table><tr>
<tr><td>Owner: <code>0vercl0k</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2021-10-08 16:47:53+00:00</code></td>
    <td>Latest: <code>2022-04-24 17:57:39-07:00</code></td></tr>
<tr><td>Commits: <code>13</code></td>
    <td>Stargazers: <code>129</code></td>
    <td>Watchers: <code>129</code></td>
    <td>Forks: <code>24</code></td></tr>
</table>
Keywords: remote code execution exploitation, remote code execution exploit, remote code execution vulnerability

---

# GitHub search -> Windows integer
# Burp-SessionAuthTool

https://github.com/thomaspatzke/Burp-SessionAuthTool
<blockquote>
Burp plugin which supports in finding privilege escalation vulnerabilities
</blockquote>

<table><tr>
<tr><td>Owner: <code>thomaspatzke</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2013-06-14 14:44:23+00:00</code></td>
    <td>Latest: <code>2022-04-22 19:14:00+02:00</code></td></tr>
<tr><td>Commits: <code>23</code></td>
    <td>Stargazers: <code>40</code></td>
    <td>Watchers: <code>40</code></td>
    <td>Forks: <code>15</code></td></tr>
</table>
Keywords: session vulnerability

---

# GitHub search -> Windows integer
# rcea

https://github.com/hesim-dev/rcea
<blockquote>
Course materials for learning how to perform applied cost-effectiveness analysis with R
</blockquote>

<table><tr>
<tr><td>Owner: <code>hesim-dev</code></td>
    <td>Language: <code>R</code></td>
    <td>Started: <code>2020-01-29 01:23:20+00:00</code></td>
    <td>Latest: <code>2022-04-19 18:21:04-07:00</code></td></tr>
<tr><td>Commits: <code>276</code></td>
    <td>Stargazers: <code>23</code></td>
    <td>Watchers: <code>23</code></td>
    <td>Forks: <code>11</code></td></tr>
</table>
Keywords: rce analysis

---

# GitHub search -> Windows integer
# CVE-2022-26809

https://github.com/websecnl/CVE-2022-26809
<blockquote>
Remote Code Execution Exploit in the RPC Library
</blockquote>

<table><tr>
<tr><td>Owner: <code>websecnl</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2022-04-14 08:12:24+00:00</code></td>
    <td>Latest: <code>2022-04-19 19:04:04+02:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>28</code></td>
    <td>Watchers: <code>28</code></td>
    <td>Forks: <code>3</code></td></tr>
</table>
Keywords: remote code execution exploitation, remote code execution exploit

---

# GitHub search -> Windows integer
# testenv

https://github.com/sqlmapproject/testenv
<blockquote>
A collection of web pages vulnerable to SQL injection flaws
</blockquote>

<table><tr>
<tr><td>Owner: <code>sqlmapproject</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2012-07-09 23:09:34+00:00</code></td>
    <td>Latest: <code>2022-04-14 11:05:57+02:00</code></td></tr>
<tr><td>Commits: <code>139</code></td>
    <td>Stargazers: <code>347</code></td>
    <td>Watchers: <code>347</code></td>
    <td>Forks: <code>131</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# Log4jRCE-ExploitWindows

https://github.com/h4ckti/Log4jRCE-ExploitWindows
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>h4ckti</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-04-03 17:04:11+00:00</code></td>
    <td>Latest: <code>2022-04-03 17:04:11+00:00</code></td></tr>
<tr><td>Commits: <code>0</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows rce, Win rce

---

# GitHub search -> Windows integer
# solar-wind-hacker-book

https://github.com/Mario-Kart-Felix/solar-wind-hacker-book
<blockquote>
2020 was a roller coaster of major, world-shaking events. We all couldn't wait for the year to end. But just as 2020 was about to close, it pulled another fast one on us: the SolarWinds hack, one of the biggest cybersecurity breaches of the 21st century.  The SolarWinds hack was a major event not because a single company was breached, but because it triggered a much larger supply chain incident that affected thousands of organizations, including the U.S. government.  What is SolarWinds? SolarWinds is a major software company based in Tulsa, Okla., which provides system management tools for network and infrastructure monitoring, and other technical services to hundreds of thousands of organizations around the world. Among the company's products is an IT performance monitoring system called Orion.   As an IT monitoring system, SolarWinds Orion has privileged access to IT systems to obtain log and system performance data. It is that privileged position and its wide deployment that made So...
</blockquote>

<table><tr>
<tr><td>Owner: <code>Mario-Kart-Felix</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-03-10 00:46:23+00:00</code></td>
    <td>Latest: <code>2022-03-26 17:00:40-05:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>17</code></td>
    <td>Watchers: <code>17</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: Win use after free, use after free analysis, Win use after free exploit, Microsoft use after free exploitation, use after free exploitation, Microsoft use after free vulnerability, Microsoft use after free exploit, Win use after free exploitation, Microsoft use after free analysis, Microsoft use after free, use after free vulnerability, use after free exploit, Win use after free analysis, Win use after free vulnerability

---

# GitHub search -> Windows integer
# Disclosures

https://github.com/alisaesage/Disclosures
<blockquote>
Zero-day and N-day security vulnerability notes, analysis, and proof-of-concepts
</blockquote>

<table><tr>
<tr><td>Owner: <code>alisaesage</code></td>
    <td>Language: <code>HTML</code></td>
    <td>Started: <code>2019-11-02 12:53:45+00:00</code></td>
    <td>Latest: <code>2022-03-20 23:58:26+07:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>423</code></td>
    <td>Watchers: <code>423</code></td>
    <td>Forks: <code>79</code></td></tr>
</table>
Keywords: zero-day vulnerability, zero-day analysis, zero-day disclosure, zero-day proof of concept

---

# GitHub search -> Windows integer
# MemTrace

https://github.com/kristopher-pellizzi/MemTrace
<blockquote>
Dynamic analysis tool to find memory overlaps in an executable
</blockquote>

<table><tr>
<tr><td>Owner: <code>kristopher-pellizzi</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2020-12-11 00:02:01+00:00</code></td>
    <td>Latest: <code>2022-03-14 14:53:21+01:00</code></td></tr>
<tr><td>Commits: <code>585</code></td>
    <td>Stargazers: <code>10</code></td>
    <td>Watchers: <code>10</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: memory leak analysis

---

# GitHub search -> Windows integer
# gosession

https://github.com/tapvanvn/gosession
<blockquote>
An attempt to manage session and prevent ddos attack
</blockquote>

<table><tr>
<tr><td>Owner: <code>tapvanvn</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2021-10-27 11:06:09+00:00</code></td>
    <td>Latest: <code>2022-02-25 11:53:43+07:00</code></td></tr>
<tr><td>Commits: <code>20</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: session attack

---

# GitHub search -> Windows integer
# sql_injection

https://github.com/claraj/sql_injection
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>claraj</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2016-01-06 18:29:38+00:00</code></td>
    <td>Latest: <code>2022-02-14 15:56:20-06:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>50</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# 0xsp-Mongoose

https://github.com/zux0x3a/0xsp-Mongoose
<blockquote>
a unique framework for cybersecurity simulation and red teaming operations, windows auditing for newer vulnerabilities, misconfigurations and privilege escalations attacks, replicate the tactics and techniques of an advanced adversary in a network.
</blockquote>

<table><tr>
<tr><td>Owner: <code>zux0x3a</code></td>
    <td>Language: <code>Pascal</code></td>
    <td>Started: <code>2019-06-12 20:12:16+00:00</code></td>
    <td>Latest: <code>2022-02-14 11:04:23+08:00</code></td></tr>
<tr><td>Commits: <code>233</code></td>
    <td>Stargazers: <code>538</code></td>
    <td>Watchers: <code>538</code></td>
    <td>Forks: <code>121</code></td></tr>
</table>
Keywords: Windows escalation of privileges vulnerability, escalation of privileges vulnerability, Windows escalation of privileges

---

# GitHub search -> Windows integer
# Disclosures

https://github.com/DrunkenShells/Disclosures
<blockquote>
Public Disclosures
</blockquote>

<table><tr>
<tr><td>Owner: <code>DrunkenShells</code></td>
    <td>Language: <code>HTML</code></td>
    <td>Started: <code>2019-01-18 08:07:32+00:00</code></td>
    <td>Latest: <code>2022-02-13 23:59:47+02:00</code></td></tr>
<tr><td>Commits: <code>34</code></td>
    <td>Stargazers: <code>90</code></td>
    <td>Watchers: <code>90</code></td>
    <td>Forks: <code>19</code></td></tr>
</table>
Keywords: 0day disclosure

---

# GitHub search -> Windows integer
# tplmap

https://github.com/epinna/tplmap
<blockquote>
Server-Side Template Injection and Code Injection Detection and Exploitation Tool
</blockquote>

<table><tr>
<tr><td>Owner: <code>epinna</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2016-07-06 20:33:18+00:00</code></td>
    <td>Latest: <code>2022-02-06 15:13:15+00:00</code></td></tr>
<tr><td>Commits: <code>723</code></td>
    <td>Stargazers: <code>3957</code></td>
    <td>Watchers: <code>3957</code></td>
    <td>Forks: <code>685</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# Hack-SQL

https://github.com/Don-No7/Hack-SQL
<blockquote>
-- -- File generated with SQLiteStudio v3.2.1 on Sun Feb 7 14:58:28 2021 -- -- Text encoding used: System -- PRAGMA foreign_keys = off; BEGIN TRANSACTION;  -- Table: Commands CREATE TABLE Commands (Command_No INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL, Name TEXT REFERENCES Programs (Name) NOT NULL, Description TEXT NOT NULL, Command TEXT, File BLOB); INSERT INTO Commands (Command_No, Name, Description, Command, File) VALUES (1, 'Kerbrute', 'brute single user password', 'kerbrute bruteuers [flags]', NULL); INSERT INTO Commands (Command_No, Name, Description, Command, File) VALUES (2, 'Kerbrute', 'brute username:password combos from file or stdin', 'kerbrute brutforce [flags]', NULL); INSERT INTO Commands (Command_No, Name, Description, Command, File) VALUES (3, 'Kerbrute', 'test a single password agains a list of users', 'kerbrute passwordspray [flags]', NULL); INSERT INTO Commands (Command_No, Name, Description, Command, File) VALUES (4, 'Kerbrute', 'Enumerate valid domain usernames vi...
</blockquote>

<table><tr>
<tr><td>Owner: <code>Don-No7</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2022-01-30 17:26:02+00:00</code></td>
    <td>Latest: <code>2022-01-31 00:12:54+06:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>92</code></td>
    <td>Watchers: <code>92</code></td>
    <td>Forks: <code>14</code></td></tr>
</table>
Keywords: path traversal vulnerability, Windows escalation of privileges analysis, path traversal attack, Win escalation of privileges analysis, Win escalation of privileges exploitation, Windows remote code execution vulnerability, Win remote code execution exploit, Windows remote code execution exploit, remote code execution analysis, Windows remote code execution analysis, Win escalation of privileges, Windows remote code execution exploitation, escalation of privileges vulnerability, escalation of privileges exploitation, Win escalation of privileges vulnerability, directory traversal attack, Win remote code execution analysis, Win remote code execution, directory traversal vulnerability, Windows escalation of privileges exploit, session vulnerability, Win remote code execution exploitation, Windows escalation of privileges, Win remote code execution vulnerability, Windows remote code execution, escalation of privileges analysis, Windows escalation of privileges exploitation, Windows escalation of privileges vulnerability, Win escalation of privileges exploit, escalation of privileges exploit

---

# GitHub search -> Windows integer
# cve-lib-power-grid

https://github.com/Mario-Kart-Felix/cve-lib-power-grid
<blockquote>
Improper Input Validation vulnerability in Hitachi ABB Power Grids Relion 670 Series, Relion 670/650 Series, Relion 670/650/SAM600-IO, Relion 650, REB500, RTU500 Series, FOX615 (TEGO1), MSM, GMS600, PWC600 allows an attacker with access to the IEC 61850 network with knowledge of how to reproduce the attack, as well as the IP addresses of the different IEC 61850 access points (of IEDs/products), to force the device to reboot, which renders the device inoperable for approximately 60 seconds. This vulnerability affects only products with IEC 61850 interfaces. This issue affects: Hitachi ABB Power Grids Relion 670 Series 1.1; 1.2.3 versions prior to 1.2.3.20; 2.0 versions prior to 2.0.0.13; 2.1; 2.2.2 versions prior to 2.2.2.3; 2.2.3 versions prior to 2.2.3.2. Hitachi ABB Power Grids Relion 670/650 Series 2.2.0 versions prior to 2.2.0.13. Hitachi ABB Power Grids Relion 670/650/SAM600-IO 2.2.1 versions prior to 2.2.1.6. Hitachi ABB Power Grids Relion 650 1.1; 1.2; 1.3 versions prior to 1.3....
</blockquote>

<table><tr>
<tr><td>Owner: <code>Mario-Kart-Felix</code></td>
    <td>Language: <code>Rust</code></td>
    <td>Started: <code>2022-01-21 06:50:13+00:00</code></td>
    <td>Latest: <code>2022-01-21 03:06:05-06:00</code></td></tr>
<tr><td>Commits: <code>39</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: improper input validation

---

# GitHub search -> Windows integer
# usefull-elevation-of-privilege

https://github.com/0x727/usefull-elevation-of-privilege
<blockquote>
Usefull escalation of privilege Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>0x727</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2021-08-12 07:05:27+00:00</code></td>
    <td>Latest: <code>2021-12-22 17:23:31+08:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows escalation of privileges

---

# GitHub search -> Windows integer
# twitchget

https://github.com/david-wm-sanders/twitchget
<blockquote>
Twitch downloader using cookies via Chrome session hijacking
</blockquote>

<table><tr>
<tr><td>Owner: <code>david-wm-sanders</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2020-03-14 01:59:48+00:00</code></td>
    <td>Latest: <code>2021-12-18 17:35:35+00:00</code></td></tr>
<tr><td>Commits: <code>13</code></td>
    <td>Stargazers: <code>5</code></td>
    <td>Watchers: <code>5</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# Log4jPatch

https://github.com/simonis/Log4jPatch
<blockquote>
Deploys an agent to fix  CVE-2021-44228 (Log4j RCE vulnerability) in a running JVM process
</blockquote>

<table><tr>
<tr><td>Owner: <code>simonis</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2021-12-10 10:10:19+00:00</code></td>
    <td>Latest: <code>2021-12-12 11:32:57+01:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>108</code></td>
    <td>Watchers: <code>108</code></td>
    <td>Forks: <code>13</code></td></tr>
</table>
Keywords: rce vulnerability

---

# GitHub search -> Windows integer
# JNDI-Exploit-Bypass-Demo

https://github.com/kxcode/JNDI-Exploit-Bypass-Demo
<blockquote>
Demo code for post &amp;lt;Restrictions of JNDI Manipulation RCE &amp;amp; Bypass&amp;gt;
</blockquote>

<table><tr>
<tr><td>Owner: <code>kxcode</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2019-06-04 07:00:15+00:00</code></td>
    <td>Latest: <code>2021-12-12 11:29:21+08:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>261</code></td>
    <td>Watchers: <code>261</code></td>
    <td>Forks: <code>44</code></td></tr>
</table>
Keywords: rce exploit

---

# GitHub search -> Windows integer
# amazon-ssm-agent

https://github.com/RhinoSecurityLabs/amazon-ssm-agent
<blockquote>
Fork of amazon-ssm-agent that can run as any user in parallel with the official service.
</blockquote>

<table><tr>
<tr><td>Owner: <code>RhinoSecurityLabs</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2021-11-28 06:51:57+00:00</code></td>
    <td>Latest: <code>2021-12-03 10:18:49-08:00</code></td></tr>
<tr><td>Commits: <code>3311</code></td>
    <td>Stargazers: <code>4</code></td>
    <td>Watchers: <code>4</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# PostgreSQL_Windows_sendUDF_SMB

https://github.com/0xm4ud/PostgreSQL_Windows_sendUDF_SMB
<blockquote>
Python script send Windows DLL PostreSQL UDF  SMB RCE 
</blockquote>

<table><tr>
<tr><td>Owner: <code>0xm4ud</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2021-11-18 17:59:37+00:00</code></td>
    <td>Latest: <code>2021-11-18 16:06:21-03:00</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows rce, Win rce

---

# GitHub search -> Windows integer
# explorer-mem-leak

https://github.com/Dorumin/explorer-mem-leak
<blockquote>
Patch to solve explorer.exe memory leak on windows, by restarting it
</blockquote>

<table><tr>
<tr><td>Owner: <code>Dorumin</code></td>
    <td>Language: <code>Rust</code></td>
    <td>Started: <code>2020-12-17 02:34:50+00:00</code></td>
    <td>Latest: <code>2021-11-08 01:42:06-03:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows memory leak

---

# GitHub search -> Windows integer
# how-to-bypass-aslr-on-linux-x86_64

https://github.com/nick0ve/how-to-bypass-aslr-on-linux-x86_64
<blockquote>
ASLR bypass without infoleak
</blockquote>

<table><tr>
<tr><td>Owner: <code>nick0ve</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2021-10-27 07:58:46+00:00</code></td>
    <td>Latest: <code>2021-11-02 20:56:24+01:00</code></td></tr>
<tr><td>Commits: <code>25</code></td>
    <td>Stargazers: <code>161</code></td>
    <td>Watchers: <code>161</code></td>
    <td>Forks: <code>17</code></td></tr>
</table>
Keywords: aslr bypass

---

# GitHub search -> Windows integer
# IOMobileFrameBuffer_LPE_POC

https://github.com/saaramar/IOMobileFrameBuffer_LPE_POC
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>saaramar</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2021-07-26 21:18:43+00:00</code></td>
    <td>Latest: <code>2021-10-04 12:30:26+03:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>54</code></td>
    <td>Watchers: <code>54</code></td>
    <td>Forks: <code>12</code></td></tr>
</table>
Keywords: lpe poc

---

# GitHub search -> Windows integer
# markdown

https://github.com/snoyberg/markdown
<blockquote>
Convert Markdown to HTML, with XSS protection
</blockquote>

<table><tr>
<tr><td>Owner: <code>snoyberg</code></td>
    <td>Language: <code>Haskell</code></td>
    <td>Started: <code>2011-11-29 10:33:44+00:00</code></td>
    <td>Latest: <code>2021-09-29 08:17:34+03:00</code></td></tr>
<tr><td>Commits: <code>152</code></td>
    <td>Stargazers: <code>72</code></td>
    <td>Watchers: <code>72</code></td>
    <td>Forks: <code>396</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# Vailyn

https://github.com/VainlyStrain/Vailyn
<blockquote>
A phased, evasive Path Traversal + LFI scanning &amp;amp; exploitation tool in Python
</blockquote>

<table><tr>
<tr><td>Owner: <code>VainlyStrain</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2020-04-19 14:09:31+00:00</code></td>
    <td>Latest: <code>2021-09-25 21:18:09+02:00</code></td></tr>
<tr><td>Commits: <code>410</code></td>
    <td>Stargazers: <code>198</code></td>
    <td>Watchers: <code>198</code></td>
    <td>Forks: <code>23</code></td></tr>
</table>
Keywords: lfi, rce exploitation

---

# GitHub search -> Windows integer
# dtd-finder

https://github.com/GoSecure/dtd-finder
<blockquote>
List DTDs and generate XXE payloads using those local DTDs.
</blockquote>

<table><tr>
<tr><td>Owner: <code>GoSecure</code></td>
    <td>Language: <code>Kotlin</code></td>
    <td>Started: <code>2019-07-15 20:13:54+00:00</code></td>
    <td>Latest: <code>2021-09-22 13:53:59-04:00</code></td></tr>
<tr><td>Commits: <code>47</code></td>
    <td>Stargazers: <code>631</code></td>
    <td>Watchers: <code>631</code></td>
    <td>Forks: <code>110</code></td></tr>
</table>
Keywords: xxe

---

# GitHub search -> Windows integer
# youtube-projects

https://github.com/coding-parrot/youtube-projects
<blockquote>
These are project resources for the live YouTube lectures. Includes dependency injection, git internals, code reviews and the system design contest.
</blockquote>

<table><tr>
<tr><td>Owner: <code>coding-parrot</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2020-05-11 10:16:27+00:00</code></td>
    <td>Latest: <code>2021-09-21 17:12:45+05:30</code></td></tr>
<tr><td>Commits: <code>22</code></td>
    <td>Stargazers: <code>128</code></td>
    <td>Watchers: <code>128</code></td>
    <td>Forks: <code>81</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# RCE-python-oneliner-payload

https://github.com/shelld3v/RCE-python-oneliner-payload
<blockquote>
Python bind shell single line code for both Unix and Windows, used to find and exploit RCE (ImageMagick, Ghostscript, ...)
</blockquote>

<table><tr>
<tr><td>Owner: <code>shelld3v</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2020-04-02 08:31:44+00:00</code></td>
    <td>Latest: <code>2021-09-09 20:36:01+07:00</code></td></tr>
<tr><td>Commits: <code>18</code></td>
    <td>Stargazers: <code>32</code></td>
    <td>Watchers: <code>32</code></td>
    <td>Forks: <code>8</code></td></tr>
</table>
Keywords: Windows rce exploitation, Windows rce, rce exploitation, Windows rce exploit

---

# GitHub search -> Windows integer
# CodeInjection

https://github.com/11philip22/CodeInjection
<blockquote>
Collection of shellcode injection and execution techniques
</blockquote>

<table><tr>
<tr><td>Owner: <code>11philip22</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2021-06-03 08:47:05+00:00</code></td>
    <td>Latest: <code>2021-07-27 11:42:34+02:00</code></td></tr>
<tr><td>Commits: <code>18</code></td>
    <td>Stargazers: <code>17</code></td>
    <td>Watchers: <code>17</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# LFImagePickerController

https://github.com/lincf0912/LFImagePickerController
<blockquote>
一个支持多选图片和视频的图片选择器，同时有预览、编辑功能
</blockquote>

<table><tr>
<tr><td>Owner: <code>lincf0912</code></td>
    <td>Language: <code>Objective-C</code></td>
    <td>Started: <code>2017-02-13 00:56:28+00:00</code></td>
    <td>Latest: <code>2021-06-24 21:46:23+08:00</code></td></tr>
<tr><td>Commits: <code>470</code></td>
    <td>Stargazers: <code>228</code></td>
    <td>Watchers: <code>228</code></td>
    <td>Forks: <code>47</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# On-Time-Delivery-Prediction

https://github.com/th-rpy/On-Time-Delivery-Prediction
<blockquote>
Session Project: Shipment Arrival Prediction
</blockquote>

<table><tr>
<tr><td>Owner: <code>th-rpy</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2021-04-27 19:27:13+00:00</code></td>
    <td>Latest: <code>2021-04-29 00:08:12-04:00</code></td></tr>
<tr><td>Commits: <code>36</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session prediction

---

# GitHub search -> Windows integer
# MemLeakTracker

https://github.com/BoyC/MemLeakTracker
<blockquote>
A single file drop-in memory leak tracking solution for C++ on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>BoyC</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2021-04-12 19:31:01+00:00</code></td>
    <td>Latest: <code>2021-04-12 22:16:49+02:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>25</code></td>
    <td>Watchers: <code>25</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: Windows memory leak

---

# GitHub search -> Windows integer
# Airbnb-New-User-Prediction

https://github.com/NamrataThakur/Airbnb-New-User-Prediction
<blockquote>
The problem that this case study is dealing with predicts the location that a user is most likely to book for the first time. The accurate prediction helps to decrease the average time required to book by sharing more personalized recommendations and also in better forecasting of the demand. We use the browser’s session data as well as the user’s demographic information that is provided to us to create features that help in solving the problem.
</blockquote>

<table><tr>
<tr><td>Owner: <code>NamrataThakur</code></td>
    <td>Language: <code>Jupyter Notebook</code></td>
    <td>Started: <code>2021-01-03 14:22:00+00:00</code></td>
    <td>Latest: <code>2021-03-30 21:40:21+05:30</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>5</code></td>
    <td>Watchers: <code>5</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session prediction

---

# GitHub search -> Windows integer
# spotify-sequential-track-sequence-prediction

https://github.com/ahmad0790/spotify-sequential-track-sequence-prediction
<blockquote>
Using Transformers, Attention Based Seq2Seq, and Deep Reinforcement Learning to predict the next 10 songs listened by a user in a session
</blockquote>

<table><tr>
<tr><td>Owner: <code>ahmad0790</code></td>
    <td>Language: <code>Jupyter Notebook</code></td>
    <td>Started: <code>2021-03-18 04:46:48+00:00</code></td>
    <td>Latest: <code>2021-03-17 21:50:50-07:00</code></td></tr>
<tr><td>Commits: <code>49</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session prediction

---

# GitHub search -> Windows integer
# SpringBootVulExploit

https://github.com/LandGrey/SpringBootVulExploit
<blockquote>
SpringBoot 相关漏洞学习资料，利用方法和技巧合集，黑盒安全评估 check list
</blockquote>

<table><tr>
<tr><td>Owner: <code>LandGrey</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2020-05-20 09:18:44+00:00</code></td>
    <td>Latest: <code>2021-03-10 21:03:17+08:00</code></td></tr>
<tr><td>Commits: <code>27</code></td>
    <td>Stargazers: <code>5982</code></td>
    <td>Watchers: <code>5982</code></td>
    <td>Forks: <code>1320</code></td></tr>
</table>
Keywords: rce exploit, rce vulnerability

---

# GitHub search -> Windows integer
# Awards-Predictions-App

https://github.com/justinjaeger/Awards-Predictions-App
<blockquote>
A Next.js (React + Node) application built with secure authentication, session persistence and follower/following relationships between users. Includes ability to set / upload profile photos
</blockquote>

<table><tr>
<tr><td>Owner: <code>justinjaeger</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2021-02-16 04:44:44+00:00</code></td>
    <td>Latest: <code>2021-03-09 22:49:40-05:00</code></td></tr>
<tr><td>Commits: <code>65</code></td>
    <td>Stargazers: <code>4</code></td>
    <td>Watchers: <code>4</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: session prediction

---

# GitHub search -> Windows integer
# javascript-basic-program

https://github.com/sanusanth/javascript-basic-program
<blockquote>
What is JavaScript and what does it do?   Before you start learning something new, it’s important to understand exactly what it is and what it does. This is especially useful when it comes to mastering a new programming language.  In simple terms, JavaScript is a programming language used to make websites interactive. If you think about the basic makeup of a website, you have HTML, which describes and defines the basic content and structure of the website, then you have CSS, which tells the browser how this HTML content should be displayed—determining things like color and font. With just HTML and CSS, you have a website that looks good but doesn’t actually do much. JavaScript brings the website to life by adding functionality. JavaScript is responsible for elements that the user can interact with, such as drop-down menus, modal windows, and contact forms. It is also used to create things like animations, video players, and interactive maps.  Nowadays, JavaScript is an all-purpose prog...
</blockquote>

<table><tr>
<tr><td>Owner: <code>sanusanth</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2021-01-03 00:17:37+00:00</code></td>
    <td>Latest: <code>2021-01-10 13:19:14+05:30</code></td></tr>
<tr><td>Commits: <code>221</code></td>
    <td>Stargazers: <code>54</code></td>
    <td>Watchers: <code>54</code></td>
    <td>Forks: <code>22</code></td></tr>
</table>
Keywords: Windows use after free

---

# GitHub search -> Windows integer
# Admin-Hack-for-Windows

https://github.com/Windows10-AdminHack/Admin-Hack-for-Windows
<blockquote>
A simple script to bypass UAC in windows 10.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Windows10-AdminHack</code></td>
    <td>Language: <code>Batchfile</code></td>
    <td>Started: <code>2020-12-24 15:18:30+00:00</code></td>
    <td>Latest: <code>2020-12-24 15:53:53+00:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>8</code></td>
    <td>Watchers: <code>8</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: uac bypass

---

# GitHub search -> Windows integer
# SirepRAT

https://github.com/SafeBreach-Labs/SirepRAT
<blockquote>
Remote Command Execution as SYSTEM on Windows IoT Core (releases available for Python2.7 &amp;amp; Python3)
</blockquote>

<table><tr>
<tr><td>Owner: <code>SafeBreach-Labs</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-03-02 19:51:05+00:00</code></td>
    <td>Latest: <code>2020-12-13 11:52:54+02:00</code></td></tr>
<tr><td>Commits: <code>34</code></td>
    <td>Stargazers: <code>382</code></td>
    <td>Watchers: <code>382</code></td>
    <td>Forks: <code>90</code></td></tr>
</table>
Keywords: Windows rce, rce exploit, Windows rce exploit

---

# GitHub search -> Windows integer
# carrot47

https://github.com/JordanBarton/carrot47
<blockquote>
here's a tonne of old code, the most recent stuff is python_projects, the code used during my masters project is in Rcode. I've tried very hard to not leak any sensitive information like phone numbers, emails,addresses,usernames passwords etc.. and have replaced all the occurrences of these with XXXXXX. If you see any contact me via linkedin
</blockquote>

<table><tr>
<tr><td>Owner: <code>JordanBarton</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-11-28 14:47:07+00:00</code></td>
    <td>Latest: <code>2020-12-03 15:00:27+00:00</code></td></tr>
<tr><td>Commits: <code>19</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# ROP-Format-Exploit

https://github.com/teleplayer123/ROP-Format-Exploit
<blockquote>
Return to Libc exploit with format string vulnerability, bypass ASLR, NX, and Stack Canary
</blockquote>

<table><tr>
<tr><td>Owner: <code>teleplayer123</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2020-11-21 03:47:20+00:00</code></td>
    <td>Latest: <code>2020-11-20 19:51:44-08:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: aslr bypass, aslr bypass vulnerability, aslr bypass exploitation, aslr bypass exploit

---

# GitHub search -> Windows integer
# CVE-2016-3113

https://github.com/0xEmanuel/CVE-2016-3113
<blockquote>
A proof of concept to exploit the reflected XSS vulnerability in the oVirt web interface (RedHat). In this PoC a VM in the oVirt IaaS environment is to be started via the victim's browser session. JS code has been kept simple due to the rush.
</blockquote>

<table><tr>
<tr><td>Owner: <code>0xEmanuel</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2020-03-01 22:17:31+00:00</code></td>
    <td>Latest: <code>2020-11-09 21:00:12+01:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session vulnerability

---

# GitHub search -> Windows integer
# Alaska-altimetry

https://github.com/aaarendt/Alaska-altimetry
<blockquote>
UAF IceBridge Alaska Altimetry analysis scripts
</blockquote>

<table><tr>
<tr><td>Owner: <code>aaarendt</code></td>
    <td>Language: <code>Jupyter Notebook</code></td>
    <td>Started: <code>2015-11-18 03:52:58+00:00</code></td>
    <td>Latest: <code>2020-10-28 12:03:17-07:00</code></td></tr>
<tr><td>Commits: <code>85</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: uaf analysis

---

# GitHub search -> Windows integer
# injectionforxcode

https://github.com/johnno1962/injectionforxcode
<blockquote>
Runtime Code Injection for Objective-C &amp;amp; Swift
</blockquote>

<table><tr>
<tr><td>Owner: <code>johnno1962</code></td>
    <td>Language: <code>Objective-C</code></td>
    <td>Started: <code>2012-05-28 15:37:09+00:00</code></td>
    <td>Latest: <code>2020-08-11 06:26:28+00:00</code></td></tr>
<tr><td>Commits: <code>368</code></td>
    <td>Stargazers: <code>6555</code></td>
    <td>Watchers: <code>6555</code></td>
    <td>Forks: <code>566</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# MCIR

https://github.com/SpiderLabs/MCIR
<blockquote>
The Magical Code Injection Rainbow! MCIR is a framework for building configurable vulnerability testbeds. MCIR is also a collection of configurable vulnerability testbeds.
</blockquote>

<table><tr>
<tr><td>Owner: <code>SpiderLabs</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2013-07-19 21:07:51+00:00</code></td>
    <td>Latest: <code>2020-08-07 14:44:09+02:00</code></td></tr>
<tr><td>Commits: <code>34</code></td>
    <td>Stargazers: <code>442</code></td>
    <td>Watchers: <code>442</code></td>
    <td>Forks: <code>158</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# NoSQLAttack

https://github.com/youngyangyang04/NoSQLAttack
<blockquote>
NoSQLAttack is an open source Python tool to automate exploit MongoDB server IP on Internet and disclose the database data by MongoDB default configuration weaknesses and injection attacks.
</blockquote>

<table><tr>
<tr><td>Owner: <code>youngyangyang04</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2016-05-19 14:26:29+00:00</code></td>
    <td>Latest: <code>2020-08-05 09:29:07+08:00</code></td></tr>
<tr><td>Commits: <code>99</code></td>
    <td>Stargazers: <code>310</code></td>
    <td>Watchers: <code>310</code></td>
    <td>Forks: <code>88</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# mouse

https://github.com/fengjixuchui/mouse
<blockquote>
Mouse Payload Loader (MPL) is a post exploitation surveillance tool written in Python, C and Objective-C. It gives you a command line session with extra functionality between you and a target machine with simple MPL payload. MPL gives you the power and convenience of uploading/downloading files, tab completion, taking pictures, location tracking, shell command execution, persistence, escalating privileges, password retrieval, and much more.
</blockquote>

<table><tr>
<tr><td>Owner: <code>fengjixuchui</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-09-11 15:11:54+00:00</code></td>
    <td>Latest: <code>2020-07-04 16:50:32+08:00</code></td></tr>
<tr><td>Commits: <code>2688</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>73</code></td></tr>
</table>
Keywords: escalation of privileges exploitation, escalation of privileges exploit

---

# GitHub search -> Windows integer
# CVE-2020-0796-RCE-POC

https://github.com/jamf/CVE-2020-0796-RCE-POC
<blockquote>
CVE-2020-0796 Remote Code Execution POC
</blockquote>

<table><tr>
<tr><td>Owner: <code>jamf</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2020-04-20 14:35:48+00:00</code></td>
    <td>Latest: <code>2020-06-29 12:38:12+03:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>560</code></td>
    <td>Watchers: <code>560</code></td>
    <td>Forks: <code>173</code></td></tr>
</table>
Keywords: rce poc, remote code execution poc

---

# GitHub search -> Windows integer
# Path-Traversal-Cheat-Sheet-Linux

https://github.com/stephyards/Path-Traversal-Cheat-Sheet-Linux
<blockquote>
Got a path/directory traversal or file disclosure vulnerability on a Linux-server and need to know some interesting files to hunt for? I’ve got you covered Know any more good files to look for? Let me know!
</blockquote>

<table><tr>
<tr><td>Owner: <code>stephyards</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2020-06-10 02:44:02+00:00</code></td>
    <td>Latest: <code>2020-06-10 03:52:57+01:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: path traversal vulnerability, directory traversal vulnerability

---

# GitHub search -> Windows integer
# ClangUseAfterFree

https://github.com/michaelkurp/ClangUseAfterFree
<blockquote>
Static Analysis Tool to Find Use After Free Bugs
</blockquote>

<table><tr>
<tr><td>Owner: <code>michaelkurp</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2020-02-27 02:32:33+00:00</code></td>
    <td>Latest: <code>2020-04-29 20:15:46-07:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: use after free analysis

---

# GitHub search -> Windows integer
# Task3

https://github.com/charleenchy/Task3
<blockquote>
TASK 3  Write a Python program to find those numbers which are divisible by 7 and multiple of 5, between 1500 and 2700 (both included). Write a Python program to convert temperatures to and from celsius, fahrenheit. Write a Python program to guess a number between 1 to 9. Note : User is prompted to enter a guess. If the user guesses wrong then the prompt appears again until the guess is correct, on successful guess, user will get a &amp;quot;Well guessed!&amp;quot; message, and the program will exit. Write a Python program to check the validity of password input by users. Validation. Write a Python program to sum of two given integers. However, if the sum is between 15 to 20 it will return 20  &amp;&#35;35;30daysofcodingwithpython
</blockquote>

<table><tr>
<tr><td>Owner: <code>charleenchy</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2020-04-13 06:20:35+00:00</code></td>
    <td>Latest: <code>2020-04-15 13:38:27+01:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: wrong input validation

---

# GitHub search -> Windows integer
# TeleKiller

https://github.com/ultrasecurity/TeleKiller
<blockquote>
A Tools Session Hijacking And Stealer Local Passcode Telegram Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>ultrasecurity</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-04-05 13:13:06+00:00</code></td>
    <td>Latest: <code>2020-04-03 19:51:48+04:30</code></td></tr>
<tr><td>Commits: <code>40</code></td>
    <td>Stargazers: <code>418</code></td>
    <td>Watchers: <code>418</code></td>
    <td>Forks: <code>105</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# ridenum

https://github.com/trustedsec/ridenum
<blockquote>
Rid_enum is a null session RID cycle attack for brute forcing domain controllers.
</blockquote>

<table><tr>
<tr><td>Owner: <code>trustedsec</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2013-03-08 21:14:54+00:00</code></td>
    <td>Latest: <code>2020-03-11 16:38:23-04:00</code></td></tr>
<tr><td>Commits: <code>75</code></td>
    <td>Stargazers: <code>282</code></td>
    <td>Watchers: <code>282</code></td>
    <td>Forks: <code>85</code></td></tr>
</table>
Keywords: session attack

---

# GitHub search -> Windows integer
# SQL-Challenge-

https://github.com/presidentmanny/SQL-Challenge-
<blockquote>
 It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files. In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:   Data Modeling   Data Engineering   Data Analysis    Before You Begin   Create a new folder in your homework repository called sql-challenge.   Inside your local git repository, create a directory for the SQL challenge. Use a folder name to correspond to the challenge: EmployeeSQL.   Add your files to this folder.   Push the above changes to GitHub.    Instructions  Data Modeling Inspect the CSVs and sketch out an ERD of the tables. Feel free to use a tool like http://www.quickdatabasediagrams.com.  Data Engin...
</blockquote>

<table><tr>
<tr><td>Owner: <code>presidentmanny</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2020-02-26 23:19:26+00:00</code></td>
    <td>Latest: <code>2020-02-26 18:24:01-05:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: use after free analysis

---

# GitHub search -> Windows integer
# DHCP-Spoofing-Attack-Network-Security

https://github.com/shamiul94/DHCP-Spoofing-Attack-Network-Security
<blockquote>
Here I have implemented DHCP Spoofing attack for our Network security course sessional.
</blockquote>

<table><tr>
<tr><td>Owner: <code>shamiul94</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-08-03 03:09:40+00:00</code></td>
    <td>Latest: <code>2020-02-10 09:14:15+06:00</code></td></tr>
<tr><td>Commits: <code>10</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: spoofing session, session attack

---

# GitHub search -> Windows integer
# gosplash

https://github.com/melehin/gosplash
<blockquote>
Simple javascript renderer based on Chromium and Go with an HTTP API. A bit slower and API limited but no memory leaks as in Python splash project.
</blockquote>

<table><tr>
<tr><td>Owner: <code>melehin</code></td>
    <td>Language: <code>Go</code></td>
    <td>Started: <code>2019-09-04 11:08:45+00:00</code></td>
    <td>Latest: <code>2019-11-27 18:30:18+05:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Chromium memory leak

---

# GitHub search -> Windows integer
# CVE-2019-0232

https://github.com/pyn3rd/CVE-2019-0232
<blockquote>
Apache Tomcat Remote Code Execution on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>pyn3rd</code></td>
    <td>Language: <code>Batchfile</code></td>
    <td>Started: <code>2019-04-15 07:54:25+00:00</code></td>
    <td>Latest: <code>2019-11-27 15:39:39+08:00</code></td></tr>
<tr><td>Commits: <code>31</code></td>
    <td>Stargazers: <code>187</code></td>
    <td>Watchers: <code>187</code></td>
    <td>Forks: <code>55</code></td></tr>
</table>
Keywords: Windows remote code execution

---

# GitHub search -> Windows integer
# CVE-2019-0232

https://github.com/iumiro/CVE-2019-0232
<blockquote>
CVE-2019-0232 Exploit Remote Code Execution (RCE) in CGI Servlet – Apache Tomcat on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>iumiro</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2025-01-31 05:50:04+00:00</code></td>
    <td>Latest: <code>2019-11-21 17:03:14+02:00</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows rce

---

# GitHub search -> Windows integer
# Data_Science_with_R

https://github.com/akaidkhan/Data_Science_with_R
<blockquote>
Introduction to R  R is a programming language, which is an object oriented language created by Statisticians, R provides objects, operators and functions that allow the user to explore, model and visualize data.  R is a Programming language Developed at AT&amp;amp;T Bell Lab.  It is an open source free language, allowing anyone to use and modify it. R is licensed under the GNU General Public License, with copyright held by The R Foundation For Statistical Computing. It has no need to pay any subscription charges  R has a huge active community member. If you have any question about any function any library you can Google it and you would get a proper answer and right the way.  As it is an open source language, you, me and lots of Data Scientist, they actually built in all those, inbuilt function and they upload it in a website called CRAN and then you can download all those packages. Over 7800 packages listed on CRAN, here we listed some of the most powerful and commonly used in R packages...
</blockquote>

<table><tr>
<tr><td>Owner: <code>akaidkhan</code></td>
    <td>Language: <code>R</code></td>
    <td>Started: <code>2019-10-30 07:21:32+00:00</code></td>
    <td>Latest: <code>2019-11-12 09:58:04-08:00</code></td></tr>
<tr><td>Commits: <code>40</code></td>
    <td>Stargazers: <code>8</code></td>
    <td>Watchers: <code>8</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: Microsoft use after free poc, Windows use after free, use after free analysis, Windows use after free analysis, use after free poc, Windows use after free poc, Microsoft use after free analysis, Microsoft use after free

---

# GitHub search -> Windows integer
# ohsmap

https://github.com/bindecy/ohsmap
<blockquote>
ASLR bypass in Chrome version 77
</blockquote>

<table><tr>
<tr><td>Owner: <code>bindecy</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2019-10-27 13:22:02+00:00</code></td>
    <td>Latest: <code>2019-10-28 15:14:23+02:00</code></td></tr>
<tr><td>Commits: <code>13</code></td>
    <td>Stargazers: <code>24</code></td>
    <td>Watchers: <code>24</code></td>
    <td>Forks: <code>6</code></td></tr>
</table>
Keywords: aslr bypass, Chrome aslr bypass

---

# GitHub search -> Windows integer
# Node.js

https://github.com/GhettoGeek/Node.js
<blockquote>
Node.js is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser. Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser. Consequently, Node.js represents a &amp;quot;JavaScript everywhere&amp;quot; paradigm,[7] unifying web application development around a single programming language, rather than different languages for server side and client side scripts. 
</blockquote>

<table><tr>
<tr><td>Owner: <code>GhettoGeek</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2019-09-02 06:16:14+00:00</code></td>
    <td>Latest: <code>2019-09-01 23:45:46-04:00</code></td></tr>
<tr><td>Commits: <code>211</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: cross-side-scripting

---

# GitHub search -> Windows integer
# XSS-Session-Hijacking-Simulator

https://github.com/zenzue/XSS-Session-Hijacking-Simulator
<blockquote>
Exploiting stored XSS vulnerability to hijack sessions
</blockquote>

<table><tr>
<tr><td>Owner: <code>zenzue</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2019-08-19 05:44:30+00:00</code></td>
    <td>Latest: <code>2019-08-17 19:17:35+02:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: session vulnerability, session hijacking vulnerability, session hijacking

---

# GitHub search -> Windows integer
# myhktools

https://github.com/do0dl3/myhktools
<blockquote>
https://51pwn.com,Awesome Penetration Testing，hacker tools collection, metasploit exploit, meterpreter....struts2、weblogic, 0day,poc,apt,backdoor,VulApps,vuln,pentest-script
</blockquote>

<table><tr>
<tr><td>Owner: <code>do0dl3</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2019-12-17 02:02:40+00:00</code></td>
    <td>Latest: <code>2019-07-31 21:50:36+08:00</code></td></tr>
<tr><td>Commits: <code>710</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: 0day exploitation, 0day poc

---

# GitHub search -> Windows integer
# myhktools

https://github.com/CrackerCat/myhktools
<blockquote>
https://51pwn.com,Awesome Penetration Testing，hacker tools collection, metasploit exploit, meterpreter....struts2、weblogic, 0day,poc,apt,backdoor,VulApps,vuln,pentest-script
</blockquote>

<table><tr>
<tr><td>Owner: <code>CrackerCat</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2020-03-24 03:35:00+00:00</code></td>
    <td>Latest: <code>2019-07-31 21:50:36+08:00</code></td></tr>
<tr><td>Commits: <code>710</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: 0day poc, 0day exploitation

---

# GitHub search -> Windows integer
# ios-RCE-Vulnerability

https://github.com/TinToSer/ios-RCE-Vulnerability
<blockquote>
Latest ios RCE Vulnerability disclosed by Google Security Researcher
</blockquote>

<table><tr>
<tr><td>Owner: <code>TinToSer</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2019-07-30 15:02:37+00:00</code></td>
    <td>Latest: <code>2019-07-30 20:57:43+05:30</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>43</code></td>
    <td>Watchers: <code>43</code></td>
    <td>Forks: <code>17</code></td></tr>
</table>
Keywords: zero-day vulnerability, rce vulnerability

---

# GitHub search -> Windows integer
# LFIT

https://github.com/AFDL/LFIT
<blockquote>
A MATLAB toolkit for the interactive processing of plenoptic images. This repository is a mirror!
</blockquote>

<table><tr>
<tr><td>Owner: <code>AFDL</code></td>
    <td>Language: <code>MATLAB</code></td>
    <td>Started: <code>2015-10-05 13:59:18+00:00</code></td>
    <td>Latest: <code>2019-07-09 15:28:17+00:00</code></td></tr>
<tr><td>Commits: <code>89</code></td>
    <td>Stargazers: <code>20</code></td>
    <td>Watchers: <code>20</code></td>
    <td>Forks: <code>14</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# A8-OA-seeyon-RCE

https://github.com/RayScri/A8-OA-seeyon-RCE
<blockquote>
A Zhiyuan OA Collaborative Office Remote Code Execution Vulnerability on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>RayScri</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2019-06-27 13:45:40+00:00</code></td>
    <td>Latest: <code>2019-06-27 21:53:06+08:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>37</code></td>
    <td>Watchers: <code>37</code></td>
    <td>Forks: <code>13</code></td></tr>
</table>
Keywords: Windows remote code execution vulnerability, Windows remote code execution, Windows rce, remote code execution vulnerability, Windows rce vulnerability, rce vulnerability

---

# GitHub search -> Windows integer
# code-injection

https://github.com/thepwnrip/code-injection
<blockquote>
A collection of methods of Code Injection on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>thepwnrip</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2019-06-13 11:46:59+00:00</code></td>
    <td>Latest: <code>2019-06-13 17:18:43+05:30</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>11</code></td>
    <td>Watchers: <code>11</code></td>
    <td>Forks: <code>6</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# Refcount-Overflow-Use-After-Free

https://github.com/Spartan-X/Refcount-Overflow-Use-After-Free
<blockquote>
The join_session_keyring function in security/keys/process_keys.c in the Linux kernel before 4.4.1 mishandles object references in a certain error case, which allows local users to gain privileges or cause a denial of service (integer overflow and use-after-free) via crafted keyctl commands.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Spartan-X</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2019-05-12 22:48:59+00:00</code></td>
    <td>Latest: <code>2019-05-12 19:23:04-04:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: use after free denial of service

---

# GitHub search -> Windows integer
# Amazon-Store-Front

https://github.com/itsrichardmai/Amazon-Store-Front
<blockquote>
&amp;&#35;35; Node.js &amp;amp; MySQL  &amp;&#35;35;&amp;&#35;35; Overview  In this activity, you'll be creating an Amazon-like storefront with the MySQL skills you learned this unit. The app will take in orders from customers and deplete stock from the store's inventory. As a bonus task, you can program your app to track product sales across your store's departments and then provide a summary of the highest-grossing departments in the store.  Make sure you save and require the MySQL and Inquirer npm packages in your homework files--your app will need them for data input and storage.  &amp;&#35;35;&amp;&#35;35; Submission Guide  Make sure you use the normal GitHub. Because this is a CLI App, there will be no need to deploy it to Heroku. This time, though, you need to include screenshots, a gif, and/or a video showing us that you got the app working with no bugs. You can include these screenshots or a link to a video in a `README.md` file.  * Include screenshots (or a video) of typical user flows through your application (for the...
</blockquote>

<table><tr>
<tr><td>Owner: <code>itsrichardmai</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2019-04-25 09:29:25+00:00</code></td>
    <td>Latest: <code>2019-05-02 19:44:56-04:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Windows use after free

---

# GitHub search -> Windows integer
# Blisqy

https://github.com/JohnTroony/Blisqy
<blockquote>
Version 0.2 - Exploit Time-based blind-SQL injection in HTTP-Headers (MySQL/MariaDB).
</blockquote>

<table><tr>
<tr><td>Owner: <code>JohnTroony</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2017-03-24 08:01:19+00:00</code></td>
    <td>Latest: <code>2019-03-24 14:35:24+03:00</code></td></tr>
<tr><td>Commits: <code>20</code></td>
    <td>Stargazers: <code>389</code></td>
    <td>Watchers: <code>389</code></td>
    <td>Forks: <code>108</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# bbqsql

https://github.com/CiscoCXSecurity/bbqsql
<blockquote>
SQL Injection Exploitation Tool
</blockquote>

<table><tr>
<tr><td>Owner: <code>CiscoCXSecurity</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2012-01-10 15:10:28+00:00</code></td>
    <td>Latest: <code>2019-01-04 14:23:19-07:00</code></td></tr>
<tr><td>Commits: <code>261</code></td>
    <td>Stargazers: <code>762</code></td>
    <td>Watchers: <code>762</code></td>
    <td>Forks: <code>192</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# CS411

https://github.com/bamelegari/CS411
<blockquote>
UAF CS411 Analysis of Algorithms assignment code.
</blockquote>

<table><tr>
<tr><td>Owner: <code>bamelegari</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2018-09-20 21:56:16+00:00</code></td>
    <td>Latest: <code>2018-12-14 23:43:20-09:00</code></td></tr>
<tr><td>Commits: <code>33</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: uaf analysis

---

# GitHub search -> Windows integer
# fimap

https://github.com/kurobeats/fimap
<blockquote>
fimap is a little python tool which can find, prepare, audit, exploit and even google automatically for local and remote file inclusion bugs in webapps.
</blockquote>

<table><tr>
<tr><td>Owner: <code>kurobeats</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2015-03-27 06:11:25+00:00</code></td>
    <td>Latest: <code>2018-11-14 20:27:58+08:00</code></td></tr>
<tr><td>Commits: <code>236</code></td>
    <td>Stargazers: <code>554</code></td>
    <td>Watchers: <code>554</code></td>
    <td>Forks: <code>101</code></td></tr>
</table>
Keywords: local file inclusion

---

# GitHub search -> Windows integer
# information-leakage

https://github.com/mprechtl/information-leakage
<blockquote>
A service which is vulnerable to XML External Entity (XXE) attacks.
</blockquote>

<table><tr>
<tr><td>Owner: <code>mprechtl</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2018-07-04 18:26:15+00:00</code></td>
    <td>Latest: <code>2018-11-11 19:23:30+01:00</code></td></tr>
<tr><td>Commits: <code>49</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: xml external entity

---

# GitHub search -> Windows integer
# xsschef

https://github.com/koto/xsschef
<blockquote>
Chrome extension Exploitation Framework
</blockquote>

<table><tr>
<tr><td>Owner: <code>koto</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2012-03-05 15:18:01+00:00</code></td>
    <td>Latest: <code>2018-10-12 21:57:14+02:00</code></td></tr>
<tr><td>Commits: <code>132</code></td>
    <td>Stargazers: <code>567</code></td>
    <td>Watchers: <code>567</code></td>
    <td>Forks: <code>106</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# BratShell

https://github.com/BrianHeeseIs/BratShell
<blockquote>
PHP shell that hijacks the the incoming socket connection to provide an interactive shell session on port 80
</blockquote>

<table><tr>
<tr><td>Owner: <code>BrianHeeseIs</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2013-12-05 13:54:28+00:00</code></td>
    <td>Latest: <code>2018-08-31 12:47:34+02:00</code></td></tr>
<tr><td>Commits: <code>41</code></td>
    <td>Stargazers: <code>8</code></td>
    <td>Watchers: <code>8</code></td>
    <td>Forks: <code>4</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# ciscoasa_honeypot

https://github.com/Cymmetria/ciscoasa_honeypot
<blockquote>
A low interaction honeypot for the Cisco ASA component capable of detecting CVE-2018-0101, a DoS and remote code execution vulnerability.
</blockquote>

<table><tr>
<tr><td>Owner: <code>Cymmetria</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2018-02-08 15:52:50+00:00</code></td>
    <td>Latest: <code>2018-08-16 17:24:19+03:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>52</code></td>
    <td>Watchers: <code>52</code></td>
    <td>Forks: <code>22</code></td></tr>
</table>
Keywords: remote code execution vulnerability, remote code execution dos

---

# GitHub search -> Windows integer
# windows-lpe-examples

https://github.com/yuvatia/windows-lpe-examples
<blockquote>
<no description>
</blockquote>

<table><tr>
<tr><td>Owner: <code>yuvatia</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2018-02-09 10:26:50+00:00</code></td>
    <td>Latest: <code>2018-08-11 21:23:56+03:00</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>4</code></td></tr>
</table>
Keywords: Win lpe, Windows lpe

---

# GitHub search -> Windows integer
# psychoPATH

https://github.com/ewilded/psychoPATH
<blockquote>
psychoPATH - an advanced path traversal tool. Features: evasive techniques, dynamic web root list generation, output encoding, site map-searching payload generator, LFI mode, nix &amp;amp; windows support, single byte generator, payload export.
</blockquote>

<table><tr>
<tr><td>Owner: <code>ewilded</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2016-02-17 20:31:57+00:00</code></td>
    <td>Latest: <code>2018-07-24 09:37:49+01:00</code></td></tr>
<tr><td>Commits: <code>251</code></td>
    <td>Stargazers: <code>276</code></td>
    <td>Watchers: <code>276</code></td>
    <td>Forks: <code>91</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# OSCE

https://github.com/dhn/OSCE
<blockquote>
Some exploits, which I’ve created during my OSCE preparation.
</blockquote>

<table><tr>
<tr><td>Owner: <code>dhn</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2018-04-25 18:39:03+00:00</code></td>
    <td>Latest: <code>2018-07-08 01:56:54+02:00</code></td></tr>
<tr><td>Commits: <code>50</code></td>
    <td>Stargazers: <code>83</code></td>
    <td>Watchers: <code>83</code></td>
    <td>Forks: <code>37</code></td></tr>
</table>
Keywords: dep bypass, rce exploitation

---

# GitHub search -> Windows integer
# chromeTabMonitor

https://github.com/mdupuy/chromeTabMonitor
<blockquote>
Sometimes chrome tabs get CPU hungry, whether malicious javascript is mining bitcoin or some simple web app memory leaked all over the place after leaving it open a few days (Office365, Google Keep, etc.). This is a very simple bash script that will aid in monitoring runaway Google Tabs on a Mac and Linux (and probably Win10)
</blockquote>

<table><tr>
<tr><td>Owner: <code>mdupuy</code></td>
    <td>Language: <code>Shell</code></td>
    <td>Started: <code>2018-06-05 23:29:47+00:00</code></td>
    <td>Latest: <code>2018-06-30 14:37:21-07:00</code></td></tr>
<tr><td>Commits: <code>41</code></td>
    <td>Stargazers: <code>8</code></td>
    <td>Watchers: <code>8</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: Chrome memory leak

---

# GitHub search -> Windows integer
# AggressorScripts

https://github.com/bluscreenofjeff/AggressorScripts
<blockquote>
Aggressor scripts for use with Cobalt Strike 3.0+
</blockquote>

<table><tr>
<tr><td>Owner: <code>bluscreenofjeff</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2016-04-13 08:16:12+00:00</code></td>
    <td>Latest: <code>2018-05-30 15:20:21-07:00</code></td></tr>
<tr><td>Commits: <code>49</code></td>
    <td>Stargazers: <code>837</code></td>
    <td>Watchers: <code>837</code></td>
    <td>Forks: <code>164</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# SAML-XXE-Test

https://github.com/RUB-NDS/SAML-XXE-Test
<blockquote>
Simple XXE test suite generated specifically for SAML interfaces
</blockquote>

<table><tr>
<tr><td>Owner: <code>RUB-NDS</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2018-04-30 10:15:38+00:00</code></td>
    <td>Latest: <code>2018-05-18 15:26:51+02:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>22</code></td>
    <td>Watchers: <code>22</code></td>
    <td>Forks: <code>9</code></td></tr>
</table>
Keywords: xxe

---

# GitHub search -> Windows integer
# SanitiserX

https://github.com/Mecanik/SanitiserX
<blockquote>
Zend 2/3 Module that sanitises requests and inputs against XSS (Cross-Site Scripting), CSRF (Cross-Site Request Forgery), RFI (Remote File Inclusion), LFI (Local File Inclusion), SQLi (SQL Injection) and more...
</blockquote>

<table><tr>
<tr><td>Owner: <code>Mecanik</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2018-04-18 11:32:03+00:00</code></td>
    <td>Latest: <code>2018-05-18 14:15:06+01:00</code></td></tr>
<tr><td>Commits: <code>12</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: local file inclusion

---

# GitHub search -> Windows integer
# PowerForensics

https://github.com/Invoke-IR/PowerForensics
<blockquote>
PowerForensics provides an all in one platform for live disk forensic analysis
</blockquote>

<table><tr>
<tr><td>Owner: <code>Invoke-IR</code></td>
    <td>Language: <code>C#</code></td>
    <td>Started: <code>2015-03-07 17:12:19+00:00</code></td>
    <td>Latest: <code>2018-04-20 03:34:59-07:00</code></td></tr>
<tr><td>Commits: <code>272</code></td>
    <td>Stargazers: <code>1404</code></td>
    <td>Watchers: <code>1404</code></td>
    <td>Forks: <code>276</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# sessionhijacking

https://github.com/rrayaprolu/sessionhijacking
<blockquote>
A Technique for Preventing SQL Injection Attack and Session Hijacking using Hashing
</blockquote>

<table><tr>
<tr><td>Owner: <code>rrayaprolu</code></td>
    <td>Language: <code>HTML</code></td>
    <td>Started: <code>2018-03-12 14:03:41+00:00</code></td>
    <td>Latest: <code>2018-04-02 11:26:41-05:00</code></td></tr>
<tr><td>Commits: <code>7</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session hijacking attack, session attack, session hijacking

---

# GitHub search -> Windows integer
# external_c2_framework

https://github.com/RhinoSecurityLabs/external_c2_framework
<blockquote>
Python api for usage with cobalt strike's External C2 specification 
</blockquote>

<table><tr>
<tr><td>Owner: <code>RhinoSecurityLabs</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2018-02-14 00:39:25+00:00</code></td>
    <td>Latest: <code>2018-02-15 00:49:59-08:00</code></td></tr>
<tr><td>Commits: <code>109</code></td>
    <td>Stargazers: <code>70</code></td>
    <td>Watchers: <code>70</code></td>
    <td>Forks: <code>18</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# ssrf_proxy

https://github.com/bcoles/ssrf_proxy
<blockquote>
SSRF Proxy facilitates tunneling HTTP communications through servers vulnerable to Server-Side Request Forgery.
</blockquote>

<table><tr>
<tr><td>Owner: <code>bcoles</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2015-10-02 06:01:19+00:00</code></td>
    <td>Latest: <code>2017-12-22 12:56:31+00:00</code></td></tr>
<tr><td>Commits: <code>313</code></td>
    <td>Stargazers: <code>465</code></td>
    <td>Watchers: <code>465</code></td>
    <td>Forks: <code>74</code></td></tr>
</table>
Keywords: server side request forgery, ssrf

---

# GitHub search -> Windows integer
# flame-darknet

https://github.com/bachsh/flame-darknet
<blockquote>
Light up the darknet by crawling it for posts advertising new hacking tools and zero-day vulnerabilities.
</blockquote>

<table><tr>
<tr><td>Owner: <code>bachsh</code></td>
    <td>Language: <code>Jupyter Notebook</code></td>
    <td>Started: <code>2017-11-23 21:21:40+00:00</code></td>
    <td>Latest: <code>2017-11-27 09:37:01+02:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>6</code></td>
    <td>Watchers: <code>6</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: zero-day vulnerability

---

# GitHub search -> Windows integer
# ValidationNumbers

https://github.com/MuhammadFadel/ValidationNumbers
<blockquote>
With this Java Class you can validate your input, test its and make a comparison. Now you can valid your GUI Input Fields easier. This Class all method Static, implemented to help you to be saved from any wrong counted in your App. Also, it support Float, Integer All kind of Types with More Flexibility.
</blockquote>

<table><tr>
<tr><td>Owner: <code>MuhammadFadel</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2017-10-26 02:43:25+00:00</code></td>
    <td>Latest: <code>2017-10-26 04:52:31+02:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: wrong input validation

---

# GitHub search -> Windows integer
# PowerSploit

https://github.com/HarmJoy/PowerSploit
<blockquote>
PowerSploit - A PowerShell Post-Exploitation Framework
</blockquote>

<table><tr>
<tr><td>Owner: <code>HarmJoy</code></td>
    <td>Language: <code>PowerShell</code></td>
    <td>Started: <code>2017-09-28 23:05:20+00:00</code></td>
    <td>Latest: <code>2017-09-28 16:35:41-07:00</code></td></tr>
<tr><td>Commits: <code>252</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# netelf

https://github.com/XiphosResearch/netelf
<blockquote>
Run executables from memory, over the network, on Windows, Linux, OpenVMS... routers... spaceships... toasters etc.
</blockquote>

<table><tr>
<tr><td>Owner: <code>XiphosResearch</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2016-08-24 11:58:44+00:00</code></td>
    <td>Latest: <code>2017-09-28 18:42:39+01:00</code></td></tr>
<tr><td>Commits: <code>19</code></td>
    <td>Stargazers: <code>283</code></td>
    <td>Watchers: <code>283</code></td>
    <td>Forks: <code>33</code></td></tr>
</table>
Keywords: Windows rce

---

# GitHub search -> Windows integer
# bad-apple

https://github.com/pasodoff/bad-apple
<blockquote>
Java REST application to test hard coded passwords and code vulnerability scanning
</blockquote>

<table><tr>
<tr><td>Owner: <code>pasodoff</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2017-06-15 09:17:22+00:00</code></td>
    <td>Latest: <code>2017-07-26 15:18:00+01:00</code></td></tr>
<tr><td>Commits: <code>25</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# windows_kernel_address_leaks

https://github.com/sam-b/windows_kernel_address_leaks
<blockquote>
Examples of leaking Kernel Mode information from User Mode on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>sam-b</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2017-01-30 23:06:11+00:00</code></td>
    <td>Latest: <code>2017-07-07 11:05:33+01:00</code></td></tr>
<tr><td>Commits: <code>69</code></td>
    <td>Stargazers: <code>608</code></td>
    <td>Watchers: <code>608</code></td>
    <td>Forks: <code>160</code></td></tr>
</table>
Keywords: Win address leak, Windows address leak

---

# GitHub search -> Windows integer
# PowerShell-MS16-051-IE-RCE

https://github.com/CrossGroupSecurity/PowerShell-MS16-051-IE-RCE
<blockquote>
Leverages MS16-051 to execute powershell in unpatched browsers. This is a file-less vector which works on IE9/10/11 and all versions of Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>CrossGroupSecurity</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2017-06-29 06:16:25+00:00</code></td>
    <td>Latest: <code>2017-06-29 08:09:09+01:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>4</code></td></tr>
</table>
Keywords: Windows rce

---

# GitHub search -> Windows integer
# bad-apple

https://github.com/gjtaylor/bad-apple
<blockquote>
Java REST application to test hard coded passwords and code vulnerability scanning
</blockquote>

<table><tr>
<tr><td>Owner: <code>gjtaylor</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2017-06-21 15:07:42+00:00</code></td>
    <td>Latest: <code>2017-06-19 18:04:15+01:00</code></td></tr>
<tr><td>Commits: <code>12</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: hard coded password

---

# GitHub search -> Windows integer
# BlueLotus_XSSReceiver

https://github.com/trysec/BlueLotus_XSSReceiver
<blockquote>
XSS平台 CTF工具 Web安全工具
</blockquote>

<table><tr>
<tr><td>Owner: <code>trysec</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2018-01-29 04:00:18+00:00</code></td>
    <td>Latest: <code>2017-05-26 11:18:40+08:00</code></td></tr>
<tr><td>Commits: <code>46</code></td>
    <td>Stargazers: <code>271</code></td>
    <td>Watchers: <code>271</code></td>
    <td>Forks: <code>69</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# PS4-4.0x-Code-Execution-PoC

https://github.com/Cryptogenic/PS4-4.0x-Code-Execution-PoC
<blockquote>
My edit of qwertyoruiopz 4.0x exploit PoC from http://rce.party/ps4
</blockquote>

<table><tr>
<tr><td>Owner: <code>Cryptogenic</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2017-04-05 00:20:00+00:00</code></td>
    <td>Latest: <code>2017-04-08 17:09:07-04:00</code></td></tr>
<tr><td>Commits: <code>7</code></td>
    <td>Stargazers: <code>63</code></td>
    <td>Watchers: <code>63</code></td>
    <td>Forks: <code>17</code></td></tr>
</table>
Keywords: rce poc, rce exploitation, rce exploit

---

# GitHub search -> Windows integer
# StrutsExploit

https://github.com/Svti/StrutsExploit
<blockquote>
Apache Struts Remote Code Execution
</blockquote>

<table><tr>
<tr><td>Owner: <code>Svti</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2017-03-08 02:37:41+00:00</code></td>
    <td>Latest: <code>2017-03-23 13:22:51+08:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>9</code></td>
    <td>Watchers: <code>9</code></td>
    <td>Forks: <code>6</code></td></tr>
</table>
Keywords: remote code execution exploit

---

# GitHub search -> Windows integer
# PocketBus

https://github.com/hansenji/PocketBus
<blockquote>
Rx based event bus that doesn't leak memory
</blockquote>

<table><tr>
<tr><td>Owner: <code>hansenji</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2016-02-21 15:13:34+00:00</code></td>
    <td>Latest: <code>2017-03-14 09:27:09-06:00</code></td></tr>
<tr><td>Commits: <code>38</code></td>
    <td>Stargazers: <code>5</code></td>
    <td>Watchers: <code>5</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: memory leak poc

---

# GitHub search -> Windows integer
# dyci-main

https://github.com/DyCI/dyci-main
<blockquote>
Dynamic Code Injection Tool for Objective-C
</blockquote>

<table><tr>
<tr><td>Owner: <code>DyCI</code></td>
    <td>Language: <code>Objective-C</code></td>
    <td>Started: <code>2012-10-31 06:56:39+00:00</code></td>
    <td>Latest: <code>2017-03-13 22:48:27+02:00</code></td></tr>
<tr><td>Commits: <code>235</code></td>
    <td>Stargazers: <code>1115</code></td>
    <td>Watchers: <code>1115</code></td>
    <td>Forks: <code>121</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# HttpPwnly

https://github.com/Danladi/HttpPwnly
<blockquote>
&amp;quot;Repeater&amp;quot; style XSS post-exploitation tool for mass browser control. Primarily a PoC to show why HttpOnly flag isn't a complete protection against session hijacking via XSS
</blockquote>

<table><tr>
<tr><td>Owner: <code>Danladi</code></td>
    <td>Language: <code>HTML</code></td>
    <td>Started: <code>2016-05-30 22:57:47+00:00</code></td>
    <td>Latest: <code>2017-03-04 20:54:55+00:00</code></td></tr>
<tr><td>Commits: <code>50</code></td>
    <td>Stargazers: <code>136</code></td>
    <td>Watchers: <code>136</code></td>
    <td>Forks: <code>48</code></td></tr>
</table>
Keywords: session hijacking

---

# GitHub search -> Windows integer
# fingertec-tool

https://github.com/FSecureLABS/fingertec-tool
<blockquote>
A tool for communicating with FingerTec access control devices, as well as other ZKTeco based devices
</blockquote>

<table><tr>
<tr><td>Owner: <code>FSecureLABS</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2017-01-04 13:31:36+00:00</code></td>
    <td>Latest: <code>2017-01-10 15:07:34+00:00</code></td></tr>
<tr><td>Commits: <code>3</code></td>
    <td>Stargazers: <code>20</code></td>
    <td>Watchers: <code>20</code></td>
    <td>Forks: <code>12</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# esp-vnc

https://github.com/sensepost/esp-vnc
<blockquote>
Our fork of the esp-link firmware with a built in VNC server for passing input events to an AVR. Part of our Universal Serial aBUSe project.
</blockquote>

<table><tr>
<tr><td>Owner: <code>sensepost</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2016-08-11 07:12:37+00:00</code></td>
    <td>Latest: <code>2016-12-07 14:44:27+02:00</code></td></tr>
<tr><td>Commits: <code>537</code></td>
    <td>Stargazers: <code>11</code></td>
    <td>Watchers: <code>11</code></td>
    <td>Forks: <code>5</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# ImpDump

https://github.com/HarmJoy/ImpDump
<blockquote>
This is a simple parser for/decrypter for Impacket's esentutl.py utility. It assists with decrypting hashes and hash histories from ntds.dit databases.
</blockquote>

<table><tr>
<tr><td>Owner: <code>HarmJoy</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2017-09-28 23:05:01+00:00</code></td>
    <td>Latest: <code>2016-12-05 09:26:00-05:00</code></td></tr>
<tr><td>Commits: <code>9</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# atom-bombing

https://github.com/BreakingMalwareResearch/atom-bombing
<blockquote>
Brand New Code Injection for Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>BreakingMalwareResearch</code></td>
    <td>Language: <code>C++</code></td>
    <td>Started: <code>2016-10-27 11:24:44+00:00</code></td>
    <td>Latest: <code>2016-10-28 20:24:05+03:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>732</code></td>
    <td>Watchers: <code>732</code></td>
    <td>Forks: <code>268</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# binnavi-gueb

https://github.com/montyly/binnavi-gueb
<blockquote>
Version of Binnavi used for the thesis &amp;quot;Finding the needle in the heap : combining binary analysis techniques to trigger use-after-free&amp;quot;
</blockquote>

<table><tr>
<tr><td>Owner: <code>montyly</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2018-03-23 11:13:27+00:00</code></td>
    <td>Latest: <code>2016-09-22 13:49:55+02:00</code></td></tr>
<tr><td>Commits: <code>280</code></td>
    <td>Stargazers: <code>10</code></td>
    <td>Watchers: <code>10</code></td>
    <td>Forks: <code>5</code></td></tr>
</table>
Keywords: use after free analysis

---

# GitHub search -> Windows integer
# pupy

https://github.com/zrohdes/pupy
<blockquote>
Pupy is an opensource, multi-platform (Windows, Linux, OSX, Android), multi function RAT (Remote Administration Tool) mainly written in python. It features a all-in-memory execution guideline and leaves very low footprint. Pupy can communicate using various transports, migrate into processes (reflective injection), load remote python code, pytho…
</blockquote>

<table><tr>
<tr><td>Owner: <code>zrohdes</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2018-08-03 03:46:47+00:00</code></td>
    <td>Latest: <code>2016-08-28 19:53:58+02:00</code></td></tr>
<tr><td>Commits: <code>548</code></td>
    <td>Stargazers: <code>5</code></td>
    <td>Watchers: <code>5</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: Windows remote code execution

---

# GitHub search -> Windows integer
# examine

https://github.com/vtorri/examine
<blockquote>
Examine, a memory leak checker on Windows
</blockquote>

<table><tr>
<tr><td>Owner: <code>vtorri</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2013-03-28 15:16:32+00:00</code></td>
    <td>Latest: <code>2016-06-04 06:59:01+02:00</code></td></tr>
<tr><td>Commits: <code>224</code></td>
    <td>Stargazers: <code>12</code></td>
    <td>Watchers: <code>12</code></td>
    <td>Forks: <code>4</code></td></tr>
</table>
Keywords: Windows memory leak

---

# GitHub search -> Windows integer
# Opee

https://github.com/alexzielenski/Opee
<blockquote>
Code Injection Platform for OS X
</blockquote>

<table><tr>
<tr><td>Owner: <code>alexzielenski</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2014-07-23 02:03:30+00:00</code></td>
    <td>Latest: <code>2016-06-01 06:22:45-07:00</code></td></tr>
<tr><td>Commits: <code>71</code></td>
    <td>Stargazers: <code>109</code></td>
    <td>Watchers: <code>109</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# OSX-Pineapple-Backdoor

https://github.com/dalofeco/OSX-Pineapple-Backdoor
<blockquote>
A collection of python-based scripts that exploit a privilege escalation vulnerability in OS X versions 10.10.2 - 10.10.5 and sets up a listening client that allows custom backdoor activities.
</blockquote>

<table><tr>
<tr><td>Owner: <code>dalofeco</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2016-05-27 00:06:40+00:00</code></td>
    <td>Latest: <code>2016-05-26 20:16:53-04:00</code></td></tr>
<tr><td>Commits: <code>5</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: escalation of privileges exploitation, escalation of privileges vulnerability, escalation of privileges exploit

---

# GitHub search -> Windows integer
# Tater

https://github.com/Kevin-Robertson/Tater
<blockquote>
Tater is a PowerShell implementation of the Hot Potato Windows Privilege Escalation exploit from @breenmachine and @foxglovesec
</blockquote>

<table><tr>
<tr><td>Owner: <code>Kevin-Robertson</code></td>
    <td>Language: <code>PowerShell</code></td>
    <td>Started: <code>2016-01-26 01:28:05+00:00</code></td>
    <td>Latest: <code>2016-04-21 23:04:10-04:00</code></td></tr>
<tr><td>Commits: <code>17</code></td>
    <td>Stargazers: <code>451</code></td>
    <td>Watchers: <code>451</code></td>
    <td>Forks: <code>116</code></td></tr>
</table>
Keywords: Windows escalation of privileges exploit, escalation of privileges exploitation, Windows escalation of privileges exploitation, Windows escalation of privileges, escalation of privileges exploit

---

# GitHub search -> Windows integer
# php-lfi

https://github.com/andolojm/php-lfi
<blockquote>
Local File Inclusion &amp;amp; Social Engineering Practice Site
</blockquote>

<table><tr>
<tr><td>Owner: <code>andolojm</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2015-11-11 16:06:08+00:00</code></td>
    <td>Latest: <code>2016-02-27 17:36:46-05:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: local file inclusion

---

# GitHub search -> Windows integer
# php-lfi

https://github.com/rollys/php-lfi
<blockquote>
Local File Inclusion &amp;amp; Social Engineering Practice Site
</blockquote>

<table><tr>
<tr><td>Owner: <code>rollys</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2017-09-19 05:56:44+00:00</code></td>
    <td>Latest: <code>2016-02-27 17:36:46-05:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: local file inclusion

---

# GitHub search -> Windows integer
# cve-2015-1538-1

https://github.com/jduck/cve-2015-1538-1
<blockquote>
An exploit for CVE-2015-1538-1 - Google Stagefright ‘stsc’ MP4 Atom Integer Overflow Remote Code Execution
</blockquote>

<table><tr>
<tr><td>Owner: <code>jduck</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2015-09-10 23:00:59+00:00</code></td>
    <td>Latest: <code>2015-09-10 10:36:10-05:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>205</code></td>
    <td>Watchers: <code>205</code></td>
    <td>Forks: <code>118</code></td></tr>
</table>
Keywords: remote code execution exploitation, remote code execution exploit

---

# GitHub search -> Windows integer
# cve-2015-1538-1

https://github.com/oguzhantopgul/cve-2015-1538-1
<blockquote>
An exploit for CVE-2015-1538-1 - Google Stagefright ‘stsc’ MP4 Atom Integer Overflow Remote Code Execution
</blockquote>

<table><tr>
<tr><td>Owner: <code>oguzhantopgul</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2015-09-09 16:28:30+00:00</code></td>
    <td>Latest: <code>2015-09-02 05:27:00-05:00</code></td></tr>
<tr><td>Commits: <code>4</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>12</code></td></tr>
</table>
Keywords: remote code execution exploitation, remote code execution exploit

---

# GitHub search -> Windows integer
# P2PSystemsProject

https://github.com/netankit/P2PSystemsProject
<blockquote>
Handles call initiation, termination, call busy and waiting; Performs interaction with DHT (Distributed Hash Table) and KX (Key Exchange) modules. Generates pseudo-identities of callee, based on the DH (Diffe-Hellman) Key Exchange method and maintains session between caller and callee. Uses the RTP protocol to stream/exchange audio over the network reliably in real-time. Also performs self calling to mitigate profiling attacks.
</blockquote>

<table><tr>
<tr><td>Owner: <code>netankit</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2015-08-12 18:32:54+00:00</code></td>
    <td>Latest: <code>2015-08-23 22:58:14+02:00</code></td></tr>
<tr><td>Commits: <code>74</code></td>
    <td>Stargazers: <code>6</code></td>
    <td>Watchers: <code>6</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: session attack

---

# GitHub search -> Windows integer
# xwaf

https://github.com/FallDi/xwaf
<blockquote>
Web application firewall based on rules; Protected from popular web-vulnerabilities such as SQL-injection, Path traversal, etc
</blockquote>

<table><tr>
<tr><td>Owner: <code>FallDi</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2013-09-23 15:17:18+00:00</code></td>
    <td>Latest: <code>2015-07-20 23:40:15+06:00</code></td></tr>
<tr><td>Commits: <code>15</code></td>
    <td>Stargazers: <code>3</code></td>
    <td>Watchers: <code>3</code></td>
    <td>Forks: <code>4</code></td></tr>
</table>
Keywords: path traversal vulnerability

---

# GitHub search -> Windows integer
# LPE-Common

https://github.com/sopeco/LPE-Common
<blockquote>
Common libraries used for DynamicSpotter and related performance analysis tools.
</blockquote>

<table><tr>
<tr><td>Owner: <code>sopeco</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2014-07-07 06:07:13+00:00</code></td>
    <td>Latest: <code>2015-03-06 19:38:37+01:00</code></td></tr>
<tr><td>Commits: <code>140</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>7</code></td></tr>
</table>
Keywords: lpe analysis

---

# GitHub search -> Windows integer
# libnice

https://github.com/shadeslayer/libnice
<blockquote>
Libnice is an implementation of the IETF's Interactive Connectivity Establishment (ICE) standard (RFC 5245) and the Session Traversal Utilities for NAT (STUN) standard (RFC 5389).  It provides a GLib-based library, libnice and a Glib-free library, libstun as well as GStreamer elements.  ICE is useful for applications that want to establish peer-to-peer UDP data streams. It automates the process of traversing NATs and provides security against some attacks. It also allows applications to create reliable streams using a TCP over UDP layer.  Existing standards that use ICE include Session Initiation Protocol (SIP) and XMPP Jingle.
</blockquote>

<table><tr>
<tr><td>Owner: <code>shadeslayer</code></td>
    <td>Language: <code>C</code></td>
    <td>Started: <code>2012-03-10 17:50:27+00:00</code></td>
    <td>Latest: <code>2015-02-11 12:37:51+00:00</code></td></tr>
<tr><td>Commits: <code>2209</code></td>
    <td>Stargazers: <code>74</code></td>
    <td>Watchers: <code>74</code></td>
    <td>Forks: <code>25</code></td></tr>
</table>
Keywords: session attack

---

# GitHub search -> Windows integer
# sirs

https://github.com/diogoleitao/sirs
<blockquote>
Network and Computer Security course project: node.js crawler/scanner to find SQLi, XSS and Path Traversal vulnerabilities
</blockquote>

<table><tr>
<tr><td>Owner: <code>diogoleitao</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2014-11-13 13:24:58+00:00</code></td>
    <td>Latest: <code>2014-12-05 17:25:44+00:00</code></td></tr>
<tr><td>Commits: <code>60</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: path traversal vulnerability

---

# GitHub search -> Windows integer
# thresher

https://github.com/cuplv/thresher
<blockquote>
Static heap reachability analysis for Java bytecode and Android memory leak finder.
</blockquote>

<table><tr>
<tr><td>Owner: <code>cuplv</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2013-02-08 17:09:30+00:00</code></td>
    <td>Latest: <code>2014-10-24 21:22:19-06:00</code></td></tr>
<tr><td>Commits: <code>232</code></td>
    <td>Stargazers: <code>32</code></td>
    <td>Watchers: <code>32</code></td>
    <td>Forks: <code>15</code></td></tr>
</table>
Keywords: memory leak analysis

---

# GitHub search -> Windows integer
# auto-patcher

https://github.com/mateor/auto-patcher
<blockquote>
smali patcher for Android code injection
</blockquote>

<table><tr>
<tr><td>Owner: <code>mateor</code></td>
    <td>Language: <code>Shell</code></td>
    <td>Started: <code>2012-09-02 19:36:43+00:00</code></td>
    <td>Latest: <code>2014-10-21 00:31:13-05:00</code></td></tr>
<tr><td>Commits: <code>1259</code></td>
    <td>Stargazers: <code>75</code></td>
    <td>Watchers: <code>75</code></td>
    <td>Forks: <code>42</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# LFilterView

https://github.com/lukagabric/LFilterView
<blockquote>
iOS Filter View - Checkbox and Radio
</blockquote>

<table><tr>
<tr><td>Owner: <code>lukagabric</code></td>
    <td>Language: <code>Objective-C</code></td>
    <td>Started: <code>2013-01-24 10:34:57+00:00</code></td>
    <td>Latest: <code>2014-06-21 22:16:57+02:00</code></td></tr>
<tr><td>Commits: <code>32</code></td>
    <td>Stargazers: <code>15</code></td>
    <td>Watchers: <code>15</code></td>
    <td>Forks: <code>3</code></td></tr>
</table>
Keywords: lfi

---

# GitHub search -> Windows integer
# safecurl

https://github.com/wkcaj/safecurl
<blockquote>
SSRF Protection Library for PHP - http://safecurl.fin1te.net
</blockquote>

<table><tr>
<tr><td>Owner: <code>wkcaj</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2014-05-12 19:14:14+00:00</code></td>
    <td>Latest: <code>2014-05-22 15:28:18+01:00</code></td></tr>
<tr><td>Commits: <code>11</code></td>
    <td>Stargazers: <code>73</code></td>
    <td>Watchers: <code>73</code></td>
    <td>Forks: <code>22</code></td></tr>
</table>
Keywords: ssrf

---

# GitHub search -> Windows integer
# Abraxas

https://github.com/youngdev/Abraxas
<blockquote>
Zero Day Exploit
</blockquote>

<table><tr>
<tr><td>Owner: <code>youngdev</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2014-03-16 04:53:48+00:00</code></td>
    <td>Latest: <code>2014-03-15 23:30:22-05:00</code></td></tr>
<tr><td>Commits: <code>115</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: zero-day exploitation, zero-day exploit

---

# GitHub search -> Windows integer
# mwr-tls

https://github.com/FSecureLABS/mwr-tls
<blockquote>
A collection of utilities for interacting with SSL and X509 Certificates on Android.
</blockquote>

<table><tr>
<tr><td>Owner: <code>FSecureLABS</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2013-02-06 09:39:39+00:00</code></td>
    <td>Latest: <code>2013-12-20 11:12:34+00:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>7</code></td>
    <td>Watchers: <code>7</code></td>
    <td>Forks: <code>8</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# SecretWord

https://github.com/SuperSpyTX/SecretWord
<blockquote>
Protects your moderators and administrators from getting exploited by session stealers and any other MITM attacks in Minecraft.
</blockquote>

<table><tr>
<tr><td>Owner: <code>SuperSpyTX</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2012-05-30 03:46:47+00:00</code></td>
    <td>Latest: <code>2013-09-02 18:08:21-05:00</code></td></tr>
<tr><td>Commits: <code>25</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: session attack

---

# GitHub search -> Windows integer
# JavaZone-Code-Injection

https://github.com/holyjak/JavaZone-Code-Injection
<blockquote>
Code for my Code Injection presentation on JavaZone 2011
</blockquote>

<table><tr>
<tr><td>Owner: <code>holyjak</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2011-04-08 15:17:00+00:00</code></td>
    <td>Latest: <code>2013-07-29 05:01:05-07:00</code></td></tr>
<tr><td>Commits: <code>20</code></td>
    <td>Stargazers: <code>13</code></td>
    <td>Watchers: <code>13</code></td>
    <td>Forks: <code>8</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# SQLol

https://github.com/SpiderLabs/SQLol
<blockquote>
A configurable SQL injection test-bed
</blockquote>

<table><tr>
<tr><td>Owner: <code>SpiderLabs</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2012-01-06 15:22:39+00:00</code></td>
    <td>Latest: <code>2013-07-19 16:15:43-05:00</code></td></tr>
<tr><td>Commits: <code>16</code></td>
    <td>Stargazers: <code>121</code></td>
    <td>Watchers: <code>121</code></td>
    <td>Forks: <code>47</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# bvapi

https://github.com/sensepost/bvapi
<blockquote>
Deprecated BroadView API Client - see https://bitbucket.org/checksec/bvapi
</blockquote>

<table><tr>
<tr><td>Owner: <code>sensepost</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2013-03-26 09:53:24+00:00</code></td>
    <td>Latest: <code>2013-03-27 10:03:30+02:00</code></td></tr>
<tr><td>Commits: <code>8</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: by_owner

---

# GitHub search -> Windows integer
# pysqli

https://github.com/sysdream/pysqli
<blockquote>
Python SQL injection framework
</blockquote>

<table><tr>
<tr><td>Owner: <code>sysdream</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2012-11-03 20:26:35+00:00</code></td>
    <td>Latest: <code>2013-03-25 22:51:59+01:00</code></td></tr>
<tr><td>Commits: <code>21</code></td>
    <td>Stargazers: <code>133</code></td>
    <td>Watchers: <code>133</code></td>
    <td>Forks: <code>36</code></td></tr>
</table>
Keywords: sql injection

---

# GitHub search -> Windows integer
# Disabler

https://github.com/miktam/Disabler
<blockquote>
Code injection in Android, presented on Devoxx conference
</blockquote>

<table><tr>
<tr><td>Owner: <code>miktam</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2012-11-05 14:30:56+00:00</code></td>
    <td>Latest: <code>2012-11-14 20:50:26+01:00</code></td></tr>
<tr><td>Commits: <code>19</code></td>
    <td>Stargazers: <code>44</code></td>
    <td>Watchers: <code>44</code></td>
    <td>Forks: <code>15</code></td></tr>
</table>
Keywords: code injection

---

# GitHub search -> Windows integer
# winfuzz

https://github.com/realhalo/winfuzz
<blockquote>
A security researching tool/fuzzer for windows that attempts to cause memory corruption scenarios in the form of integer and/or buffer overflows. (src currently offline)
</blockquote>

<table><tr>
<tr><td>Owner: <code>realhalo</code></td>
    <td>Language: <code>None</code></td>
    <td>Started: <code>2012-10-09 03:35:26+00:00</code></td>
    <td>Latest: <code>2012-10-08 23:40:07-04:00</code></td></tr>
<tr><td>Commits: <code>1</code></td>
    <td>Stargazers: <code>7</code></td>
    <td>Watchers: <code>7</code></td>
    <td>Forks: <code>3</code></td></tr>
</table>
Keywords: Windows corruption overflow, Win corruption overflow

---

# GitHub search -> Windows integer
# dlist_api

https://github.com/chrb22/dlist_api
<blockquote>
This is a project im doing for my programming classes at GU(Gentofte Youth school) Its a java library for importing into eclipse when doing an android app and a cross platform app for getting the 'duks' of the week ( duks is the person who is gonna clean the classroom after school) We are gonna have a server wich is gonna hold multiple schools and grades branches students etc. The java apps is supposed to use the api just for interfacing with the server and fetching data. its for easy and innovative administration of the 'duks'. If it becomes a succes well expand and add more features. Follow me for more info about the other subjects such as the server side scripts the client side scripts and the web interface. Feel free to download and modify, you can even put your own name on it... but i would love if you gave me credit! :D Im not working alone tho.. I have a full team of 5 including me. This is adams repo, he is doing the server stuff: github.com/theadamlt(Check out the server stuff...
</blockquote>

<table><tr>
<tr><td>Owner: <code>chrb22</code></td>
    <td>Language: <code>Java</code></td>
    <td>Started: <code>2011-11-24 16:22:03+00:00</code></td>
    <td>Latest: <code>2011-10-06 22:23:17+02:00</code></td></tr>
<tr><td>Commits: <code>2</code></td>
    <td>Stargazers: <code>0</code></td>
    <td>Watchers: <code>0</code></td>
    <td>Forks: <code>2</code></td></tr>
</table>
Keywords: cross-side-scripting

---

# GitHub search -> Windows integer
# montrain.fr

https://github.com/KuiKui/montrain.fr
<blockquote>
Simple, stable and unauthenticated instant messaging service for train users
</blockquote>

<table><tr>
<tr><td>Owner: <code>KuiKui</code></td>
    <td>Language: <code>PHP</code></td>
    <td>Started: <code>2011-04-24 16:10:38+00:00</code></td>
    <td>Latest: <code>2011-09-27 10:16:09+02:00</code></td></tr>
<tr><td>Commits: <code>24</code></td>
    <td>Stargazers: <code>1</code></td>
    <td>Watchers: <code>1</code></td>
    <td>Forks: <code>1</code></td></tr>
</table>
Keywords: unauthenticated user

---

# GitHub search -> Windows integer
# NoFix

https://github.com/BramBonne/NoFix
<blockquote>
A Firefox extension countering the Session Fixation and Session Hijacking attacks
</blockquote>

<table><tr>
<tr><td>Owner: <code>BramBonne</code></td>
    <td>Language: <code>JavaScript</code></td>
    <td>Started: <code>2011-02-13 12:03:09+00:00</code></td>
    <td>Latest: <code>2011-07-09 21:10:32+02:00</code></td></tr>
<tr><td>Commits: <code>23</code></td>
    <td>Stargazers: <code>4</code></td>
    <td>Watchers: <code>4</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: session hijacking attack, session attack, session hijacking

---

# GitHub search -> Windows integer
# rails_xss

https://github.com/NZKoz/rails_xss
<blockquote>
A plugin for rails 2.3.5 applications which switches the default to escape by default.  Later versions should use rails/rails_xss
</blockquote>

<table><tr>
<tr><td>Owner: <code>NZKoz</code></td>
    <td>Language: <code>Ruby</code></td>
    <td>Started: <code>2009-06-26 05:51:18+00:00</code></td>
    <td>Latest: <code>2010-05-25 10:04:28+12:00</code></td></tr>
<tr><td>Commits: <code>18</code></td>
    <td>Stargazers: <code>216</code></td>
    <td>Watchers: <code>216</code></td>
    <td>Forks: <code>39</code></td></tr>
</table>
Keywords: xss

---

# GitHub search -> Windows integer
# uaFrequency

https://github.com/emres/uaFrequency
<blockquote>
A highly organization specific set of scripts for the analysis of word frequencies
</blockquote>

<table><tr>
<tr><td>Owner: <code>emres</code></td>
    <td>Language: <code>Python</code></td>
    <td>Started: <code>2010-04-22 13:01:56+00:00</code></td>
    <td>Latest: <code>2010-05-18 11:44:44+02:00</code></td></tr>
<tr><td>Commits: <code>27</code></td>
    <td>Stargazers: <code>2</code></td>
    <td>Watchers: <code>2</code></td>
    <td>Forks: <code>0</code></td></tr>
</table>
Keywords: uaf analysis

---

