---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
author: Alexis Meskowski
date: {{ .Date }}
description: ''
show_in_homepage: yes
show_description: yes
resources:
- name: featured-image
  src: stream highlights {ENTER NUMBER} blog preview.png
- name: featured-image-preview
  src: stream highlights {ENTER NUMBER} blog preview.png
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

## Hello friends, {Summary}

{Short recipe summary w/ links }

<br>

```{r, echo=FALSE}
blogdown::shortcode("youtube", "")
```

<br>

---

### Notes:

-