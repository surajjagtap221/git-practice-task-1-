# git-practice-task-1-
practice exam of the FCT
# Git & GitLab Practical Assignment

##  Project Overview

This repository demonstrates practical Git and GitLab operations including:

- Repository creation and cloning
- Branching strategy
- Pull Request workflow
- Merge conflict resolution
- Forking and contribution workflow
- GitLab repository management
- Repository mirroring between GitLab and GitHub
- Branch protection rules

---

##  Candidate Details

| Field | Details |
|---------|---------|
| Name | Suraj Jagtap |
| Batch | 03-Nov |
| Course | AWS & DevOps |
| Assignment | Git & GitLab Practical Assignment |

---

##  Repository Links

### GitHub Repository

```text
https://github.com/surajjagtap221/git-practice-task
```

### GitLab Repository

```text
https://gitlab.com/surajjagtap221/my-project-for-mirror.git
```

---

# Task Completion Report

##  Task 1: GitHub Repository Creation

Created a public GitHub repository named:

```text
git-practice-task
```

### Screenshot


![](docs/screenshots/task1-github-repo.png)
---

##  Task 2: Repository Clone

Repository cloned successfully to local machine.

### Commands Used

```bash
git clone https://github.com/surajjagtap221/git-practice-task.git
cd git-practice-task
```

### Screenshot

![](docs/screenshots/task2-clone.png)

---

##  Task 3: Initial Development on Main Branch

Updated README with:


- Name : Suraj Jagtap
- Batch : 03-Nov
- Course : MCA - AWS & DevOps

### Commit

```bash
git commit -m "updated readme.md file"
```

### Screenshot


![](docs/screenshots/task3-readme-update.png)

---

##  Task 4: Feature-A Branch

Created branch:

```bash
git switch -c feature-A
```

Created: From main branch

```text
index.html
```

Committed and pushed changes from main branch and then after feature-A branch.

### Screenshot

![main branch push](docs/screenshots/task4-main.png)
![feature-A branch push](docs/screenshots/task4-featureA.png)

---

##  Task 5: Pull Request (Feature-A)

Created Pull Request:

```text
feature-A → main
```

### Screenshot

![](docs/screenshots/task5-pr-featureA.png)

---

##  Task 6: Feature-B Branch

Created branch:

```bash
git switch -c feature-B
```

Modified same lines in `index.html` and push.

### Screenshot

![](docs/screenshots/task6-featureB-modify&push.png)

Created Pull Request:

```text
feature-B → main
```

### Screenshot

![](docs/screenshots/task6-featureB-pr.png)

---

##  Task 7: Merge Feature-A

Attempted merge of Feature-A and encountered conflict. Reviewed and merged Feature-A into main.


### Screenshot

![](docs/screenshots/task7-conflict-featureA.png)
![](docs/screenshots/task7-merge-featureA.png)

---

## Task 8: Merge Conflict Resolution

Attempted merge of Feature-B and encountered conflict.

### Steps Performed

1. Pulled latest main branch changes
2. Resolved conflict manually
3. Committed resolved code
4. Pushed updated branch

### Screenshot

![](docs/screenshots/task8-conflict-occured.png)
![](docs/screenshots/task8-conflict-resolution.png)

---

##  Task 9: Merge Feature-B

Successfully merged Feature-B after conflict resolution.

### Screenshot

![](docs/screenshots/task9-merge-featureB.png)

### final merge of all branch

![](docs/screenshots/task9-merge-all-branch.png)

---

##  Task 10: Fork and Contribution

Forked a public repository.

Performed:

- Clone fork
- README modification
- Push changes
- Create Pull Request

### Screenshot

Create fork

![](docs/screenshots/task10-fork-create.png)

Clone fork

![](docs/screenshots/task10-fork-clone.png)

Readme.md modification

![](docs/screenshots/task10-redme-modify.png)

Create Pull Request

![](docs/screenshots/task10-fork-pr.png)

---

##  Task 11: GitLab Repository Setup

Created private GitLab repository.

Project structure:

```text
project/
├── src/
│   └── app.py
├── docs/
│   └── guide.md
└── README.md
```

### Screenshot

Gitlab repo, it's Clone and above structure

![](docs/screenshots/task11-gitlab-repo.png)
![](docs/screenshots/task11-gitlab-repo-clone.png)
![](docs/screenshots/task11-gitlab-structure.png)

---

##  Task 12: Repository Mirroring

Configured repository mirroring:

```text
GitLab ➜ GitHub
```

Verified automatic synchronization.

### Screenshot

![](docs/screenshots/task12-mirroring.png)

---

##  Task 13: Branch Protection

Configured branch protection for:

```text
main
```

Rules applied:

- Direct push disabled
- Pull Request required
- Protected branch enabled

### Screenshot

Add screenshot here:

![](docs/screenshots/task13-branch-protection.png)

---

##  Task 14: Final Verification Checklist

| Requirement | Status |
|------------|---------|
| GitHub repository created | ✅ |
| Repository cloned locally | ✅ |
| Feature branches created | ✅ |
| Pull Requests created | ✅ |
| Pull Requests merged | ✅ |
| Merge conflict resolved | ✅ |
| Fork created | ✅ |
| GitLab repository configured | ✅ |
| Repository mirroring working | ✅ |
| Branch protection enabled | ✅ |

---

#  Required Screenshots

Create the following folder structure:

# Screenshots Included

```text
docs/
└── screenshots/
    ├── task1-github-repo.png
    │   └── GitHub repository created
    │
    ├── task2-clone.png
    │   └── Repository cloned locally
    │
    ├── task3-readme-update.png
    │   └── README updated with assignment details
    │
    ├── task4-main.png
    │   └── Initial changes pushed to main branch
    │
    ├── task4-featureA.png
    │   └── feature-A branch creation and changes
    │
    ├── task5-pr-featureA.png
    │   └── Pull Request created for feature-A
    │
    ├── task6-featureB-pr.png
    │   └── Pull Request created for feature-B
    │
    ├── task7-conflict-featureA.png
    │   └── Conflict scenario after feature-A merge
    │
    ├── task7-merge-featureA.png
    │   └── feature-A merged into main
    │
    ├── task8-conflict-occured.png
    │   └── Merge conflict encountered
    │
    ├── task8-conflict-resolution.png
    │   └── Merge conflict resolved manually
    │
    ├── task9-merge-featureB.png
    │   └── feature-B merged successfully
    │
    ├── task9-merge-all-branch.png
    │   └── Verification of all merged changes
    │
    ├── task10-fork-create.png
    │   └── Public repository forked
    │
    ├── task10-fork-clone.png
    │   └── Fork cloned locally
    │
    ├── task10-redme-modify.png
    │   └── README modified in forked repository
    │
    ├── task10-fork-pr.png
    │   └── Pull Request created in fork
    │
    ├── task11-gitlab-repo.png
    │   └── GitLab repository created
    │
    ├── task11-gitlab-repo-clone.png
    │   └── GitLab repository cloned via SSH
    │
    ├── task11-gitlab-structure.png
    │   └── Project directory structure created
    │
    ├── task12-mirroring.png
    │   └── GitLab to GitHub repository mirroring
    │
    └── task13-branch-protection.png
        └── Branch protection rules configured
```
---

#  Technologies Used

- Git
- GitHub
- GitLab
- SSH
- Pull Requests
- Branch Protection Rules
- Repository Mirroring

---

#  Conclusion

This assignment demonstrates practical usage of Git and GitLab workflows including collaboration, branching strategies, conflict resolution, repository synchronization, and branch protection mechanisms commonly used in DevOps environments.
