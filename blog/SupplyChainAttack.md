---
title: Comment se protéger d'une "Supply Chain Attack" ?
# menu_order: 1
# post_status can be publish, draft, pending, future
post_status: publish
# post_excerpt: A WordPress excerpt is basically a summary of a longer article, often used as a replacement on the blog index and archives pages to avoid needing to display the full content of each post. By default, WordPress generates excerpts by simply selecting the first 55 words of a post
taxonomy:
    category: 
        - DevSecOps
        - DevOps
    post_tag:
        - security
        - cicd
        - kubernetes
custom_fields:
    language: fr

# custom_fields:
#     field1: value 1
#     field2: value 2        
---
![Broken Chain](/_images/chain-broken-nobg.png)

# La Supply Chain Attack ?

Changement de paradigme

Une « supply chain attack » est une cyberattaque qui cherche à nuire à une organisation en ciblant les éléments les moins sécurisés de la chaîne d'approvisionnement.


## Publier sa SBOM

* Liste exhaustive des composants 
* Dépendances directes et indirectes
* Package et version sont identifiés de manière unique
* Approche vertueuse uniquement ?
    * Découverte des dépendances inconnues
    * Transparence
    * Exiger les SBOM's


## Mettre à jour régulièrement ses dépendances !

* Nouvelles **vulnérabilités** et correctifs constants
* Avantages collatéraux (corrections de bugs)
* Responsabilité de l'équipe en charge du produit
* Pas gratuit :
  * Effort à budgéter
  * Capacité à réserver
* Adapter la fréquence de mise à jour à sa capacité à déployer


![MAJ Deps](/_images/Blog_SupplyChain_03_MAJ_Deps.png)


* Réduire ses dépendances
* Considérer des outils de veille
* Standardiser ses images de base !
* Utiliser semver pour les mises à jour !


==> Test de non régression obligatoire




