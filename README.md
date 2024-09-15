# GitSteps 🐙

#### Project in Progress ⚠️

### Step by step how to use git with github for beginners
<img><center> 

![image](https://user-images.githubusercontent.com/100430135/182463113-50b296fb-b67f-4e1e-a986-4fc2c610e357.png)

</center></img>

### Prerequisites ⚠️
- Git
- Account on Github

---

### In this short Tutorial I will show you how to use Git Basics for your projects and code versioning, this includes doing:

- clones
- init's
- Commits
- Push's
- Pull's


## Step 1
### download git
### First, you'll need to have Git installed on your machine, 
### if you don't already, click here -> [Download Git](https://git-scm.com/) , download and install.

<br>


![GitSite](https://user-images.githubusercontent.com/100430135/184555032-982838bb-8cae-4641-9729-f624d10de1dc.png)

<br>

---

<br>

## Step 2
### Create or access an account on the GitHub remote repository.
### If you don't have access to GitHub, go to the official website or click here -> [GitHub](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) to be directed to the Github page, you can login to an account or create your own.

<br>

![GithubSite](https://user-images.githubusercontent.com/100430135/184555266-9e8e631f-6391-455e-b006-7812e5fdb547.png)

<br>

---

<br>

## Step #3
### Create a repository on GitHub.
### That's right, after creating your Github account, enter it and go to repositories, they are at the top center, next to 'Projects'.
### Click on the "New" option to create a new one and you will be directed to the page where you will choose the characteristics of your repository, such as: Name, Description, Visualization options and the like.

<br>

![NewRepository](https://user-images.githubusercontent.com/100430135/184555470-97a3931d-468d-4ebd-ba19-d5b2e32bfc2c.png)


<br>

### Choose a name for your repository, mine will be called gitSteps.

### If you like that other people such as college colleagues or even recruiters can see this repository, it is interesting to leave the "Public" option checked, if not, that it is a private project, select the "Private" option.

### It is also important to leave the Add a README film option active, since the README file serves as a cover for your repository, it is where the main warnings, methods of use and characteristics of your repository will be.

### With all the choices made, create your Remote Repository in Create Repository.

<br>

--- 

<br>

## Step #4
### Clone the remote repository to your computer.
### Inside your repository that was created, click on the green box "Code", in this there will be an HTTPS link that serves as a locator of the remote repository, it is with it that we will be able to clone the remote repository to the local computer, save this link , it's very important.

<br>

![GitClone1](https://user-images.githubusercontent.com/100430135/184555763-b711175c-6e6b-467e-9a77-c8fe6140aec6.png)


<br>

### Create a folder on your computer where you will save the files you are going to work on, it can be on the desktop, or anywhere else you want, mine will be on the desktop.
### Give the folder a name to better identify it, when I do your projects, I'll call mine "Git".

<br>

![PastaGit1](https://user-images.githubusercontent.com/100430135/184556009-2d64d691-26e0-4ecd-8e94-95ceb42cf408.png)

![PastaGit2](https://user-images.githubusercontent.com/100430135/184556010-0a92750d-fdd0-42ed-9d2c-0aad4c82d382.png)

<br>

### Enter the folder and right-click, if you already have Git installed, select the Open Bash Here option, this option will open the Git terminal (Bash) that responds by command line, and that is what we are going to use to versioning our codes and projects.

<br>

![GitBashHere](https://user-images.githubusercontent.com/100430135/184556106-4692af03-4974-4968-9e64-0a96d4b720dc.png)

<br>

### After initializing git, still in Bash (Git Terminal) type the command <span style="color:red">git clone + repository link</span>

### This link I used is the link to my remote repository (the one I told you to keep), that is, that repository you created on GitHub, use it with the command <span style="color:red">git clone + link</span>

<br>

![gitClone2](https://user-images.githubusercontent.com/100430135/184556271-7197e926-7261-41d0-9e19-33eb1969304e.png)

<br>

### After this command, git will download a clone from the remote repository to the local folder you created, where you will be able to work with your codes and projects.

<br>

![2022-08-14 (12)](https://user-images.githubusercontent.com/100430135/184558866-12684abd-bf5c-45bc-b153-aa9ccf91b375.png)

<br>

---

<br>

## Step #5
### Add Files that will be part of your project.
### In this part of the walkthrough, with the repository already cloned in your folder where git is running, add the files that will compose your project, for example:
- index.html
- wallpaper.png
- style.css

<br>

![gitAdd1](https://user-images.githubusercontent.com/100430135/184556873-d8a70027-84f0-4dfb-911e-2abcf620151f.png)

<br>

### Once your files are inside the page, assuming you created them from vscode inside the page, which is possible and recommended, open the git (Bash) terminal and type the command <span style="color:red">( git add . ) </span>
### This command will put all the files on the page under git version control, this means that the files will be ready to be updated and uploaded to Github.

<br>

![gitAdd2](https://user-images.githubusercontent.com/100430135/184556969-ed5f7234-b7ed-4ff1-9054-30ac1de04345.png)

<br>

### I used the <span style="color:red">git status</span> command to show the status of new files that are in the local repository folder

<br>

![gitAdd3](https://user-images.githubusercontent.com/100430135/184556968-225e71da-ed63-4e9d-a3b1-ddc7915bc013.png)

<br>

---

<br>

## Step 6
### The commit command.
### The commit command will trigger the file or files that are part of the project to its most updated version, with a brief description, that is, the commit command, marks the end of a procedure, which will be the next one to push the files to the remote repository, Github.

### the syntax of the commit command is <span style="color:red">git commit -m "mensage "</span> , that is, the -m expects a message, the quotes (" ") is where it will contain the message, this message is a brief description of your update, for example:

- git commit -m "add new features"
- git commit -m "add new header"
- git commit -m "add new image to site"

<br>

![gitCommit1](https://user-images.githubusercontent.com/100430135/184557179-102e3aad-d6f3-4cfe-acb4-f908e4e5e96a.png)

<br>

### after this command the terminal will show some messages on the screen showing which files you committed

<br>

![gitCommit2](https://user-images.githubusercontent.com/100430135/184557178-e7e7bc9c-d9b2-4cec-96ab-1b412ff4038f.png)

<br>

---

<br>

## Step 7
### The Push command and Github.
### Now, finally, it's time to push your files to Github through the Push command, that is, the <span style="color:red">git push</span> command serves to allocate all the latest updates of your project files to Github, in this way, with each push , your remote repository keeps abreast of updates from your local repository.

<br>

![gitPush1](https://user-images.githubusercontent.com/100430135/184557609-3257405c-ef47-44eb-9d6a-6b8ee8fa1969.png)

<br>

### After the <span style="color:red">push </span> command, the terminal will show some messages on the screen, regarding the push, showing that it was done successfully.

<br>

![gitPush2](https://user-images.githubusercontent.com/100430135/184557610-61b6c998-42f6-4e42-924b-15735cb3254a.png)

<br>

### After the push, enter your Github account and you will see in your repositories that the new repository has been updated with the files you added on your computer, so whenever you want to upload a new file or modify an existing one in the folder, just use the git add command. then the command git commit -m "message" and finally the command git push.

---

<br>
