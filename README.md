# gilhardl.github.io

## Création du projet

Taper la commande suivante:
```
$ docker run --rm -v /c/Users/LG/code/LG/gilhardl.github.io:/srv/jekyll  -it jekyll/jekyll:3.8 jekyll new gilhardl
```

## Exécution de l'application

Taper la commande suivante:
```
$ docker run --rm --name gilhardl -v /c/Users/LG/code/LG/gilhardl.github.io:/srv/jekyll -p 4000:4000 -it jekyll/jekyll:3.8 jekyll serve
```