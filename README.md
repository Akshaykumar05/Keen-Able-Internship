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
* Google Spreadsheet [Resources](https://youtu.be/8TpSEyTR8Jk?si=iYJ0ZcSArNJ6l993)
* Redmine

### Redmine
![](https://raw.githubusercontent.com/docker-library/docs/969091c4c590befe236a71d4a7bce5823fff020d/redmine/logo.png)
* Redmine is a **free and open source**, web-based project management and **issue tracking tool**. It allows users to manage multiple projects and associated subprojects. It features per project wikis and forums, time tracking, and flexible, role-based access control. It includes a calendar and Gantt charts to aid visual representation of projects and their deadlines. Redmine integrates with various version control systems and includes a repository browser and diff viewer.
#### Main features
* Manage all your projects with one Redmine instance
* Each user can have a different role on each project
* Each project can be declared as public (visible by anyone) or private (visible by project members only)
* Modules (eg. wiki, repository, issue tracking, ...) can be enabled/disabled at project level
* [Link of Redmine](http://pems.keenable.io:3000/)

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

### Success Secrets of Internship
* Reach the office on time.
* Send the DPT/DSR daily on time.
* Be responsible with your tasks.
* Do all the task with good quality.
* Communication is important so focus on it. (learn to write good emails)
* Keep a hunger to learn.
* Do participate in random tasks given by mentors.
* Keep good relations with all the mentors and staff.
* Use your creative mind, and understand the Keenable organisation requirments to make something new.
  
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
  - [Reference chown](https://www.geeksforgeeks.org/chown-command-in-linux-with-examples/)
* **chmod**: the chmod command is used to change the access mode of a file.
  - chmod <options> <permission_combination> <file_name>
* **chgrp**: The `chgrp` command in Linux is used to change the group ownership of a file or directory. All files in Linux belong to an owner and a group.
   - Note First we need to have administrator permission to add or delete groups. We can login as root for this purpose or use sudo. In order to add a new group, we can use:
   - Syntax: sudo addgroup growin
   - To change the group ownership of a file.
   - Syntax: sudo chgrp growin filename.txt
     
  ![Screenshot from 2023-12-23 00-22-20](https://github.com/Akshaykumar05/Keen-Able-Internship/assets/114390890/edd191a8-0757-4134-a2ba-1e2d6474867f)
  ![Screenshot from 2023-12-23 00-22-56](https://github.com/Akshaykumar05/Keen-Able-Internship/assets/114390890/fd67d8ff-c793-4616-99c5-7b30e978746b)

4. Check File/Folder/Content (LS, LL, CAT, GREP, HEAD, TAIL, LESS, MORE, ECHO)
* **ls**: provide the list of files and directories.
* **ls -l**: provide long details of all files with alphabetic order.
* **ls -ltr**: to list all the files with with long details and wrt dates.
* **ll command**: The 'll' command is a robust utility that displays detailed directory listings. (details like permissions, number of links, owner, group, size, and time of last modification)
* -a: This option makes 'll' display all files, including hidden ones
* -h: This option makes 'll' display file size in human-readable format (K for kilobytes, M for megabytes, etc.).
* -R: This option makes 'll' list directories recursively, showing their content and the content of their subdirectories.
* Syntax: ll [file_name]
  
* **Grep Command**: The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern.
  - Syntax: grep "pattern" [file_name] 
  
* **Cat > file_name**: to create a file and write content in it. (use "Control+C" to exit from the file)
  
* **Head Command**: Head command prints the first lines of one or more files (or piped data) to standard output.
  - Syntax: head [file_name]
* **Tail Command**: Tail command is used to display the last ten lines of one or more files. Its main purpose is to read the error message. By default, it displays the last ten lines of a file. Additionally, it is used to monitor the file changes in real-time.
  - Syntax: tail [file_name]

* **Less**: 
* **More**: The More command in Linux is a command-line utility that allows users to view text files one page at a time. The more command is often used when dealing with large files that cannot be viewed in their entirety on a single screen.
  - Syntax: more [file_name]

* **Echo**:

5. Copy and Move Command (RM, CP, MV, SCP, RSYNC)
  - **RM Command**: rm stands for remove here. rm command is used to remove objects such as files, directories, symbolic links and so on from the file system like UNIX.
  - Syntax: rm [OPTION]... FILE...
  - **CP Command**: cp stands for a copy. This command is used to copy files or groups of files or directories. It creates an exact image of a file on a disk with a different file name.
  - Syntax: cp [Source_file] [Destination_file]
  - **MV Command**: The mv command moves files and directories from one directory to another or renames a file or directory. If you move a file or directory to a new directory, it retains the base file name. When you move a file, all links to other files remain intact, except when you move it to a different file system. When you move a directory into an existing directory, the directory and its contents are added under the existing directory.
  - Syntax: mv [options(s)] [source_file_name(s)] [Destination_file_name]
6. User/Group and Access (USERADD, USERDEL, USERMOD, GROUPADD, GROUPDEL, SU, SUDO, SSH,)


## Project:Open-Source Community forum
* In this project I'm building a Community forum using "Zulip" tool as a platform, where all people of Keenable can communicate together.

### Deployment Architecture
![Screenshot from 2023-12-27 15-06-53](https://github.com/Akshaykumar05/Keen-Able-Internship/assets/114390890/8a78b41d-b19c-4bab-b62e-c1cfe5e39ab0)

* [Detailed Documentation about this project](https://github.com/Akshaykumar05/Keenable-Community-Forum)

## My learnings:
### 1. Proxy issue
  * My system was unable to connect the the wifi other than office ( where the proxy was apllied to the internet on Firewall browser.

  * The terminal commands
    
    ![image](https://github.com/Akshaykumar05/Keen-Able-Internship/assets/114390890/cc0e2830-31cf-4917-b733-0b12a5727132)
### 2. Installation
   * There are diffrenet types installation such Normal imstallation and installation through Docker.
   * I instaaled Zulip with normal installtion and also with Docker by making containers.


#### [Postmaster Tools](https://support.google.com/a/answer/9981691?sjid=10149656671777075305-AP&visit_id=638436024132136020-3878062968&rd=2) 

### 3. Open-Source Software
* Open source software (OSS) is software that is distributed with its source code, making it available for use, modification, and distribution with its original rights.

### 4. Web Server
### 5. Databases
### 6. SMTP Service
### 7. Docker
### 8. Making accessable a localhost project to others with same IP address.

### 9. Selenium
![image](https://github.com/Akshaykumar05/Keen-Able-Internship/assets/114390890/32ab218c-fc0c-4aca-82fd-6f495aad3768)

* It is an Open-Source framework for automating and testing web browsers.

  #### Why tesyting is important.
  * Software testing is now a key component of software development because it improves consistency and performance. Though the main benefit of testing involves finding errors and defects, it also helps the team in understanding actual and expected outcomes so that they can improve the quality of their products.
  #### Uses:
  * Testing web applications
  * Performing automation tasks
  * Scraping data from websites
  #### Support multiple programming languages:
  * Java
  * Python
  * C#
  * Ruby
  #### Selenium consists of different components:
  * Se web driver == Automation browser interactions
  * Se Grid == Parallel testing on multiple machines or browsers
  * Se IDE == Intregated Development environmenet for creating and running Selenium test cases.
  #### Key advantages of Selenium
  * Simulate real-world user interactions with web application, this helps to identitify potential issues andbugs before the becomes a problem for the end user.
  * Selenium supports multiple web browsers making it easier to test web applications on different platforms, this helps to ensure compatibility and reduce the risk of issues arises from differences between browser.
    ### Other tool for testing
    * [Playwright](https://playwright.dev/)
### 10. Logical Replication
* Logical replication is a method of replicating data objects and their changes, based upon their replication identity.
* We use the term logical in contrast to physical replication, which uses exact block addresses and byte-by-byte replication.

### PgBackRest
* PgBackRest is a reliable backup and restore solution for PostgreSQL that seamlessly scales up to the largest databases and workloads.
### PgAdmin
