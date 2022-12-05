---
title: Comment se protéger d'une "Supply Chain Attack" ?
# menu_order: 1
# post_status can be publish, draft, pending, future
post_status: draft
# post_excerpt: A WordPress excerpt is basically a summary of a longer article, often used as a replacement on the blog index and archives pages to avoid needing to display the full content of each post. By default, WordPress generates excerpts by simply selecting the first 55 words of a post
taxonomy:
    category: 
        - DevSecOps
    post_tag:
        - security
        - cicd
        - kubernetes
custom_fields:
    ByGit: true
#     field2: value 2        
---


# La Supply Chain Attack ?

![Broken Chain](/_images/chain-broken-nobg.png)

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
