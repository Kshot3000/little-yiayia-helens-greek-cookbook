# Little Yiayia Helen's Greek Cookbook

A GitHub Pages-ready website honoring Helen, born in Chicago and raised by Greek immigrant parents. The site preserves her family recipes and stories, with real photographs of the dishes and a Greek island (white houses + Greek flag) as the site backdrop.

## Pages
- `index.html` — Home: hero over an Oia village photo, island roots, featured recipes
- `about.html` — About Yiayia Helen, with a flag-and-white-houses alley photo
- `recipes.html` — All 17 recipes (appetizers, soups & stews, mains, desserts), each with a photo

## Structure
```
├── index.html
├── about.html
├── recipes.html
├── css/styles.css      — Greek blue/white theme, responsive, mobile nav
├── js/main.js          — nav toggle, scroll-reveal, footer year
├── images/             — locally bundled photos (Wikimedia Commons, free licenses)
└── README.md
```

## Photos & attribution
All photography is from [Wikimedia Commons](https://commons.wikimedia.org) under free licenses (CC BY, CC BY-SA, CC0, public domain) and is bundled locally in `images/`:

| Image | Dish / Scene | Photographer | License |
|---|---|---|---|
| `background-santorini.jpg` | Site background — white church & Greek flag, Santorini | LBM1948 | CC BY-SA 4.0 |
| `oia-village.jpg` | Oia village, white houses & blue domes | Norbert Nagel | CC BY-SA 3.0 |
| `santorini-flag-alley.jpg` | Greek flag over whitewashed houses | Klearchos Kapoutsis | CC BY 2.0 |
| `tzatziki.jpg` | Tzatziki | Nikodem Nijaki | CC BY-SA 3.0 |
| `greek-salad.jpg` | Greek salad | Geoff Peters | CC BY 2.0 |
| `dolmades.jpg` | Dolmades | Sina.ahm | CC BY-SA 4.0 |
| `taramosalata.jpg` | Taramosalata | Robert Kindermann | CC BY-SA 2.5 |
| `avgolemono.jpg` | Avgolemono soup | Missvain | CC BY 4.0 |
| `fasolada.jpg` | Fasolada | EUGASTRONOMES | CC BY-SA 4.0 |
| `giouvetsi.jpg` | Giouvetsi | Robert Kindermann | CC BY-SA 2.5 |
| `moussaka.jpg` | Moussaka | Andy Li | CC0 |
| `spanakopita.jpg` | Spanakopita | Fajardoalacant | CC0 |
| `briam.jpg` | Briam | Benoit5656 | CC BY 2.0 |
| `souvlaki.jpg` | Souvlaki | Leeturtle | CC BY-SA 4.0 |
| `stifado.jpg` | Stifado | Fajardoalacant | CC BY-SA 3.0 |
| `fasolakia.jpg` | Fasolakia | Robert Kindermann (RobertK) | CC BY-SA 2.5 |
| `galaktoboureko.jpg` | Galaktoboureko | Badseed | CC BY 3.0 |
| `baklava.jpg` | Baklava | Challiyan | CC BY-SA 4.0 |
| `koulourakia.jpg` | Koulourakia | Mvolz | CC0 |
| `yogurt-honey.jpg` | Greek yogurt with honey | LeonardKong | CC BY 2.0 |

The attribution line is also included in the footer of every page.

## Deploy to GitHub Pages
1. Push this folder to a repository (e.g. `little-yiayia-helens-greek-cookbook`)
2. In repository Settings > Pages, set source to the `main` branch, `/` root
3. Your site will be live at `https://<username>.github.io/little-yiayia-helens-greek-cookbook/`

## Local preview
Open `index.html` in a browser, or serve the folder:
```bash
python -m http.server 8000
# then visit http://localhost:8000
```

Made with love in Chicago.
