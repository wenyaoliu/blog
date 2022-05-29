---
title: "How to update content"
description: "Regularly update the installed npm packages to keep your Doks website stable, usable, and secure."
lead: "Regularly update the installed npm packages to keep your Doks website stable, usable, and secure."
date: 2020-11-12T13:26:54+01:00
lastmod: 2020-11-12T13:26:54+01:00
draft: false
images: []
type: docs
menu:
  learn:
    parent: "final"
weight: 610
toc: true
contributors: ["Wenyao Liu"]
cycleofdata: ["Processing", "Analysis", "Sharing"]
programlang: ["R", "Python"]
---

## Create

Create new content for your site:

```bash
npm run create [path] [flags]
```

See also the Hugo docs: [hugo new](https://gohugo.io/commands/hugo_new/).

### Docs based tree

Create a docs based tree — with a single command:

```bash
npm run create -- --kind docs [section]
```

For example, create a docs based tree named learn:

```bash
npm run create -- --kind docs learn
```

The command for creating docs sections under existing "learn" folder

```bash
npm run create -- --kind docs learn/03_Sharing
```

## Start

Start local development server:

```bash
npm run start
```

## Build

Build production website:

```bash
npm run build
```

### preview

Build production website including draft and future content:

```bash
npm run build:preview
```

### functions

Build Lambda functions:

```bash
npm run build:functions
```

## clean

Delete temporary directories:

```bash
npm run clean
```

## lint

Check scripts, styles, and markdown for errors:

```bash
npm run lint
```

### scripts

Check scripts for errors:

```bash
npm run lint:scripts [-- --fix]
```

### styles

Check styles for errors:

```bash
npm run lint:styles [-- --fix]
```

### markdown

Check markdown for errors:

```bash
npm run lint:markdown [-- --fix]
```
