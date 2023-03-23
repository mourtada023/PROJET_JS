# TP1 JS : Starship, the triple A shooter.

Voici le dépôt du TP1 noté de JS, sur le jeu vidéo Starship.

# Participant
- Zidani Mohamed
- Niemczycki Justinien
- Diallo Mamadou
- Le Guen Romain

# Prérequis

- Avoir nodeJS. (Pour l'installation si vous êtes au M5 : https://intranet.fil.univ-lille1.fr/2020/04/09/nodejs-et-npm/. Si vous êtes sur votre poste personnel : https://nodejs.org/fr/download/. Si vous êtes sur Linux https://nodejs.org/fr/download/package-manager/)
- Avoir extrait le fichier ou avoir cloné le git.

# Installation du jeu

Après avoir remplis les prérequis. Il faut accéder au dossier via le terminal il faut se déplacer avec la commande cd si vous êtes sur Linux.
Une fois arrivé dans tp-starship faite :


```shell
npm install
```

Il faudra attendre un peu puis après faite la commande:

```shell
npm run build
```

Qui va créer un fichier dist.

# Resumé:
Jeu vidéo où le joueur essaye d’abattre des
vaisseaux enemmis à l’aide d’un vaisseau
qu’il contrôle au clavier

# Accéder au jeu
Pour accéder à celui-ci il suffit de se rendre à l'endroit où se trouve le fichier dist/ et cliquer sur index.html
Le jeu se lancera.

# Prise en main du jeu

Après le chargement votre vaisseau apparaîtra à gauche pour vous déplacez appuyez sur les flèches du haut et du bas.
Pour tirer il suffit d'appuyer sur espace.

Il y a deux boutons en dessous du jeu l'un permet de faire apparaître un vaisseau et l'autre en faire apparaître à intervalle régulier.
Vous gagnez 200 points par vaisseau abattu et en perd 1000 quand il passe derrière vous.
