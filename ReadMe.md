# Projet TEST GIT

Projet de test git

## Line de commande

**Initialisation du repertoire:**
```bash
$ git init
```

**Avoir le status de git:**
```
$ git status
```

**voir les commits:**
```
$ git log
```

**lister toutes les branches:**
```
$ git branch
```

**créer nouvelle branche:**
```
$ git branch [maBranche]
```

**swicher sur la branche:**
```
$ git checkout [maBranche]
```

**positionner sur un commit:**
```
$ git checkout SHADuCommit
```

** *"revert"* un commit, créer un nouveau commit qui fait l'inverse du précédent:**
```
$ git revert SHADuCommit
```

**ajouter le(s) ficher(s) dans l'index pour preparer le commit:**
```
$ git add filename]
$ git add .
```

**Commit des modifications:**
```
$ git commit -m "label du commit"
```

**Envoyer sur le remote les commits:**
```
$ git push -u origin
```

**recuperer depuis le remote les commits:**
```
$ git pull origin
```

**Avoir ligne par ligne l'autor et le commit:**
```
$ git blame [filename]
$ git blame -L 10,15 [filename]
```

**voir le modification d'un commit:**
```
$ git show [SHA:266ba62d^]
```

**Permet de resoudre des confits, en ouvrant winmerge:**
```
$ git mergetool --tool=winmerge
```

