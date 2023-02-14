Importe Switch depuis la bibliothèque picozero puis définis les broches pour plusieurs commutateurs, utilise le code suivant :

--- code ---
---
language: python filename: line_numbers: false line_number_start: 1
line_highlights:
---
from picozero import Switch

switch_1 = Switch(18) switch_2 = Switch(22) switch_3 = Switch(28)
--- /code ---

**Astuce**: Tu voudras peut-être donner à tes commutateurs des noms de variables qui se rapportent à ce qu'ils font. Par exemple, `interrupteur_rouge` pour allumer un feu rouge.

***
Ce projet a été traduit par des bénévoles:

[name]

[name]

[name]

Grâce aux bénévoles, nous pouvons donner aux gens du monde entier la chance d'apprendre dans leur propre langue. Vous pouvez nous aider à atteindre plus de personnes en vous portant volontaire pour la traduction - plus d'informations sur [rpf.io/translate](https://rpf.io/translate).
