# Git Collaboration Game - 2 Person Activity 
This repository is a hands-on git  learning activity designed for 2 participants to practice real world Git collaboration concepts such as branching, merging, conflicts, pull requests, and git stash.
----
## Roles
- Person A -> Developer
- Person B -> Team Lead / Repository Owner

---
## Assumptions
- Repository name: ``` fintech-app```

--- 
## Phase 1 - Project Birth
**Step 1: Developer A creates project locally**
```bash 
mkdir  fintech-app
cd fintech-app
echo "FinTech App - Initial Version" > README.md
echo "console.log('Hello Fintech');" > app.js
git init 
git add .
git commit -m "Initial Commit"
```


