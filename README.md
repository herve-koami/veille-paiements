# Veille paiements : frise du marché 2026-2030

Frise des échéances réglementaires, des nouveaux rails et des menaces sur les paiements, la fraude et la conformité, en Europe et en Afrique.

**Site :** https://herve-koami.github.io/veille-paiements/

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | La frise, en une page autonome (filtres, détail au clic, liste complète) |
| `frise.pdf` | Export PDF de la page complète |
| `data/radar.json` | Les 96 lignes du radar, au format JSON |
| `.nojekyll` | Sert les fichiers tels quels sur GitHub Pages |

Source : radar réglementaire paiements, fraude et conformité, veille du 19 novembre 2026.

## Clés de `data/radar.json`

| Clé | Colonne du radar |
|---|---|
| `d` | Échéance (AAAA, AAAA-MM ou AAAA-MM-JJ) |
| `t` | Type de veille |
| `z` | Zone |
| `n` | Texte ou initiative |
| `c` | Ce qui change |
| `o` | Opportunité |
| `th` | Thème |
| `q` | Qui est concerné |
| `i` | Impact pour un éditeur B2B |
| `s` | Statut |
| `f` | Confiance |
| `u` | Source |

## Mettre à jour

1. Les données sont intégrées dans `index.html` (tableau `D`) et dupliquées dans `data/radar.json`. Modifier les deux.
2. Changer la date de la ligne « Aujourd'hui » et celle du pied de page.
3. Pousser sur `main` : GitHub Pages republie le site en une à deux minutes, à la même adresse.

## Publication

Settings → Pages → Build and deployment → Deploy from a branch → `main`, dossier `/ (root)`.
