---
tags:
  - game
status: 
title: "{{name}}"
developer: "{{developers}}"
release: "{{released}}"
genre: "{{genres}}"
platform: "{{platforms}}"
rating: "{{metacritic}}/100"
playtime: "{{playtime}}h"
thumbnail: "{{background_image}}"
---

![{{name}}]({{background_image}})

# [[{{name}}]]

> {{description_raw}}

<% await tp.file.move("/3 Resources/Games/" + tp.file.title) %>
