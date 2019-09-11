Ce document présente une synthèse des problèmes identifiés lors de la réunion de juin 2019, ainsi qu'une liste de propositions d'évolutions.

Vous pouvez commenter ces propositions dans les issues correspondantes ou directement par email en écrivant à [Bastien](mailto:bastien.guerry@data.gouv.fr).


# Problèmes identifiés


## #1: Manque de clarté sur le soutien de la DINSIC

Avant 2019, la DINSIC faisait valider le SILL par les DSI des ministères en CSIC-TECH.  Aujourd'hui, la DINSIC ne fait plus valider le SILL ainsi.  La DINSIC ne fait que relayer la publication du SILL sans le publier directement.


## #2: Manque de clarté et de respect des critères d'entrée

Aujourd'hui, la liste des critères existe mais elle n'est pas facilement accessible (pour ceux qui ne sont pas dans les groupes MIM), rien n'indique dans le document publié que tous les critères sont respectés et certains ne le sont pas.


## #3: Manque de référents

Les groupes MIM ont du mal à mobiliser des référents pour les souches présentes dans le SILL et pour d'autres qui pourraient y entrer.


## #4: Difficulté de coordination opérationnelle des groupes MIM

Il existe trois documents distincts pour le suivi des souches présentes dans le sill, un pour chaque groupe MIMO, MIMDEV et MIMPROD, sur trois outils différents.  Publier un document unique pour le SILL nécessite chaque année un travail d'harmonisation fastidieux.


# Propositions


## #1: [Retravailler les catégories de recommandation](https://github.com/DISIC/sill/issues/20)

Aujourd'hui, le SILL distingue trois niveaux :

1.  les souches libres *recommandées* (`R`)
2.  les souches libres *en observation* (`O`)
3.  les souches libres *en fin de recommandation* (`FR`)

La proposition consiste à proposer ces niveaux :

1.  les souches libres *recommandées* (`R`)
2.  les souches libres *en observation* (`O`)
3.  les souches libres *en usage* (`U`)

Les souches en fin de recommandation ne feraient plus partie du SILL (mais la mise à jour du SILL indiquerait la liste des souches qui en sortent) et les souches *en usage* seraient des logiciels utilisés sans avoir cocher tous les critères pour atteindre le niveau *recommandé*.


## #2: [Distinguer deux rôles : "référent" et "utilisateur"](https://github.com/DISIC/sill/issues/21)

Aujourd'hui, un référent est une personne dont le nom n'apparaît pas publiquement sur le SILL mais qui est la personne ressource pour les groupes MIM quand ceux-ci cherchent des informations sur une souche.  Aucune souche n'entre dans le SILL sans référent.

La proposition consiste à distinguer deux rôles :

-   **Référent:** la personne « porte » la souche dans les groupes MIM.

-   **Utilisateur (ou « porteur »):** la personne se déclare utilisateur d'une souche qui est soit *recommandée* (`R`) soit simplement *utilisée* (`U`) cf. la proposition #0.

Une souche pourrait entrer en *recommandation* (`R`) seulement si elle a un *référent*.  Mais une souche portée seulement par un *utilisateur* pourrait entrer en *observation* (`O`) et/ou en *utilisation* (`U`).


## #3: [Mieux définir les « critères » d'entrée dans le SILL](https://github.com/DISIC/sill/issues/22)

Aujourd'hui, la liste des critères est publiée dans un document interne aux groupes MIM.

Nous proposition de les réorganiser en (1) **prérequis** (pour tous les niveaux), (2) **critères** obligatoires pour le niveau *recommandé* (`R`) et en (3) informations complètementaires (pour tous les niveaux `R`, `O` et `U`.)

**Prérequis pour tous les niveaux :**

-   Le code source du logiciel est publié sous l'une des licences libres reconnue par la FSF ou l'OSI, sans délai de publication entre le code source et la version exécutable.

**Critères obligatoires pour le niveau *recommandé* (`R`) :**

-   Il existe un **référent** (pas seulement un utilisateur) pour le logiciel libre comme recommandé au sein des groupes MIM.

-   Le logiciel est **utilisé significativement** dans au moins un ministère ou un organisme public.

-   Un ministère ou organisme public qui a un usage significatif du logiciel a publié **des informations sur son usage**.

**Informations complémentaires (optionnelles pour tous les niveaux) :**

-   Le logiciel est *mûr et actif* : la longévité est constatée et il y a de bonnes garanties sur la pérennité ; il existe une communauté dynamique, une feuille de route.

-   Le logiciel est *performant*, il a une bonne couverture fonctionnelle par rapport au besoin.

-   Pour les outils de bureautique, le logiciel est *multiplateforme*.

-   Le logiciel respecte des *normes et standards*, notamment ceux du RGI et du RGAA.

-   Le logiciel propose des *facilités d'exploitation* : supervision, administration, configuration, sauvegarde, existence d'installeurs, d'outils de configuration et de déploiement.

-   Le logiciel est adapté aux besoins des ministères français : intégration dans les SI ministériels et respect de la PSSIE, traduction en français, besoins spécifiques aux grands comptes.


## #4: [Publier le sill sur sill.etalab.gouv.fr](https://github.com/DISIC/sill/issues/23)

Le SILL est aujourd'hui publié par les groupes MIM en PDF dans sa version stable.

Il est aussi publié sur ce dépôt comme une version de travail.

La publication du SILL sur un sous-domaine d'Etalab répondrait en partie au problème du portage officiel du SILL par la DINSIC.  L'outil de publication devrait aussi permettre de gérer les demandes d'entrée dans le SILL et l'harmonisation du travail des trois groupes MIM\*.


## #5: [Publier des cas d'usage et des informations sur l'utilisation](https://github.com/DISIC/sill/issues/24)

Si l'entrée d'un logiciel libre au niveau *recommandé* (`R`) dépend de l'existence d'informations publiques sur son utilisation effective par un ministère ou un organisme public, il faut commencer à publier ce genre d'informations quelque part.


## #6 Ouvrir (tous?) les niveaux à tous les organismes publics

Aujourd'hui, les souches présentes dans le SILL sont utilisées dans les ministères centraux, qu'elles soient en recommandation ou en observation.

Nous pouvons envisager d'ouvrir le nouveau niveau U à tous les organismes publics, voire même tous les niveaux à tous les organismes publics, au-delà des seuls ministères centraux.

