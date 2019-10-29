## Introduction to GitHub

[Link to post](https://www.notion.so/Introduction-to-GitHub-202af6f64bbd4299b15f238dcd09d2a7)

### 1. What is GitHub?
Git is a version control system, the tool that tracks changes to our files over time and GitHub is a hosting service for project that use Git.

>GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.

>GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

### 2. Getting started with GitHub

### 3. Registering a GitHub account

### 3. Using GitHub

```
mkdir hello-world
cd hello-world

git init

git add .
git commit -m "Initial commit message"
```

#### 3.1. Creating a new GitHub repository

#### 3.2. Pushing our code to the GitHub repository
#### Create a new repository on a command line
```
echo "# playlist" >> README.md
git init
git add README.md
git commit -m "Commit message"
git remote add origin https://github.com/TenzinTsundue/playlist.git
git push -u origin master
```

#### Push an existing repository from the command line
```
git remote add origin http://github.com/TenzinTsundue/playlist.git
git remote -v
git push -u origin master
```

#### 3.3. Making changes to the GitHub repository

```
console.log("Geetings, World!")

git add .
git commit -m "Change greeting"

git push origin master
```

####3.4. Cloning an existing GitHub repository
```
git clone <github-repo-link>
```

### 4. Branching and merging

#### 4.1. Pushing a branch to GitHub
```
# create a branch with name new-feature and initiate it
git checkout -b new-feature

console.log("New greeting!")

git add .
git commit -m "Add new greeting"

git push origin new-feature
```

#### 4.2. Creating a Pull Request (PR)

#### 4.3. Pull changes form GitHub
```
git remote -v
git pull origin master
```

### 5. Forking projects on GitHub

#### 5.1. Forking a repository
```
git clone https://github.com/Username/gitname.git
```

#### 5.3. Proposing changes to the original project

### 6. Concluding words
- [https://help.github.com](https://help.github.com/)
- [https://guides.github.com/](https://guides.github.com/)




