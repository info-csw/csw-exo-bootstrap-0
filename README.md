# Exercice : Carte de produit Bootstrap

L'objectif de cet exercice est de créer une mise en page de carte pour un produit en utilisant le framework Bootstrap. Cette carte contiendra une image, un titre, une description et des composants Bootstrap pour l'embellir.

## Étape 1 : Mise en page basique

1. **Initialisation** :
    - Créez une nouvelle page HTML.
    - [Télécharger Bootstrap](https://github.com/twbs/bootstrap/releases/download/v5.3.2/bootstrap-5.3.2-dist.zip)
    - Intégrez les liens CSS Bootstrap dans l'en-tête (bootstrap.min.css est suffisant).

2. **Ajout du conteneur** :
    Englobez votre contenu dans un conteneur Bootstrap :
    ```
    <div class="container">
        <!-- Votre grille ici -->
    </div>
    ```

3. **Mise en place de la grille** :
    - À l'intérieur du `container`, créez une `row` (ligne).
    - Ajoutez deux `col` (colonnes) : une pour l'image, une pour le titre et la description.
    ```
    <div class="row">
        <div class="col-md-4">Image du produit</div>
        <div class="col-md-8">Détails du produit</div>
    </div>
    ```

4. **Ajout de contenu** :
    - Dans la `col-md-4`, ajoutez une image représentant le produit.
    - Dans la `col-md-8`, ajoutez un titre pour le nom du produit et un paragraphe pour sa description.

5. **Style** :
    Utilisez les classes utilitaires de Bootstrap pour ajouter des marges, des paddings ou styliser le titre et le paragraphe.

6. **Testez votre mise en page** :
    Ouvrez votre page dans un navigateur pour s'assurer que la mise en page est correcte.

## Étape 2 : Intégration des composants Bootstrap

1. **Carte Bootstrap** :
    Transformez votre mise en page en composant `card` de Bootstrap.
    ```
    <div class="card">
        <img src="path_to_image.jpg" class="card-img-top" alt="Nom du produit">
        <div class="card-body">
            <h5 class="card-title">Nom du produit</h5>
            <p class="card-text">Description du produit.</p>
        </div>
    </div>
    ```

2. **Boutons** :
    Ajoutez un bouton sous la description pour simuler une action, comme "Ajouter au panier".
    ```
    <button class="btn btn-primary">Ajouter au panier</button>
    ```

3. **Badges** :
    Indiquez que le produit est en solde ou nouveau en utilisant les badges de Bootstrap.
    ```
    <h5 class="card-title">Nom du produit <span class="badge badge-success">Nouveau</span></h5>
    ```

4. **Liste de groupes** :
    Si le produit a des caractéristiques spécifiques, listez-les en utilisant le composant "list group".
    ```
    <ul class="list-group list-group-flush">
        <li class="list-group-item">Caractéristique 1</li>
        <li class="list-group-item">Caractéristique 2</li>
    </ul>
    ```

5. **Alertes** :
    Ajoutez une alerte sous le bouton pour fournir des informations supplémentaires.
    ```
    <div class="alert alert-info" role="alert">
        Livraison gratuite pour cet article !
    </div>
    ```

6. **Testez votre mise en page** :
    Ouvrez votre page dans un navigateur pour vérifier que tout fonctionne correctement.
