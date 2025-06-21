**LAB 1**

**TITLE:** Getting started with git for managing code

**OBJECTIVE:** To introduce the fundamentals of Git, a distributed version control system, and demonstrate its basic operations for managing code collaboratively and efficiently.


**THEORY:** Git is a distributed version control system used to track changes in source code during software development. It allows multiple developers to work on a project simultaneously, without interfering with each other’s work

**KEY CONCEPT:**

* Repository (Repo): A directory that contains your project files and a .git folder for version tracking.

* Commit: A snapshot of changes made to files in the repository.

* Branch: A separate line of development.

* Merge: Combining changes from one branch into another.

* Remote Repository: A version of your project hosted on the internet or network (e.g., GitHub, GitLab).

**STEPS:**

**1. Configure Git (One-time setup)**

```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
**2. Create a New Project Directory**

```
mkdir my-first-git-project
cd my-first-git-project

```


**3. Initialize a Git Repository**

```
git init

```
This creates a hidden .git folder where Git tracks your changes.

**4. Create a File and Add Content**

```
echo "# My First Git Project" > README.md

```
**5. Check Git Status**
```
git status

```

**6. Add File to Staging Area**
```
git add README.md

```

**7. Commit the File**
```
git commit -m "Initial commit with README"

```

**8. Create a Repository on GitHub**

* Go to https://github.com

* Click on New Repository

* Name it my-first-git-project

* Do not initialize with README (you already have one locally)
  
  **9. Link Local Repo with Remote**
  ```
  git remote add origin https://github.com/your-username/my-first-git-project.git 
  ```

**10. Push Code to GitHub
```
git push -u origin master

```

**CONCLUSION:** These skills are essential for modern software development, enabling effective collaboration, version tracking, and efficient code management. Mastering Git is foundational for any developer working on individual or team projects.

