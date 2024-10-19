# Projet Simple de Confirmation de Paiement

Il s'agit d'un projet simple en HTML, CSS et JavaScript simulant un processus de confirmation de paiement pour des produits. Le projet est composé de deux pages HTML :

1. **index.html** : Affiche une liste de produits et contient deux boutons : "annuler" (Annuler) et "payer" (Payer).
2. **succ.html** : Affiche une page de confirmation avec un minuteur de 10 secondes qui redirige vers une URL spécifiée (dans ce cas, la page GitHub).

## Structure du Projet

- **index.html** : Affiche une liste de produits et permet à l'utilisateur d'annuler la transaction ou de procéder au paiement. En cliquant sur le bouton "Payer", une fenêtre de confirmation s'affiche pour demander à l'utilisateur de confirmer le paiement.
- **succ.html** : Une fois le paiement confirmé, cette page s'affiche. Elle montre un message indiquant que le paiement a été effectué avec succès et démarre un compte à rebours de 10 secondes avant de rediriger l'utilisateur vers une URL spécifiée.

### Fichiers :

- `index.html` : Page principale avec la liste de produits et les boutons.
- `succ.html` : Page de succès avec un minuteur de redirection.
- `README.md` : Description et instructions du projet.
- `.git/` : Configuration du dépôt Git.

## Comment Exécuter

1. Ouvrez `index.html` dans un navigateur web.
2. Consultez la liste des produits.
3. Cliquez sur "payer" pour lancer le processus de paiement. Une boîte de dialogue de confirmation apparaîtra.
4. Si confirmé, la page redirigera vers `succ.html` où le succès du paiement est affiché.
5. Après 10 secondes, la page redirige automatiquement vers `https://github.com/ArthurXian`.

## Fonctionnalités

- **Boîte de Confirmation** : Une boîte de dialogue apparaît lorsque l'utilisateur clique sur le bouton "Payer" pour confirmer le paiement.
- **Minuteur de Redirection** : Après la confirmation du paiement, la page de succès (`succ.html`) affiche un compte à rebours de 10 secondes avant de rediriger l'utilisateur vers une autre page.
- **Design Réactif** : La page s'adapte à différentes tailles d'écran grâce au CSS.

## Technologies Utilisées

- **HTML5** : Pour structurer le contenu des pages.
- **CSS** : Pour la mise en page et le style de base.
- **JavaScript** : Pour implémenter la boîte de confirmation, la logique de redirection et le minuteur.

## Améliorations Futures

- Ajouter une logique backend pour le traitement réel des paiements.
- Améliorer l'interface utilisateur avec des descriptions de produits plus détaillées et des images.
- Implémenter des designs spécifiques pour les mobiles pour une meilleure réactivité.

## Licence

Ce projet est open source et disponible sous la licence MIT.

