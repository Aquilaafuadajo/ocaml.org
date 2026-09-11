---
title: '[OCaml''25] Taming the Flat Float Array Optimization: Tracking Separability
  in the Type System'
description: "Taming the Flat Float Array Optimization: Tracking Separability in the
  Type System (Video, OCaml 2025) Diana Kalinichenko, and Richard A. Eisenberg (Jane
  Street; Jane Street) Abstract: OCaml\u2019s flat..."
url: https://watch.ocaml.org/w/eAdpqFJRZUjYJjfQoXcda9
date: 2026-01-27T21:27:06-00:00
preview_image: https://watch.ocaml.org/lazy-static/previews/702af2fa-37b0-409c-a109-cb5ba81502a6.jpg
authors:
- Watch OCaml
source:
---

<p>Taming the Flat Float Array Optimization: Tracking Separability in the Type System (Video, OCaml 2025)<br/>
Diana Kalinichenko, and Richard A. Eisenberg<br/>
(Jane Street; Jane Street)</p>
<p>Abstract: OCaml&rsquo;s flat float array optimization stores floating-point values directly in arrays rather than through pointers, preventing performance degradation for numerical algorithms. However, this optimization requires that all types be \textit{separable} &mdash; containing either all float values or none. This restriction prevents certain useful types, such as unboxed existentials and an unboxed version of options. We present the approach taken by OxCaml (OCaml with Jane Street&rsquo;s extensions) to tracking separability through the type system using a three-valued separability axis. This design enables previously rejected non-separable types while maintaining compatibility with existing code and enabling new optimizations for arrays of known non-float types. Our implementation builds on OxCaml&rsquo;s kind system but could be adapted to vanilla OCaml.</p>
<p>Presentation at the OCaml 2025 workshop, Oct 17, 2025, <a href="https://conf.researchr.org/home/icfp-splash-2025/ocaml-2025" target="_blank" rel="noopener noreferrer">https://conf.researchr.org/home/icfp-splash-2025/ocaml-2025</a><br/>
Sponsored by ACM SIGPLAN.</p>

