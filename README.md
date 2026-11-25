## Projet de groupe de fin d'études de Master Informatique parcours Géométrie Informatique Graphique.

### Membres du groupe :
- MAGET Paul : [paul.maget@etu.univ-amu.fr](mailto:paul.maget@etu.univ-amu.fr)
- PLUQUET Antoine : [antoine.pluquet@etu.univ-amu.fr](mailto:antoine.pluquet@etu.univ-amu.fr)
- SOYSALAN Aral : [aral.soysalan@etu.univ-amu.fr](mailto:aral.soysalan@etu.univ-amu.fr)

Ceci est une sous projet qui répertorie une partie des choix de libs explorées SparkJS et Radix.

### Mise en oeuvre du projet :

Installer les dépendances :

```shell
    cd spark-bench
    npm install
```

Il y a potentionellement des erreurs de dépendances avec le package **@sparkjsdev/radix** sur **fsevents** uniquement utile sur macOS mais bloquant. Dans ce cas forcer l'installation avec :

```shell
     npm install @sparkjsdev/radix --force 
```

Enfin pour lancer le serveur et afficher le résultat de sparkJS et Radix : 
```shell
    npm run dev
```

