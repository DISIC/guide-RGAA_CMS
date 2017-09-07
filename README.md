# Guide méthodologique RGAA-CMS

Ce document a été établi dans le cadre des ressources venant accompagner la prise en main du [référentiel CMS](https://github.com/DISIC/referentiel-cms).
Le référentiel CMS vous est proposé dans le cadre des ressources accompagnant la prise en main de la version 3 du référentiel général d'accessibilité pour les administrations (RGAA&nbsp;3).

Il s'agit du guide d'accompagnement du référentiel CMS documentant les étapes permettant de reconnaître un critère conforme ou non via des exemples illustrés ou des enchainements d'actions à effectuer. Attention les méthodes proposées ne sont pas les seules possibles.

Pour chaque critère ou test, une méthode de validation est proposée. Deux types de méthodes sont proposées :

- des méthodes simples : dans le cas de critère dont l'application est trop large ou peu répandue, il est difficile de déterminer une méthode, voire d'en trouver un exemple qui ne réduise pas la portée du critère. Dans ces cas, la méthodologie s'attache simplement à rendre le critère plus explicite si nécessaire.
- des méthodes par l'exemple : pour certains critères, dont l'application dans les CMS est plus répandue, des exemples issus de CMS permettent de comprendre la logique de la validation et d'illustrer la manière d'agir pour tester le critère.

Les méthodes proposées ne sont pas les seules possibles, bien au contraire. La particularité du référentiel CMS est que l'objet (les CMS) ne sont pas contraints à un standard dans l'implémentation de processus (sauvegarde, session utilisateur par exemple). Il est donc difficile de déterminer a priori de quelle manière certains processus peuvent opérer dans les CMS. C'est à l'auditeur de rechercher si le processus existe et de comprendre de quelle manière il opère. Aucune généralité ne peut être faite.

Aucun outil n'est nécessaire pour tester les critères propres du référentiel CMS, sauf les critères relatifs  au RGAA. Pour cela, nous vous renvoyons à la [méthodologie de tests du RGAA](http://disic.github.io/rgaa_methodologie/). Pour tester ces critères, vous allez devoir utiliser du contenu (par exemple, pour tester l'accessibilité des contenus générés). Nous vous conseillons donc de préparer dans votre CMS un contenu dans une des zones d'édition qui reprennent toutes les typologies de contenus référencées dans le RGAA&nbsp;:
- des paragraphes de texte (balise `p`)&nbsp;;
- des titres (balise `hx`)&nbsp;;
- des liens (balise `a`)&nbsp;;
- des images (balises `img`, `svg`, `embed`, `object`, `canvas`) dont une image de décoration, une image porteuse d'information et une image néccessitant une longue description&nbsp;;
- un tableau de données (balise `table`)&nbsp;;
- une liste non ordonnée (`ul li`)&nbsp;;
- une liste ordonnée (`ol li`)&nbsp;;
- un contenu multimédia (une vidéo par exemple)&nbsp;;
- un cadre (balise `iframe`)&nbsp;;
- etc.

Pour établir la liste complète des contenus nécessaires, vous devez simplement suivre les [thématiques et critères du RGAA 3](http://references.modernisation.gouv.fr/referentiel/criteres.html).

À noter que cette méthodologie est un document d'accompagnement visant à vous aider dans l'utilisation du référentiel CMS. Il ne dispense pas d'une lecture approfondie du référentiel technique.

## Thématiques

 - [1 - Interface](criteres.md#t-1)
 - [2 - Options de configuration](criteres.md#t-2)
 - [3 - Navigation](criteres.md#t-3)
 - [4 - Consultation](criteres.md#t-4)
 - [5 - Aide à la réparation](criteres.md#t-5)
 - [6 - Édition](criteres.md#t-6)
 - [7 - Gabarits et contenus pré-conçus](criteres.md#t-7)
 - [8 - Documentation](criteres.md#t-8)


## Licence d'utilisation

Ce document est la propriété du secrétariat général à la modernisation de l'action publique français (SGMAP). Il est placé sous la [licence ouverte 1.0 ou ultérieure](https://www.etalab.gouv.fr/licence-ouverte-open-licence), équivalente à une licence <i lang="en">Creative Commons BY</i>. Pour indiquer la paternité, ajouter un lien vers la version originale du document disponible sur le [compte <span lang="en">GitHub</span> de la DInSIC](https://github.com/DISIC).
