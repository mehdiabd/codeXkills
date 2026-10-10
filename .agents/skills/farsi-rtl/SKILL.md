---
name: farsi-rtl
description: Make the current answer readable in right-to-left Persian and English mixed text. Use when explicitly invoked with $farsi-rtl.
---

# Farsi RTL

Make the answer comfortable to read as right-to-left text, especially when Persian and English appear together. Do not translate everything into Persian: retain English technical terms, names, paths, URLs, and code where they are useful or natural. Use Persian for surrounding prose when the user writes in Persian or requests it; otherwise follow the user's requested language.

Keep mixed-direction fragments stable. Prefer short sentences and place English terms, numbers, paths, and punctuation so their reading order is unambiguous. Use inline code for standalone commands, identifiers, file paths, URLs, and other literal left-to-right fragments. For substantial Persian prose in an HTML-capable response, wrap the prose in a container with `dir="rtl"` and `lang="fa"`; keep code blocks and other inherently left-to-right content outside it or explicitly left-to-right. Avoid raw directional control characters unless necessary, because they are hard to inspect and copy. Preserve correct Markdown rendering and copyable code.
