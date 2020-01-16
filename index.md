
# Table des matières

-   [Le SILL 2019](#org1f2046d)
-   [Les communautés qui construisent le SILL](#org430ec75)
-   [Les documents de construction du SILL 2020](#org246ef26)
-   [Les critères d’entrée d’un logiciel dans le SILL](#orga8e6449)
-   [Comment ajouter un logiciel libre dans le SILL ?](#org9365945)
-   [Que signifie être « référent » d’un logiciel ?](#org46f80b7)
-   [Présentations partagées dans les groupes MIM](#org74daec8)
-   [Le mouvement `#BlueHats`](#org7b756e8)
-   [Licence du SILL et de ce dépôt](#org0772cdc)

Le socle interministériel de logiciels libres (SILL) est le catalogue
de référence des logiciels libres recommandés par l’Etat.

Il est construit de façon collaborative par des communautés d’agents
informaticiens de l’État, d’opérateurs publics et de collectivités
territoriales.

-   La page d'accueil du SILL côté DINUM : [disic.github.io/sill](https://disic.github.io/sill/index.html)
-   La page d'accueil des groupes MIM : [www.mim-libre.fr](https://www.mim-libre.fr/)
-   L'ancienne page de présentation du SILL [côté DINSIC](https://references.modernisation.gouv.fr/socle-logiciels-libres)

Pour toute question, écrire à [bastien.guerry@data.gouv.fr](mailto:bastien.guerry@data.gouv.fr)


<a id="org1f2046d"></a>

# Le SILL 2019

Voici toutes les versions du SILL 2019 :

-   Version [HTML](2019/)
-   Version [PDF](2019/sill-2019.pdf) et [ODT](2019/sill-2019.odt)
-   Version [ODS](2019/sill-2019.ods) et [CSV](2019/sill-2019.csv)

Vous pouvez voir la liste des changements depuis 2018 ([ODT](2019/sill-diff-2018-2019.odt) et [PDF](2019/sill-diff-2018-2019.pdf)).

Vous pouvez [télécharger l'installateur de LibreOffice MIMO](ftp://eoleng.ac-dijon.fr/SILL2019/).


<a id="org430ec75"></a>

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


<a id="org246ef26"></a>

# Les documents de construction du SILL 2020

Les documents de construction du SILL 2020 sont disponibles via
l'espace de partage <https://groupes.mim.ovh>.  Si vous êtes référent,
vous pouvez obtenir un compte sur cet espace.

Une fois connecté sur cet espace, les documents de préparations sont
accessibles ici :

-   [MIMO](https://cloud.mim.ovh/apps/files/?dir=/Partage%20MIM/MIMO/SILL&fileid=10858)
-   [MIMDEV](https://calc.mim.ovh/MIMDEV/edit)
-   [MIMPROD](https://calc.mim.ovh/MIMPROD/edit)

Le [dépôt SILL](https://github.com/DISIC/sill/) contient aussi [un fichier csv pour le SILL 2020](https://github.com/DISIC/sill/blob/master/2020/sill-2020.csv) dans
lequel sont régulièrement consolidées les contributions faites sur
ces documents privés.


<a id="orga8e6449"></a>

# Les critères d’entrée d’un logiciel dans le SILL


## Un prérequis pour tous les logiciels

-   Le code source du logiciel est publié sous l'une des licences libres
    reconnues par la [Free Software Foundation](https://www.gnu.org/licenses/license-list.fr.html) ou l'[Open Source
    Initiative](https://opensource.org/licenses), sans délai de publication entre le code source et la
    version exécutable.


## Deux critères obligatoires pour les logiciels recommandés

-   Il existe un agent public d’une administration centrale référent
    pour ce logiciel libre.

-   Le logiciel est actuellement utilisé dans au moins une
    administration centrale.


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


<a id="org9365945"></a>

# Comment ajouter un logiciel libre dans le SILL ?

Pour proposer un nouveau logiciel en vue du SILL 2020, vous pouvez
[ouvrir un ticket sur le dépôt de travail](https://github.com/DISIC/sill/issues/new?assignees=bzg&labels=Soumission&template=ajout-logiciel.md&title=Nouveau+logiciel+%3A+).

**Attention**: pour qu’un logiciel entre dans le SILL, il faut qu’un agent
public se porte volontaire pour en être le *référent* (voir ci-dessous.)


<a id="org46f80b7"></a>

# Que signifie être « référent » d’un logiciel ?


## Vous souhaitez être référent ?

Pour cela, vous pouvez [ouvrir un ticket](https://github.com/DISIC/sill/issues/new/choose) sur le dépôt du SILL, demander
de vous inscrire sur la [liste de discussion des référents](https://listes.etalab.gouv.fr/listinfo/sill-mainteneurs) ou envoyer
un mail à `bastien.guerry@data.gouv.fr`.


## Qui peut être « référent SILL » ?

Tout agent public travaillant dans une administration centrale peut
être référent d’un logiciel libre dont il connaît l’usage au sein de
son ministère.


## Quels sont les tâches du référent ?

**Le référent :**

1.  atteste de l’usage d’un logiciel libre dans son administration centrale ;
2.  collecte les informations pertinentes (de la version utilisée à des cas d’usage complets) sur le logiciel ;
3.  remonte ces informations aux mainteneurs du [dépôt SILL](https://github.com/disic/sill) hébergé par la DINUM - s’il peut, il met à jour ce dépôt directement ;
4.  participe au moins une fois par an à l’une des réunions du groupe MIM pertinent (MIMO, MIMPROD ou MIMDEV) ;
5.  participe aux discussions entre mainteneurs sur la liste [sill-mainteneurs](https://listes.etalab.gouv.fr/listinfo/sill-mainteneurs) ;
6.  cherche un référent pour le remplacer s’il venait à ne plus pouvoir être référent.

**Le référent n’est pas :**

-   un contact de support pour l’ensemble de l’administration ;
-   obligé de rester référent toute l’année ;
-   obligé de publier son identité.


<a id="org74daec8"></a>

# Présentations partagées dans les groupes MIM

-   27/11/2019 (MIMO) : [Présentation Management Poste de travail](https://speakerdeck.com/bluehats/presentation-management-poste-de-travail)
-   27/11/2019 (MIMO) : [Firefox for Entreprise](https://speakerdeck.com/bluehats/firefox-for-enterprise)
-   27/11/2019 (MIMO) : [La gestion du poste de travail temps réel](https://speakerdeck.com/bluehats/la-gestion-du-poste-de-travail-temps-reel)
-   27/11/2019 (MIMO) : [Nextcloud - Le cloud alternatif aux GAFAM](https://speakerdeck.com/bluehats/nextcloud-le-cloud-alternatif-aux-gafam)


<a id="org7b756e8"></a>

# Le mouvement `#BlueHats`

Le mouvement #BlueHats a été lancé en décembre 2018 par la DINUM et il
rassemble toutes celles et ceux qui soutiennent le développement et
l'utilisation de logiciels libres dans l'administration publique.

Vous pouvez retrouver [la gazette #BlueHats](https://github.com/DISIC/gazette-bluehats) publiée par la DINUM, [vous
y inscrire](https://infolettres.etalab.gouv.fr/subscribe/bluehats@mail.etalab.studio) et voir la [documentation sur les événements #BlueHats](https://github.com/DISIC/evenements-bluehats).


<a id="org0772cdc"></a>

# Licence du SILL et de ce dépôt

Le SILL est publié par les groupes de mutualisation interministérielle
sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

Ce dépôt est publié sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

