# Evolution of Version Control System 

---

Recognizing the need for effective version control is a crucial starting point. However, the existence of a problem statement alone does not bring a Version Control System into play. To truly appreciate the value of such systems, it's vital to examine the landscape of version control before and after their introduction and understand the evolution that led to their current state.

Let's look at how VCS evolved:

* ### Local VCS
  
   In the early days of computing, programmers developed basic local version control systems. These systems allowed users to keep track of different versions of their files on their local machines.
  In other words they are designed to manage the history and changes of files on an individual user's local machine or computer.<br><br>

   Local version control systems help users keep track of changes to their files, revert to previous versions, and maintain a history of their work, all without the need for a central server.<br><br>

  Let's consider an example: Imagine you are working on a project called "my_project." In manual tracking, you would need to create multiple copies to keep track of different versions, such as "my_project_v1," "my_project_v2," and so on.<br><br>
  However, this approach leads to duplicate files in all your project versions, resulting in wasted memory space. It also becomes challenging to track changes, knowing where and when changes were made in each version.<br><br>
  Local Version Control addresses these issues by storing different versions of your files within a single directory, which is more space-efficient compared to maintaining complete duplicate project folders for each version. Unchanged files are stored as a single original copy. When a file is modified, and a new version is created, only the changes are stored, along with the complete content of that version. This approach minimizes redundancy and optimizes storage.<br><br>

   Two examples of Local VCS tools are: <br><br>

   *  Source Code Version Control System:
   *  Revision Control System

* ### Centralized VCS

  Centralized VCS, like Concurrent Versions System (CVS) and Subversion (SVN), became popular in the 1980s and 1990s. These systems stored all project files and their version history on a central server. Multiple users could check out and update files from this central repository. While they improved collaboration, they had some drawbacks, such as a single point of failure and network dependencies

* ### Distributed VCS

  The 2000s saw the rise of distributed version control systems, with Git being the most prominent example. These systems addressed the limitations of centralized VCS. In distributed VCS, each user has a complete copy of the project's history on their local machine. This decentralization provides greater flexibility, enables offline work, and eliminates the need for a central server.
  <br><br>
  Today, Git is one of the most popular VCSs, used by software developers, writers, and many others. It has a user-friendly interface and is widely adopted because it simplifies the process of tracking changes and collaborating on digital projects.Other distributed VCSs like Mercurial also gained popularity. These systems made it easier for large and distributed teams to collaborate on complex software projects.
  <br><br>
  Alongside the rise of Git, online hosted version control services like GitHub, GitLab, and Bitbucket gained prominence. These platforms provided a centralized place to store and collaborate on Git repositories, making it easier for developers to share and contribute to open-source projects.

   
[Documentation Index](Index.md)
