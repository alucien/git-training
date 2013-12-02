2. Validation des idées
• Afin de séparer l'ajout des deux fichiers dans deux commits différents, supprimer
TODO.txt de l'index actuel et commiter un fichier puis l'autre les messages seront
◦ Pour le premier commit
▪ Titre : "Initialisation du projet"
▪ Contenu : "Ajout du fichier README.txt décrivant le projet"
◦ Pour le second
▪ Titre : "Définition des tâches à effectuer"
▪ Contenu : "Création du fichier TODO.txt listant toutes les tâches actuellement
prévues pour le projet"
• Vérifier que les deux fichiers soient biens commités dans deux commits différents avec la
commande git log
3. Retour vers le premier commit
• Afin de préparer la création des futures branches, dont une pour gérer la todolist, remontez
au commit initial avec la commande git checkout et le hash du premier commit qui est
accessible depuis le log
• Lister le contenu du dossier