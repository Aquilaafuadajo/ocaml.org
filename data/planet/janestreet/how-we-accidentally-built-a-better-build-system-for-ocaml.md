---
title: How we accidentally built a better build system for OCaml
description: "A \u201Cbuild system\u201D is one of the most important tools in a developer\u2019s
  toolbox. Roughly, it figures out how to create runnable programs from a bunch of
  differe..."
url: https://blog.janestreet.com/how-we-accidentally-built-a-better-build-system-for-ocaml-index/
date: 2025-01-24T00:00:00-00:00
preview_image: https://blog.janestreet.com/how-we-accidentally-built-a-better-build-system-for-ocaml-index/dune-jenga.png
authors:
- Jane Street Tech Blog
source:
---

<p>A &ldquo;build system&rdquo; is one of the most important tools in a developer&rsquo;s
toolbox. Roughly, it figures out how to create runnable programs from
a bunch of different source files by calling out to the compiler,
setting up and executing test suites, and so on. Because you interact
with it daily, above all it has to be <a href="https://xkcd.com/303/">fast</a> &ndash;
but it also has to be flexible.</p>


