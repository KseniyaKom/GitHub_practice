# GitHub

## Homework pt.2 branches for (git branch Postman (etc.)

`Postman`

`Jmeter`

`CheckLists`

`Bug Reports`

`SQL`

`Charles`

`Mobile testing`

### 2. Push all branches to external repository

`git push -u origin Postman (etc.)`

### 3. Create a text file with a structure of Bug report within Bug Reports branch

`git checkout Bug_reports`
`cat > "Bug report structure" / vim "Bug report structure"`

### 4. Push the file to external repository

`git add .`
`git commit -m "Bug report structure"`
`git push`

### 5. Merge Bag Reports branch into Main

`git checkout main`
`git merge Bug_reports`

### 6. Push Main to external repository

`git push`

### 7. Create a text file with a structure of Check list within CheckLists branch

`git checkout CheckLists`
`cat > "CheckLists structure" / vim "CheckLists structure"`

### 8. Push the file to external repository

`git add .`
`git commit -m "Check list structure"`
`git push`

### 9. Do Pull Request of CheckLists branch into Main

`click "Compare and pull request --> Create pull request --> Merge pull request --> Confirm merge`

### 10. Synchronize external and local repositories

`git checkout main`
`git pull`
