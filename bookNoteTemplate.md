---
tags:
  - book
status: 
title: "{{title}}"
author: "[[{{author}}]]"
category: "{{category}}"
pages: "{{totalPage}}"
thumbnail: "{{coverUrl}}"
---

![cover|150]({{coverUrl}})

# [[{{title}}]]

> {{description}}

<% await tp.file.move("/3 Resources/Books/" + tp.file.title) %>
