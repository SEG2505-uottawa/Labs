
# Lab 1 


## Consignes:

- Vous devez compléter ce laboratoire en groupe de 4-5.
- **Chaque personne peut que modifier 1 fichier `PersonInfoN`**
- Il est recommandé d'utiliser que la ligne de commande pour compléter ce laboratoire
- Chaque membre de l'équipe va devoir faire un merge dans la branche **master**. Rappel: l'objectif est d'apprendre à utiliser l'outil Git.
- Optionnelle: complétez le laboratoire en communicant avec votre équipe seulement avec Git / GitHub

## Démarche
1. Créez votre répertoire de projet.
2. Clonez le répertoire (repo) `https://github.com/mgarzon/seg2505_2018/`
3. Modifiez un fichier `PersonInfoN` pour qu'il contienne vos informations
4. Ajoutez le document à l'état "staging" (`git add`)
5. Faites un commit dans votre branche **master**
6. Créez une nouvelle branche avec `git checkout -b newBranch`
7. Modifiez votre fichier `PersonInfoN`
8. Ajoutez le document à l'état "staging" (`git add`)
9. Faites un commit dans votre branche **newBranch**
10. Changez à votre branche **master**
11. Modifiez votre fichier `PersonInfoN`, ajoutez d'autres informations à votre description
12. Ajoutez le document à l'état "staging" (`git add`)
13. Faites un commit
14. Dans la branche **master**, faites un `get merge newBranch`

Que voyez-vous?

## Démonstration

1. Un (1) membre de votre équipe fera un _clone_ de la branche **master** trouvé dans ce répertoire.
2. Les autres membres feront un pull de cette branche trouvé dans le répertoire (repo) du membre qui a fait le _clone_.
3. À la fin du laboratoire, le fichier **TheBest.java** dans la branche **master** doit avoir une sortie similaire à

        71 (master) $ j TheBest
        
        Bonjour, je m'appelle  <NOM DU MEMBRE 1>.
        Mon numéro étudiant est <NUMÉRO ÉTUDIANT DU MEMBRE 1>.
        Un peu sur moi : <...>.
        
        Bonjour, je m'appelle  <NOM DU MEMBRE 2>.
        Mon numéro étudiant est <NUMÉRO ÉTUDIANT DU MEMBRE 2>.
        Un peu sur moi : <...>.
        
        Bonjour, je m'appelle  <NOM DU MEMBRE 3>.
        Mon numéro étudiant est <NUMÉRO ÉTUDIANT DU MEMBRE 3>.
        Un peu sur moi : <...>.
        
        Bonjour, je m'appelle  <NOM DU MEMBRE 4>.
        Mon numéro étudiant est <NUMÉRO ÉTUDIANT DU MEMBRE 4>.
        Un peu sur moi : <...>.

