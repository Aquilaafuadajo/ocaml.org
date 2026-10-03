---
title: How recurring network maintenance exposed 6 bugs
description: Jane Street does a lot of network maintenance over the weekends. In each
  maintenance, a cabinet may lose connectivity for 15 to 25 minutes. Our internal
  Kafk...
url: https://blog.janestreet.com/how-recurring-network-maintenance-exposed-6-bugs/
date: 2026-10-02T00:00:00-00:00
preview_image: https://blog.janestreet.com/how-recurring-network-maintenance-exposed-6-bugs/cover-maintenance-panel.jpg
authors:
- Jane Street Tech Blog
source:
---

<p>Jane Street does a lot of network maintenance over the weekends. In each maintenance, a
cabinet may lose connectivity for 15 to 25 minutes. Our internal Kafka infrastructure is
supposed to be resilient to these partitions, and reconnect when connectivity resumes. For
several months this year, it didn&rsquo;t: processes segfaulted, leaked hundreds of thousands of
sockets, or crashed in a surge of half a million TCP connections.</p>


