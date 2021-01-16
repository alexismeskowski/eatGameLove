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

Amount of servings: 4

:::: {style="display: grid; grid-template-columns: 1fr 1fr; grid-column-gap: 10px;"}

::: {}

### <u>Ingredients</u>

- {Ingrediant 1}
- {Ingrediant 2}

::: 

::: {}

### <u>Preparation</u> 

1. {Step 1}
1. {Step 2}

:::

::::

<br>

---

### Notes:

-