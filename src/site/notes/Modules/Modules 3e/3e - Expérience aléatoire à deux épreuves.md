---
{"dg-publish":true,"permalink":"/modules/modules-3e/3e-experience-aleatoire-a-deux-epreuves/","title":"Expérience aléatoire à deux épreuves","dg-note-properties":{"title":"Expérience aléatoire à deux épreuves","description":null,"tags":null,"theme":"Gestion de données","niveaux":["3e"]}}
---

# Expérience aléatoire à deux épreuves
>[!definition] Définition :
>Une **expérience aléatoire à deux épreuves** est une succession de deux épreuves aléatoires. Une issue est un **couple** formé par les deux issues obtenues lors de chaque expérience.

>[!exemple] Exemple :
>Une urne contient 4 boules rouges et deux boules vertes indiscernables au toucher. On tire deux fois de suite, avec remise, une boule dans l’urne et on note les couleurs obtenues.
>
>Quelle est la probabilité de l’événement $A$ : `les deux boules sont de la même couleur` ?
>
>On peut résoudre ce problème en faisant un **tableau à double entrée** :
>
>|       | R      | R      | R      | R      | V   | V   |
>| ----- | ------ | ------ | ------ | ------ | --- | --- |
>| **R** | ==RR== | ==RR== | ==RR== | ==RR== | RV  | RV  |
>| **R** | ==RR== | ==RR== | ==RR== | ==RR== | RV  | RV  |
>| **R** | ==RR== | ==RR== | ==RR== | ==RR== | RV  | RV  |
>| **R** | ==RR== | ==RR== | ==RR== | ==RR== | RV  | RV  |
>| **V** | VR     | VR     | VR     | VR     | ==VV==  | ==VV==  |
>| **V** | VR     | VR     | VR     | VR     | ==VV==  | ==VV==  |
>
>La probabilité que les deux boules soient de la même couleur regroupe les issues $RR$ et $VV$.
>Il y a 20 issues favorables sur 36 issues au total. La probabilité de $A$ est donc $P(A)=\frac{20}{36}=\frac{5}{9}$.

