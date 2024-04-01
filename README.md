# Lotus Écarlate

Custom Thunderstore modpack for Lotus Écarlate's Lethal Company sessions.
Nothing to see here, get to work employee!

## Installation

- Télécharger et installer [**r2modman** (lien cliquable)](https://thunderstore.io/c/lethal-company/p/ebkr/r2modman/). Instructions détaillées :
  - `Manual Download` > extraire zip > installer via `r2modman Setup X.X.X.exe`
- Lancer **r2modman** et sélectionner le jeu **Lethal Company**
  - `Lethal Company` > `Select game`
- Sélectionner le profil **Default**
  - `Default` > `Select profile`
- Installer le pack **Lotus Ecarlate**
  - `Online` > chercher `Lotus` > `Lotus Ecarlate` > `Download` > `Download dependencies`
- Lancer le jeu avec les mods depuis **r2modman** puis quitter immédiatement (nécessaire pour créer les fichiers de configuration)
  - `Start modded` > attendre qu'il se lance
  - Si vous avez tout bien fait, au lancement du jeu il y a une console qui s'ouvre, et sur le menu principal il y aura écrit `More Company` à la place de `Lethal Company` 😉
  - Quitter le jeu
- Paramétrer la résolution du jeu depuis **r2modman**
  - `Config editor` > `BepInEx\config\LCUltrawide.cfg` > `Edit config`
  - Changer la valeur `Height` en fonction de votre résolution d'écran (e.g. 1920x1080 => `1080`, 2560x1440 => `1440`)
  - Pas besoin de toucher `Width`, laisser `0`
  - `Save`

## Lancer le jeu avec les mods actifs

Deux possibilités :

- Depuis **r2modman**
  - `Lethal Company` > `Select game` > `Default` > `Select profile` > `Start modded`
- Depuis **Steam**
  - Paramètrer **Steam** pour lancer automatiquement **Lethal Company** avec les mods
    - Sur **r2modman** : `Settings` > `Debugging` > `Set launch parameters` > copier la ligne de paramètres `Modded`
    - Sur **Steam** : clic droit sur `Lethal Company` dans la bibliothèque > `Propriétés` > coller dans `Options de lancement`
  - À partir de maintenant vous pouvez lancer le jeu depuis **Steam** comme d'habitude, sans passer par **r2modman**

## Mise à jour

- Lancer **r2modman** et sélectionner **Lethal Company** puis le profil **Default**
  - `Lethal Company` > `Select game` > `Default` > `Select profile`
- Mettre à jour le pack **Lotus Ecarlate**
  - `Installed` > `Lotus Ecarlate` > `Update` > `Download with dependencies`
  - Ne pas utiliser le `Update all` de la bannière en haut de la liste `Installed`
