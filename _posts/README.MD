## Post template

```

---
layout: post
title: 
posturl: 
tags: 
- 
---

## {{ page.title }}
<span style="font-size: 0.8em; line-height: 0.8em">Posted on {{ page.date | date: "%Y %B %-d" }} by <a href="https://twitter.com/polgarp">polgarp</a> &middot; Tagged in {{ page.tags | array_to_sentence_string }}</span>  
<span style="font-size: 0.8em; line-height: 0.8em">Original link: <{{page.posturl}}></span>  



<!--more-->
<a href="{{ site.baseurl }}">Back to home</a>

```
