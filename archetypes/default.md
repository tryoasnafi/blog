---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: {{ .BaseFileName }}
date: {{ .Date }}
publishdate: {{ now.Format "2006-01-02" }}
lastmod: {{ now.Format "2006-01-02" }}
draft: true

type: page

image: ""
description: ""
---
