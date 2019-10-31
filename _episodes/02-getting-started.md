---
title: "Getting started with GitHub"
teaching: 20
exercises: 0
questions:
- "What are repositories and how are they created?"
#- "What do `add` and `commit` mean?"
#- "How do I check the status of my repository?"
objectives:
- "create a git repository"
#- "track changes to files using the git repository"
#- "query the current status of the git repository"
keypoints:
#- "Git repositories contain metadata about files under version control"
#- "This metadata enables us to track changes to files over time"
#- "Git uses a two-stage commit process. Changes to files must first be added to the staging area, then committed to the repository"
---

<!-- ### Using Git

One of the main barriers to getting started with git is the language. Although some of the language used in git is fairly self-explanatory, other terms are not so clear. The best way to get to learn the language - which consists of a number of verbs such as `add`, `commit` and `push` (preceded by the word 'git') - is by using it, which is what we will be doing during this lesson. These commands will be explained as we proceed from setting up a new version-controlled project to publishing our own website. -->


### Creating a repository

A git **repository** is a data structure used to track changes to a set of project files over time.  Repositories are stored within the same directory as these project files, in a hidden directory called `.git`. We can create a new git
repository either by using [GitHub's web interface](https://github.com/new), or via the command line. Let's go to GitHub to create a repostiory.

First, go to [github.com](https://github.com/) and log in.

Click the green **New** button on the left side of the page. This will open the "Create a New Repository" form.

Enter a memorial repository name. I'm going to do a variation on the date.
~~~
sclayton29/LC_2019-11-01
~~~

You can add a description if you would like. Then select **Create Repository**.

You should now see a page of instructions for how you could add this to your local files. Note that there are options for the command line and for GitHub Desktop.

### Creating a File
We can get started by clicking the **creating a new file link** under the Set up in Desktop button.

Name your file README.md. It is good practice to have a file like this to explain what is in the repository.

Add a brief description of the repository. Because this is markdown, we can add a header by using #.

~~~
# Description
This is a test repository for Library Carpentry on November 1, 2019 in Rochester, NY.
~~~

*We are using markdown because it is a plain-text file that GitHub can render nicely. This is the foundation for the webpage we will build later. You can see how this markdown will render by using the Preview tab.*

Now we are ready to save our changes.

Scroll to the bottom of the page to where you see **Commit new file.** Commit is similar to the save functionality we are used to in most tools. The major difference is that the new version is also being recorded within version control system meaning we can return to this exact version even after lots of other changes have been made.

Our commit message is critical because it is tells us what this version contains, which will help us if we are trying to come back to it later. So try to be as descriptive as possible. However you will want to keep the first message short. You can add more info in the extended description box if desired.

~~~
Started file. Added min info.
~~~

When you are satisfied with your message. Select the green **Commit new file** button.

This will return you to the main page of your repository.

Click on README.md to open the file again.

*Note: your readme is a special file that will also appear on the main page of your repository.*

Notice the actions across the top.
* **Raw** will show you the un-rendered file.
* **Blame** will show you who made changes and when.
* **History** will show you all the commit messages.

You can also open in GitHub Desktop, Edit, and Delete.

>### Challenge  
Edit the README.md file again. Write a strong commit message. Look at the blame and history again.  


Let's add another file. This time we will also create a new folder.

On the main page of your repository, select **Create a new file**.

This time in the name of the file. First write the new folder name followed by a slash and then the file name.

~~~
LC_2019-11-01/Folder1/NewFile.md
~~~

Add some text in your new file and commit it.

Click the code button to return to the main page. Notice how your new folder and file can be accessed via this page.
