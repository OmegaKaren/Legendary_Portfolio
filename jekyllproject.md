--- 
layout: post
title: Jekyll Project
--- 
# How to start a portfolio website with GitHub Pages and Jekyll


![jekyll and github pages](assets\images\jekyll_github.webp)


Starting your journey as a software engineer can be a daunting task to say the least.  One of the best places to start is building a portfolio website to showcase your skills to potential employers. Luckily, it is relatively easy to host a website regardless of your experience level with [GitHub Pages](https://pages.github.com/) and [Jekyll static site generator](https://jekyllrb.com/). GitHub allows for an easy way to host all your files for your website in a single place while also not requiring you to configure any servers. Jekyll takes these files hosted on your github repository and creates a simple static website that you can customize as much or as little as you would like. Please note that while it is not necessary to have prior knowledge with HTML, CSS, or Javascript it will certainly be a requirement if you plan on customizing your website beyond the generic theme Jekyll provides you with.

# Create a [GitHub Account and repository](https://github.com)

The first step for creating your website is to create a github account. Once you have created your GitHub account you have to create the repository to store all of your files and code in.

![Github create repository](assets\images\github_repository.jpg)

When creating your new repository, name it whatever you like (note: The repository name will be the name and url of your website unless you specifically create a custom URL)

Once you create your new repository, you will see this screen (ignore the red box for now, you will have to come back to this to inilize your repository)

![GitHub repository setup](assets\images\Github_setup.png)

A person like myself who has never experienced Github or using git for workflow management the process for starting can be quite confusing. Essentially, github is where you store all your files and git is the version control system used to manage all those files on your github. While I am not an expert at git or github I have learned the basics of git to start the project. Here are the steps I took. 

Your first step is to download [git](https://git-scm.com/). 

Once you have installed git you see a software called git bash that will be used to interact with your repository. To verify you have the correct version of git installed open up git bash and type <span style="color:red">`git --version`</span>. My version of git is 2.36.1.windows.1 

![git version](assets\images\git_version.png)

Once you have verified your git version is correct, you have to configure git to communicate with your GitHub repository. 

 Add your username you created for your GitHub account <span style="color:red">`git config --global user.name "YourName"`</span>

 Then add your email you used as well <span style="color:red">`git config --global user.email "TestEmail@example.com"`</span>

 ![github username and email config](assets\images\gitusername.png)

 Now that you have added your GitHub account, you now have to create a directory to store all your local files on your computer. You can create this anywhere on your computer that youd like. Once the directory is created, you have to initalize git in the that directory. To do this you are going to cd into the directory you created. 

 ![git init](assets\images\git-init.png)

 As you can see I created a directory called /d/test-website and then I initlized git using the <span style="color:red">`git init`</span> command.


 Once your directory is inilized you have to connect git to your repository, if you recall back to the quick setup page right after creating your repository you will see the steps to creating a new repository on the command line. The line you are going to be most interested in is the <span style="color:red"> git remote add origin (insert your URL given to you on your quick setup page)</span>. 

 ![git-origin](assets\images\git-origin.png)