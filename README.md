# Tool Dashboard

Collection d'applications configurée par un fichier JSON.

## Fichiers

- `index.html` : interface et chargement dynamique des tuiles.
- `liens.json` : données des applications.

## Configuration JSON

Le seul champ obligatoire à la racine est `titre`. Les champs suivants sont
optionnels :

- `titreNavigateur` : titre affiché dans l'onglet. Par défaut, `titre` est
  utilisé.
- `contentNavigateur` : description HTML de la page. Par défaut :
  `Tool Dashboard - Collection de liens vers des sites ou applications web`.
- `sousTitre` et `description` : textes affichés dans l'en-tête.
- `footer` : texte affiché dans le pied de page. Par défaut, un lien vers le
  dépôt Tool Dashboard et le texte `by Agile Toolkit` sont affichés.
- `categories` : tableau des catégories. S'il est absent, la page indique
  qu'aucune catégorie n'est configurée.

Le JSON standard n'autorise pas les commentaires. La documentation des champs
est donc placée dans ce README, plutôt que dans `liens.json`.

## Lancement local

Le chargement du JSON utilise `fetch()`. Il faut donc servir le dossier avec
un serveur HTTP :

```sh
python3 -m http.server 8080
```

Puis ouvrir <http://localhost:8080>.