
# Table des matières

-   [Socle interministériel des logiciels libres](#orgc4cca56)
-   [Le SILL 2019](#orgc15982c)
-   [Les communautés qui construisent le SILL](#orgc81c27c)
-   [Les critères d’entrée d’un logiciel dans le SILL](#orgfe2bb27)
-   [Comment ajouter un logiciel libre dans le SILL ?](#org13ac8e5)
-   [Que signifie être « référent » d’un logiciel ?](#org95c3272)
-   [Licence du SILL et de ce dépôt](#org8595873)



<a id="orgc4cca56"></a>

# Socle interministériel des logiciels libres

Le socle interministériel de logiciels libres (SILL) est le catalogue
de référence des logiciels libres recommandés par l’Etat.

Il est construit de façon collaborative par des communautés d’agents
informaticiens de l’État, d’opérateurs publics et de collectivités
territoriales.

-   La page d'accueil du SILL côté DINUM : [disic.github.io/sill](https://disic.github.io/sill/index.html)
-   La page d'accueil des groupes MIM : [www.mim-libre.fr](https://www.mim-libre.fr/)
-   L'ancienne page de présentation du SILL [côté DINSIC](https://references.modernisation.gouv.fr/socle-logiciels-libres)

Pour toute question, écrire à [bastien.guerry@data.gouv.fr](mailto:bastien.guerry@data.gouv.fr)


<a id="orgc15982c"></a>

# Le SILL 2019

Voici toutes les versions du SILL 2019 :

-   Version [HTML](2019/)
-   Version [PDF](2019/sill-2019.pdf) et [ODT](2019/sill-2019.odt)
-   Version [ODS](2019/sill-2019.ods) et [CSV](2019/sill-2019.csv)

Vous pouvez voir la liste des changements depuis 2018 ([ODT](2019/sill-diff-2018-2019.odt) et [PDF](2019/sill-diff-2018-2019.pdf)).

Vous pouvez [télécharger l'installateur de LibreOffice MIMO](ftp://eoleng.ac-dijon.fr/SILL2019/).


<a id="orgc81c27c"></a>

# Les communautés qui construisent le SILL

Le SILL est rédigé par trois groupes :

-   [le groupe MIMO](https://www.mim-libre.fr/mimo/) se consacre aux outils de bureautique ;
-   [le groupe MIMDEV](https://www.mim-libre.fr/mimdev-outils-de-developpements/) se consacre aux outils de développement ;
-   [le groupe MIMPROD](https://www.mim-libre.fr/mimprod-outils-de-production/) se consacre aux outils de mise en production.

Le préfixe "MIM" signifie "Mutualisation interministérielle".

Chaque groupe se réunit en présentiel et échange régulièrement par
email ; un groupe « noyau » assure la coordination de l'ensemble.

Pour demander à participer aux échanges des groupes :

-   s’inscrire sur [la liste MIMDEV](https://listes.etalab.gouv.fr/listinfo/mimdev) ;
-   s’inscrire sur [la liste MIMO](https://listes.etalab.gouv.fr/listinfo/mimo) ;
-   s’inscrire sur [la liste MIMPROD](https://listes.etalab.gouv.fr/listinfo/mimprod) ;


<a id="orgfe2bb27"></a>

# Les critères d’entrée d’un logiciel dans le SILL


## Un prérequis pour tous les logiciels

-   Le code source du logiciel est publié sous l'une des licences libres
    reconnues par la [Free Software Foundation](https://www.gnu.org/licenses/license-list.fr.html) ou l'[Open Source
    Initiative](https://opensource.org/licenses), sans délai de publication entre le code source et la
    version exécutable.


## Deux critères obligatoires pour les logiciels recommandés

-   Il existe un agent public d’une administration centrale référent
    pour ce logiciel libre.

-   Le logiciel est actuellement utilisé dans au moins un ministère.


## D’autres informations optionnelles

-   Le logiciel est **mûr et actif** : la longévité est constatée, il y a de
    bonnes garanties sur la pérennité et il existe une communauté
    dynamique ainsi qu’une feuille de route.

-   Le logiciel est **performant**, il a une bonne couverture fonctionnelle
    par rapport au besoin.

-   Pour les outils de bureautique, le **logiciel est multiplateforme**.

-   Si pertinent, le **logiciel respecte des normes et des standards**,
    notamment ceux du [RGI](http://references.modernisation.gouv.fr/interoperabilite) et du [RGAA](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/).

-   Le logiciel propose des **facilités d'exploitation** : supervision,
    administration, configuration, sauvegarde, existence d'installeurs,
    d'outils de configuration et de déploiement.

-   Le logiciel est **adapté aux besoins des ministères** français :
    intégration dans les SI ministériels et respect de la PSSIE,
    traduction en français, besoins spécifiques aux grands comptes.

-   L’un des ministères utilisateur ayant un usage significatif du
    logiciel a **publié des informations sur cet usage**.


<a id="org13ac8e5"></a>

# Comment ajouter un logiciel libre dans le SILL ?

Pour proposer un nouveau logiciel en vue du SILL 2020, vous pouvez
[ouvrir un ticket sur le dépôt de travail](https://github.com/DISIC/sill/issues/new).

**Attention**: pour qu’un logiciel entre dans le SILL, il faut qu’un agent
public se porte volontaire pour en être le *référent* (voir ci-dessous.)


<a id="org95c3272"></a>

# Que signifie être « référent » d’un logiciel ?


## Qui peut être « référent SILL » ?

Tout agent public travaillant dans une administration central peut
être référent d’un logiciel libre dont il connaît l’usage au sein de
son ministère.


## Quels sont les tâches du référent ?

Le référent :

1.  atteste de l’usage d’un logiciel libre dans son administration
    centrale ;

2.  collecte les informations pertinentes (de la version utilisée à des
    cas d’usage complets) sur le logiciel ;

3.  remonte ces informations aux mainteneurs du [dépôt SILL](https://github.com/disic/sill) hébergé par
    la DINUM - s’il peut, il met à jour ce dépôt directement ;

4.  participe au moins une fois par an à l’une des réunions du groupe
    MIM pertinent (MIMO, MIMPROD ou MIMDEV) ;

5.  participe aux discussions entre mainteneurs sur [sill-mainteneurs](https://listes.etalab.gouv.fr/listinfo/sill-mainteneurs) ;

6.  cherche un référent pour le remplacer s’il venait à ne plus pouvoir
    être référent.

Le référent **n’est pas** : 

-   un contact de support pour l’ensemble de l’administration ;
-   obligé de rester référent toute l’année ;
-   obligé de publier son identité.


<a id="org8595873"></a>

# Licence du SILL et de ce dépôt

Le SILL est publié par les groupes de mutualisation interministérielle
sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

Ce dépôt est publié sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

