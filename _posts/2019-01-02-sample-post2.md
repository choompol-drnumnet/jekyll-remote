---
title: 'Sample Post2'
date: 2019-01-02
permalink: /2019/01/02/sample-post2/
categories:
  - teaching
  - advising
  - scholarship
  - history
  - policy
  - Educational Studies
  - Trinity College
  - Hartford
  - community engagement
  - technology
  - tutorial
  - GitHub
  - data visualization
  - web writing
---
### Link to sample.PDF in uploads 2019 with pre-slash
- [link to PDF](/uploads/2019/sample.pdf)

### Link to sample.PDF in uploads 2019 without pre-slash
- [link to PDF](uploads/2019/sample.pdf)

### Sample image with standard markdown in uploads 2019 with pre-slash
![sample caption](/uploads/2019/sample2-300x200.jpg)

does not work *without* pre-slash, and probably does not work *with* pre-slash

### Sample image in uploads 2019 (bridge) with Liquid
{% include figure image_path="uploads/2019/sample2-300x200.jpg" alt="sample image" caption="sample caption" %}

### Sample image in uploads (plain) with Liquid
{% include figure image_path="/uploads/sample-300x200.jpg" alt="sample image" caption="sample caption" %}

### Sample image alignment (right or left) with Liquid
{% include figure image_path="/uploads/2019/sample2-300x200.jpg" alt="sample image" caption="sample caption" %}{: .align-right}
This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing.

### Sample YouTube
{% include video id="3sK7-g0otGM" provider="youtube" %}
