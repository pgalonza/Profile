---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
draft: false
description: "{{ replace .Name "-" " " | title }}"
summary: ""
---
