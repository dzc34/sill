# Dépôt pour la publication et la gestion du SILL

Ce dépôt sert pour la publication du Socle Interministériel de
Logiciels Libres en HTML et le suivi des logiciels référencés : mise à
jour des informations, entrées et sorties du Socle Interministériel de
Logiciels Libres.

Voir [le site](https://disic.github.io/sill/).

L'interface d'affichage du SILL est développée [sur ce
dépôt](https://github.com/etalab/sillweb).

# Modèle de données

- Clef primaire : `nom`
- Tous les champs sont de type "chaîne de caractère".

| Nom             | Description                      | Exemple                     | Propriétés         |
|-----------------|----------------------------------|-----------------------------|--------------------|
| nom             | Nom du logiciel                  | Gimp                        | Valeur obligatoire |
| licence         | Licence du logiciel              | GPL-3.0-only                | Valeur obligatoire |
| statut          | Recommandé, en observation       | R                           | Valeur obligatoire |
| fonction        | Fonctionnalité du logiciel       | Outil de traitement d'image | Valeur obligatoire |
| composant       | Description du composant         | Test & Intégration          | Valeur obligatoire |
| secteur         | Description du secteur           | Conception & Développement  | Valeur obligatoire |
| version         | Version recommandée              | 1.0                         | Valeur obligatoire |
| parent          | Logiciel parent                  | LibreOffice                 | Valeur optionnelle |
| mots-clefs      | Mots-clefs assiociés             | image                       | Valeur optionnelle |
| formats         | Formats associés au logiciel     | odt                         | Valeur optionnelle |
| cas-usage       | Cas d'usage du logiciel          | https://                    | Valeur optionnelle |
| referent        | Administration référente         | DINUM                       | Valeur optionnelle |
| wikidata_entity | Identifiant de l'entité Wikidata | Q8038                       | Valeur optionnelle |
| utilisateurs    | Administrations utilisatrices    | DINUM, MINEFI               | Valeur optionnelle |

# Licence

Les Groupes Mutualisation Interministérielle et contributeurs du dépôt, 2019.

Le contenu du SILL et de ce dépôt est sous [licence Ouverte 2.0](LICENCE.md).
