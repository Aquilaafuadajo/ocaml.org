---
title: Can you reverse engineer our neural network?
description: "A lot of \u201Ccapture-the-flag\u201D style ML puzzles give you a black
  box neural net, and your job is to figure out what it does. When we were thinking
  of creating o..."
url: https://blog.janestreet.com/can-you-reverse-engineer-our-neural-network/
date: 2026-02-24T00:00:00-00:00
preview_image: https://blog.janestreet.com/can-you-reverse-engineer-our-neural-network/puzzle.png
authors:
- Jane Street Tech Blog
source:
---

<p>A lot of &ldquo;capture-the-flag&rdquo; style ML puzzles give you a black box neural net, and your job
is to figure out what it does. When we were thinking of creating our <a href="https://huggingface.co/spaces/jane-street/puzzle">own ML
puzzle</a> early last year, we wanted to do
something a little different. We thought it&rsquo;d be neat to give users a complete
specification of the neural net, weights and all. They would then be forced to use the
tools of mechanistic interpretability to reverse engineer the network&mdash;which is a
situation we sometimes find ourselves facing in our own research, when trying to interpret
features of complex models.</p>


