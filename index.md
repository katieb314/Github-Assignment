
## WELCOME TO MY GITHUB WEBSITE

**When should you use Git for a project?**

* Git is useful when working on a project that involves multiple collaborators. Files can be seen easily by multiple collaborators working on the same project using Github. Changes made by different individuals are also easily seen and older versions of a file are easily accessible.

**What kind of files/info should be saved in a Git repository?** 

* 

**What types of files/info should not be included in a Git repo?**

* Datafiles and confidential/sensitive material should not be included in a Git repo. This is because the Git repo is online and can be accessed by anyone. 

**What are the commands to undo a commit?**

* If you have commit too early and you wished that you had added something to the file or used a different message, you can use the `git commit --amend` command. This will allow you to edit the file or edit the message and it will appear as a single commit in your `git log`.
* To undo a commit for a single file, you can use the `git reset HEAD <file>` command. 
* If you modified a file and then realized you didn't actually want to make that modification, you can use the `git checkout -- <file>` command. This will bring you back to your last version of that file.

**Explain the pros and cons of using Git for your research project.**

*Pros:*

* All resources can be accessed remotely
* You can look at a log of all the modifications you have made to your project, and go back to any one of them
* You can easily collaborate with other researchers, and others can easily contribute to your open-source projects
* It's free
* It uses a simple text editor that allows you to output impressive-looking documents
* Good for creating a back-up of your work

*Cons:*

* Files can be accessible by anyone
* Not intuitive to learn and may be time-intensive to learn
* The repository can only hold 1 Gb of information and the file size can't be greater than 100 Mb

**Explain the pros/cons of hosting your project in a public (or private) repository on Github/Bitbucket/Gitlab etc.**

*Pros:*

* Other researches can easily contribute to public open-source research projects
* Employers can look up how often you have contributed to other projects
* Meet new developers - GitHub is like the "Facebook" of the coding world

*Cons:*

* Hosting a private repository is costly
