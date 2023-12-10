# Keen-Able-Internship
(**Based on November-2023 batch**)
![photo_6303038419151993282_y](https://github.com/Akshaykumar05/Keen-Able-Internship/assets/114390890/6411af82-8b52-405d-b2a7-632e3404cf51)

* In this repo I am summarising all the related things of this training. There are two parts of the internship.
1. Non-technical
2. Technical

## 1. Non-Tech (6 Tasks) 

| Skills Measuring                                                         | Task                                                                                 
| :------------------------------------------------------------------ | :--------------------------------------------------------------------------------------- |
| 1. Written Communication Skills/ Quality of Work/ Planning & Problem Solving Skills/ Teamwork | Diwali Office Decoration
| 2. Ability to Learn | Learn Google Spreadsheets.
| 3. Research Skills/ Quality of Work | Search Engine Questionnaire
| 4. Problem Solving Skills | Brainteaser
| 5. Communication Skills/ Research Skills/ Quality of Work/ Planning & Problem Solving | Teach a Topic
| 6. Research Skills/ Communication Skills/ Quality of Work | Group Discussion

#### WBS (Work Breakdown Structure)
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRuuqBkH9r6tecoHrKvn1CuJ3HU21M_EBmnEdcLOieScCan6mE1BqTdYFKlHn0JWCFiszA&usqp=CAU)
* Breaking work into smaller tasks is a common productivity technique used to make the work more manageable and approachable. For projects, the Work Breakdown Structure (WBS) is the tool that utilizes this technique and is one of the most important project management documents.

#### [My WBS of these 6 tasks](https://docs.google.com/spreadsheets/d/1XqhWew23b-FNKplvbDdNHRxFnZZv6ZabzMsyWrOodGE/edit?usp=sharing)
#### [DPT Sample](https://docs.google.com/spreadsheets/d/15wWwTZIbxCZoAYrP4czUjAf2vSXrMcjXT2A3DeH6neU/edit?usp=sharing)
#### [DSR Sample](https://docs.google.com/spreadsheets/d/1txpPFfq3oH3lkPiDeoKKaU6cgyGa5g01IISc8BMECJI/edit?usp=sharing)

# Other Tools to learn
* Google Spreadsheet
* Redmine

### Redmine
![](https://raw.githubusercontent.com/docker-library/docs/969091c4c590befe236a71d4a7bce5823fff020d/redmine/logo.png)
* Redmine is a **free and open source**, web-based project management and **issue tracking tool**. It allows users to manage multiple projects and associated subprojects. It features per project wikis and forums, time tracking, and flexible, role-based access control. It includes a calendar and Gantt charts to aid visual representation of projects and their deadlines. Redmine integrates with various version control systems and includes a repository browser and diff viewer.
#### Main features
* Manage all your projects with one Redmine instance
* Each user can have a different role on each project
* Each project can be declared as public (visible by anyone) or private (visible by project members only)
* Modules (eg. wiki, repository, issue tracking, ...) can be enabled/disabled at project level

# Sessions 
1. Public Speaking
2. Email and Google Spreadsheet
3. Empathy and Proactive Behaviour
4. Discussion on GitHub - Discussion among interns.
5. On-line session by Shreesh Chaudhary on "Storytelling". (I shared my Vipassana experience along with PPT) (18/11/23)
6. Book Reading **"But How Do It Know? - The Basic Principles of Computers for Everyone"**. Purpose: to develope curiosity.
   * [Book link](https://www.amazon.in/But-How-Know-Principles-Computers-ebook/dp/B00F25LEVC)
8. How to ask Good Questions.
9. How to search on Google.
10. Book reading **"Mother Pious Lady: Making Sense of Everyday India"**
   [](https://4.bp.blogspot.com/_VMCCOqUYc5c/S_z8Ror_C1I/AAAAAAAABDg/4FYCRI-1DwE/w1200-h630-p-k-no-nu/Mother.bmp)
    * [Book link](https://www.amazon.in/Mother-Pious-Lady-Making-Everyday/dp/8172238649)
11. Experience Sharing Session (By- Ashish Jha, Keenable Employee)
* My Takeaway from the session:
  * Keep the interest in learning (that can be either in your technical stuff or any hobby)
  * Find out the solution if you phase any challange (so that it can't repeat in future)
    
# 2. Technical 
## Documentation
* Docker
* Podman
* Kubernetes
* AWS
## (Linux 40 task) 🐧
1. File and Folder Create Command (TOUCH, MKDIR, VIM )
* Touch: used to create, change and modify the timestamps of a file.
  - **cat command**: It is used to create the file with content.
  - **Touch command**: It is used to create a file without any content. The file created using the touch command is empty. This command can be used when the user doesn’t have data to store at the time of file creation.
  - **Vim command**: Vim is an advanced and highly configurable text editor built to enable efficient text editing. Vim text editor is developed by Bram Moolenaar. It supports most file types and vim editor is also known as a programmer’s editor.
    
* mkdir: used used to make a new directory.
* vim: Vim is an advanced and highly configurable text editor built to enable efficient text editing. It supports most file types and vim editor is also known as a programmer’s editor. We can use its plugin based on our needs.
  
2. File and Folder Permission (CHOWN, CHMOD, CHGRP)
* **chown**: used to change the file Owner or group. Whenever you want to change ownership, you can use chown command.
  - Syntax: chown owner_name file_name
* **chmod**
* [Reference](https://www.geeksforgeeks.org/chown-command-in-linux-with-examples/)
4. Check File/Folder/Content (LS, LL, CAT, GREP, HEAD, TAIL, LESS, MORE, ECHO)
* **ll command**: The 'll' command is a robust utility that displays detailed directory listings. (details like permissions, number of links, owner, group, size, and time of last modification)
* -a: This option makes 'll' display all files, including hidden ones
* -h: This option makes 'll' display file size in human-readable format (K for kilobytes, M for megabytes, etc.).
* -R: This option makes 'll' list directories recursively, showing their content and the content of their subdirectories.
  
* Syntax: ll [file_name]
5. Copy and Move Command (RM, CP, MV, SCP, RSYNC)
  - **RM Command**: rm stands for remove here. rm command is used to remove objects such as files, directories, symbolic links and so on from the file system like UNIX.
  - Syntax: rm [OPTION]... FILE...
  - **CP Command**: cp stands for a copy. This command is used to copy files or groups of files or directories. It creates an exact image of a file on a disk with a different file name.
  - Syntax: cp [Source_file] [Destination_file]
  - **MV Command**: The mv command moves files and directories from one directory to another or renames a file or directory. If you move a file or directory to a new directory, it retains the base file name. When you move a file, all links to other files remain intact, except when you move it to a different file system. When you move a directory into an existing directory, the directory and its contents are added under the existing directory.
  - Syntax: mv [options(s)] [source_file_name(s)] [Destination_file_name]
6. User/Group and Access (USERADD, USERDEL, USERMOD, GROUPADD, GROUPDEL, SU, SUDO, SSH,)
