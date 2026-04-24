# macOS Cheatsheet

Ce dépôt rassemble un aide-mémoire pour prendre ses repères sur macOS en venant de Windows.

Il a été construit à partir d'un usage réel, avec une attention particulière aux claviers `Mac français` et à la disposition `AZERTY FR`, car de nombreux raccourcis, symboles et caractères spéciaux diffèrent de ce qu'on voit dans des guides plus génériques.

Il est partagé tel quel pour aider d'autres personnes dans le même cas, surtout celles qui découvrent macOS sur un clavier français. On y trouve des symboles utiles, des raccourcis clavier, des repères Finder et quelques commandes Terminal pratiques.

Ce mémo a été rédigé à partir d'un usage réel, avec l'aide de l'IA pour la mise en forme et la consolidation.

## Symboles utiles

Symboles clavier souvent affichés dans les menus macOS, la documentation et les listes de raccourcis.

| Symbole | Signification     |
| ------- | ----------------- |
| ⌘       | Commande          |
| ⌥       | Option / Alt      |
| ⇧       | Majuscule         |
| ⌃       | Contrôle          |
| ↩       | Retour / Entrée   |
| ⌫       | Supprimer         |
| ⎋       | Échap             |
| ⇥       | Tabulation        |
| ⇪       | Verr. Maj         |
| ↑       | Flèche haut       |
| ↓       | Flèche bas        |
| ←       | Flèche gauche     |
| →       | Flèche droite     |

## Saisie de caractères spéciaux

Sur Mac, les combinaisons pour les caractères spéciaux varient selon la source d'entrée utilisée (`Français`, `Français - numérique`, `ABC`, etc.).

Ce mémo note surtout des repères constatés sur un clavier `AZERTY FR`, plutôt que des raccourcis "génériques" trouvés en ligne.

### Repères utiles

Certains raccourcis et certains caractères peuvent varier selon la version de macOS, la source d'entrée active et la disposition exacte du clavier.

