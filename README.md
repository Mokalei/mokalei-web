# Site MOKALEI — Mo'orea Caldera Retreat

Site en deux langues : anglais à l'adresse principale (`/`), français sur `/fr/`.

## Où se trouve quoi

| Ce que vous voulez changer | Fichier | Depuis Pages CMS |
| --- | --- | --- |
| Photos, vidéos, email, Instagram, lien Airbnb, n° d'enregistrement | `src/_data/site.json` | 📷 Photos, vidéos et coordonnées |
| Textes en français | `src/_data/fr.json` | 🇫🇷 Textes en français |
| Textes en anglais | `src/_data/en.json` | 🇬🇧 Textes en anglais |
| Photos et vidéos téléversées | `src/media/` | (automatique) |
| Mise en page (ne pas toucher sans développeur) | `src/_includes/page.njk`, `src/style.css` | — |

## Réglages Cloudflare Pages

- Framework preset : Eleventy (ou « None »)
- Commande de build : `npm run build`
- Dossier de sortie : `_site`
- Version de Node : 22 (fichier `.node-version`)

## Vidéos

Format MP4, moins de 20 Mo par fichier (limite Cloudflare Pages : 25 Mo par fichier).

## Tester sur un ordinateur (facultatif)

```
npm install
npm start
```
puis ouvrir http://localhost:8080
