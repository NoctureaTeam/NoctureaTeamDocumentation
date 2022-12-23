# Pinceaux

FAWE est un plugin qui vous permet de construire et de dessiner depuis loin grâce à ses outils de pinceau. Lorsque vous activez un pinceau, il est lié à l'objet que vous tenez actuellement. Vous pouvez avoir différents outils liés à différents objets et jusqu'à deux pinceaux liés à un seul objet.

## Équiper un pinceau

* `/br <pinceau>` Pour lier à n'importe quel clic
* `/br primary <pinceau>` Pour l'équiper au clic droit
* `/br secondary <pinceau>` Pour l'équiper au clic gauche

### Pour changer les paramètres d'un pinceau

* `/mat <modèle>` Le modèle décide quoi placer
* `/mask <masque>` Un masque de destination décide si un bloc doit être modifié
* `/smask <masque>` Un masque de source décide si un bloc peut être placé
* `/targetmask <masque>` Quels blocs sont ciblés par le pinceau. Le masque par défaut est !air
* `/transform <transformation>` Une transformation change où les blocs sont placés
* `/range <portée>` La distance à laquelle vous pouvez utiliser le pinceau
* `/size <taille>` La taille du pinceau (par exemple, un cercle de rayon 10)
* `/none` - Délier l'outil&#x20;

Utilisez le drapeau `-h` pour changer les paramètres de votre pinceau de la main gauche.

### Modifier le ciblage des pinceaux

Vous pouvez changer le mode de ciblage de votre pinceau pour vous aider à construire dans différents environnements (air, murs, sol, etc.). Vous pouvez également utiliser la commande `//brush range` pour changer la distance à laquelle vous pouvez utiliser votre pinceau. Utilisez la commande `/br target <0-3>` pour changer le mode de ciblage :

* `0` : cible le bloc
* `1` : cible le point directement devant vous, la distance dépend de l'angle de votre vue
* `2` : cible le point, la distance dépend de la hauteur par rapport au sol
* `3` : cible la face du bloc

### Ajouter des actions de pinceau

Ajoutez des actions de pinceau en utilisant la molette de la souris :

* `br scroll clipboard <fichier|dossier|URL de l'asset>`
* `/br scroll mask <masque1> <masque2...>`
* `/br scroll pattern <mat1> <mat2...>`
* `/br scroll range`
* `/br scroll size`
* `/br scroll target`

### Réinitialisation du pinceau

Appuyez sur la touche "maj" et cliquez avec le pinceau sélectionné pour le réinitialiser. Cela effacera par exemple le presse-papiers du pinceau copier-coller et réinitialisera les points du pinceau spline.

### Visualiser le pinceau (actuellement non appliqué)

Utilisez la commande `/br vis <0-2>` pour choisir le mode de visualisation :

* 0 = Pas de visualisation
* 1 = Point unique
* 2 = Tous les changements de blocs sont visualisés

### Vidéo

{% embed url="https://www.youtube.com/watch?v=xX-MTSLoNXw" %}

### Pinceaux

{% content-ref url="commandes-et-autorisations-principales.md" %}
[commandes-et-autorisations-principales.md](commandes-et-autorisations-principales.md)
{% endcontent-ref %}
