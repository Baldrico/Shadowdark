## Wizard Spells

```dataview
TABLE WITHOUT ID
link(file.name, name) AS Spell,
tier AS Tier,
duration AS Duration
FROM #spell
WHERE contains(class,"Wizard")
SORT tier ASC, file.name ASC
```
^spells-wizard
## Priest Spells

```dataview
TABLE WITHOUT ID
link(file.name, name) AS Spell,
tier AS Tier,
duration AS Duration
FROM #spell
WHERE contains(class,"Priest")
SORT tier ASC, file.name ASC
```
^spells-priest