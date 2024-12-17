echo "Contenu de file1" > file1
echo "Contenu de file2" > file2
echo "Contenu de file3" > file3
### 4. Créer des fichiers file1, file2 et file3 sur develop
touch file1 file2 file3
echo "Contenu de file1" > file1
echo "Contenu de file2" > file2
echo "Contenu de file3" > file3
### 5. Fusionner le contenu de develop dans master
git checkout master
git merge develop
### 6. Renommer file1 en file1.txt
git mv file1 file1.txt
### 7. Supprimer file3
git rm file3