| Astuce | Description |
| ------ | ----------- |
| Maintenir une lettre | Maintenir `e`, `a`, `u`, etc. affiche le sélecteur d'accents de macOS. |
| Choisir un accent | Sur mon clavier AZERTY, le choix peut se faire avec `⇧ + chiffre` après avoir relâché la touche maintenue. |
| Vérifier la source d'entrée | Les combinaisons changent selon le layout activé dans macOS. |
| Afficher le visualiseur de clavier | Très pratique pour voir en direct ce que produisent `⌥` et `⇧ + ⌥`. Voir le guide Apple : [Utiliser le visualiseur de clavier sur Mac](https://support.apple.com/fr-fr/guide/mac-help/mchlp1015/mac)|
| Tester les caractères de dev | Le visualiseur de clavier est le moyen le plus fiable pour retrouver les caractères utiles en dev. |

### Caractères utiles en dev

Raccourcis utiles relevés pour un clavier Mac français.

| Touches       | Caractère | Usage |
| ------------- | --------- | ----- |
| ⌥ + n         | `~`       | Tilde |
| ⌥ + ⇧ + /     | `\`       | Antislash |
| ⌥ + ⇧ + L     | <code>&#124;</code> | Pipe |
| ⌥ + (         | `{`       | Accolade ouvrante |
| ⌥ + )         | `}`       | Accolade fermante |
| ⌥ + ⇧ + (     | `[`       | Crochet ouvrant |
| ⌥ + ⇧ + )     | `]`       | Crochet fermant |

Pour afficher le visualiseur de clavier :

1. Ouvre `Réglages Système`.
2. Va dans `Clavier`.
3. Active l'option liée au menu de saisie dans la barre des menus.
4. Ouvre ensuite le `Visualiseur de clavier` depuis la barre des menus.

## Raccourcis clavier

Certains raccourcis peuvent varier selon la version de macOS, l'application utilisée ou la disposition du clavier.

| Raccourci       | Action                      |
| --------------- | --------------------------- |
| ⌘ + Espace      | Ouvrir Spotlight            |
| ⌘ + Tab         | Changer d'application       |
| ⌘ + Q           | Quitter l'application       |
| ⌘ + W           | Fermer la fenêtre           |
| ⌘ + H           | Masquer l'application       |
| ⌘ + M           | Réduire la fenêtre          |
| ⌘ + `           | Changer de fenêtre active   |
| ⌘ + ,           | Ouvrir les préférences      |
| ⌘ + ⌥ + Esc     | Menu forcer à quitter       |

## VS Code

Raccourcis utiles relevés sur un clavier `Mac français` dans Visual Studio Code.

| Raccourci   | Action |
| ----------- | ------ |
| ⌥ + ⇧ + F   | Auto-indenter / formater le document |
| ⌃ + G       | Aller à la ligne |
| ⌥ + ⇧ + V   | Ouvrir la prévisualisation Markdown |
| ⌘ + ⇧ + ;   | Afficher le menu des actions de correction (`Quick Fix`) |
| ⌥ + clic    | Replier récursivement toute l'arborescence d'un dossier dans l'explorateur |

## Finder

Raccourcis notés pour un clavier `Mac français`. Certains équivalents peuvent être affichés différemment dans d'autres documentations selon la disposition du clavier et la version de macOS.

| Raccourci         | Action                        |
| ----------------- | ----------------------------- |
| ⌘ + N             | Nouvelle fenêtre Finder       |
| ⌘ + ⇧ + N         | Nouveau dossier               |
| ⌘ + T             | Nouvel onglet                 |
| ⌘ + ^             | Revenir en arrière            |
| ⌘ + $             | Avancer                       |
| ⌘ + Delete        | Mettre le fichier à la corbeille |
| ⌘ + ⇧ + Delete    | Vider la corbeille            |
| ⌘ + ⇧ + .         | Afficher / masquer les fichiers cachés |
| Espace            | Aperçu rapide                 |

## Captures d'écran

Raccourcis utiles à garder sous la main :

| Raccourci              | Action                                           |
| ---------------------- | ------------------------------------------------ |
| ⌘ + ⇧ + 3              | Capturer tout l'écran                            |
| ⌘ + ⇧ + 4              | Capturer une zone                                |
| ⌘ + ⇧ + 4 puis Espace  | Capturer une fenêtre                             |
| ⌘ + ⇧ + 5              | Outil de capture                                 |
| ⌘ + ⇧ + S dans Firefox | Capturer la zone visible ou la page complète     |

Astuce : maintiens **Contrôle** pour copier la capture dans le presse-papiers au lieu de l'enregistrer.

## Commandes Terminal

| Commande       | Description                         |
| -------------- | ----------------------------------- |
| open .         | Ouvrir le dossier courant dans Finder |
| open -a Safari | Ouvrir Safari depuis le terminal    |
| pbcopy         | Copier la sortie vers le presse-papiers |
| pbpaste        | Coller le presse-papiers dans le terminal |
| say "hello"    | Lire un texte à voix haute          |
| caffeinate     | Empêcher le Mac de se mettre en veille |
| clear          | Effacer l'écran du terminal         |
| history        | Afficher l'historique des commandes |

Exemple :

```bash
echo "hello" | pbcopy
```

## Gestion des fichiers

| Commande     | Description                        |
| ------------ | ---------------------------------- |
| ls           | Lister les fichiers                |
| ls -la       | Lister tous les fichiers, y compris les fichiers masqués |
| pwd          | Afficher le dossier courant        |
| cd dossier   | Changer de dossier                 |
| mkdir dossier | Créer un dossier                  |
| rm fichier   | Supprimer un fichier               |

## Réseau

| Commande         | Description                         |
| ---------------- | ----------------------------------- |
| ifconfig         | Afficher les interfaces réseau      |
| ping github.com  | Tester la connexion réseau          |

## Système

| Commande               | Description                           |
| ---------------------- | ------------------------------------- |
| top                    | Afficher les processus en cours       |
| htop                   | Vue améliorée des processus (si installé) |
| open /Applications     | Ouvrir le dossier Applications        |
| softwareupdate --list  | Lister les mises à jour macOS disponibles |
| uptime                 | Afficher le temps de fonctionnement   |
| whoami                 | Afficher l'utilisateur courant        
