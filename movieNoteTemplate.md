---
tags:
  - movie
status: 
title: "{{Title}}"
release: "{{Year}}"
genre: "{{Genre}}"
rating: "{{Ratings}}"
runtime: "{{Runtime}}m"
thumbnail: "{{Poster}}"
---

![{{Title}}]({{Poster}})

# [[{{Title}} ({{Year}})]]

{{YoutubeEmbed}}

> {{Plot}}

- Director: {{Director}}
- Actors: {{Actors}}
- Box Office: {{BoxOffice}}
- Awards: {{Awards}}

<% await tp.file.move("/3 Resources/Movies/" + tp.file.title) %>
