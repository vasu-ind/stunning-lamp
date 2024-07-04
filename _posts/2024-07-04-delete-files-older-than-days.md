---
title: How to delete files older than X days
author: vasu
date: 2024-07-04 12:10:00 +0530
categories: [Unix, HowTo]
tags: [unix,delete,find]
render_with_liquid: false
---

This tutorial will guide you how to find and delete files older than x days.

## How do I delete files older than x days via command line?


### using find command

```

find /path/to/dir -mindepth 1 -mtime +5 -delete

```

[More Info](https://unix.stackexchange.com/questions/194863/delete-files-older-than-x-days)
