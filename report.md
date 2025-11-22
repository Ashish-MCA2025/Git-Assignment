# Git Practical Report

## Student Details
**Name:** Ashish Pal
**Roll Number:** *Add here*
**Course:** MCA
**Subject:** Git & Version Control Practical

---

# Task 1: Installation and Setup

### Check Git Version
```bash
git --version
git version 2.47.3
```

### View Git Configuration
```bash
git config --list
user.name=Ashish Pal
user.email=ashishp.mca25@cs.du.ac.in
color.ui=auto
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
```

---

# Task 2: Initialize Repository and First Commit

### Stage Files and Create Initial Commit
```bash
git add .
git commit -m "Initial Commit"
[master 47644e6] Initial Commit
 1 file changed, 1 insertion(+)
```

### View Commit History (Oneline Log)
```bash
git log --oneline
47644e6 (HEAD -> master) Initial Commit
23826e4 Add README file
```

---

# Task 3: Staging, Diff and Commit Workflow

Screenshot demonstrating this workflow is included in the `screenshots` folder.

---

# Task 4: Branching and Merging

### List Branches
```bash
git branch
  feature-x
* master
```

---

# Task 5: Merge Conflict

Screenshots for merge conflict and its resolution:
- `task5.png`
- `task5ii.png`

---

# Task 6: Remotes and Push/Pull

Screenshot of remote operations is included in `screenshots` folder.

---

# End of Report
