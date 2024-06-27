---
title: How to install .deb file
author: vasu
date: 2024-06-27 14:20:00 +0530
categories: [Unix, Tutorial]
tags: [unix,ubuntu,installation]
render_with_liquid: false
---

This tutorial will guide you how to install a debian package.

## How do I install a .deb file via the command line?

Create a new file named `YYYY-MM-DD-TITLE.EXTENSION`{: .filepath} and put it in the `_posts`{: .filepath} of the root directory. Please note that the `EXTENSION`{: .filepath} must be one of `md`{: .filepath} and `markdown`{: .filepath}. If you want to save time of creating files, please consider using the plugin [`Jekyll-Compose`](https://github.com/jekyll/jekyll-compose) to accomplish this.

## Install a package

Basically, you can install packaged directly from the command line in ubuntu.

```

sudo dpkg -i DEB_PACKAGE

```

## Remove a package

Simmilarly, you can remove a package from terminal

```

sudo dpkg -r DEB_PACKAGE

```

[More Info](https://askubuntu.com/questions/40779/how-do-i-install-a-deb-file-via-the-command-line)
