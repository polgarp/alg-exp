## Post template

```

---
layout: post
title: 
posturl: 
tags: 
- 
---

## [{{ page.title }}]({{page.posturl}})
<small>Posted on {{ page.date | date: "%Y %B %-d" }} by <a href="https://twitter.com/polgarp">polgarp</a> &middot; Tagged in {{ page.tags | array_to_sentence_string }}</small>  
<small>Original link: <{{page.posturl}}></small>



<!--more-->
<a href="http://twitter.com/share?text={{page.title}}&url={{site.site_baseurl}}{{page.url}}&via=polgarp" target="_blank">Tweet this post</a> &#x25cf; <a href="{{ site.baseurl }}">Back to home</a>

```
