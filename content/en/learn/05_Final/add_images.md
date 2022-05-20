---
title: "How to add images"
description: "Solutions to common problems."
lead: "Solutions to common problems."
date: 2020-11-12T15:22:20+01:00
lastmod: 2020-11-12T15:22:20+01:00
draft: false
images: []
type: docs
menu: 
  learn:
    parent: "05_Final"
weight: 620
toc: true
contributors: ["Wenyao Liu"]
programlang: 
---

When writing docs under Doks theme the images were strictly organized under [page bundle](https://gohugo.io/content-management/page-bundles/).

```bash
├── blog/
│   ├── say-hello-to-doks/
│   │   ├── index.md
│   │   └── say-hello-to-doks.png
│   └── _index.md
└── _index.md
```

If you want to refer to images not following the above structure, you can refer to images in hyperlink

```bash

[asf](/2022-05-19-18-31-12.png)
\![images](/2022-05-19-18-31-12.png)
\![images](/images/2022-05-19-18-31-14.png)

```

and will get:

[asf](/2022-05-19-18-31-12.png)
\![images](/2022-05-19-18-31-12.png)
\![images](/images/2022-05-19-18-31-14.png)

Or you can place images using html code:

```bash

<img src="/2022-05-19-18-31-12.png" height="150" width = "300" />

<img src="/images/2022-05-19-18-31-14.png" height="150" width = "300" />

<img src="/doks.png" height="150" width = "300" />

```

Then you can get images in place:

<img src="/2022-05-19-18-31-12.png" height="150" width = "300" />

<img src="/images/2022-05-19-18-31-14.png" height="150" width = "300" />

<img src="/doks.png" height="150" width = "300" />
