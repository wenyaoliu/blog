---
title: Another R post of Docs
author: ''
date: '2022-05-21'
slug: another-r-post-of-docs
categories: []
tags: []
description: ''
lastmod: '2022-05-21T23:12:40-05:00'
images: []
type: docs
menu:
  learn:
    parent: "final"
weight: 650

contributors:
  - Wenyao Liu
programlang:
  - R
  - Python
cycleofdata:
  - Processing
  - Analysis
  - Sharing
---

# Hello

Hello, another trial

## Level 2

### Level 3

# Hi

## Level 2

### Level 3


```r
library(ggplot2)

x = seq(-1, 1, .01)
y = sin(x^3)/(1 + x^6)

ggplot(mapping = aes(x = x, 
                     y = y)) +
geom_line() +
geom_ribbon(aes(ymin = 0, 
                ymax = y), 
            fill = "pink", 
            alpha = 0.5) +
theme_void() 
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-1.png" width="672" />


```python
print("Hello")
```

```
## Hello
```

Python content
