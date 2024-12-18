# Git Exercise 

## Bundle 1 

### Exercise 1 

```bash
 1  git init
 2  ls
 3  git status
 4  git add .
 5  git commit -m "Initial Changes"
 6  git remote add origin https://github.com/Prime-Cave/TheGym-Git-Basics-Exercises.git
 7  git branch -M main
 8  git push -u origin main
 9  ls
 10  git branch 
 11  git checkout dev
 12  git branch dev
 13  git branch 
 14  git check out dev
 15  git checkout dev
 16  git branch 
 17  git branch test
 18  git branch
 19  git checkout test
 20  git branch 
 21  git checkout dev
 22  git branch -b test
 23  git branch -d test
 24  git add .
 25  git commit -m "Added terminal History"
 26  git push 
 27  git status
 28  clear
 29  git status
 30  git push 
 31  git push --set-upstream origin dev
 32  clear
```

### Exercise 2

```bash 
 1  git stash -u //Stash all unsaved changes 
 2  git stash pop // Returns last stashed changes 
 3  git stash
 4  git stash -u 
 5  git stash list // Returns list of stashed changes 
 6  git stash save " This is the about page" -u //Saves stashes with info 
 7  git stash save "The Teams Page" -u
 8  git stash pop stash@{1} // Returns stashed change at a specific index 
 9  git stash list 
 10  git stash pop stash@{1}
 11  git add . 
 12  git commit -m "Practcing Stash Commands"
 13  git ls-files 
 14  git ls-files -s 
 15  git add bundle1/team.html
 16  git ls-files -s 100644 09057472405afdee5449c7310627e1d4e22d738b 0  bundle1/team.html
 17  git log // Get Log of commits 
 18  git reset --hard // Does a hard reset at the WIP level
 19  git status 
 20  git push 
 21  clear
 22  history 
```
## Bundle 3

### Exercise 1 

```bash 
 1  git switch ft/team-page
 2  git add . 
 3  git commit -m "Bundle 3 Exercise 1"
 4  git push 
 5  git push --set-upstream origin ft/team-page
 6  git branch ft/contact-page
 7  git checkout ft/contact-page
 8  git checkout ft/team-page
 9  git log 
 10  git checkout ft/contact-page
 11  git cherry-pick e026644aa23bb4a0456f54affb1e322a893018c4
 12  git add .
 13  git commit -m "chanegs from the Contact page"
 14  git push 
 15  git push --set-upstream origin ft/contact-page
 16  git branch ft/faq-page
 17  git checkout ft/faq-page
 18  git add . 
 19  git commit -m "Faq changes added"
 20  git push 
 21  git push --set-upstream origin ft/faq-page
 22  git checkout ft/team-page
 23  git branch 
 24  git log
 25  git revert e026644aa23bb4a0456f54affb1e322a893018c4
 26  git branch 
 27  git switch ft/faq-page
 28  git switch ft/team-page
```

## Bundle 3

### Exercise 2

```bash 

```



## RANDOM AND USEFUL COMMANDS

```bash 
    1 git log --oneline // shows a log of all the live merges 
    2 git push --force // Forces a push 
    3 
```