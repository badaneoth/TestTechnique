# LBPTest

Pour la partie front : créer un module Angular "products" pour afficher la liste des produits
avec une nouvelle route http://localhost:4200/products
Faire les Tests unitaires pour la partie front ( il faut que la couverture des TU soit supérieure à 80%)
Pour la partie back :Développer  une api Rest en spring boot ou en Node JS permettant la gestion de produits
Le back-end doit gérer les API REST suivantes : 

| Resource           | POST                        | GET                               | DELETE                |
| ------------------ | --------------------------- | ----------------------------------| --------------------- |
| **/products**      | Ajouter un nouveau produit  | Récupérer tous les produits       |     X                 |
| **/products/1**    | X                           | Récupérer le détail d'un produit  | supprimer un produit  |

faire les Tests unitaires pour la partie backend ( il faut que la couverture des TU soit supérieure à 80%)
créer une collection POSTMAN contenant les 4 requettes HTTP avec vos jeux de données
-creerProduit
-récupérerListeProduits
-récupérerDetailsProduit
-supprimerProduit
le model Produit à utiliser dans vos dévelopements : 

class Product {
  id: number;
  code: string;
  name: string;
  description: string;
  price: number;
  quantity: number;
  category: string;
  image: string;
}

Bonus:
utiliser PrimeNg https://primeng.org/installation pour ajouter un système de pagination (https://primeng.org/paginator), chercher et filtrer les produits (https://primeng.org/dataview)
