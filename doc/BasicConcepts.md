# Basic Concepts of VCS

---

## Repository

A repository, in simple terms, is like a special folder or storage place where you keep all the different versions of your files and their history. It's a central location where you store your project's history and changes over time. Here's an example to help illustrate the concept:

Imagine you're working on final year project, and you want to keep track of all the changes you make to it. You create a folder on your computer called "final_year_project" and inside it, you save the different versions of your story:

* **"final_year_project_v1"** for the first draft.
* **"final_year_project_v2"** for the second draft.
* **"final_year_project_v3"** for the final version.

Each time you make changes, you save a new version of your project in the same folder. However, this approach has a few drawbacks:

* It takes up a lot of space because you're saving complete copies of your story, even if only a few words changed.

* It's hard to keep track of what changed between versions, as you have to compare files manually.

This is where a version control repository comes in. Instead of creating separate folders for each version, you use a version control system. In this system, you have a single "final_year_project" folder, and you keep making changes to the same file. The system records the history of your story and tracks every change you make, so you can easily:

* See what you changed between versions.
* [Roll back](TerminologyGuide.md/#rollback) to a previous version if needed.
* Collaborate with others on the same story.

The repository is like a smart organizer that keeps all your versions and their changes in one place, making it easier to work on your project and manage its history.

---

## Commit (Check-In)

Committing is the act of saving a new version of files into the VCS repository. It captures the state of the project at a specific point in time and includes [metadata](TerminologyGuide.md/#metadata) like who made the changes and when.

You can think of a commit in a version control system as a bookmark or a reference point that you can use to come back to a specific state of your project at any time. It's like marking a point in your project's history that you can revisit whenever needed.

Just as you might use a bookmark in a book to return to a particular page or location, a commit allows you to return to a specific version or snapshot of your project. Commits in version control systems like Git serve as a way to navigate your project's history and access past states or changes easily, making it a valuable tool for managing and tracking your work.

Commits are essential for tracking the evolution of your project and collaborating with others. They ensure that you can always return to an earlier version if something goes wrong or compare different versions of your work.

---

## Checkout

In Version Control Systems (VCS), "checkout" is an action that allows you to switch to a specific version of your project or file. It's like picking a particular edition of a book to read, and that edition represents a particular point in time for your project.

--- 

## Branch

In simple words, think of a branch in a Version Control System (VCS) like a separate, isolated workspace for your project. It's like having a copy of your project where you can work on new ideas or features without affecting the main project.

* In a VCS, the commit history typically forms a linear chain or a tree-like structure.
* Let's assume you have a linear commit history like this:
````
  A - B - C - D
````

* When you create a new branch, you're essentially creating a new reference to a specific commit. It doesn't create a new commit on its own. Let's say you create two branches, "Branch1" and "Branch2," from commit C:

````
A - B - C - D (Branch1)
         \
          E (Branch2)
````

* Both "Branch1" and "Branch2" share the same history up to commit C. This means the changes made up to commit C are common between the two branches.
* From commit C, changes made in "Branch1" are independent of changes in "Branch2." If you make a new commit in "Branch1," it doesn't affect "Branch2," and vice versa.


---

## Merge










