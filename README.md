# 🧩 Community Picross

Un jeu de **nonogramme (picross)** intégré au randomizer multimonde **[Archipelago](https://archipelago.gg/)**.
Joue en solo, en multiworld, et **crée tes propres nonogrammes** que la communauté pourra ajouter !

## ▶️ Jouer

**[Cliquez ici pour jouer](https://ymithos.github.io/Community_Picross/)**

Fonctionne directement dans le navigateur — ordinateur, Android et iOS (Safari).
Rien à installer.

### Modes de jeu
- **Solo** : tous les tableaux sont accessibles librement, plus un nonogramme du jour.
- **Archipelago** : connecte-toi à une partie multiworld ; les tableaux se débloquent au fil des objets reçus.

## ✏️ Créer ton propre nonogramme

Le jeu inclut un **éditeur** (bouton « 🎨 Créer un nonogramme ») :
- Dessine à la main, ou **importe une image** (convertie automatiquement en grille).
- Vérifie que ton dessin a une **solution unique** avec le bouton « 🧩 Vérifier ».
- **Exporte un code** que tu peux partager.

### Proposer ta création à la communauté
Tu as créé un nonogramme sympa ? Partage-le pour qu'il soit ajouté au jeu :
1. Dans l'éditeur, clique **📤 Exporter code**.
2. Ouvre une **[Issue](../../issues/new)** sur ce dépôt.
3. Colle ton code, donne un nom à ton nonogramme, et indique une difficulté.

Les meilleures créations pourront être intégrées au **Monde Spécial** !

## 🎮 Héberger une partie Archipelago

Pour générer une partie multiworld avec ce jeu :
1. Récupère le fichier **`picross.apworld`** (voir les *Releases* ou demande à l'hôte).
2. Place-le dans le dossier `custom_worlds/` de ton installation Archipelago.
3. Configure ta partie avec le fichier **`Picross_AP_exemple.yaml`** (un par joueur).
4. Génère et héberge comme n'importe quelle partie Archipelago.

> ⚠️ Le **mode de déblocage** (`unlock_mode: ordered` ou `random`) est figé **au moment de la génération** de la partie. Pour le changer, il faut régénérer.

## 🙏 Crédits

Créé par **Ymithos**.
Les sprites sont des créations originales de style pixel-art ; ce projet est un travail de fan non commercial.
