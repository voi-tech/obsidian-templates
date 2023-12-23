---
tags:
  - daily
---

# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, DD MMMM YYYY") %>

> [!weather]
> {{weather}}

> [!calendar]
> {{calendar}}

> [!todo]
> {{tasks}}

---

## Notes

```dataview
LIST 
WHERE file.cday = this.file.day AND file.name != this.file.name
SORT file.ctime ASC
```
