# angular 2_tuto

*ngFor fait partie d'une des directives structurelles. 
Les directives structurelles façonnent ou remodèlent 
la structure du DOM, en ajoutant, supprimant et manipulant des éléments.
(*ngFor agit comme 1 boucle)

{{ }} représente une instruction de la sytaxe d'interpolaion d'Angular qui permet de rendre la valeur de la propriété sous forme de texte.

[ ]: 1 syntaxe de liaison de propriété qui porte le nom du produit suivi de mot 'details'
Elle permet d'utiliser la valeur de la propriété dans une expression de modèle.

La balise "p" est un élément sous forme de texte (qui est une description des produits).</br>
Avec la directive structurelle *ngIf qui ne crée l'élément que si le produit a 1 description.</br>
Ici, le paragrphe de description de Phone Standard n'a pas été crée car la valeur de sa propriété (description) est vide.</br>
Comme on peut voir ds  les données produit prédéfinies ds le fichier products.ts :</br>
id: 3,</br>
name: 'Phone Standard',</br>
price: 299,</br>
description: ''</br>

Boutton "Share" est lié l'événement click qui appelle la méthode share qui se trouve ds la product-list.component.ts</br>
share(){</br>
    window.alert('The product has been shared!');</br>
  }









