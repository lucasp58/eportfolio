# Portfolio de Lucas Poidevin

Site statique en HTML + CSS (aucun JavaScript, aucun outil à installer).

## Ouvrir le site sur ton ordinateur
1. **Décompresse le zip** (clic droit > Extraire tout). Ne l'ouvre pas depuis l'aperçu du zip : la page perdrait son style.
2. Garde `index.html`, `style.css` et le dossier `assets/` **dans le même dossier**.
3. Double-clique sur `index.html`.

## Le publier sur GitHub Pages
1. Sur github.com : **New repository**, nom `eportfolio` (ou `ton-pseudo.github.io`), public.
2. **Add file > Upload files** : glisse `index.html`, `style.css`, `README.md` et le dossier `assets`, puis **Commit changes**.
3. **Settings > Pages** : Source = *Deploy from a branch*, Branch = `main`, dossier `/ (root)`, **Save**.
4. Après 1 à 2 minutes, le site est en ligne sur `https://ton-pseudo.github.io/eportfolio/`.

## Compléter le contenu
- Dans `index.html`, fais **Ctrl+F « À compléter »** : chaque cadre en pointillés est un champ à remplir.
- Photo : mets ton image dans `assets/` et change `assets/photo-placeholder.svg` par son nom dans le bloc « About me ».
- CV : dépose `CV_Lucas_Poidevin.pdf` dans `assets/`.
- Contact : remplace chaque cadre par un lien (exemples en commentaire dans la section Contact).
- Ajouter une fiche : copie un bloc `<article class="entry">…</article>` et modifie son texte.
- Ajouter un sous-onglet : dans le bloc `tabs` du domaine, ajoute un `<input type="radio">`, un `<label>` et un `<div class="tabs__panel">` au même rang (6 onglets maximum).

## Les 7 domaines
Welcome · Engineering course · International Mobility · Civic Engagement · Sport & other activities · Career Development · Contact
