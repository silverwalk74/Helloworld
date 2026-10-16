Hook pre-commit du projet

Ce hook demande, à chaque commit, s'il faut ajouter le fichier
suivi/commitInfo.txt contenant la date de vérification.

Installation (à faire une seule fois après le clone) :

Option 1 (recommandée) : depuis la racine du dépôt
    git config core.hooksPath hooks

Option 2 : copier le hook
    cp hooks/pre-commit .git/hooks/pre-commit
    chmod +x .git/hooks/pre-commit
