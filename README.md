# Mariage d'Alice & Grégoire

Site du mariage d'Alice & Grégoire, les 17 et 18 juillet 2027 à Vannes.

## Prévisualiser

Le site est entièrement statique : aucune compilation n'est nécessaire.
Ouvrir `index.html` dans un navigateur, ou servir le dossier avec n'importe quel petit serveur local.

## Où modifier quoi

- **Contenu des sections** : `index.html`
- **Styles** : `css/styles.min.css` (styles généraux) et `css/queries.css` (adaptations tablette et téléphone).
  Ces fichiers sont modifiés directement : il n'y a plus de compilation Sass.
- **Comportements** (animations, carrousel, menu mobile) : `js/scripts.min.js`
- **Images** : `img/` (logos dans `img/logo/`, photos des témoins dans `img/temoins/`, galerie dans `img/eng_pics/`)
- **Icônes du site** (onglet, téléphone) : `favicon*`, `apple-touch-icon.png`, `android-chrome-*.png`, `mstile-150x150.png`

### Ajouter une photo à la galerie « À bientôt »

1. Mettre deux versions de la photo dans `img/eng_pics/` : une petite (`nom-sm.jpg`, pour la vignette) et une grande (`nom-lg.jpg`, pour l'agrandissement).
2. Dans `index.html`, copier un bloc `<li>` du carrousel et y mettre les deux noms de fichier.

## Publication

Le site est prévu pour GitHub Pages : https://delyy56.github.io/wedding-website/

## Crédits

Basé sur le modèle [wedding-website](https://github.com/rampatra/wedding-website) de Ram Patra, sous licence GPL-3.0 (voir `LICENSE`).
