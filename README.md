# Calco

Application web en français pour calculer le produit de deux matrices. Tout le calcul est effectué dans le navigateur; aucune donnée n'est envoyée à un serveur.

## Utilisation

Ouvrez `index.html` dans un navigateur. Choisissez les dimensions de A et B, saisissez les nombres, puis cliquez sur **Calculer A × B**. Le nombre de lignes de B suit automatiquement le nombre de colonnes de A. Les dimensions sont limitées à 8; le résultat peut être téléchargé en CSV.

## Publication sur GitHub Pages

1. Créez un dépôt GitHub et ajoutez-y `index.html` et `README.md`.
2. Dans le dépôt, ouvrez **Settings > Pages**.
3. Sous **Build and deployment**, choisissez **Deploy from a branch**.
4. Sélectionnez la branche `main` et le dossier `/(root)`, puis enregistrez.
5. Après la publication, GitHub Pages affiche l'adresse du site dans cette même section. Elle ressemble à `https://votre-nom.github.io/nom-du-depot/`.

Aucune compilation ni dépendance n'est nécessaire : `index.html` est directement publiable comme site statique.