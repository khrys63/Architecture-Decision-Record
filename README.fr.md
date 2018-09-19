# Architecture Decision Record 

L'architecture decision record (ADR) est un document permettant de tracer toutes les décisions d'architecture prises sur la conception d'un produit, en précisant le contexte et en mesurant les conséquences.

Cette pratique a été classée dans la catégorie ADOPT par Thoughworks en novembre 2017.

## Qu'est ce que l'ADR ?

L'architecture decision record (ADR) est un document permettant de tracer toutes les décisions d'architecture prises sur la conception d'un produit, en précisant le contexte et en mesurant les conséquences.

Une décision d'architecture est un choix d'implémentation réalisée dans un produit pour respecter une exigence.

Un éxigence est un élément contraignant affectant un produit de façon mesurable.

Le Catalogue des décisions regroupe l'ensemble des ADR d'un produit.

Le but de ce projet est de fournir le guide de bonnes pratiques afin de tracer toutes vos décisions d'architecture ainsi qu'un template d'ADR à appliquer à vos produits.

## Comment initialiser le catalogue de décisions

Rien de plus simple, il suffit de créer un répertoire à la racine de votre projet.

Ensuite pour chaque décision, il suffira de créer un fichier, de renseigner la décision dedans puis de le committer.

## Convention de nommage

Nous allons utiliser une convention de nommage assez simple.

La convention de nommage :
```
On préfixe avec la date AAAAMMJJ.
On affiche la décision.
On utilise l'extension Markdown.
```

Exemples :
```
20180102_Choose_js_framework.md
20180210_Choose_graph_database.md
20180601_Replace_js_framework.md
```

## Contenu

Une décision d'architecture doit toujours respecter les pratiques suivantes :
- Etre datée. Quand la décision a été prise.
- Etre rationnelle. Il faut expliquer pourquoi la décision a été prise.
- Etre immuable. Le contenu d'une décision n'est pas modifiable. 
- Etre unique. Elle ne doit décrire qu'une seule décision.

Le contexte doit toujours être précisé. Il faut expliquer pourquoi la décision a été prise :
- Priorité business à adresser rapidement.
- Choix d'organisation.
- Compétences dans l'équipe.

Les conséquences doivent être mesurées :
- Bonne approche. Le choix est pertinent et sera stable dans le temps.
- Mauvais choix sous contrainte. Expliquer ce qui peut se passer et ce qui sera à surveiller.

Une décision d'architecture peut remplacer une ancienne décision :
- Identifier l'ADR remplacée et la renseigner dans la nouvelle décision.


## Sources

- [ThoughtWorks - Lightweight Architecture Decision Records](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records)
- [joelparkerhenderson/architecture_decision_record](https://github.com/joelparkerhenderson/architecture_decision_record)