# Dépôt pour la publication et la gestion du SILL

Ce dépôt sert pour la publication du Socle Interministériel de
Logiciels Libres en HTML et le suivi des logiciels référencés : mise à
jour des informations, entrées et sorties du Socle Interministériel de
Logiciels Libres.

Voir [ce site qui expose les données du
SILL](https://sill.etalab.gouv.fr) et [ce site qui explique le
fonctionnement des groupes](https://disic.github.io/sill/).

L'interface d'affichage du SILL est développée [sur ce
dépôt](https://github.com/etalab/sillweb).

# Modèle de données

- Clef primaire : `nom`
- Tous les champs sont de type "chaîne de caractère".

| Nom            | Description                           | Exemple                     | Propriétés         |
|----------------|---------------------------------------|-----------------------------|--------------------|
| annees         | Année(s) de présence dans le SILL     | 2018 ; 2019                 | Valeur obligatoire |
| composant      | Description du composant              | Test & Intégration          | Valeur obligatoire |
| contexte-usage | Cas d'usage du logiciel               | https://                    | Valeur optionnelle |
| fonction       | Fonctionnalité du logiciel            | Outil de traitement d'image | Valeur optionnelle |
| groupe         | Nom du groupe MIM responsable         | MIMDEV                      | Valeur obligatoire |
| label          | Lien vers catalogue.numerique.gouv.fr | https://catalogue...        | Valeur optionnelle |
| licence        | Licence du logiciel                   | GPL-3.0-only                | Valeur obligatoire |
| nom            | Nom du logiciel                       | Gimp                        | Valeur obligatoire |
| parent         | Logiciel parent                       | LibreOffice                 | Valeur optionnelle |
| public         | Logiciel porté par l'administration   | VITAM                       | Valeur optionnelle |
| support        | Présent dans le marché de support     | Apache HTTP server          | Valeur optionnelle |
| secteur        | Description du secteur                | Conception & Développement  | Valeur obligatoire |
| similaire-a    | Logiciels similaires                  | Redmine                     | Valeur optionnelle |
| statut         | Recommandé, en observation            | R                           | Valeur obligatoire |
| version        | Version recommandée                   | 1.0                         | Valeur obligatoire |
| wikidata       | Identifiant de l'entité Wikidata      | Q8038                       | Valeur optionnelle |

# Licence

Les Groupes Mutualisation Interministérielle et contributeurs du dépôt, 2019-2021.

Le contenu du SILL et de ce dépôt est sous [licence Ouverte 2.0](LICENCE.md).
