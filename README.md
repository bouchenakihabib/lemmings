## Projet Lemming BOUCHENAKI Habib 3522424 et MEYNIER Florent 3700051

# Projet

Jeu lemming en Haskell-SDL2, code + quelques niveaux, possibilité d'en ajouter de nouveaux 

## Compilation

Ce projet requiert la bibliothèque sdl2 (Simple Media Libary, v2.0).

Sous Linux ou MacOS, il suffit d'installer la dépendance associée
(par exemple `libsdl2-dev` sous Debian/Ubuntu).

**Remarque**: SDL2 ne semble pas encore compatible avec la puce M1 des nouveaux MAC.

Sous Windows, c'est un peu plus complexe (comme d'habitude).  Le plus simple est de passer par *msys2* dont une version est installée par *stack*.  Normalement, la commande suivante devrait suffire :

```
stack exec -- pacman -S mingw-w64-x86_64-pkg-config mingw-w64-x86_64-SDL2
```

Dans tous les cas, on utilisera :

```
stack build
```

Pour construire le projet.

et :

```
stack run
```

Pour le lancer...

