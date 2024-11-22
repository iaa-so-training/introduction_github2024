# Repository management and collaborative science platforms:  GitHub

**Table of contents**

[0. Pre-requisites. Create a Github account](#createaccount)  
[1. Creating a new repository and configure the main options](#createrepo)  
[2. Adding content to our repository](#Addingcontenttoourrepository)  
[3. Working with the version history](#Workingwiththeversionhistory)  
[4. Collaborating with other users and repositories](#Collaboratingwithotherusersandrepositories)  
[5. Adding different branches to your repository](#Addingdifferentbranchestoyourrepository)  
[6. Forking a repository and creating a Pull Request](#ForkingarepositoryandcreatingaPullRequest)  


# 0. <a name='createaccount'></a>Pre-requisites. Create a Github account

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

:warning: *To complete this session, [you need a GitHub account](http://github.com/) and Internet access. You don't need to know how to code, use the command line, or install Git (the version control software that GitHub is built on). If you have a question about any of the expressions used in this session, head on over to the **[glossary](https://docs.github.com/en/get-started/quickstart/github-glossary)** to find out more about our terminology.*

:fire: A repository is usually used to organize a single project. 

:exclamation: Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs. Often, repositories include a `README` file, a file with information about your project. `README` files are written in the plain text [Markdown language](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). You can use this cheat sheet to get started with Markdown syntax. GitHub lets you add a `README` file at the same time you create your new repository. GitHub also offers other common options such as a *license file*.
You need to create or have a GitHub account:

**How to create a Github account**

To create a GitHub account for the first time, follow the six steps below.

:one: Go to your browser and open [GitHub](https://github.com/).

:two: Click top left on `Sign up`.  
![SignUp](media/practice1.1.pre.png)  

:three: Then select your GitHub `email`,  `password` and the `username`.  
![SignUp](media/practice1.2.pre.png)  

:four: Verify you account by solving a `"Puzzle"`.  
![SignUp](media/practice1.3.pre.png)  

:five: That's all. You have your new GitHub account. 

:six: :rocket: You can now continue with the course.

<HR>



# 1. <a name='createrepo'></a>Creating a new repository and configure the main options


We want to create a repository named `hello-world` where you can store ideas, resources, or even share and discuss things with others. To do that:

- :one: In the upper-right corner of any page, use the drop-down menu, and select **New repository**. 

![practice example 1](./media/practice1.1.png)

- :two: In the Repository name box, enter `hello-world`. 

![practice example 1](./media/practice1.6.png)

- :three: In the Description box, write a short description. 

![practice example 1](./media/practice1.7.png)

- :four: Select Add a README file. Then we will change it. 

![practice example 1](./media/practice1.9.png)

- :five: Select whether your repository will be Public or Private. In or case we will select Public. 

![practice example 1](./media/practice1.8.png)

- :six: Click Create repository. 

![practice example 1](./media/practice1.10.png)

![practice example 1](./media/practice1.2.png) 

That done, we now have our first repository ready to be used.

We will see the initial screen of our repository and we will explain each section of it:

![practice example 1](./media/practice1.11.jpg) 


##  2. <a name='Addingcontenttoourrepository'></a>Adding content to our repository. Commits.

A `commit` is like a snapshot of all the files in your project at a particular point in time.

When we created your new repository, we initialized it with a `README.md` file. `README` files are a great place to describe your project in more detail, or add some documentation such as how to install or use your project. The contents of your `README`  file are automatically shown on the front page of your repository for each folder you have it.

Let's commit a change to the `README.md` file:

:one: In your repository's list of files, click `README.md`. 

![practice example 1](./media/practice1.12.png) 


:two: Above the file's content, click on the icon of a pencil (to edit).


:three: On the Edit file tab, type some information about your respository. 

![practice example 1](./media/practice1.13.png) 

For example, add the following text to the README file.

```
## Aim of this repository
This is my first repository to store information from my research on XXXX.

## How to collaborate:

- One: Clone this repository.
- Two: Add your features and collaborate with us on this research project.

## How to cite this repository

	@misc{YouName2022,
  		author = {Your Name},
  		title = {My first repository},
  		year = {2022},
  		publisher = {GitHub},
  		journal = {GitHub repository},
  		howpublished = {\url{URL_OF_THIS_REPO}}
		}

```


:four: Above the new content, click `Preview changes`. 

![practice example 1](./media/practice1.14.png) 


:five: At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message.

:six: Below the commit message fields, decide whether to add your commit to the current branch or to a new branch.

:seven: Commit the changes.

![practice example 1](./media/practice1.15.png) 


##  3. <a name='Workingwiththeversionhistory'></a>Working with the version history

Now it's time to make some more changes by adding a folder and inside that folder include a file with this content. Copy and paste the content into the file you want to edit and add it to the repository.

Add this new file in this path: `/funtions/plot.py`:

```
import matplotlib.pyplot as plt
fig = plt.figure()
ax = fig.add_axes([0,0,1,1])
langs = ['C', 'C++', 'Java', 'Python', 'PHP']
students = [23,17,35,29,12]
ax.bar(langs,students)
plt.show()
```

By doing this, we already have several changes fixed in the repository, so we can check the history of changes we have made. 

To do so, access the history from this option:

![practice example 1](./media/practice1.16.png) 

And we will see a list of changes we've made:

![practice example 1](./media/practice1.17.png) 

In this list we can review what changes we have made during the lifetime of the repository and compare the changes with respect to a certain date.

![practice example 1](./media/practice1.18.png) 

:one: Copy the ID of the commit.

:two: View and check differences and changes/deletions made in the repository and files.

:three: See the status of the repository at this point.

##  4. <a name='Collaboratingwithotherusersandrepositories'></a>Collaborating with other users and repositories

![p1.23](./media/practice1.23.png)


Issues allow you to track your work on GitHub. When you mention an issue in another issue or pull request, the issue timeline reflects the cross-reference so you can track related work. To indicate that work is in progress, you can link an issue to a pull request. When the pull request is merged, the linked issue is automatically closed.

**Track work**

You can organize and prioritize issues with projects. To track issues as part of a larger issue, you can use task lists. To categorize related issues, you can use labels and milestones.

**Efficient communication**

You can @mention collaborators who have access to your repository in an issue to draw their attention to a comment. To link related issues in the same repository, you can type # followed by part of the issue title and then clicking the issue that you want to link. To communicate responsibility, you can assign issues.

**Opening a blank issue**

First, create an issue. There are multiple ways to create an issue; you can choose the most convenient method for your workflow. This example will use the GitHub UI. For more information about other ways to create an issue, see "Creating an issue."

:one: On GitHub, navigate to the main page of the repository.

:two: Under your repository name, click Issues. Issues tab

:three: Click New issue. 

:four: In this example, we will start with a blank issue. Your repository may use issue templates and issue forms to encourage contributors to provide specific information. If your repository uses issue templates, click Open a blank issue.
	
**Filling in information**

Give your issue a descriptive title. The title should convey at a glance what the issue is about.

Add a description that explains the purpose of the issue, including any details that might help resolve the issue. For example, if this is a bug report, describe the steps to reproduce the bug, the expected result, and the actual result.

You can use markdown to add formatting, links, emojis, and more. For more information, see [Markdown language](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
	
**Adding a task list**

It can be helpful to break large issues into smaller tasks, or to track multiple related issues in a single larger issue. 
	
**Adding labels**

Add a label to categorize your issue. For example, you might use a bug label and a good first issue label to indicate that an issue is a bug that a first-time contributor could pick up. 	
	
**Adding milestones**

You can add a milestone to track the issue as part of a date based target. A milestone will show the progress of the issue.
	
**Assigning the issue**

To communicate responsibility, you can assign the issue to a member of your organization.	
	
##  5. <a name='Addingdifferentbranchestoyourrepository'></a>Adding different branches to your repository

Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named main that is considered to be the definitive branch. You can create additional branches off of main in your repository. You can use branches to have different versions of a project at one time. This is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to main.

When you create a branch off the main branch, *you're making a copy*, or *snapshot*, of main as it was at that point in time. If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.

![practice example 1](./media/practice1.3.png) 

This diagram shows:

- The main branch
- A new branch called feature
- The journey that feature takes before it's merged into main

Have you saved different versions of a file? Something like:

    story.txt
    story-edit.txt
    story-edit-reviewed.txt

Branches accomplish similar goals in GitHub repositories.

In GitHub, use branches for **keeping bug fixes** and **feature work** separate from our main (production) branch. When a change is ready, you can merge branches  into main.

**To create a new branch**

- :one: Click the Code tab of your XXXXX repository. 

![practice example 1](./media/practice1.4.png) 

- :two: Click the drop down at the top of the file list that says `Main/Master` Branch menu.

- :three: Type a branch name, with the name `readme-collaborators`, into the text box to `create` a new branch.

![practice example 1](./media/practice1.5.png) 

- :four: Click Create branch: `readme-collaborators` from main.

Now you have two branches, `main` and `readme-collaborators`. Right now, they look exactly the same. 

We will now make changes to the Branch we have just made `readme-collaborators`. To do this, once selected, edit the `README.md` file and add the following text before the references section:


```
## Contributors

- Manuel Parra-Royón (use here your name)

```

Once the change has been made, we can merge the branch we just changed with the `main` branch so that we have those changes reflected.

To do this you can go to the main repository page and you will be prompted to merge these changes with the `main` branch by clicking "Compare and Pull Request"
	
![p1.20](./media/practice1.20.png)

Then you will see the screen to Check the merge and create a pull request.

![p1.21](./media/practice1.21.png)
	
After that you have to merge it
	
![p1.22](./media/practice1.22.png)
	
Now, your main branch is updated with the content of the `readme-collaborators`.


## 6. <a name='ForkingarepositoryandcreatingaPullRequest'></a>Forking a repository and creating a Pull Request

:bulb: A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

*Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.*

Two options with Fork:

- :construction_worker_woman: Propose changes to someone else's project. For example, you can use forks to propose changes related to fixing a bug or an improvement or new documentation, etc.
- :fireworks: Use someone else's project as a starting point for your own idea. Open source software is based on the idea that by sharing code, we can make better, more reliable software. 

:one: Go to our respository for the course: https://github.com/spsrc/reproducibility-course

:two: In the top-right corner of the page, click `Fork`. 

![practice example 1](./media/practice1.16.png) 

:three: Once this is done, we have a copy of the original repository in our account, so we can work with this copy and make all the changes we need. This way you work in the same way as with your own repository, but with the advantage that you already have a starting point from which you can work on a new idea or propose improvements to the original repository.

:bulb: *If we make some changes, for example to the README.md in this fork, we will see that a message appears indicating that our new "forked" repository is further ahead in "changes" (or commits) than the original, which means that we can either request a merge of our changes into the original via a Pull Request or compare both repositories.*

