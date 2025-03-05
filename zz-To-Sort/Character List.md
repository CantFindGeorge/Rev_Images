[[Character Ideas]]

---
# IRL
```dataview
Table charIRL_Gender, charIRL_Age, charIRL_Occupation
FROM "My Game/Characters" 
WHERE contains(char_Species,"IRL")
SORT file.name ASC
SORT char_Class ASC
```

---
# AI
```dataview
Table char_Class, char_Sex
FROM "My Game/Characters" 
WHERE contains(char_Species,"AI")
SORT file.name ASC
SORT char_Class ASC
```

# NPCs
```dataview
Table char_Class, char_Sex
FROM "My Game/Characters" 
WHERE contains(char_Species,"NPC")
SORT file.name ASC
SORT char_Class ASC
```

# Player Characters
```dataview
Table char_Class, char_Sex
FROM "My Game/Characters" 
WHERE contains(char_Species,"Player Character")
SORT file.name ASC
SORT char_Class ASC
```

---
# All Characters
```dataview
Table char_Species, char_Class, char_Sex
FROM "My Game/Characters" 
SORT file.name ASC
SORT char_Species ASC
SORT char_Class ASC
```


