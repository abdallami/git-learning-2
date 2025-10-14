## Correction d'exercice n°2 :  
# Branching & Merging .
1. Creation d'une branche  on tape la commande suivante:   
 - git branch le nom de la branche ("myself") ;
2. Accedez à la branche crée ,créer un fichier about.Txt avec des infos:  
 - git checkout le nom de la branch ("myself") ou git branch -M nom de la branche("elle permet de naviguer entre les branches)
 - touch about.txt ("pour creer un fichier")
 - nano about.txt 
3. Fire un commit puis poschez la branche myself:
  - git add .  ("pour changer l'etat d'un ajout de modifier en starget ")
  - git commit -m "message" ("pour le faire entrer dans l'history")
  - git push origin myself "nom de la branche"("pour pousser la branche  local en ligne ")
4. faire un pull request de git-learning2/myself ->main.  
  - git pull ("pour recuperer toutes les modifications de la branche myself en ligne au local")
5. Mergez le pull request:  
  - git merge myself ("pour combiner la branche myself avec main)