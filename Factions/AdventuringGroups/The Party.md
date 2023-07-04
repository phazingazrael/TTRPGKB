---
aliases: [The Party]
creation_date: <%+ tp.file.creation_date("dddd Do MMMM YYYY HH:mm:ss") %>
linter-yaml-title-alias: The Party
modification_date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
tags: []
title: The Party
---
# The Party


```dataview
table player as "Player"
from #Player and !"Obsidian"
sort player 
```