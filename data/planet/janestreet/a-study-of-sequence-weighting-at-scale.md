---
title: A study of sequence weighting at scale
description: 'TL;DR: We study the scaling laws of data weighting across in-house and
  open-weight LMs, finding non-monotonic behavior across scales. We vary the weight
  assi...'
url: https://blog.janestreet.com/a-study-of-sequence-weighting-at-scale/
date: 2026-09-14T00:00:00-00:00
preview_image: https://blog.janestreet.com/a-study-of-sequence-weighting-at-scale/featimg.jpg
authors:
- Jane Street Tech Blog
source:
---

<p><em>TL;DR: We study the scaling laws of data weighting across in-house and open-weight LMs, finding non-monotonic behavior across scales.</em>
<em>We vary the weight assigned to sequences during training and measure how strongly the model&rsquo;s loss reduction on a sequence depends on the sequence&rsquo;s weight.</em>
<em>Taken together, our results are consistent with a general trend: as models transition from small to medium scale, they transition from learning general patterns independent of data weight to learning data-specific patterns proportional to the data weights.</em>
<em>As models then transition from medium to large scale they are able to learn all patterns present in the data, once again independent of data weight.</em></p>


