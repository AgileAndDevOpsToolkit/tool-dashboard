# Tool Dashboard

Collection d'applications

Fichiers :

index.html : interface et chargement dynamique des tuiles

liens.json : données des applications

Lancement local

Le chargement du JSON utilise fetch(). Il faut donc servir le dossier avec un serveur HTTP :

python3 -m http.server 8080

Puis ouvrir : http://localhost:8080