---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
author: "{{ $.Param "author.display_name" }}"
cover: "/img/cover.jpg"
tags: ["tagA", "tagB"]
date: {{ .Date }}
draft: true
---

Cut out summary from your post content here.

<!--more-->

The remaining content of your post.
