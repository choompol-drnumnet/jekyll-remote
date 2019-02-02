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
### Markdown image in pre-slash baseurl root images
![sample caption](/jekyll-remote/images/lobster-root-300x300.jpg)

### Markdown image in no-slash baseurl root images
![sample caption](jekyll-remote/images/lobster-root-300x300.jpg)

## FIX PDFs later

### Link to sample.PDF in pre-slash repo-assets-2019 with pre-slash
- [link to PDF](/jekyll-remote/assets/2019/sample.pdf)

### Link to sample.PDF in no-slash repo-assets-2019
- [link to PDF](jekyll-remote/assets/2019/sample.pdf)

### Link to sample.PDF in pre-slash assets-2019
- [link to PDF](/assets/2019/sample.pdf)

### Link to sample.PDF in no-slash assets-2019
- [link to PDF](assets/2019/sample.pdf)


### Sample image in assets 2019 with Liquid
{% include figure image_path="assets/2019/sample-post-image-300x200.jpg" alt="sample image" caption="sample caption" %}

### Sample image in assets with Liquid with pre-slash
{% include figure image_path="/assets/sample-post-image-300x200.jpg" alt="sample image" caption="sample caption" %}

### Sample image alignment (right or left) with Liquid
{% include figure image_path="/assets/2019/sample-post-image-300x200.jpg" alt="sample image" caption="sample caption" %}{: .align-right}
This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing. This is Liquid format with sample text, with space for caption, for alignment testing.

### Sample YouTube
{% include video id="3sK7-g0otGM" provider="youtube" %}
