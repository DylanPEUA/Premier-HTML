# Devoir HTML - Formation Développeur Junior

## Présentation

Ce projet est un devoir appliqué visant à mettre en pratique les bases du HTML5. Il est structuré autour de 4 exercices, chacun illustrant un aspect fondamental du développement web statique :

- **Exercice 1** : Page d'accueil et navigation
- **Exercice 2** : Tableaux HTML et gestion des dates
- **Exercice 3** : Formulaire de contact avec validation
- **Exercice 4** : Affichage et organisation d'images

## Structure du projet

```
1/
├── index.html                # Page d'accueil (racine)
├── README.md                 # Ce fichier
├── pages/                    # Dossier contenant les pages des exercices
│   ├── exercice-2.html
│   ├── exercice-3.html
│   └── exercice-4.html
└── assets/
    └── images/               # Images utilisées dans l'exercice 4
        ├── flex-1.jpg ...
        └── grid-5.jpg ...
```

## Consignes respectées

- **Organisation** :
  - Seule la page d'accueil est à la racine, les autres pages sont dans `pages/`.
  - Toutes les ressources (images) sont dans `assets/images/`.
- **Sémantique** :
  - Utilisation systématique des balises `<header>`, `<main>`, `<footer>`.
  - Utilisation de `<time>` pour les dates et heures.
  - Attributs `alt` sur toutes les images.
- **Accessibilité et bonnes pratiques** :
  - Bouton de réinitialisation de formulaire (`type="reset"`).
  - Attribut `required` sur les champs obligatoires.
  - Utilisation de `<th>` pour les totaux dans les tableaux.
- **Commentaires** :
  - Chaque fichier HTML contient un en-tête de commentaire expliquant son rôle.

## Navigation

- La navigation entre les exercices se fait via le menu présent dans chaque page.
- Un lien de retour à l'accueil est disponible dans chaque page d'exercice.

## Auteur

- Projet réalisé dans le cadre de la formation développeur junior.
- Date : avril 2025

---

*Ce projet est un exercice pédagogique et n'est pas destiné à la production.*
