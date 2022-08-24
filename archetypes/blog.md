---
title: "{{ replace .Name "-" " " | title }}"
slug: {{ .Name }}
cover: img/blog/sample.jpg

description: "Text that forms the lede, informing readers quickly and efficiently about what's most interesting in this post's contents."

categories: Game design
tags:
- one
- two

date: {{ .Date }}
feature: true
draft: true
---

Lorem ipsum.
