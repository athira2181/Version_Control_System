# Terminologies

---

## Metadata

  Metadata in simple words means data about data. Let's understand metadata here in context of VCS. 
  
  The files themselves (which includes contents of your code, documents etc) are considered the primary data. Metadata, in this context, involves data about these files. It provides information about the files, their history, and the changes made to them, helping you manage, track, and understand the data (files) more effectively. So, you can think of metadata as data that provides context and details about the primary data (the files).

  Here are some common examples of metadata in the context of VCS:

  * **Commit Metadata**: This includes information about each commit, such as the author's name and email address, the date and time of the commit, and a commit message describing the changes made in that commit.
  * **File Metadata**: For each file, metadata might include details like the last modified date and time, the file size, and the file type (e.g., source code, text, binary).
  * **Version Metadata**: Information about each version of a file, such as a version or revision number, can also be considered metadata. This helps identify and reference specific versions of a file.
  * **Branch Metadata**: In the context of branching and merging, metadata might include information about the branch's name, the branch point, and which branches have been merged together.

  Metadata is essential for tracking changes, understanding the history of a project, and facilitating collaboration. It provides context and details that help users navigate and work with versioned files and projects in a version control system.

---

## Rollback

A rollback is a term commonly used in the context of version control systems and software development. It refers to the action of reverting to a previous version or state of a file, project, or software system. When you perform a rollback, you essentially go back in time to an earlier point in the project's history, discarding the changes made after that point.

Rollbacks are often used for several purposes:

* **Undoing Mistakes**: If you or your team make a mistake or introduce a bug in the code, a rollback allows you to return to a version of the code where the mistake or bug doesn't exist.

* **Reverting to a Stable State**: When a project is in an unstable or problematic state, you can perform a rollback to return to a known stable state.

* **Comparing Versions:** Rollbacks enable you to compare the current version with a previous version, helping you identify what changed and when.

* **Dealing with Conflicts:** In collaborative development, when multiple team members make conflicting changes, a rollback can help resolve conflicts by starting from a common previous version.

* **Recovery:** In the event of data loss or corruption, a rollback can help recover an earlier, uncorrupted version of the project.

Rollbacks are a crucial feature in version control systems like Git. They allow developers to manage and maintain control over the history of their projects, ensuring that they can always return to a known state in case of issues or changes that need to be undone.
