Importeer Switch uit de picozero-bibliotheek en stel vervolgens de pinnen in voor meerdere schakelaars, gebruik daarbij de volgende code:

--- code ---
---
language: python 
filename: 
line_numbers: false 
line_number_start: 1
line_highlights:
---
from picozero import Switch

schakelaar_1 = Switch(18) 
schakelaar_2 = Switch(22) 
schakelaar_3 = Switch(28)
--- /code ---

**Tip**: Misschien kun je je schakelaars variabele namen geven die betrekking hebben op wat ze doen. Bijvoorbeeld `rode_schakelaar` om een rood licht in te schakelen.
