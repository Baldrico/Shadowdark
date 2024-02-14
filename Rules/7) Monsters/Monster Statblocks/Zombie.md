# [[<% tp.file.title %>]]

*<% tp.frontmatter.Description %>*

AC: **<% await tp.frontmatter["AC"] %>**
HP: **<% await tp.frontmatter.HP %>**
MV: **<% await tp.frontmatter.MV %>**

ATK: **<% await tp.frontmatter.ATK %>**
TxC: ** Dmg: **

| STR                           | DEX                            | CON                               | INT                               | WIS                         | CHA                           |
| ----------------------------- | ------------------------------ | --------------------------------- | --------------------------------- | --------------------------- | ----------------------------- |
| <% await tp.frontmatter.Strength %> | <% await tp.frontmatter.Dexterity %> | <% await tp.frontmatter.Constitution %> | <% tp.frontmatter.Intelligence %> | <% tp.frontmatter.Wisdom %> | <% tp.frontmatter.Charisma %> |
 ^stats

Alignment: **<% await tp.frontmatter.Alignment %>**
Level: **<% await tp.frontmatter.Level %>**

### Abilità
<% tp.frontmatter.Abilities.map(prop => {
  const [ability, description] = Object.entries(prop)[0];
  const formattedAbility = `* *${ability}*. ${description}`;
  return formattedAbility;
}).join("\n") %>

### Note

---
<% await tp.frontmatter.System %>
<% await tp.file.creation_date('DD/MM/YY') %>
