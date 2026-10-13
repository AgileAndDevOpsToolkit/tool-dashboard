# Prompts initiaux

Premier promt, avec ChatGPT 5.6 sol le 2027-07-30

```
Je veux développer une nouvelle application en html/CSS/JS qui me permettrait d'afficher des sortes de tuiles avec une tuile = un lien vers une appli gadget de ma collection d'applis (mots mêlés, roue des prénoms, BingoDemo etc). Pour le visuel je te donne un screenshot d'une application qu'on a développé il y a quelques mois : le site prompt-collection dont la page html est disponible ici : https://github.com/AgileAndDevOpsToolkit/prompt-collection/blob/main/index.html 
Je veux que toutes les datas des tuiles soient stockées dans un fichier json unique : un tableau de "liens" et pour chaque "lien" il y a un lien bien sûr (ce sur quoi on va cliquer), un titre, un texte de description et éventuellement une image. 
Je ne sais pas si c'est important mais plus tard, cette page sera hébergée dans un conteneur docker et les liens seront des liens vers d'autres conteneurs sur la même machine (donc pas forcément des URL http mais des liens de réseau docker vers d'autres conteneurs). 
Fais-moi une page index.html et un fichier liens.json d'exemple. Je veux quelque chose de pro, clair et épuré
```

```
L'application est très bien mais je voudrais l'enrichir : en fait je voudrais mettre les applications dans plusieurs catégories :
au lieu que ce soit écrit "Applications disponibles", il faudrait que ça soit écrit le nom de la catégorie et toutes les catégories se suivent de haut en bas. Peux-tu me faire cette modification et me proposer un nouveau JSON pour la gestion des catégories : au lieu d'être un tableau d'applications, c'est un tableau de catégories, chaque catégorie contient un titre et un tableau d'applictions
```
