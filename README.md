# Linktree Universitaire - Thibaut FONTAINE

Page de liens personnelle pour enseignants et etudiants de l'Universite de La Reunion.

## Apercu

- Design moderne avec glassmorphism
- Theme clair/sombre
- Couleurs officielles Universite de La Reunion (`#203363`)
- Responsive (mobile, tablette, desktop)

## Technologies

- [Bulma CSS](https://bulma.io/)
- [Font Awesome 6](https://fontawesome.com/)

## Utilisation

1. Cloner ou telecharger ce dossier
2. Modifier `index.html` avec vos informations :
   - Nom et photo de profil
   - Bio et etablissement
   - Liens personnels
3. Deployer sur GitHub Pages ou autre hebergeur

## Personnalisation

### Changer les couleurs

```css
:root {
    --univ-blue: #203363;  /* Couleur principale */
    --univ-light: #2a4a8a; /* Couleur secondaire */
}
```

### Ajouter un lien

```html
<a href="VOTRE_URL" class="button is-large is-fullwidth link-button fade-in-up" target="_blank">
    <span class="icon"><i class="fas fa-icon"></i></span>
    <span>Nom du lien</span>
    <span class="icon arrow-icon"><i class="fas fa-arrow-right"></i></span>
</a>
```

### Icones disponibles

- `fa-terminal` - Terminal/Code
- `fa-network-wired` - Reseaux
- `fa-shield-halved` - Securite
- `fab fa-github` - GitHub
- `fab fa-linkedin` - LinkedIn

Liste complete : [fontawesome.com/icons](https://fontawesome.com/icons)

## Deploiement GitHub Pages

1. Creer un repo GitHub
2. Pousser les fichiers
3. Settings > Pages > Source: `main` / `root`
4. Votre site sera sur `https://username.github.io/repo-name/`

## Structure

```
univ/
├── index.html           # Page principale
├── pika-deadpool.jpg    # Photo de profil
├── Univ_LOGO_2025.svg   # Logo Universite
├── logo-IUT-*.png       # Logo IUT
├── ESIROI-logo.jpg      # Logo ESIROI
├── Logo-clusir-*.png    # Logo CLUSIR
├── README.md
└── LICENSE
```

## Auteur

**Thibaut FONTAINE**
Security Engineer at Kodetis
Teacher at University of Reunion Island

## Licence

MIT License - Libre d'utilisation et modification.
Voir le fichier [LICENSE](LICENSE) pour plus de details.
