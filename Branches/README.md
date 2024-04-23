# Branches 

> Branches in Git serve critical purposes in managing code changes within a project. Here’s why they are essential:
>> ***Why I Need Branches in Git:***   
Branches in Git allow you to diverge from the main line of development and continue to work independently without affecting the main codebase. This enables multiple functionalities:  
**Isolation:** Each branch creates an isolated environment, allowing changes to be made without impacting the stability of the main codebase (often the main or master branch). This is crucial when developing new features, fixing bugs, or experimenting.  
**Parallel Development:** Developers can work on different features or bugs simultaneously on separate branches. This parallel development helps speed up the software development process and reduces the risk of conflicting changes.  
**Controlled Integration:** Branches make it easier to control when and how changes are integrated back into the main branch. This is typically done through a process called merging or pull requests, which can include code reviews and automated testing to ensure quality.  
>>>***Why Developers Need a Feature Branch for a Project:***  
A feature branch is a type of branch specifically used for developing new features in a project. The advantages of using feature branches include:  
**Focused Work:** Each feature branch is dedicated to a specific task, making it easier for developers to focus on that task without distractions from other changes in the project. This focused approach can lead to higher quality and more coherent feature development.  
**Reduced Risk:** Since the development is isolated, it minimizes the risk of introducing errors into the main codebase. The main branch usually represents the stable version of the product and is protected from the instability of ongoing development in feature branches.  
**Enhanced Review Process:** Using feature branches facilitates a thorough review process before merging. This review often involves checking for code quality, adherence to project standards, and ensuring compatibility with the existing codebase. The separation into branches simplifies understanding the impact of specific changes.  
**Incremental Development:** Feature branches allow for incremental updates and changes to be made and tested independently. This means that a feature can evolve in its branch, undergoing multiple rounds of review and revision without affecting the main codebase.  
Overall, branches, particularly feature branches, are foundational to modern collaborative software development, enabling teams to manage multiple aspects of a project efficiently and effectively.  

*List all local branches. Add -r flag to show all remote branches. -a flag for all branches.* 
```bash
$ git branch
```
*Create a new branch*
```bash
$ git branch <new-branch>
```
*Switch to a branch & update the working directory*
```bash
$ git checkout <branch>
```
*Create a new branch and switch to it*
```bash
$ git checkout -b <new-branch>
```
*Delete a marged branch*
```bash
git branch -d <branch>
```
*Delete a branch, wheather marged or not*
```bash
$ git branch -D <branch>
```
*Add a tag to current commit (often used for new version releases)*
```bash
$ git tag <tag-name>
```