[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15612094&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.
Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.
GitHub is a web-based hosting service for Git repositories. It allows developers to store code, track changes, and collaborate with other developers. GitHub is popular because it has a user-friendly interface, integrates with many popular tools, and has a large community of developers.
version control systems act as a safety net for data integrity by providing a comprehensive history of changes made to files, documents, or code over time. This means that if errors occur or unintended changes are made, previous versions can be easily accessed and restored.



## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
The process of create a repository is as follows;
1. In the upper-right corner of any page, select , then click New repository
2. Type a short, memorable name for your repository
3. Optionally, add a description of your repository
4. Choose a repository visibilit
5. Select Initialize this repository with a README.
6. Click Create repository.
Pre-filling form fields with a URL query may be useful if you often want to create repositories with the same default settings. For example, a teacher may want each student in a class to create a repository in their personal account with the same name, description and visibility. Using a URL query, the teacher can create a link that pre-fills the repository name, description and visibility fields and share it with the whole class.
You must have the proper permissions for any action to use the equivalent query parameter. For example, you must have permission to create a repository in an organization to specify the organization as the repository owner in a query parameter. For more information, see "Repository roles for an organization."
If you create an invalid URL using query parameters, or if you don’t have the proper permissions, the invalid query parameters will be ignored and the rest of the URL will function as normal. If you create a URL that exceeds the server limit, the URL will return a 414 URI Too Long error page.
Factors to consider when choosing a repository
 What functionality do you need now?
    - Version-control system, including web interface for online code-browsing
    - Mailing lists, list management and archives
    - Bug/issue tracker
    - Basic web server for project/software pages
    - News
    - Software package hosting/publishing
    - Statistics reporting (e.g. number of commits, number of downloads)
    - Forums
    - Wikis
    - Project/release management
    - Access Control (e.g. setting up project level roles)
    How easy is it to upgrade to additional functionality in the future?
    What is your preferred version-control system, e.g. CVS, SVN, Git, Mercurial?
    Is it important to have your code publicly available?
    Are all your code committers local?
    How easy is it to integrate other things you run separately (e.g. a website) with the repository?
    How good is the support for your IDEs of choice?
    Is there support for authentication systems such as OpenID or SSH keys?
    What additional forge, social networking, project-management functionality do you want from the site? e.g. GitHub is good      for social coolness
    Where are similar projects to yours hosted?
    What's the speed of upload/download?
    How easy is it to backup the entire repository (code, mailing lists, issue tickets, ...)
    How established and stable is the repository?
    How good is the user support?
    How much effort do you have to put into repository maintenance?
    Would it be better to use more than one repository, e.g. code stored in GitHub and a link to Assembla for its extra tools?
    What are the Service Level Agreements for uptime, downtime, time to fix outages and bandwidth?
    If you are trying to migrate your project from one repository to another, you might also want to consider two extra            factors:
    How easy will it be to transfer not just your code, but your community, to the new site, e.g. do you have mailing list         archives, wikis, user accounts
    Do you need to keep the revision history associated with your code, or can you start afresh?



## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
The Readme file is often the first file that the users read. It is a text file that contains information for the user about the software, project, code, or game, or it might contain instructions, help, or details about the patches or updates.
When you create a repository or a project, GitHub gives you the option of a default readme. The default readme file contains the repository name and some basic instructions. The file format is ‘md’, which stands for Markdown documentation. It is a lightweight markup language that can be easily converted to text.
A README file is a text file that describes and launches a project. It comprises information that is frequently needed to grasp the scope of the project. In this blog, we will talk about what a README file is, why is it necessary and how you can write a good README file.
What to Include in your README
1. Project's Title :This is the name of the project. It describes the whole project in one sentence, and helps people understand what the main goal and aim of the project is.
2. Project Description :This is an important component of your project that many new developers often overlook.Your description is an extremely important aspect of your project. A well-crafted description allows you to show off your work to other developers as well as potential employers.
3 Table of Contents (Optional) :If your README is very long, you might want to add a table of contents to make it easy for users to navigate to different sections easily. It will make it easier for readers to move around the project with ease.
4. How to Install and Run the Project :If you are working on a project that a user needs to install or run locally in a machine like a "POS", you should include the steps required to install your project and also the required dependencies if any.
Provide a step-by-step description of how to get the development environment set and running.
5. How to Use the Project :Provide instructions and examples so users/contributors can use the project. This will make it easy for them in case they encounter a problem – they will always have a place to reference what is expected.You can also make use of visual aids by including materials like screenshots to show examples of the running project and also the structure and design principles used in your project. Also if your project will require authentication like passwords or usernames, this is a good section to include the credentials.
6. Include Credits :If you worked on the project as a team or an organization, list your collaborators/team members. You should also include links to their GitHub profiles and social media too. Also, if you followed tutorials or referenced a certain material that might help the user to build that particular project, include links to those here as well. This is just a way to show your appreciation and also to help others get a first hand copy of the project.
7. Add a License :For most README files, this is usually considered the last part. It lets other developers know what they can and cannot do with your project. We have different types of licenses depending on the kind of project you are working on. Depending on the one you will choose it will determine the contributions your project gets. The most common one is the GPL License which allows other to make modification to your code and use it for commercial purposes. If you need help choosing a license, use check out this link: https://choosealicense.com/
8. Badges :Badges aren't necessary, but using them is a simple way of letting other developers know that you know what you're doing.
READMEs Improve Collaboration
Software development does not occur in a vacuum—it’s almost always a team of developers working towards a goal. As your developers collaborate and use each others’ work to build more complex workflows, README files allow everyone to stay on the same page.


## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

Public repositories are a great choice for getting started! They're visible to any user on your GitHub Enterprise instance, so you can benefit from a collaborative community.
Private repositories require a little more setup. They're only available to you, the repository owner, as well as any collaborators you choose to share with.
Public repositories are accessible to everyone on the internet.
Private repositories are only accessible to you, people you explicitly share access with, and, for organization repositories, certain organization members.
The primary benefits of using private repositories on GitHub for your project code are:
1 Confidentiality: Private repositories allow you to keep your code and related materials confidential and secure, preventing unauthorized access or exposure of sensitive information.
2 Intellectual Property Protection: Maintaining your code in a private repository helps safeguard your intellectual property and prevents others from easily accessing or copying your work without permission.
3 Collaboration Control: With private repositories, you can precisely control who has access to view, edit, and contribute to your project, allowing for more effective and secure collaboration within your team.
3 Reduced Risk of Inadvertent Exposure: Public repositories carry the risk of accidentally publishing sensitive data or code that was not intended for public view. Private repositories mitigate this risk.
4 Compliance and Regulatory Requirements: Certain industries or projects may have specific compliance or regulatory requirements that necessitate the use of private repositories to ensure the proper handling of data and code.
5 Competitive Advantage: Keeping your project code private can help maintain a competitive edge by preventing competitors from easily accessing and potentially reusing your work.
Overall, private repositories on GitHub offer enhanced security, control, and confidentiality for your project's code and related assets, making them a preferred choice for many organizations and individuals working on sensitive or proprietary projects
Some of the benefits of using a public/remote repository like GitHub are:
1 It’s a lot easier when you want to work with other developers, everyone can easily pull and push changes from the remote repository instead of having to share files all the time
2 When using a local repository there’s risk of losing files. Imagine something happens to your hard disk, all your code is gone. You’ll have to start building your project afresh not a very good experience 
3 Public repositories promote open source development. You can collaborate with the public to build tools or whatever it is you want to build.
Public repositories are a great way to show off your skills and shares you ideas with other people. But for websites that you’re developing for clients you shouldn’t use public repositories since they are paying you for this work and you might not have the rights to share that code without their permission. Developing with other people can be a lot easier with public repositories and sharing ideas.
I only really use my github for sharing ideas with people, but not because every project I’ve ever written is on github, I have a private git repository on a server for those private projects that I don’t want or cannot share with others



## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
1 Create a sample : projectTo start, create a sample project in GitLab. In GitLab, on the left sidebar, at the top, select  Create new and New project/repository.For Project name, enter My sample project. The project slug is generated for you. This slug is the URL you can use to access the project after it’s created.Ensure Initialize repository with a README is selected. How you complete the other fields is up to you. Select Create project. 
2 Clone the repository :Now you can clone the repository in your project. Cloning a repository means you’re creating a copy on your computer, or wherever you want to store and work with the files.
On your project’s overview page, in the upper-right corner, select Code, then copy the URL for Clone with SSH.
Open a terminal on your computer and go to the directory where you want to clone the files.
Enter git clone and paste the URL:
git clone git@gitlab.com:gitlab-example/my-sample-project.git
Go to the directory:
cd my-sample-project
By default, you’ve cloned the default branch for the repository. Usually this branch is main. To be sure, get the name of the default branch:
git branch
The branch you’re on is marked with an asterisk. Press Q on your keyboard to return to the main terminal window.
3 Create a branch and make changes
Now that you have a copy of the repository, create your own branch so you can work on your changes independently.
Create a new branch called example-tutorial-branch.
git checkout -b example-tutorial-branch
In a text editor like Visual Studio Code, Sublime, vi, or any other editor, open the README.md file and add this text:
Hello world! I'm using Git!
Save the file.
Git keeps track of changed files. To confirm which files have changed, get the status.
git status
You should get output similar to the following:
On branch example-student-branch
Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   README.md
no changes added to commit (use "git add" and/or "git commit -a")
4 Commit and push your changes
You’ve made changes to a file in your repository. Now it’s time to record those changes by making your first commit. Add the README.md file to the staging area. The staging area is where you put files before you commit them.
git add README.md
Confirm the file is staged:
git status
You should get output similar to the following, and the filename should be in green text.
On branch example-tutorial-branch
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
modified:   README.md
Now commit the staged file, and include a message that describes the change you made. Make sure you surround the message in double quotes (“).
git commit -m "I added text to the README file"
The change has been committed to your branch, but your branch and its commits are still only available on your computer. No one else has access to
them yet. Push your branch to GitLab:
git push origin example-student-branch
5 Merge your changes
Now you’re ready to merge the changes from your example-tutorial-branch branch to the default branch (main).
Check out the default branch for your repository.
git checkout main 
Merge your branch into the default branch.
git merge example-student-branch
Push the changes.
git push
For this student, you merge your branch directly to the default branch for your repository. In GitLab, you typically use a merge request to merge your branch.
6 View your changes in GitLab
You did it! You updated the README.md file in your branch, and you merged those changes into the main branch.
Let’s look in the UI and confirm your changes. Go to your project.
Scroll down and view the contents of the README.md file. Your changes should be visible.
Above the README.md file, view the text in the Last commit column. Your commit message is displayed in this column:
Commit message 
Each commit represents a specific, saved state of the project and includes a unique identifier, allowing developers to keep track of different versions of a project. This means if a mistake is made, one can easily revert to a previous commit. Commit is used to facilitate collaboration and tracking changes in a project.

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made.
Aside from isolating feature development, branches make it possible to discuss changes via pull requests. Once someone completes a feature, they don't immediately merge it into main . Instead, they push the feature branch to the central server and file a pull request asking to merge their additions into main .
Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.
You always create a branch from an existing branch. Typically, you might create a new branch from the default branch of your repository. You can then work on this new branch in isolation from changes that other people are making to the repository. A branch you create to build a feature is commonly referred to as a feature branch or topic branch. For more information, see "Creating and deleting branches within your repository."
You can also use a branch to publish a GitHub Pages site. For more information, see "About GitHub Pages."
You must have write access to a repository to create a branch, open a pull request, or delete and restore branches in a pull request. For more information, see "Access permissions on GitHub."
Three popular Git branching strategies:
Trunk-Based Development
Feature Branching
Git Flow
Strategy 1: Trunk-Based Development
What is Trunk-Based Development?
Trunk-based development (TBD) is a branching strategy in which all developers make changes directly on the main branch, commonly referred to as the trunk, which holds the project’s deployable code. Developers are encouraged to commit frequently and use feature toggles* and other techniques to manage changes that are not yet ready for release. Testing is typically automated, with a focus on continuous integration (CI) and continuous delivery (CD) to ensure that code changes are thoroughly tested before they are deployed.
Strategy 2: Feature Branching
What is Feature Branching?
Feature Branching is a commonly used workflow that involves creating a new branch for a specific feature or change in the codebase. This allows developers to work on the feature independently without affecting the main branch. When the feature is complete, it can be merged back into the main branch through a pull request. The pull request allows other team members to review the changes and suggest modifications or improvements before merging the feature into the main branch.
Feature Branching Workflow
Create feature branches: Create a new branch for each feature or task you’re working on. This branch should be created from the main branch.
Work on the feature: After creating the feature branch, you can start implementing the new feature by making as many commits as necessary. The branch should only contain changes relating to that particular feature. Create a pull request: When you’re finished working on the feature branch, you create a pull request to merge the changes into the main branch.
Review and approve: Other developers review the changes in the pull request and approve them if they are satisfied with the changes. Code review can help catch issues or mistakes before they are merged into the main branch.
Merge the feature branch: Once you’re done working on the feature, you can merge the feature branch back into the main branch.
Clean up: After merging, you can delete the feature branch, as it is no longer needed.
Teams and Projects
Feature Branching is commonly used in collaborative software development environments where multiple developers are working on different features or tasks concurrently.
Strategy 3: Git Flow
What is Git Flow?
Git Flow is a branching strategy that uses two main long-lived branches - main and develop - that remain in the project during its entire lifetime. Additionally, it employs several short-lived branches - feature, release, and hotfix - that are created as needed to manage the development process and deleted once they have fulfilled their purpose. The main branch is the stable production-ready code and the develop branch is where all development takes place. Feature branches are used to develop new features or changes, release branches are used to prepare for a new release, and hotfix branches are used to quickly address critical issues in the production code.

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
Pull requests communicate changes to a branch in a repository. Once a pull request is opened, you can review changes with collaborators and add follow-up commits.A pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase. Pull requests display the differences, or diffs, between the content in the source branch and the content in the target branch.
Pull requests enable efficient code review, facilitate knowledge sharing, and improve code quality. By requiring team members to review and approve changes, potential issues, bugs, or suboptimal design decisions can be identified and addressed before the changes are integrated into the main codebase.
Pull requests follow a basic five step process
1 Fork Main Repository and Create a Local Clone. ...
2 Make Needed Changes Locally. ...
3 Push Local Changes to Forked Repository. ...
4 Make a Pull Request. ...
5 Any edits are then sent back to the developer for additional commits (changes to code) that may be needed.

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
A fork is a new repository that shares code and visibility settings with the original “upstream” repository. Forks are often used to iterate on ideas or changes before they are proposed back to the upstream repository, such as in open source projects or when a user does not have write access to the upstream repository.
Forking creates your own copy of a repository in a remote location (for example, GitHub). Your own copy means that you will be able to contribute changes to your copy of the repository without affecting the original repository. Cloning makes a local copy of a repository, not your own copy.
Forking creates your own copy of a repository in a remote location (for example, GitHub). Your own copy means that you will be able to contribute changes to your copy of the repository without affecting the original repository.
Cloning makes a local copy of a repository, not your own copy. Think of it as downloading a repository onto your local hard drive. Unlike forks, clones have references to their original repositories.
When a process uses fork, it creates a duplicate copy of itself and this duplicates becomes the child of the process. The fork is implemented using clone system call in linux which returns twice from kernel.
A non-zero value(Process ID of child) is returned to the parent. A value of zero is returned to the child.
In case the child is not created successfully due to any issues like low memory, -1 is returned to the fork.

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
GitHub Issues are items you can create in a repository to plan, discuss and track work.Issues let you track your work on GitHub. When you mention an issue in another issue or pull request, the issue's timeline reflects the cross-reference so that you can keep track of related work. To indicate that work is in progress, you can link an issue to a pull request. When the pull request merges, the linked issue automatically closes.
Issues are simple to create and flexible to suit a variety of scenarios. You can use issues to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.
How issue tracking software works
Streamline the process from issue identification to resolution with these steps:
Create tickets: Report issues by creating tickets and documenting problems with details about  occurrence, steps to reproduce, and expected versus actual behavior.
Assign issues: Assign tickets to team members responsible for addressing the problem to maintain accountability.
Track issues: Monitor the progress of each issue as it moves through stages such as open, in progress, resolved, or closed.
Iterate: Use reporting tools to gain insights into issue volume, types, handling times, and resolution rates to help improve processes.
Benefits of using an issue tracker
Using an issue tracking tool offers several benefits that streamline project management and enhance team performance:
Improved team collaboration: Foster a collaborative environment by centralizing communication and providing a platform for team members to work together on resolving issues.
Task organization: Organize tasks effectively, allowing for easy categorization, prioritization, and tracking of issues.
Visibility into project progress: Get real-time insights into the status of various issues, giving teams a clear view of project progress and helping to ensure that critical issues are addtime insights into the status of various issues, giving teams a clear view of project progress and helping to ensure that critical issues are addressed promptly.
Efficient issue resolution: Help teams resolve issues more efficiently, reducing downtime and improving overall productivity by systematically managing the issue resolution process. 


## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
Here are some best practices for Git that you can adopt:
1. Make small incremental changes
One of the most significant best practices version control Git is making small, gradual changes. First, write the smallest piece code needed to solve a particular issue.
After pinpointing the enhancement or problem, the wisest way to try something untested and new is to divide it into small batches of value that can rapidly and easily be tested to prove whether the proposed solution is valid. If it is not, changes could be reverted without affecting or deprecating the whole new functionality.
2. Keeping commits atomic
This Git standard practice is closely related to making tiny changes. Atomic commits are single units of work that involve only a single task or fix, for example, a refractor, bug fix, or upgrade.
Atomic habits facilitate faster code reviews and easier revert because they can be reverted or applied without unintended side effects. The primary objective of atomic commits is to group commits using context rather than creating hundreds of commits.
For instance, if a programmer wants to refactor code and incorporate a new feature, they would need to create two separate commits instead of a single monolithic commit that will include changes that serve different purposes.
3. Developing using branches
Branches are an excellent way for software development teams to make changes without interfering with the main code line. It is possible to track the history of changes in a branch, and after the code is ready, it could be merged into the main branch.
Branching organizes development and distinguishes between work in progress and stable and tested code in the main branch.
4. Identifying a branching strategy
Software development teams are typically made up of professionals with diverse experiences and from various backgrounds, which could potentially result in conflicting workflows. Creating and implementing a single branching strategy is one of the best practices in Git for handling the chaotic development experience.
There are a number of approaches to development that you could choose depending on your preference, but the most common ones include the following: Feature branching: Your team could use a new branch for every new feature without committing directly to the main branch. Personalized branching: This is similar to feature branching, except instead of developing on different branches per feature, it’s per developer. Every user then merges to the main branch once their work is complete.
Centralized workflow: Your team could use only one repository and directly commit to the main branch.
 GitFlow: This is an extreme version of feature branching where development takes place on the develop branch, then moves to a release branch, before finally merging into the main branch.
Some teams follow an established workflow policy, while others prefer to create a customized approach that aligns with their specific needs. Regardless of your chosen strategy, it is crucial to communicate the workflow logistics and decisions to team members and provide them with training for a seamless transition.
5. Writing descriptive commit messages
A descriptive commit message can be just as important as an actual change. To write a descriptive commit message, start with a verb in the present tense in an imperative mood to show each commit’s function clearly and concisely.
6. Obtaining feedback through code reviews
Getting feedback from other developers and team members is an ideal way to ensure code quality. Code reviews are an excellent methodology for identifying whether a recommendation will solve a problem effectively.You can also ask individuals from other teams to review the code because some of its areas could include specific domain knowledge or have security implications beyond the attributions of the individual contributor.
Common Git Mistakes and How to Fix Them
1. Accidentally deleting a file in Git is quite a common mistake. When working on feature upgrades, for example, developers often think that some files aren’t needed, and in this anticipation, they delete a file before its needs expire. If you’ve accidentally deleted a file in Git, you might think that you’ve made an irreparable mistake. But don’t worry; Git is quite generous with files. It always keeps track of the files that were added or deleted in the repository. This means you can get your file back with just one Git command. Or, you can use the magical Undo button available in GitKraken Client..For a better understanding, let’s say, for example, that you’ve deleted the 404.html file from your Git repository. To get the file back, you can type the below command into your terminal of choice. 
git checkout HEAD 404.html
2. Pushing Unfinished Code.As a developer, you often end up working on important features that need extremely fast delivery, or production bugs that are haunting users and need to be solved quickly. In such cases of high pressure, you may forget to switch your working Git branches and end up working and committing files to the main branch. Pushing unfinished code to the remote main branch can cause havoc with the CI/CD and deployment sections of your team’s workflow. 
If you’ve recently pushed your code to a remote main branch, you can revert the changes if you have the previous version of the remote branch synced with your local branch. You can get the older version of the remote branch by using the below command. 
git reset - -hard <remote_branch>/<branch>@{1}
The Git reset command used in this context will reset and update your remote branch with your local history’s last working version of the main branch. If you want to protect this branch from such direct commits, you can also use the below setting in your remote Git repository and sync it with local. 
git config --system receive.denyNonFastForwards true
3. Poor Git Commit Messages. Writing good commit messages is essential to having a better codebase that everyone can understand. Commit messages should be self-explanatory to anyone who looks at the code. Messages like “fixed,” “edited,” etc., without any additional context don’t serve any purpose. Many developers make the mistake of adding poor commit messages while working rapidly, and in the end, they wish they would have written a better commit message, not just for their team members, but also for themselves. The good news is that Git allows you to edit commit messages whenever you want. To edit a commit message, use the following Git commit amend command: 
git commit --amend
After typing the above command into your terminal, press enter. This will open a text editor where you can easily edit the last commit message.
4. Accidentally Deleting an Entire Git Branch. Working on a branch for a long time and, in the end, accidentally deleting it without merging it can sound like the biggest horror for developers. But it is not as big of a deal as people think. You can recover that branch with just a few commands from the terminal. To perfectly recover the branch, you first need to find the commit from where you switched to that deleted branch. To do that, you can use the Git reflog command
to get all the journal entries of commits and details. Once you’ve found the commit, you can use the below command to get your deleted branch back so you can merge and push it to remote branches. 
git checkout -b <branch-name> <commit-id>
In the above command, branch-name is the branch name that you have deleted, and commit-id is the commit that you’ve determined from your Git reflog results.
5. Bad Git Commits.Making a commit with errors is a common Git mistake, but it can also be pretty devastating. Your commit could introduce problems into your codebase, for example, or conflict with another change. 
These mistakes can cause unmeasurable damage to production builds if the errors make it past the deployment stages. But if you identify the mistake early, you can take steps to remedy it.
Fix bad commits by reverting to old commits using the following Git revert commit command:
git revert <commit-id>
In the above command, the commit-id is the commit id for the old commit which has the better and more stable version of code. 
6. Too Many Git Commits.Git is used to keeping track of changes in the codebase incrementally, but sometimes people end up making too many commits. This typically happens when you’re experimenting with something new, and as things start to work, you commit incrementally throughout the process.
In the end, when the experiment is successful, and you’re ready to commit to the main branch, you may be left with numerous commits with not-so-explanatory commit messages. These commits will make it hard for other developers to understand your code.
In such cases, you can resort to squashing commits from your terminal and then pushing your changes to the remote. Below is the process to Git squash multiple commits down to one. 
First, Git checkout to the branch you want to merge using the following command: 
git checkout <branch-name> 
Next, use the following command: 
git merge - -squash <branch-name-to-be-merged>
Once you’ve performed the above two commands, you’ll have some merge conflicts that need to be solved. 
7. Forgot To Add the Files. Forgetting to add a file is another common Git mistake that can cause trouble. Sometimes you may have different directories, and if you forget to add an essential file to your commit, you can end up with a bad codebase. 
To fix this mistake quickly, you can use the following Git add command: 
git add <missed-file>
After you perform the above command, use: 
git commit - -amend This will add the file to the last commit. 






