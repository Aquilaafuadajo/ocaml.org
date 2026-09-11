---
title: strace-ui, Bonsai_term, and the TUI renaissance
description: "We\u2019ve always found strace useful but somewhat hard to work with.
  Its output is often inscrutable, it\u2019s hard to follow subprocesses or threads,
  and if you wan..."
url: https://blog.janestreet.com/strace-ui-bonsai-term-and-the-tui-renaissance/
date: 2026-05-26T00:00:00-00:00
preview_image: https://blog.janestreet.com/strace-ui-bonsai-term-and-the-tui-renaissance/bonsai-trees.gif
authors:
- Jane Street Tech Blog
source:
---

<p>We&rsquo;ve always found strace useful but somewhat hard to work with. Its output is often
inscrutable, it&rsquo;s hard to follow subprocesses or threads, and if you want to filter
syscalls you have to rerun the trace with a flag for each one. What you want in debugging
is a tool for exploring, refining, etc., but strace can make this difficult.</p>


