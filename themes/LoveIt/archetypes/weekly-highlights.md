---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
author: Alexis Meskowski
date: {{ .Date }}
description: ''
show_in_homepage: yes
show_description: yes
resources:
- name: featured-image
  src: {File Name}.png
- name: featured-image-preview
  src: {File Name}.png
math:
  enable: false
share:
  enable: true
comment:
  enable: true
draft: false
---

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