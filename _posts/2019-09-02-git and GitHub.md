---
published: true
---
## Introduction
**What is git?** git is a distributed version-control system (DVCS) for tracking changes in source code during software development.” *[Wikipedia](https://en.wikipedia.org/wiki/Git).* Version control systems like git track changes made to files by "storing the modifications in a central repository.” *[howtogeek](https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/).* git can work with local files and is an ideal version control system for small individual projects like those in this course. 

**What is GitHub?** “GitHub is a git repository hosting service, but it adds many of its own features. While git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project.” *[techcrunch](https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway)*

**What is a repository?** “A repository (usually abbreviated to “repo”) is a location where all the files for a particular project are stored. Each project has its own repo, and you can access it with a unique URL.” *[howtogeek](https://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/).* 

**Why should you care?** git and GitHub will allow you to create and share your content, while also keeping track of any changes that you make to your content as you work. This is particularly useful when coding a project, as you may need to backtrack to find and resolve issues in your code. 

## Set up a git / GitHub Repository
<iframe width="560" height="315" src="https://www.youtube.com/embed/MRNDIvX41eU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
### Before you begin
* Download [Atom text editor](https://atom.io/).  
    Atom is a text editor created by the makers of GitHub. This means that Atom will integrate with your git - GitHub Desktop - GitHub Pages environment very well and make editing and publishing your code easy.

* Download and install [git](https://git-scm.com/).  
    git will allow you to track changes and manage different versions of your code to your local computer. 

* Set up a [GitHub account](https://github.com).  
   GitHub is a cloud-based repository hoster for git. We recommend setting up a personal GitHub account so you can continue building an online portfolio beyond your time at the University.

* Download and install [GitHub desktop](https://desktop.github.com/).  
    GitHub Desktop is an accessible user interface for git, so you don't have to use the command line to manage your remote repository on GitHub.  

### Clone template website files
To begin building your website, you will use a very basic template from this GitHub repository:[https://github.umn.edu/alink/sample-html-site](https://github.umn.edu/alink/sample-html-site).

To get the files on your local computer, you will clone the repository.
1. Navigate to [https://github.umn.edu/alink/sample-html-site](https://github.umn.edu/alink/sample-html-site) **NOTE:** You will asked yo log in with your "LDAP login credentials." These are your UMN login username and password.

2. Select **Clone or download**, and choose **download zip**.  

3. Extract the folder in the zip file and place it on your desktop.  

**NOTE**: You can put the folder elsewhere, but this tutorial will use the Desktop.  

4. Rename the folder to "Template_Website."  

**NOTE**: You can, of course, name this folder whatever you like, but this tutorial will refer to "Template_Website".

### Create local Git repository
**WARNING: Follow the file paths listed below exactly. If you navigate to the incorrect location on your computer, you run the risk of removing all of your files from your computer. If you think you have done something wrong, stop immediately and contact your TA or professor.**

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
   
   **NOTE**: You will recieve a notice of initilizing an empty repository. The files within the "Template_Website" folder still need to be **added** to the repository you just created.  

2. Add files to the repository.  
	a. In GitHub Desktop, select **File > Add Local Repository.**  
    
    b. Select **Choose** and navigate to the "Template_Website" folder on your computer.  
    
    c. Select **Add Repository**. The "Template_Website" repository will open in GitHub Desktop.  
    
### Push the local Git repository to GitHub 
GitHub Desktop will indicate that there are "2 changed files", referring to the new files we added to the "Template_Website" repository. To complete these change, we will use the **commit** operation. Committing these changes will tell git that you want to adopt the added files into your repository. 

To commit the changes:
1. Enter a brief change descripton into the **Summary** field. 

2. *Optional*: Enter a more detailed change description into the **Description** field.

3. Select **Commit to master**  
**NOTE**: The "Template_Website" repository is local to you. Other users are unable to access your repository.  

4. To push your repository to your GitHub cloud account, select **Publish repository**.

### Make and commit changes to your repository
1. Open files in Atom  
	a. **File > Add Project Folder**, then navigate to "Template_Website" on your desktop.
    
    b. Select **OK**.  
    
    c. Select **Add this window and discard state**.  
    
    d. Close all windows that Atom automatically opened at startup.  
    
    **NOTE**: You can open different files in your project folder into separate tabs by double clicking the file name in the **Project** side bar.  
    
    
    **NOTE**: Atom does not wrap text by default, so you will notice your code running out of frame. To turn on text wrapping, **View > Toggle Soft Wrap**. 
    
2. Replace the `Page title goes Here` text in line 9 with your own page title.

3. Replace the `Section 1` text in line 20 with your own section title.

4. Save your changes. 

5. Commit the file changes to GitHub with GitHub Desktop.  
	
    **NOTE**: GitHub Desktop will indicate "1 changed file," and highlight the code changes in red.  
    
    a. Enter a brief change summary in the **Summary** field.  
    
    b. *Optional*: Enter a more detailed change description into the **Description** field.  
    
    c. Select **Commit to master**.  
    
    d. Select **Push origin** to push the file changes to your GitHub cloud account.

6. Preview your simple website by double clicking the index.html file on your desktop.
