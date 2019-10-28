# Introduction to Git

### [Link to post](https://www.notion.so/Introduction-to-Git-ac396a0697704709a12b6a0e545db049)

### 1. Setup instruction
git —version

#### Configuring your name and email
```
git config —global user.name “Your Name”
git config —global user.email “your@email.com”
```
### 2. Repositories

### 3. Initializing a repository
```
git init
```

### 4. Staging and committing code

#### 4.1. Checking the status
git status
```

#### 4.2. Staging files 
```
git add file.js
git add file.js file2.js file3.js
git add .
```
#### 4.3. Making commits
```
git commit -m “Commit message”
```

#### 4.4. Commit history
```
git log
git checkout <commit-hash>
git checkout master
```

#### 4.5. Ignoring files

### 5. Branches

#### 5.1. Creating a new branch
```
git branch <new-branch-name>
```

#### 5.2. Changing branches
```
git checkout <branch-name>
git checkout -b <new-branch-name>
git checkout master
```

#### 5.3. Merging branches
```
git merge <branch-name>
```

#### 5.4. Deleting a branch
```
git branch -d <branch-name>
```

### 6. Further learning

- Git official documentation: https://git-scm.com/doc
- The free Pro Git book: https://git-scm.com/book/en/v2
- Learn about GitHub: https://guides.github.com/





