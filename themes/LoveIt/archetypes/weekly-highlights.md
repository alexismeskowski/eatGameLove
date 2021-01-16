---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
author: "Alexis Meskowski"
date: {{ .Date }}
description: ''
show_in_homepage: yes
show_description: yes
resources:
- name: featured-image
  src: ""
- name: featured-image-preview
  src: ""
math:
  enable: false
share:
  enable: true
comment:
  enable: true
---

<!-- draft: true -->
<!-- Featured Image: 780x234 -->
<!-- Links: [](){target="_blank"} -->

<br>

## Hello friends, {Summary} this week :)

{Short Summary}

<br>

```{r, echo=FALSE}
blogdown::shortcode("youtube", "")
```

<br>