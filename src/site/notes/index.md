---
{"dg-publish":true,"permalink":"/index/","title":"Accueil","pinned":true,"tags":["gardenEntry"],"dg-note-properties":{"title":"Accueil","description":"Modules pour apprendre les mathématiques.","draft":false}}
---

# Bienvenue sur MorganDesk

Ressources et modules de mathématiques conçus pour le collège, entièrement mis à jour en accord avec la **réforme des programmes 2026**.

> 💡 **Astuces de navigation :** 
> - Sur ordinateur, passez votre curseur sur un lien pour afficher un aperçu de la page. Cliquez sur le lien pour accéder à la page. Site optimisé pour écran large.
> - Utilisez les liens **Réviser** et **Approfondir** en fin de page pour naviguer entre notions connexes.
> ⚠️ Les notions sont en cours de construction, il est possible que certains liens n’aient pas de cible.

# Comment utiliser ce site ?
* **Interconnexion :** Les modules sont indépendants mais liés entre eux pour faire des ponts entre les notions.
* **Navigation :** Suivez les liens internes pour réviser un rappel ou approfondir un concept.
* **Entraînement :** Chaque module intègre des liens directs vers des exercices dédiés (en cours de création).

# Les séquences
[[10 Séquences/5ème/Toutes les séquences de 5ème\|Toutes les séquences de 5ème]]


```base
views:
  - type: table
    name: Tableau
    filters:
      and:
        - file.inFolder("Modules")
        - file.name != "index"
        - file.ext != "base"
    order:
      - file.name
      - description
      - theme
      - niveaux
      - dg-publish
      - dg-hide
    sort:
      - property: niveaux
        direction: ASC
      - property: file.name
        direction: ASC
      - property: draft
        direction: DESC
    columnSize:
      file.name: 156
      note.description: 644
      note.theme: 146
      note.niveaux: 107

```

