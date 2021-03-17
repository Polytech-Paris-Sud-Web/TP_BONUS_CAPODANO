# TP Migration Angular 9 -> 11

Il est d'abord possible de determiner quelle est la dernière version d'angular.
Pour cela, utiliser la commande ng update.

Il est recommandé de ne pas sauter plus de deux version d'Angular lors d'une migration.

Passer de la version 9 à 10 :
```
ng update @angular/core@10 @angular/cli@10
```
Passer de la version 10 à 11 :
```
ng update @angular/core @angular/cli --force
```

# Changements majeurs

Les nouvelles d'Angular apportent des corrections des dépendances obsolètes et corrigent les vulnérabilités des versions précédentes.
Egalement, des corrections et ajouts sont apportés au tslint afin d'ajuster certaines règles.

# Astuces
Utiliser ce site : https://update.angular.io/
