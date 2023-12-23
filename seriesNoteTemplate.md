---
tags:
  - series
status: 
title: "{{Title}}"
release: "{{Year}}"
genre: "{{Genre}}"
rating: "{{Ratings}}"
runtime: "{{Runtime}}m"
Seasons: "{{totalSeasons}}"
thumbnail: "{{Poster}}"
---

![{{Title}}]({{Poster}})

# [[{{Title}} ({{Year}})]]

{{YoutubeEmbed}}

> {{Plot}}

- Actors: {{Actors}}
- Awards: {{Awards}}

<% await tp.file.move("/3 Resources/Series/" + tp.file.title) %>
