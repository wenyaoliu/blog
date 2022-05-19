---
title: "Troubleshooting2"
description: "Solutions to common problems."
lead: "Solutions to common problems."
date: 2020-11-12T15:22:20+01:00
lastmod: 2020-11-12T15:22:20+01:00
draft: false
images: []
type: docs
menu: 
  docs:
    parent: "02_analysis"
weight: 620
toc: true
contributors: ["Wenyao Liu"]
programlang: ["R"]
---

## Problems updating npm packages

Delete the `./node_modules` folder, and run again:

```bash
npm install
```

## Problems with cache

Delete the temporary directories:

```bash
npm run clean
```

