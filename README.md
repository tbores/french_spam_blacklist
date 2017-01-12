# Dépôt french_spam_blacklist
Liste noire d'expéditeurs de spam en France
[https://github.com/tbores/french_spam_blacklist.git](https://github.com/tbores/french_spam_blacklist.git)

# Description
Il s'agit d'un filtre de messages pour Thunderbird

# Installation
1. Télécharger le fichier msgFilterRules.dat
2. Trouver où se trouve le répertoire contenant votre profil Thunderbird
...Pour les utilisateurs windows voir ce [http://kb.mozillazine.org/Profile](lien).
3. Placer le fichier msgFilterRules.dat dans votre répertoire profil.
4. Si un fichier du même nom existe déjà il faudra fusionner les deux fichier manuellemnt


# Participer
1. Demandez l'accès au dépôt via l'inferface github
...Vous pouvez lire la [https://guides.github.com/activities/contributing-to-open-source/](documentation github officielle)
2. Allez dans votre répertoire profil
3. Démarrer un dépôt git depuis cet endroit: git init
4. Modifier l'adresse du dépôt originel: git remote add origin https://github.com/tbores/french_spam_blacklist.git
5. Fusionner votre msgFilterRules.dat avec celui du dépôt github: git pull origin master --allow-unrelated-histories

