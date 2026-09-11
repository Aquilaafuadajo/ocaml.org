---
title: '[OCaml''25] Embedding WebAssembly in OCaml for Safe Program Construction'
description: 'Embedding WebAssembly in OCaml for Safe Program Construction (Video,
  OCaml 2025) Hunter DeMeyer (University of Illinois Urbana-Champaign) Abstract: WebAssembly
  (wasm) is a binary instruction format...'
url: https://watch.ocaml.org/w/ggxSZ98Y3XRoDonLBE4Xxs
date: 2026-01-27T21:37:35-00:00
preview_image: https://watch.ocaml.org/lazy-static/previews/e8d3c280-749a-4c2c-9152-b79406841a7e.jpg
authors:
- Watch OCaml
source:
---

<p>Embedding WebAssembly in OCaml for Safe Program Construction (Video, OCaml 2025)<br/>
Hunter DeMeyer<br/>
(University of Illinois Urbana-Champaign)</p>
<p>Abstract: WebAssembly (wasm) is a binary instruction format for a stack-based virtual machine originally designed to improve the safety and performance of client-side web applications. It has since gained popularity outside of the browser because of its portability and security guarantees. These features make it an ideal encoding for serialized representations of computation, and a critical format for modern programming languages to interface with. While existing OCaml libraries support standards development, symbolic execution, and compiling OCaml to wasm, they lack explicit facilities for manipulating wasm modules. The ability to construct and rewrite wasm code, as provided in Rust by tools such as wasm-bindgen and wirm, would elevate wasm&rsquo;s utility in the OCaml ecosystem. Leveraging OCaml&rsquo;s strong typing and powerful type inference can help to ergonomically make illegal wasm programs unrepresentable.<br/>
Inspired by TyXML and Hardcaml, I propose WasML: a library that enforces syntactic and semantic constraints in wasm programs via OCaml types. WasML enables OCaml programmers to build and rewrite wasm programs with a higher assurance of correctness at compile time, laying the foundation for future work on serializable computation and parameterized code generation.</p>
<p>Presentation at the OCaml 2025 workshop, Oct 17, 2025, <a href="https://conf.researchr.org/home/icfp-splash-2025/ocaml-2025" target="_blank" rel="noopener noreferrer">https://conf.researchr.org/home/icfp-splash-2025/ocaml-2025</a><br/>
Sponsored by ACM SIGPLAN.</p>

