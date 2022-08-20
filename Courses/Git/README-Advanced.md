![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/logo.png)

<div style="text-align: center">

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=nirgeier)&emsp;[![Linkedin Badge](https://img.shields.io/badge/-nirgeier-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nirgeier/)](https://www.linkedin.com/in/nirgeier/)

[![](https://img.shields.io/badge/-nirg@codewizard.co.il_/_054_8122310-fcc624?style=for-the-badge&logo=microsoftoutlook&logoColor=red&link=mailto:nirg@codewizard.co.il)](mailto:nirg@codewizard.co.il)&emsp;[![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/whatsapp-icon.png)](https://api.whatsapp.com/send/?phone=972548122310&text=%D7%A9%D7%9C%D7%95%D7%9D.%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%AA%D7%A2%D7%A0%D7%99%D7%99%D7%9F%20%D7%91%D7%A7%D7%95%D7%A8%D7%A1%D7%99%D7%9D)

</div>

---

# Git Advanced topics

|                                                                                           | Level    | Duration |
| ----------------------------------------------------------------------------------------- | -------- | -------- |
| ![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/git.png) | Advanced | 2 days   |

---

On one hand Git is a pretty simple tool, on the other hand to manage git on organization level... <br/>**This is another story**.

## Git Advanced course main objectives

- The main objective of this course is to **learn how to manage Git**, 
- In this course the participants will learn what are the essentials and critical aspects tha need attention when you working in teams/ organizations
- The course will teach best practices and recommendation for managing Git with **AzureDevOps**
- At the end fo this course the participants should know how to avoid and resolve critical and import issues like:
  - Avoiding conflicts and how to resolve them effectively
  - Block deleting GIT history / branches and how to fix those issues if someone did it by mistake
  - Advanced topics like working with Pull Requests and verifying the bew content doesn't break the existing branch.
  - What are git hooks and when to use them
  - Managing multiple fixes on multiple branches simultaneously
  - Best practices and policies for different teams who are using Git

### Audience and prerequisites

- This course assume the participants has been working with Git and have prior knowledge before attending this course.
- The course is for `Developers` / `DevOps` / `Git Administrators`

### Main Goals

- How to configure git for your organization (configuration, hooks, aliases, gitconfig)
- What are branches and how to use them efficiently to improve your team productivity
- How do merges work (`ff`, `no-ff`, `rebase`) and when to choose each merge strategy
- GitFlow and why it is recommended to use it
- Git hooks, what are git hooks, how to create & use them, and why/when to use them to enforce policies and to improve productivity
- Why using Pull Request is important and how to use it correctly.
- CI/CD for Git repositories for improving productivity
- Tips & Tricks and Beyond


---
<div style="page-break-after: always;"></div>

|                           |                                                                                                                                                             |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Session**               | **Content**                                                                                                                                                 |
| **Intro**                 |                                                                                                                                                             |
|                           | :small_blue_diamond: Git & Azure DevOps - overview & configuration                                                                                          |
|                           | &emsp;&emsp; :small_orange_diamond: Azure Repos Setting                                                                                                     |
|                           | &emsp;&emsp; :small_orange_diamond: Azure Repos Policies                                                                                                    |
|                           | &emsp;&emsp; :small_orange_diamond: Azure Repos Security                                                                                                    |
|                           | &emsp;&emsp; :small_orange_diamond: Azure Repos Advanced Security                                                                                           |
| **Project Management**    |                                                                                                                                                             |
|                           | :small_blue_diamond: Git & Project management                                                                                                               |
|                           | &emsp;&emsp; :small_orange_diamond: Integration with AzureDevOps/Jira or any other management tool                                                          |
|                           | &emsp;&emsp; :small_orange_diamond: How to add visibility for managers                                                                                      |
|                           | &emsp;&emsp; :small_orange_diamond: Integration with AzureDevOps/3rd part tools like Jenkins                                                                |
|                           | &emsp;&emsp; :small_orange_diamond: How to link git commits/branches/pr/builds to AzureDevOps                                                               |
| **Git Administrations**   |                                                                                                                                                             |
|                           | :small_blue_diamond: Managing Git (Cross teams / Multiple teams)                                                                                            |
|                           | &emsp;&emsp; :small_orange_diamond: Define the suitable branching model for your team / organization                                                        |
|                           | &emsp;&emsp; :small_orange_diamond: Managing branches                                                                                                       |
|                           | &emsp;&emsp; :small_orange_diamond: Managing changes (single/multiple branches like hotfix)                                                                 |
|                           | &emsp;&emsp; :small_orange_diamond: Define git hooks                                                                                                        |
| **GitFlow**               |                                                                                                                                                             |
|                           | :small_blue_diamond: What is GitFlow                                                                                                                        |
|                           | &emsp;&emsp; :small_orange_diamond: Deep understanding of the GitFlow model                                                                                 |
|                           | &emsp;&emsp; :small_orange_diamond: Why should we use it                                                                                                    |
|                           | &emsp;&emsp; :small_orange_diamond: How can this model improve out productivity                                                                             |
|                           | &emsp;&emsp; :small_orange_diamond: What are the different branches in the model                                                                            |
|                           | &emsp;&emsp; :small_orange_diamond: How can we use the GitFlow scripts for automating the flow                                                              |
|                           | &emsp;&emsp; :small_orange_diamond: Best practice for GitFlow                                                                                               |
| **Advanced Topics**       |                                                                                                                                                             |
|                           | :small_blue_diamond: Advanced git features focusing on commands / features for administrators                                                               |
|                           | :small_blue_diamond: **assume-unchanged** <br/>&emsp;&emsp; Ability to change files locally without exposing changes to git                                 |
|                           | :small_blue_diamond: **auto-completion / autocorrect**                                                                                                      |
|                           | :small_blue_diamond: **bisect**<br/>&emsp;&emsp; Search git history for code changes (finding bugs, wrong merges ...)                                       |
|                           | :small_blue_diamond: **cherry-pick**<br/>&emsp;&emsp; Ability to pick specific commits to different repositories or branches                                |
|                           | :small_blue_diamond: **smudge / clean**<br/>&emsp;&emsp; One of the most **important** features of Git                                                      |
|                           | :small_blue_diamond: **merge** <br/>&emsp;&emsp; Deep understating of git merge and how to configure merges across teams to avoid conflicts and more        |
|                           | :small_blue_diamond: **git LFS** <br/>&emsp;&emsp; Manage binaries and big files with GIT                                                                   |
|                           | :small_blue_diamond: **hooks** <br/>&emsp;&emsp; Manage hooks to enforce policies, improve productivity and integration with other tools                    |
|                           | :small_blue_diamond: **notes** <br/>&emsp;&emsp; What are git notes, when to use them and why                                                               |
|                           | :small_blue_diamond: **reflog** <br/>&emsp;&emsp; One of the most **important** commands of Git which allow you to fix many common problems fast and easily |
|                           | :small_blue_diamond: **rerere** <br/>&emsp;&emsp; Letting git resolve conflict you **already resolved** automatically                                       |
|                           | :small_blue_diamond: **squash** <br/>&emsp;&emsp; What is `squash`, when and how to use it to keep history organized and clean                              |
|                           | :small_blue_diamond: **stash**                                                                                                                              |
|                           | :small_blue_diamond: **submodule / subtree** <br/>&emsp;&emsp; Working with dependencies and multiple git projects                                          |
|                           | :small_blue_diamond: **tags**                                                                                                                               |
|                           | :small_blue_diamond: **interactive rebase** <br/>&emsp;&emsp; Rewriting git history                                                                         |
|                           | :small_blue_diamond: **partial add** <br/>&emsp;&emsp; Adding partial file content and not the whole file                                                   |
|                           | :small_blue_diamond: **worktree** <br/>&emsp;&emsp; The most efficient way of **truly** working with multiple branches                                      |
|                           | :small_blue_diamond: **Detached HEAD** <br/>&emsp;&emsp; What is it, why we got it, how to "fix" it                                                         |
|                           | :small_blue_diamond: **reset/revert** <br/>&emsp;&emsp; How to use `reset` & `revert` to fix problems                                                       |
| **Pull Request**          |                                                                                                                                                             |
|                           | :small_blue_diamond: What is pull request                                                                                                                   |
|                           | &emsp;&emsp; :small_orange_diamond: Why should we always use it                                                                                             |
|                           | &emsp;&emsp; :small_orange_diamond: What does the pull request include                                                                                      |
|                           | &emsp;&emsp; :small_orange_diamond: CI/CD with pull request                                                                                                 |
|                           | &emsp;&emsp; :small_orange_diamond: Code review                                                                                                             |
|                           | &emsp;&emsp; :small_orange_diamond: Approvers                                                                                                               |
|                           | &emsp;&emsp; :small_orange_diamond: Verifying code before merging it                                                                                        |
| **Best practices & Tips** |                                                                                                                                                             |
|                           | :small_blue_diamond: Managing binaries / artifacts (Git LFS)                                                                                                |
|                           | :small_blue_diamond: Managing sensitive information with AzureDevOps                                                                                        |
|                           | :small_blue_diamond: Managing sensitive information with Git (Secrets, certificates, tokens etc)                                                            |
|                           | :small_blue_diamond: Searching history (for deleted files, for changes to specific lines, blocks of code)                                                   |
|                           | :small_blue_diamond: Generating release notes                                                                                                               |
|                           | :small_blue_diamond: Advanced Smudge/ Clean demos and abilities                                                                                             |
|                           | :small_blue_diamond: Advanced branching management / policies                                                                                               |
|                           | :small_blue_diamond: Advanced log (flags, grep ...)                                                                                                         |
|                           | :small_blue_diamond: Remove content from git (in case some one committed unwanted content like sensitive information)                                       |
|                           | :small_blue_diamond: Managing hooks globally for teams/ organization                                                                                        |
|                           | :small_blue_diamond: Repository management (clean old branches, find in which branches contains certain commits)                                            |
|                           | :small_blue_diamond: Using `worktree` to improve productivity                                                                                               |
|                           | :small_blue_diamond: Enforcing git message structure (ex: must have link to ticket system)                                                                  |
|                           | :small_blue_diamond: More... `git show`, `git whatchanged`                                                                                                  |

 

---

<a href="https://github.com/nirgeier/CodeWizard-Academy/tree/main?tab=readme-ov-file#codewizard-courses-list">Back to courses list</a>

---
©CodeWizard LTD 2024