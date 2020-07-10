
# Table des matières

-   [Les critères d’entrée d’un logiciel dans le SILL](#org6b0fa2b)
-   [Les communautés qui construisent le SILL : groupes MIM](#orgc27b2ce)
-   [Les documents de construction du SILL 2020](#orgd96e79a)
-   [Comment ajouter un logiciel libre dans le SILL ?](#org9f7b366)
-   [Que signifie être « référent » d’un logiciel ?](#org053c384)
-   [Présentations partagées dans les groupes MIM](#orgc6bee1b)
-   [Le mouvement `#BlueHats`](#org5a94e63)
-   [Licence du SILL et de ce dépôt](#org872d8b9)

Le socle interministériel de logiciels libres (SILL) est le catalogue
de référence des logiciels libres recommandés par l’Etat.

Il est construit de façon collaborative par des communautés d’agents
informaticiens de la fonction publique d'État et de la fonction
publique hospitalière.

-   La page d'accueil du SILL : <https://sill.etalab.gouv.fr>
-   Cette page de présentation détaillée : [disic.github.io/sill](https://disic.github.io/sill/index.html)
-   La page d'accueil des groupes MIM : [www.mim-libre.fr](https://www.mim-libre.fr/)

Pour toute question, écrire à [bastien.guerry@data.gouv.fr](mailto:bastien.guerry@data.gouv.fr) ou à
[mim-noyau@listes.etalab.gouv.fr](mailto:mim-noyau@listes.etalab.gouv.fr) pour contacter l'équipe d'animation
des groupes MIM.


<a id="org6b0fa2b"></a>

# Les critères d’entrée d’un logiciel dans le SILL


## Prérequis : le code source doit être publié sous licence libre sans délai entre le code source et la version exécutable

Le code source du logiciel doit être publié sous l'une des licences
libres reconnues par la [Free Software Foundation](https://www.gnu.org/licenses/license-list.fr.html) ou l'[Open Source
Initiative](https://opensource.org/licenses).

La licence ne doit contenir aucun ajout ou modification risquant d'en
altérer le caractère libre.  En cas de doute sur une licence, le
groupe noyau qui coordonne l'ensemble du SILL est libre de refuser un
logiciel.

D'autre part, il ne doit y avoir aucun délai de publication entre le
code source et la version exécutable du logiciel.


## Deux critères obligatoires pour les logiciels recommandés

-   Il existe un agent public, le « référent SILL », de la fonction
    publique d'État ou hospitalière pour ce logiciel libre.

-   Le logiciel est significativement utilisé dans un organisme public
    de la fonction publique d'État ou hospitalière.


## Plusieurs logiciels aux fonctionnalités similaires sont admissibles

Le SILL aide les administrations à s'y retrouver dans les logiciels
libres dont elles peuvent considérer l'usage.

Plusieurs logiciels aux fonctionnalités similaires peuvent figurer
dans le SILL (voir par exemple ces [éditeurs de texte](https://sill.etalab.gouv.fr/fr/software?id=174), ou ces [systèmes
de gestion de contenus](https://sill.etalab.gouv.fr/fr/software?id=36)) : les référents SILL travaillent à faire
évoluer le SILL de façon à ce qu'il aide à choisir entre ces solutions
multiples.


## D’autres informations optionnelles

D'autres informations sont accessibles aux référents SILL sans être
affichées publiquement :

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

-   Le logiciel est **adapté aux besoins des organismes publics** français :
    intégration dans les SI, traduction en français, besoins spécifiques
    aux grands comptes.

-   L’un des organismes publics utilisateur ayant un usage significatif
    du logiciel a **publié des informations sur cet usage**.


<a id="orgc27b2ce"></a>

# Les communautés qui construisent le SILL : groupes MIM

Le préfixe "MIM" signifie "Mutualisation interministérielle".

Le SILL est rédigé par deux groupes : le groupe **MIMO** qui se consacre
aux outils de bureautique et le groupe MIMDEVOPS dédié aux outils de
développement et de production.

Chaque groupe se réunit en présentiel et échange régulièrement par
email ; un groupe « noyau » assure la coordination de l'ensemble.

Pour demander à participer aux échanges des groupes :

-   s’inscrire sur [la liste MIMO](https://listes.etalab.gouv.fr/listinfo/mimo) ;
-   s’inscrire sur [la liste MIMDEVOPS](https://listes.etalab.gouv.fr/listinfo/mim-devops).


<a id="orgd96e79a"></a>

# Les documents de construction du SILL 2020

Les documents de construction du SILL 2020 sont disponibles via
l'espace de partage <https://groupes.mim-libre.fr>.  Si vous êtes
référent, vous pouvez obtenir un compte sur cet espace.

Une fois connecté sur cet espace, les documents de préparations sont
accessibles ici :

-   [MIMO](https://cloud.mim-libre.fr/apps/files/?dir=/Partage%20MIM/MIMO/SILL&fileid=10858)
-   [MIMDEV](https://calc.mim-libre.fr/MIMDEV/edit)
-   [MIMPROD](https://calc.mim-libre.fr/MIMPROD/edit)

Le [dépôt SILL](https://github.com/DISIC/sill/) contient aussi [un fichier csv pour le SILL 2020](https://github.com/DISIC/sill/blob/master/2020/sill-2020.csv) dans
lequel sont régulièrement consolidées les contributions faites sur ces
documents privés.


<a id="org9f7b366"></a>

# Comment ajouter un logiciel libre dans le SILL ?

**Attention**: pour qu’un logiciel entre dans le SILL, il faut qu’un agent
public se porte volontaire pour en être le *référent* (voir ci-dessous.)

Pour proposer un nouveau logiciel en vue du SILL 2020, vous pouvez
[ouvrir un ticket sur le dépôt de travail](https://github.com/DISIC/sill/issues/new?assignees=bzg&labels=Soumission&template=ajout-logiciel.md&title=Nouveau+logiciel+%3A+), nous contacter via le
[formulaire de contact](https://sill.etalab.gouv.fr/fr/contact) ou écrire à `bastien.guerry@data.gouv.fr`.


<a id="org053c384"></a>

# Que signifie être « référent » d’un logiciel ?


## Vous souhaitez être référent ?

Pour cela, vous pouvez [ouvrir un ticket](https://github.com/DISIC/sill/issues/new/choose) sur le dépôt du SILL, demander
de vous inscrire sur la [liste de discussion des référents](https://listes.etalab.gouv.fr/listinfo/sill-mainteneurs) ou envoyer
un mail à `bastien.guerry@data.gouv.fr`.


## Qui peut être « référent SILL » ?

Tout agent public travaillant dans un organisme public de la fonction
publique d'État ou hospitalière peut être référent d’un logiciel libre
dont il connaît l’usage au sein de son administration.


## Quels sont les tâches du référent ?

**Le référent :**

1.  atteste de l’usage d’un logiciel libre dans son administration ;
2.  collecte les informations pertinentes (de la version utilisée à des cas d’usage complets) sur le logiciel ;
3.  remonte ces informations aux mainteneurs du [dépôt SILL](https://github.com/disic/sill) hébergé par la DINUM - s’il peut, il met à jour ce dépôt directement ;
4.  participe une fois par an à l’une des réunions du groupe MIM pertinent (MIMO, MIMPROD ou MIMDEV) ;
5.  participe aux discussions entre mainteneurs sur la liste [sill-mainteneurs](https://listes.etalab.gouv.fr/listinfo/sill-mainteneurs) ;
6.  cherche un référent pour le remplacer s’il venait à ne plus pouvoir être référent.

**Le référent n’est pas :**

-   un contact de support pour l’ensemble de l’administration ;
-   obligé de rester référent toute l’année ;
-   obligé de publier son identité.


<a id="orgc6bee1b"></a>

# Présentations partagées dans les groupes MIM

-   27/11/2019 (MIMO) : [Présentation Management Poste de travail](https://speakerdeck.com/bluehats/presentation-management-poste-de-travail)
-   27/11/2019 (MIMO) : [Firefox for Entreprise](https://speakerdeck.com/bluehats/firefox-for-enterprise)
-   27/11/2019 (MIMO) : [La gestion du poste de travail temps réel](https://speakerdeck.com/bluehats/la-gestion-du-poste-de-travail-temps-reel)
-   27/11/2019 (MIMO) : [Nextcloud - Le cloud alternatif aux GAFAM](https://speakerdeck.com/bluehats/nextcloud-le-cloud-alternatif-aux-gafam)


<a id="org5a94e63"></a>

# Le mouvement `#BlueHats`

Le mouvement #BlueHats a été lancé en décembre 2018 par la DINUM et il
rassemble toutes celles et ceux qui soutiennent le développement et
l'utilisation de logiciels libres dans l'administration publique.

Vous pouvez retrouver [la gazette #BlueHats](https://github.com/DISIC/gazette-bluehats) publiée par la DINUM, [vous
y inscrire](https://infolettres.etalab.gouv.fr/subscribe/bluehats@mail.etalab.studio) et voir la [documentation sur les événements #BlueHats](https://github.com/DISIC/evenements-bluehats).


<a id="org872d8b9"></a>

# Licence du SILL et de ce dépôt

Le SILL est publié par les groupes de mutualisation interministérielle
sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

Ce dépôt est publié sous [licence Ouverte 2.0](https://github.com/etalab/Licence-Ouverte/blob/master/LO.md).

