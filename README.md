# Lotus Écarlate

Custom Thunderstore modpack for Lotus Écarlate's Lethal Company sessions.
Nothing to see here, get to work employee!

## Installation

- Télécharger et installer [**r2modman** (lien cliquable)](https://thunderstore.io/c/lethal-company/p/ebkr/r2modman/). Instructions détaillées :
  - `Manual Download` > extraire zip > installer `r2modman Setup X.X.X.exe`
- Lancer **r2modman** et sélectionner le jeu **Lethal Company**
  - `Lethal Company` > `Select game`
- Sélectionner le profil **Default**
  - `Default` > `Select profile`
- Installer le pack **Lotus Ecarlate**
  - `Online` > chercher `Lotus` > `Lotus Ecarlate` > `Download` > `Download dependencies`

## Lancer le jeu avec les mods

Si vous lancez le jeu depuis Steam, les mods ne seront pas actifs.
Il faut toujours lancer depuis **r2modman** :

- `Lethal Company` > `Select game` > `Default` > `Select profile` > `Start modded`
- Si vous avez tout bien fait, au lancement du jeu il y a une console qui s'ouvre, et sur le menu principal il y aura écrit `More Company` à la place de `Lethal Company` 😉

## Configuration

- Lancer le jeu avec les mods depuis **r2modman** au moins une fois, comme indiqué ci-dessus (nécessaire pour créer les fichiers de configuration) puis quitter immédiatement
- Paramétrer la résolution du jeu depuis **r2modman**
  - `Config editor` > `BepInEx\config\LCUltrawide.cfg` > `Edit config`
  - Changer la valeur `Height` en fonction de votre résolution d'écran (e.g. 1920x1080 => `1080`, 2560x1440 => `1440`)
  - Pas besoin de toucher `Width`, laisser `0`
  - `Save`

## Mises à jour

Lorsque des mises à jour sont disponibles, une bannière `Update all` s'affichera en haut de la liste des mods sur **r2modman**.

Synchronisez-vous avec l'hôte sur quand et quoi mettre à jour, la moindre différence entre client et serveur peut générer des problèmes allant d'une impossibilité de se connecter (scénario chanceux, parce qu'on sait direct que y a un problème) à des bugs bizarres en jeu (scénario pas chanceux, parce qu'on a l'impression que ça marche mais en fait non...!).
