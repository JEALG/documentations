Ewattch 
=======

Description 
-----------

Ce plugin permet d’établir et de récupérer les informations du
superviseur Ewattch.

Configuration du plugin 
-----------------------

Après téléchargement du plugin il vous faut l’activer, vous avez ensuite
accès à la configuration de base du plugin :

![ewattch1](./images/ewattch1.PNG)

Vous retrouvez ici la configuration de base :

-   **IP du superviseur** : IP du superviseur sur le réseau

-   **Synchroniser** : Permet de synchroniser la liste des équipements
    sur le superviseur avec Jeedom

Configuration des équipements 
-----------------------------

La configuration des équipements Ewattch est accessible à partir du menu
Plugins :

![ewattch2](./images/ewattch2.PNG)

Voilà à quoi ressemble la page du plugin Ewattch (ici avec déjà quelques
équipements) :

![ewattch3](./images/ewattch3.PNG)

> **Tip**
>
> Comme à beaucoup d’endroits sur Jeedom, mettre la souris tout à gauche
> permet de faire apparaître un menu d’accès rapide (vous pouvez, à
> partir de votre profil, le laisser toujours visible).

Une fois que vous cliquez sur l’un d’eux, vous obtenez :

![ewattch4](./images/ewattch4.PNG)

Vous retrouvez ici toute la configuration de votre équipement :

-   **Nom de l’équipement** : nom de votre équipement Ewattch,

-   **Objet parent** : indique l’objet parent auquel appartient
    l’équipement,

-   **Activer** : permet de rendre votre équipement actif,

-   **Visible** : le rend visible sur le dashboard,

-   **Catégorie** : les catégories de l’équipement (il peut appartenir à
    plusieurs catégories),

-   **ID** : ID logique de l’équipement dans le superviseur (il est
    recommandé de ne pas y toucher),

-   **IP** : IP du superviseur (à titre indicatif pour le moment).

En dessous, vous retrouvez la configuration de l’équipement :

-   le nom affiché sur le dashboard,

-   le sous-type,

-   ID logique de la commande dans le superviseur (il est recommandé de
    ne pas y toucher),

-   historiser : permet d’historiser la donnée,

-   afficher : permet d’afficher la donnée sur le dashboard,

-   unité : unité de la donnée (peut être vide),

-   min/max : bornes de la donnée (peuvent être vides),

-   configuration avancée (petites roues crantées) : permet d’afficher
    la configuration avancée de la commande (méthode d’historisation,
    widget…​),

-   Tester : permet de tester la commande,

-   supprimer (signe -) : permet de supprimer la commande.


