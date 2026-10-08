# Présentation indépendante — Inovix Market

Ouvrir `index.html` dans un navigateur pour consulter la page. Elle contient son propre HTML, CSS, JavaScript et favicon, sans dépendance à PHP, MySQL, Stripe, au réseau ou aux fichiers du marketplace. Les seuls liens externes ouvrent le site public lorsque le visiteur les utilise.

Le dossier est ignoré par le Git du marketplace et exclu du script de préparation de `deploy/`. Il n'est pas ajouté aux routes du site d'origine. L'aperçu des trois rôles est illustratif et n'utilise aucune donnée réelle.

## Publier dans un portfolio GitHub Pages

1. Copier uniquement `index.html` dans le dépôt GitHub de votre portfolio, par exemple dans `projets/inovix-market/index.html`.
2. Publier ce dépôt avec GitHub Pages selon sa configuration habituelle. Aucun build n'est nécessaire pour cette page HTML.
3. Ajouter un lien depuis votre portfolio vers `./projets/inovix-market/` (adapter le chemin à l'emplacement de la page).

Pour un dépôt Pages dédié, placer `index.html` à sa racine et choisir la branche et le dossier correspondants dans **Settings → Pages → Deploy from a branch**.

Voir la [documentation officielle de publication GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

L'exclusion concerne le dépôt du marketplace uniquement : pour rendre la page accessible sur GitHub Pages, sa copie doit bien être publiée dans le dépôt séparé du portfolio.

## Personnaliser

- Modifier le titre, les descriptions et les styles directement dans `index.html`.
- Les deux liens vers l'application utilisent actuellement `https://recommender-media.com/` : les remplacer si le domaine change.
- Aucun secret, identifiant de compte, cookie, suivi analytique ou formulaire de paiement n'est inclus.
