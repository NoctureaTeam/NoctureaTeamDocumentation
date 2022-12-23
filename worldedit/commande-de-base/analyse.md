# Analyse

Raccourcie

<table data-view="cards"><thead><tr><th align="center"></th><th align="center"></th><th align="center"></th></tr></thead><tbody><tr><td align="center">//Nbtinfo</td><td align="center"><code>//nbtinfo</code></td><td align="center"><p></p><p>Information conteneur</p></td></tr><tr><td align="center">//chunkinfo</td><td align="center"><code>//chunkinfo</code></td><td align="center"><p></p><p>Info par chunk</p></td></tr><tr><td align="center">//distr</td><td align="center"><code>//distr [-c] [-d] [-p &#x3C;page>]</code></td><td align="center">Distribution de bloc</td></tr><tr><td align="center">//count</td><td align="center"><code>//count &#x3C;block></code></td><td align="center">Compte</td></tr><tr><td align="center">//size</td><td align="center"><code>//size [-c]</code></td><td align="center">Mesure </td></tr></tbody></table>

## Nbtinfo

* La commande `Nbtinfo` affiche les informations NBT pour le bloc cible dans votre viseur sous forme de chaîne lisible par l'utilisateur (texte brut). Le format "Named Binary Tag" (NBT) est utilisé pour stocker les données dans une structure en arbre composée de différents tags dans Minecraft. Pour plus d'informations sur le format NBT, [cliquez ici](https://minecraft.fandom.com/fr/wiki/Format\_NBT).
* L'utilisation : `//nbtinfo`

<figure><img src="../../.gitbook/assets/nbtinfo.jpg" alt=""><figcaption><p><code>//nbtinfo</code></p></figcaption></figure>

## Chunkinfo

* La commande `Chunkinfo` vous donne des informations sur le chunk dans lequel vous vous trouvez. La première ligne affiche les coordonnées X et Z de votre chunk. Les deux autres lignes affichent les noms des fichiers de chunk. Pour plus d'informations sur le format de fichier de région, [cliquez ici](https://minecraft.fandom.com/fr/wiki/Tron%C3%A7on). En appuyant sur F3+G, vous pouvez voir la bordure du chunk.
* Utilisation : `//chunkinfo`

<figure><img src="../../.gitbook/assets/chunkinfo (1).png" alt=""><figcaption><p><code>//chunkinfo</code></p></figcaption></figure>

## Distr

* La commande `Distr` récupère la distribution des blocs dans la sélection (image 1) avec la distribution en pourcentage, le nombre et le nom de ce bloc traduit dans votre langue de client Minecraft. Vous pouvez analyser la distribution de blocs de votre presse-papiers (par exemple, après une commande //copy) au lieu de votre sélection en utilisant le drapeau -c. Avec le drapeau -d, la liste de blocs séparera tous les blocs ayant des valeurs de blocs différentes (image 2). En passant la souris sur les noms de bloc, vous verrez les noms techniques (par exemple, "<mark style="color:blue;">ajouter</mark>") et, avec l'utilisation du drapeau -d, les valeurs de bloc en crochet également (image 2). Avec le drapeau optionnel -p et un numéro de côté, vous pouvez passer d'un côté de la liste à l'autre.
* Utilisation : `//distr` ou `//distr [-c] [-d] [-p <page>]`

<figure><img src="../../.gitbook/assets/distr.png" alt=""><figcaption><p><code>image n°1</code></p></figcaption></figure>

## Count

* La commande `Count` vous donne le nombre de blocs d'un certain type dans votre sélection. Vous pouvez rechercher un bloc avec une valeur de bloc spécifiée en utilisant des crochets (par exemple, `stripped_dark_oak_log` ).
* Utilisation : `//count <block>`

<figure><img src="../../.gitbook/assets/count.png" alt=""><figcaption><p><code>//count</code></p></figcaption></figure>

## Size

* La commande `Size` vous donne différentes mesures et autres informations sur votre sélection. Vous pouvez analyser les mesures de bloc de votre presse-papiers / schématique (par exemple, après une commande //copy) au lieu de votre sélection en utilisant le drapeau -c. En analysant une sélection, vous obtiendrez le type de sélection, des informations spécifiques au type, la taille maximale de la longueur, de la hauteur et de la largeur, la distance diagonale en longueur de bloc et le nombre de blocs (avec AIR). En analysant un presse-
* Utilisation : `//size [-c]`

<figure><img src="../../.gitbook/assets/size (1).png" alt=""><figcaption><p><code>//size</code></p></figcaption></figure>

### Analyzing a clipboard <a href="#_analyzing_a_clipboard" id="_analyzing_a_clipboard"></a>

*   Utilisation : `//size -c`


* numéro de la liste de clipboard,&#x20;
* dimensions d'un cuboïde en longueur,&#x20;
* hauteur et largeur,&#x20;
* position de votre copie (important pour l'offset du schématique),&#x20;
* nombre de blocs (avec AIR).

<figure><img src="../../.gitbook/assets/clipboard analyse.png" alt=""><figcaption><p><code>//size -c</code></p></figcaption></figure>

### Analyzing a schematic <a href="#_analyzing_a_schematic" id="_analyzing_a_schematic"></a>

*   Utilisation : `//size -c`


* nom du schématique
* dimensions d'un cuboïde en longueur
* hauteur et largeur
* offset du schématique (distance entre un coin et votre position de sauvegarde)
* nombre de blocs (avec AIR)

<figure><img src="../../.gitbook/assets/schematic analyse.png" alt=""><figcaption><p><code>//size -c</code></p></figcaption></figure>

{% hint style="info" %}
Le lien vers le site officiel de [fastasyncworldedit](https://intellectualsites.github.io/fastasyncworldedit-documentation/basic-commands/analysis.html)&#x20;
{% endhint %}
