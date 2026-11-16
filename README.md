La différence entre une classe et un identifiant

 Pour cibler les id, on utilisera un # tandis que pour cibler une class, on utilisera un point (.) avant la
valeur et utiliser une même valeur d'id pour plusieurs éléments est strictement interdit alors qu'il est possible de faire cela avec une class

exemple: 
 Pour une class
Dans le fichier html
<h2 class="aster">Aster, est une boutique ...
<h2 class="aster">Au cas où ...

Dans le fichier CSS
.aster{
    margin-top: 50px;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
}

Pour un identifiant

Dans le fichier html

<h2 id="liste">Une liste

Dans le fichier CSS

#liste{
    font-weight: bold;
}


La différence entre un élément bloc et un élément inline

Les différences entre les éléments de type block et inline:
Un élément de type block va toujours commencer sur une
nouvelle ligne et prendre toute la largeur disponible dans une
page
Un élément de type block peut contenir un autre élément de type
block ainsi qu'un élément de type inline
Les éléments de type block commencent par défaut sur une
nouvelle ligne
Quelques éléments de type block:
p, h(1, 2, 3,...), ol, ul, form, div


Les éléments de type inline ne commencent pas sur une
nouvelle ligne mais vont s'insérer dans la ligne actuelle , elles
vont prendre seulement le largeur qui leur est nécéssaire
c'est-à-dire la largeur de leur contenu.
Quelques éléments de type inline:
strong, em, a, img, span

exemple: <h3>Notre instagram: <strong>Aster_Flow</strong></h3>

h3 est un élément de type block et strong, un élément de type inline

<h2 class="aster">Aster, est une boutique de fleur qui propose <span class="white">une variété de fleur</span></h2>

h2 est un élément de type block et span, un élément de type inline