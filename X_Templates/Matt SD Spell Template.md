---
name: <% title = await tp.system.prompt("Please enter a value") %>
aliases: 
tier: 
class: 
duration: 
range: 
source: Core
aliases:
tags:
  - spell
---

>[!summary]
> *Tier* {{}}
> <% tp.frontmatter.class.map(prop => `${prop}`).join(", ") %>
> *Duration*: <% tp.frontmatter.duration %>
> *Range*: <% tp.frontmatter.range %>
> 
> *Source:* <% tp.frontmatter.source %>