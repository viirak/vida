---
draft: true
title: "{{ replace .Name "-" " " | title }}"
description: ""
date: {{ .Date }}
lastmod: {{ .Date }}
cover: ""
images: ["{{ .Name | urlize }}.jpg"]
---