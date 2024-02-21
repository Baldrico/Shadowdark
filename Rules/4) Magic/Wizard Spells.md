```dataview
TABLE WITHOUT ID
link(file.name, name) AS Spell,
tier AS Tier,
duration AS Duration,
range AS Range
FROM #spell
WHERE contains(caster,"Wizard")
SORT tier ASC, file.name ASC
```
^spells-wizard