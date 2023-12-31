---
title: {{ replace .File.ContentBaseName "-" " " | title }}
date: {{ .Date }}
archives:
  - {{ now.Format "2006" }}
  - {{ now.Format "2006-01" }}
---
