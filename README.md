
## Git cheat sheet

Créer une branche

```bash
 git checkout b <name_branch>
```
Faire un rebase interactif(depuis current branch feature) 

```bash
git rebase -i HEAD~n° 
```
  
Forcer le push

```bash
 git push -f (current feature branch)
 ```
 
Merger current feature branch avec la dev 

```bash
 entrer dans master et puis : git merge feature name ensui git push -f 
 ```
  
Supprimer une branche en local

```bash
 git branch -d feature 
 ```
 
  
Supprimer une branche en remote

```bash
git push origin --delete -d feature 
```
