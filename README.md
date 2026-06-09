## Git Practice Evidence

### git log --oneline
```
494983f (HEAD -> main, origin/main) Merge pull request #6 from fvaz27/feature/responsive-styling
b13ec0f add: add css styles and responsive mobile layout
39879d3 Merge pull request #5 from fvaz27/feature/do-not-commit
776b4ec add: add do not commit safety section
ab60d72 Merge pull request #4 from fvaz27/feature/command-reference
6c495bd Merge branch 'main' into feature/command-reference
62feb13 Add: add git restore to command reference section
748fc1c add: add HTML structure
3bfb1d7 update: update gitignore file
5af42ce add: Add .gitignore
```

### git log --oneline --graph --all
```
*   494983f (HEAD -> main, origin/main) Merge pull request #6 from fvaz27/feature/responsive-styling
|\  
| * b13ec0f add: add css styles and responsive mobile layout
|/  
*   39879d3 Merge pull request #5 from fvaz27/feature/do-not-commit
|\  
| * 776b4ec add: add do not commit safety section
|/  
*   ab60d72 Merge pull request #4 from fvaz27/feature/command-reference
|\  
| *   6c495bd Merge branch 'main' into feature/command-reference
| |\  
| |/  
|/|   
* | 748fc1c add: add HTML structure
| * 62feb13 Add: add git restore to command reference section
|/  
* 3bfb1d7 update: update gitignore file
* 5af42ce add: Add .gitignore
```

### git branch --all
```
  feature/command-reference
  feature/do-not-commit
  feature/responsive-styling
* main
  remotes/origin/feature/command-reference
  remotes/origin/feature/do-not-commit
  remotes/origin/feature/responsive-styling
  remotes/origin/main
```