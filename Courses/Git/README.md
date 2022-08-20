![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/logo.png)

<div style="text-align: center">

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=nirgeier)&emsp;[![Linkedin Badge](https://img.shields.io/badge/-nirgeier-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nirgeier/)](https://www.linkedin.com/in/nirgeier/)

[![](https://img.shields.io/badge/-nirg@codewizard.co.il_/_054_8122310-fcc624?style=for-the-badge&logo=microsoftoutlook&logoColor=red&link=mailto:nirg@codewizard.co.il)](mailto:nirg@codewizard.co.il)&emsp;[![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/whatsapp-icon.png)](https://api.whatsapp.com/send/?phone=972548122310&text=%D7%A9%D7%9C%D7%95%D7%9D.%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%AA%D7%A2%D7%A0%D7%99%D7%99%D7%9F%20%D7%91%D7%A7%D7%95%D7%A8%D7%A1%D7%99%D7%9D)

</div>

---

# Git Basic

|                                                                                           | Level                       | Duration |
| ----------------------------------------------------------------------------------------- | --------------------------- | -------- |
| ![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/git.png) | Introduction / Intermediate | 2 days   |

---

## Course Description

- The main objective of this course is to **learn Git**, its internals, and how Git works behind the scenes.
- On one hand, Git is the most popular SCM tool but on the other hand, Git is the most complicated one of them all so users need to get familiar with Git and its abilities and internals

### Audience and prerequisites

- This course is for anyone who has been using any kind of VCS (Version control system) before.
- `Developers`
- `DevOps`

### Main Goals

- How to configure git (configuration, hooks, aliases, gitconfig)
- What are the key features of git (DVCS, 3-states)
- What are branches and how to use them efficiently
- How do merges work (ff, no-ff, rebase)
- GitFlow and why it is recommended as the daily workflow
- hooks, how to create hooks, and why/when to use them
- git "servers" and clients
- How to improve their productivity and code quality (pull request)
- Tips & Tricks and Beyond


---
<div style="page-break-after: always;"></div>

|                     |                                                                                                                                       |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| **Session**         | **Content**                                                                                                                           |
| **Introduction**    |                                                                                                                                       |
|                     | :small_blue_diamond: History of Git                                                                                                   |
|                     | &emsp;&emsp; :small_orange_diamond: The history of git SCSS, RCS                                                                      |
|                     | :small_blue_diamond: **Key Features**                                                                                                 |
|                     | &emsp;&emsp; :small_orange_diamond: DVCS                                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: 3-states                                                                                          |
|                     | &emsp;&emsp; :small_orange_diamond: Storage                                                                                           |
|                     | &emsp;&emsp; :small_orange_diamond: Heuristics                                                                                        |
|                     | :small_blue_diamond: **3- states**                                                                                                    |
|                     | &emsp;&emsp; :small_orange_diamond: What is 3-states and why do we need it?                                                           |
|                     | &emsp;&emsp; :small_orange_diamond: What can we do with the 3-states                                                                  |
|                     | :small_blue_diamond: **Smudge - Clean**                                                                                               |
|                     | &emsp;&emsp; :small_orange_diamond: What are they and how can we use them                                                             |
|                     | :small_blue_diamond: **Configuration**                                                                                                |
|                     | &emsp;&emsp; :small_orange_diamond: Configure username / email                                                                        |
|                     | &emsp;&emsp; :small_orange_diamond: aliases                                                                                           |
|                     | &emsp;&emsp; :small_orange_diamond: CRLF                                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: .gitconfig                                                                                        |
|                     | &emsp;&emsp; :small_orange_diamond: .gitkeep                                                                                          |
|                     | &emsp;&emsp; :small_orange_diamond: .gitignore                                                                                        |
|                     | :small_blue_diamond: **Commit**                                                                                                       |
|                     | &emsp;&emsp; :small_orange_diamond: What is git commit?                                                                               |
|                     | &emsp;&emsp; :small_orange_diamond: How does git store snapshots                                                                      |
|                     | &emsp;&emsp; :small_orange_diamond: What is the difference between git to other CVS tools?                                            |
| **Commands/CLI**    |                                                                                                                                       |
|                     | :small_blue_diamond: The basic and most common git commands                                                                           |
|                     | &emsp;&emsp; :small_orange_diamond: init                                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: clone                                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: add                                                                                               |
|                     | &emsp;&emsp; :small_orange_diamond: rm                                                                                                |
|                     | &emsp;&emsp; :small_orange_diamond: commit                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: status                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: checkout                                                                                          |
|                     | &emsp;&emsp; :small_orange_diamond: log                                                                                               |
| **Branches**        |                                                                                                                                       |
|                     | :small_blue_diamond: What are branches                                                                                                |
|                     | :small_blue_diamond: Branches command                                                                                                 |
|                     | &emsp;&emsp; :small_orange_diamond: checkout                                                                                          |
|                     | &emsp;&emsp; :small_orange_diamond: fetch                                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: branch                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: merge                                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: pull                                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: push                                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: switch                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: worktree                                                                                          |
| **Hands-on**        |                                                                                                                                       |
|                     | :small_blue_diamond: In class hands on working with branches                                                                          |
|                     | &emsp;&emsp; :small_orange_diamond: **Single** branch                                                                                 |
|                     | &emsp;&emsp; :small_orange_diamond: **Multiple** branches                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: **Single remote** branch                                                                          |
|                     | &emsp;&emsp; :small_orange_diamond: **Multiple remote** branches                                                                      |
|                     | &emsp;&emsp; :small_orange_diamond: Multiple branches and multiple users                                                              |
| **Merge / Rebase**  |                                                                                                                                       |
|                     | :small_blue_diamond: What is git merge                                                                                                |
|                     | &emsp;&emsp; :small_orange_diamond: How does git merge branches                                                                       |
|                     | :small_blue_diamond: What are the different git merge strategies                                                                      |
|                     | &emsp;&emsp; :small_orange_diamond: `ff`                                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: `no-ff`                                                                                           |
|                     | &emsp;&emsp; :small_orange_diamond: `rebase`                                                                                          |
|                     | &emsp;&emsp; :small_orange_diamond: **merge-commit**                                                                                  |
| **GitFlow**         |                                                                                                                                       |
|                     | :small_blue_diamond: What is GitFlow                                                                                                  |
|                     | &emsp;&emsp; :small_orange_diamond: Deep understanding of the GitFlow model                                                           |
|                     | &emsp;&emsp; :small_orange_diamond: Why should we use it                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: How can this model improve out productivity                                                       |
|                     | &emsp;&emsp; :small_orange_diamond: What are the different branches in the model                                                      |
|                     | &emsp;&emsp; :small_orange_diamond: How can we use the GitFlow scripts for automating the flow                                        |
|                     | &emsp;&emsp; :small_orange_diamond: Best practice for GitFlow                                                                         |
| **Advanced Topics** |                                                                                                                                       |
|                     | :small_blue_diamond: Quick overview of advanced git features<br/>&emsp;&emsp;(Deep walkthrough is in part of the **advanced course**) |
|                     | &emsp;&emsp; :small_orange_diamond: assume-unchanged                                                                                  |
|                     | &emsp;&emsp; :small_orange_diamond: auto-completion / autocorrect                                                                     |
|                     | &emsp;&emsp; :small_orange_diamond: bisect                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: cherry-pick                                                                                       |
|                     | &emsp;&emsp; :small_orange_diamond: smudge / clean                                                                                    |
|                     | &emsp;&emsp; :small_orange_diamond: fake merge / detailed merge                                                                       |
|                     | &emsp;&emsp; :small_orange_diamond: git LFS                                                                                           |
|                     | &emsp;&emsp; :small_orange_diamond: hooks                                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: notes                                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: reflog                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: rerere                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: squash                                                                                            |
|                     | &emsp;&emsp; :small_orange_diamond: stash                                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: submodule / subtree                                                                               |
|                     | &emsp;&emsp; :small_orange_diamond: tags                                                                                              |
|                     | &emsp;&emsp; :small_orange_diamond: worktree                                                                                          |
| **Pull Request**    |                                                                                                                                       |
|                     | :small_blue_diamond: What is pull request                                                                                             |
|                     | &emsp;&emsp; :small_orange_diamond: Why should we always use it                                                                       |
|                     | &emsp;&emsp; :small_orange_diamond: What does the pull request include                                                                |
|                     | &emsp;&emsp; :small_orange_diamond: CI/CD                                                                                             |

---

<a href="https://github.com/nirgeier/CodeWizard-Academy/tree/main?tab=readme-ov-file#codewizard-courses-list">Back to courses list</a>

---

©CodeWizard LTD 2024