![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/logo.png)

<div style="text-align: center">


![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=nirgeier)&emsp;[![Linkedin Badge](https://img.shields.io/badge/-nirgeier-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nirgeier/)](https://www.linkedin.com/in/nirgeier/)<br/>
[![](https://img.shields.io/badge/-nirg@codewizard.co.il_/_054_8122310-fcc624?style=for-the-badge&logo=microsoftoutlook&logoColor=red&link=mailto:nirg@codewizard.co.il)](mailto:nirg@codewizard.co.il)&emsp;[![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/whatsapp-icon.png)](https://api.whatsapp.com/send/?phone=972548122310&text=%D7%A9%D7%9C%D7%95%D7%9D.%20%D7%90%D7%A0%D7%99%20%D7%9E%D7%AA%D7%A2%D7%A0%D7%99%D7%99%D7%9F%20%D7%91%D7%A7%D7%95%D7%A8%D7%A1%D7%99%D7%9D)

</div>

---

# Ansible

|                                                                                               | Level        | Duration |
| --------------------------------------------------------------------------------------------- | ------------ | -------- |
| ![](https://raw.githubusercontent.com/nirgeier/CodeWizard-Academy/main/resources/ansible.png) | Introduction | 1 day    |

---

## Course Description

- The main objective of this course is to learn Ansible and how to use it as configuration management tool to manage a large number of machines.

### Audience and prerequisites

- This course is mainly for `DevOps` engineers

### Main Goals

- Understand the basics of Ansible, its architecture, and how it works
- How to use it for managing multiple machines
- Apply recommended practices for effective and efficient automation with Ansible.
- Perform automation operations as rolling updates.
- Create automation execution environments to contain and scale Ansible Automation.
- Leverage capabilities of the automation content navigator to develop Ansible Playbooks.

---

| **Module**               | **Content**                                                                                      |
| ------------------------ | ------------------------------------------------------------------------------------------------ |
| **Intro**                | :small_blue_diamond: **Introduction To Ansible**                                                 |
|                          | &emsp;&emsp; :small_orange_diamond: Installing & Configuring Ansible                             |
|                          | &emsp;&emsp; :small_orange_diamond: Features Of Ansible                                          |
|                          | :small_blue_diamond: **Ansible Architecture**                                                    |
|                          | &emsp;&emsp; :small_orange_diamond: Nodes / Hosts                                                |
|                          | &emsp;&emsp; :small_orange_diamond: Children                                                     |
|                          | &emsp;&emsp; :small_orange_diamond: Modules                                                      |
|                          | &emsp;&emsp; :small_orange_diamond: Configuration                                                |
|                          | :small_blue_diamond: Ansible Terminologies                                                       |
|                          | :small_blue_diamond: Use Cases Of Ansible                                                        |
|                          | :small_blue_diamond: What Can Do In Production Environment                                       |
|                          | :small_blue_diamond: Ansible Documentation                                                       |
|                          | :small_blue_diamond: How Ansible Is Different From Configuration Management Tools                |
|                          | &emsp;&emsp; :small_orange_diamond: Differences between Ansible to IAC (ex: Terraform)           |
| **Basics**/**Inventory** |                                                                                                  |
|                          | :small_blue_diamond: Facts                                                                       |
|                          | :small_blue_diamond: Representation Of Dictionary                                                |
|                          | :small_blue_diamond: Inventory Management                                                        |
|                          | &emsp;&emsp; :small_orange_diamond: Non-group Inventory File                                     |
|                          | &emsp;&emsp; :small_orange_diamond: Group Inventory File                                         |
|                          | &emsp;&emsp; :small_orange_diamond: Ansible Inventory Parameters                                 |
| **Ansible CLI**          |                                                                                                  |
|                          | :small_blue_diamond: ansible                                                                     |
|                          | :small_blue_diamond: ansible <group>                                                             |
|                          | :small_blue_diamond: ansible-playbook                                                            |
|                          | :small_blue_diamond: ansible-galaxy                                                              |
|                          | :small_blue_diamond: ansible-playbook                                                            |
|                          | :small_blue_diamond:  Variables                                                                  |
| **Filters / Plugins**    |                                                                                                  |
|                          | :small_blue_diamond:Populate, manipulate and manage data in variables using filters and plugins. |
| **Modules**              |                                                                                                  |
|                          | :small_blue_diamond: Introduction to modules                                                     |
|                          | :small_blue_diamond: Modules in playbooks                                                        |
|                          | :small_blue_diamond: Creating a custom module (using `ansible-core` & `python`)                  |
|                          | :small_blue_diamond: Testing our module using Playbook                                           |
| **Playbooks**            |                                                                                                  |
|                          | :small_blue_diamond: Sample Ansible Playbook                                                     |
|                          | :small_blue_diamond: Ansible Playbook Format                                                     |
|                          | :small_blue_diamond: Ansible Modules                                                             |
|                          | :small_blue_diamond: Ansible Tasks                                                               |
|                          | :small_blue_diamond: Packages                                                                    |
|                          | :small_blue_diamond: Commands:                                                                   |
|                          | &emsp;&emsp; :small_orange_diamond: How To Run A Playbook                                        |
|                          | &emsp;&emsp; :small_orange_diamond: How to check the syntax of a Playbook                        |
|                          | &emsp;&emsp; :small_orange_diamond: How to Run a playbook on multiple hosts/target hosts         |
|                          | :small_blue_diamond: CI/CD with Ansible                                                          |
| **Roles**                |                                                                                                  |
|                          | :small_blue_diamond: What are role                                                               |
|                          | :small_blue_diamond: Define and build roles                                                      |
|                          | :small_blue_diamond: Using Roles in Playbooks                                                    |
|                          | &emsp;&emsp; :small_orange_diamond: Define                                                       |
|                          | &emsp;&emsp; :small_orange_diamond: Execute                                                      |
|                          | &emsp;&emsp; :small_orange_diamond: Manage Roles                                                 |
| **Templates**            |                                                                                                  |
|                          | :small_blue_diamond: Template introduction                                                       |
|                          | &emsp;&emsp; :small_orange_diamond: Jinja2 templates                                             |
|                          | &emsp;&emsp; :small_orange_diamond: Conditions                                                   |
|                          | &emsp;&emsp; :small_orange_diamond: Facts                                                        |
|                          | &emsp;&emsp; :small_orange_diamond: Loops                                                        |
|                          | &emsp;&emsp; :small_orange_diamond: Variables                                                    |
| **Galaxy**               |                                                                                                  |
| **Hand-On**              |                                                                                                  |
|                          | **Hands-on during the different modules**                                                        |

---

<a href="https://github.com/nirgeier/CodeWizard-Academy/tree/main?tab=readme-ov-file#codewizard-courses-list">Back to courses list</a>

---

©CodeWizard LTD 2024