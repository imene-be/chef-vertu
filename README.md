# Chef Vertu

Site vitrine d'une cuisine sans gluten, savoureuse et ancrée dans la science : présentation de la démarche, contenu éducatif et catalogue de recettes.

**Voir le site : [chefvertu.imenebe.fr](https://chefvertu.imenebe.fr)**

## Le projet

Chef Vertu est un projet réalisé de A à Z : direction artistique, maquettes, développement et mise en ligne. Le site veut rendre l'alimentation sans gluten accessible et désirable, avec un ton chaleureux et un contenu sérieux.

## Pages

- **Accueil** : la démarche, les troubles liés au gluten, l'approche en trois piliers
- **Pourquoi sans gluten ?** : contenu éducatif basé sur les travaux du Dr David Perlmutter, programme de 4 semaines, idées reçues
- **Recettes** : catalogue filtrable par catégorie, avec une fenêtre de détail
- **Mentions légales** : informations légales, RGPD, hébergement

## Technologies

- React 19
- React Router 7
- Vite 7
- Styles en ligne (CSS-in-JS)
- Déploiement sur Vercel

## Lancer le projet

```bash
git clone https://github.com/imene-be/chef-vertu.git
cd chef-vertu
npm install
npm run dev
```

Pour produire la version de production :

```bash
npm run build
```

## Structure

```
src/
  components/   Navbar, Footer
  pages/        Home, PourquoiSansGluten, Recettes, MentionsLegales
  data/         recettes.js (le catalogue de recettes)
  index.css     styles globaux
vercel.json     configuration du déploiement
```

## Charte graphique

| Rôle | Nom | Valeur |
|---|---|---|
| Couleur principale | Vert Chef Vertu | `#00461E` |
| Texte principal | Vert nuit | `#00170A` |
| Survol des boutons | Vert foncé | `#003618` |
| Fond de section claire | Vert très clair | `#f0f8f4` |
| Fond de section subtile | Vert pâle | `#f8fcf9` |
| Pied de page | Vert nuit profond | `#00170A` |

**Typographie : DM Sans** (Google Fonts), en graisses 400 (texte), 600 (sous-titres), 700 (titres de section) et 900 (grands titres).

---

Réalisé par [Imène Bentifraouine](https://imenebe.fr), développement et design.
