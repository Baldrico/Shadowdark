---
name: <% title = await tp.system.prompt("Please enter a value") %>
aliases: 
tier: 
class: 
duration: 
range: 
source: Core
tags:
  - spell
---



<% await tp.file.move("DM/Compendium/Spells/"+tp.file.title) %>

```button
name Applica Template
type append template
action spell_template
remove true
color green
```
