# mathieuouillon.github.io

Page d'accueil de https://mathieuouillon.github.io/ : deux cartes qui mènent aux
sites hébergés dans leurs propres dépôts.

| adresse | dépôt |
|---|---|
| `/du-noyau-au-reacteur/` | [du-noyau-au-reacteur](https://github.com/mathieuouillon/du-noyau-au-reacteur) |
| `/recettes/` | [recettes](https://github.com/mathieuouillon/recettes) |

C'est du HTML à la main, sans construction : GitHub Pages publie le dossier tel
quel depuis la branche `main` (`.nojekyll` désactive Jekyll).

- `index.html` : la page d'accueil. Pour un nouveau site, copiez une
  `<a class="carte …">` et ajoutez une couleur `--accent` si besoin.
- `404.html` : page d'erreur. Elle renvoie aussi les anciens liens du cours
  (`/posts/…`, `/glossaire/…`), qui était autrefois à la racine, vers
  `/du-noyau-au-reacteur/…`.
- `sw.min.js` : désinscrit l'ancien service worker (cache hors ligne) du
  cours, installé quand il était à la racine. À garder.
