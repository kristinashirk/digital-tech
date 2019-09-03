---
published: true
---
## Introduction
**What is Git?** Git is a distributed version-control system (DVCS) for tracking changes in source code during software development.” *[Wikipedia](https://en.wikipedia.org/wiki/Git).* Version control systems like git track changes made to files by "storing the modifications in a central repository.” *[howtogeek](https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/).* git can work with local files and is an ideal version control system for small individual projects like those in this course. 

**What is GitHub?** “GitHub is a git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.” *[techcrunch](https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway)*

**What is a repository?** “A repository (usually abbreviated to “repo”) is a location where all the files for a particular project are stored. Each project has its own repo, and you can access it with a unique URL.” *[howtogeek](https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/).* 

**Why should you care?** git and GitHub will allow you to create and share your content, while also keeping track of any changes that you make to your content as you work. This is particularly useful when coding a project, as you may need to backtrack to find and resolve issues in your code. 

## Set up a Git / GitHub Repository
### Before you begin:
* Download [Atom text editor](https://atom.io/).  
    Atom is a text editor created by the makers of GitHub. This means that Atom will integrate with your git - GitHub Desktop - GitHub Pages environment very well and make editing and publishing your code easy.

* Download and install [git](https://git-scm.com/).  
    git will allow you to track changes and manage different versions of your code to your local computer. 

* Set up a [GitHub account](https://github.com).  
    We recommend setting up a personal GitHub account so you can continue building an online portfolio beyond your time at the University.

* Download and install [GitHub desktop](https://desktop.github.com/).  
    This is a desttop version of your online GitHub account. It will allow git, on your local machine, speak with GitHub online. 

### Clone template website files
To begin building your website, you will use a very basic template from this GitHub repository:[https://github.umn.edu/alink/sample-html-site](https://github.umn.edu/alink/sample-html-site).

To get the files on your local computer, you will clone the repository.
1. Navigate to [https://github.umn.edu/alink/sample-html-site](https://github.umn.edu/alink/sample-html-site)
2. Select **Clone or download**, and choose **download zip**.
3. Extract the folder in the zip file and place it on your desktop.  
**NOTE:** You can put the folder elsewhere, but this tutorial will use the Desktop.  
4. Rename the folder to "Template_Website."  
**NOTE:** You can, of course, name this folder whatever you like, but this tutorial will refer to "Template_Website".

### Create local Git repository
1. Initlize the git repository.  
	**For Windows**  
    a. Open Command Prompt  
    b. Navigate to "Template_Website" by typing the cd command followed by the file path to the "Template_Website" folder on your desktop. The command should read as follows:  
    `cd C:\Users\USERNAME\Desktop\Template_Website`  
    c. Hit the **Enter** key.  
    d. Type the command `git init`.  
    e. Hit the **Enter** key.  
    
    **For Mac**  
    a. Open Terminal  
    b. Navigate to "Template_Website" by typing the cd command followed by the file path to the "Template_Website" folder on your desktop. The command should read as follows:  
    `cd ~/Desktop/Folder`  
    c. Hit the **Enter** key.  
    d. Type the command `git init`.  
    e. Hit the **Enter** key.
    
**NOTE:** You will recieve a notice of initilizing an empty repository. The files within the "Template_Website" folder still need to be **added** to the repository you just created.  

2. Add files to the repository.  
	a. In GitHub Desktop, select **File > Add Local Repository.**  
    b. Select **Choose** and navigate to the "Template_Website" folder on your computer.  
    c. Select **Add Repository**. The "Template_Website" repository will open in GitHub Desktop.  
    
### Push the local Git repository to GitHub (master)
GitHub Desktop will indicate that there are "2 changed files", referring to the new files we added to the "Template_Website" repository. To complete these change, we will use the **commit** operation. Committing these changes will tell git that you want to adopt the added files into your repository. 

To commit the changes:
1. Enter a brief change descripton into the **Summary** field. 
2. *Optional* Enter a more detailed change description into the **Description** field.
3. Select **Commit to master**  
**NOTE**: The repository branch is local to you. Other users are unable to access your repository. 
4. To push your repository to your GitHub cloud account, select **Publish repository**.
### Publish "Template_Website" on GitHub Pages (gh-pages)
