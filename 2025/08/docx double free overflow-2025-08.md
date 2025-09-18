## DuckDuckgo search -> docx double free overflow
`2025-08-22`

* https://book.hacktricks.wiki/en/binary-exploitation/libc-heap/double-free.html

<blockquote>
 DoubleFreeHackTricks
</blockquote>
<blockquote>
Double Free Basic Information If you free a block of memory more than once, it can mess up the allocator's data and open the door to attacks. Here's how it happens: when you free a block of memory, it goes back into a list of free chunks (e.g. the &quot;fast bin&quot;). If you free the same block twice in a row, the allocator detects this and throws an ...
</blockquote>

---

