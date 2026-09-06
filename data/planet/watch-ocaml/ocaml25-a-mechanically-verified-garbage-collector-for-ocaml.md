---
title: '[OCaml''25] A Mechanically Verified Garbage Collector for OCaml'
description: A Mechanically Verified Garbage Collector for OCaml (Video, OCaml 2025)
  Sheera Shamsu, Dipesh Kafle, Dhruv Maroo, Kartik Nagar, Karthikeyan Bhargavan, and
  KC Sivaramakrishnan (IIT Madras; NIT Trich...
url: https://watch.ocaml.org/w/irxZmnVsK5fB1TfrsK3xh3
date: 2026-01-27T20:38:10-00:00
preview_image: https://watch.ocaml.org/lazy-static/previews/018c85bc-bdf7-4162-9ce2-be13c7ec7294.jpg
authors:
- Watch OCaml
source:
---

<p>A Mechanically Verified Garbage Collector for OCaml (Video, OCaml 2025)<br/>
Sheera Shamsu, Dipesh Kafle, Dhruv Maroo, Kartik Nagar, Karthikeyan Bhargavan, and KC Sivaramakrishnan<br/>
(IIT Madras; NIT Trichy, Tiruchirappalli, India; IIT Madras, Chennai; IIT Madras; Cryspen, France; IIT Madras and Tarides)</p>
<p>Abstract: The GC is a critical component of the OCaml runtime system, and its correctness is essential for the safety of OCaml programs. Therefore, we propose a strategy for crafting a correct, proof-oriented GC from scratch, designed to evolve over time with additional language features. Our approach neatly separates abstract GC correctness from OCaml-specific GC correctness, offering the ability to integrate further GC optimizations, while preserving core abstract GC correctness. As an initial step to demonstrate the viability of our approach, we have developed a verified stop-the-world mark-and- sweep GC for OCaml. The approach is mechanized in F* and its low-level subset Low*. We use the KaRaMel compiler to compile Low* to C, and the verified GC is integrated with the OCaml runtime. Our GC is evaluated against off-the shelf OCaml GC and Boehm-Demers-Weiser conservative GC, and the experimental results show that verified GC is pragmatic.</p>
<p>Presentation at the OCaml 2025 workshop, Oct 17, 2025, <a href="https://conf.researchr.org/home/icfp-splash-2025/ocaml-2025" target="_blank" rel="noopener noreferrer">https://conf.researchr.org/home/icfp-splash-2025/ocaml-2025</a><br/>
Sponsored by ACM SIGPLAN.</p>

