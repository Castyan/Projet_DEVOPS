# Commandes utilisées dans ce projet

## 1. Créer un dossier `devops` et en faire un repository GIT
```bash
mkdir devops
cd devops
git init
```

## 2. Créer un fichier `README.md`
```bash
echo "### Commandes utilisées dans ce projet" > README.md
echo "1. Création du dossier et initialisation GIT." >> README.md
echo "2. Création des branches master et develop." >> README.md
echo "3. Création du fichier README.md." >> README.md
```

## 3. Créer des fichiers `file1`, `file2` et `file3` sur la branche `develop`
```bash
touch file1 file2 file3
echo "Contenu de file1" > file1
echo "Contenu de file2" > file2
echo "Contenu de file3" > file3
git add file1 file2 file3
git commit -m "Ajout des fichiers file1, file2 et file3 dans develop"
```

## 4. Fusionner le contenu de `develop` dans `master`
```bash
git checkout master
git merge develop
```

## 5. Renommer `file1` en `file1.txt`
```bash
git mv file1 file1.txt
git commit -m "Renommage de file1 en file1.txt"
```

## 6. Supprimer `file3`
```bash
git rm file3
git commit -m "Suppression de file3"
```

