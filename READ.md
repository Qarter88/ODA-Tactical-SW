# ODA Tactical SW — Site Merch

Site web officiel ODA Tactical SW. Vêtements tactiques multi-poches et montres all-black.

## Structure des fichiers

```
oda-tactical-sw/
├── index.html     # Page principale du site
├── logo.jpg       # Logo ODA Tactical SW
├── montre.jpg     # Photo montre ODA
└── README.md      # Ce fichier
```

## Déploiement sur GitHub Pages

1. Créez un repo sur GitHub (ex: `oda-tactical-sw`)
2. Uploadez tous les fichiers de ce dossier
3. Allez dans **Settings → Pages**
4. Source : `Deploy from a branch` → Branch : `main` → `/root`
5. Votre site sera dispo sur : `https://[votre-pseudo].github.io/oda-tactical-sw/`

## Personnalisation

- **Prix** : cherchez `149€`, `189€`, etc. dans `index.html` pour les modifier
- **Email contact** : cherchez `contact@odatactical.fr`
- **Produits** : chaque carte produit est une `div.product-card`
- **Couleurs** : modifiez les variables CSS en haut du fichier (`:root { ... }`)
