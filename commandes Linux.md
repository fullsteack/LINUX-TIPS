## Navigation dans les répertoires
__wd__ : afficher le répetroire courant  
__cd repertoire__: se déplacer dans le [répertoire]  
__cd__ : se déplacer vers le répertoire maison  
__cd ..__ :  se déplacer vers le répertoire parent  
__ls repertoire__ : lister les fichiers  
__ls -a repertoire__ : lister les fichiers cachés  
__ls -l repertoire__: lister les droits d'accès par fichier  

## Déplacer, copier, créer, supprimer...
__mv sources cible__ : déplacer un fichier (ou le renommer)  
__cp sources cible__ : copier un fichier  
__cp -R sources  cible__ : copier un répertoire  
__ln -s__ : créer un lien symbolique  
__mkdir repertoire__ : créer un répertoire  
__rmdir repertoire__ : supprimer un répertoire  
__du -ks repertoire__: afficher la taille d'un répertoire en Ko  
__rm fichier__ : supprimer un fichier  
__rm -f fichier__ : supprimer un fichier protégé en écriture (force la suppression)  
__rm -R repertoire__ : supprimer un répertoire  
__touch fichier__ : mettre à jour la date de modification d'un fichier / créer un fichier vide  

## Rechercher un fichier
__locate motif__: rechercher des fichiers dont le nom correspond au motif  
__updatedb__ : mettre à jour l'index des fichiers  
__find chemin options__ : rechercher des fichiers correspondant aux options (plus d'info : man find)
__grep -ris 'expression'__ : rechercher des mots correspondant à l'expression saisie  
