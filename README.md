How to host a resume on GitHub
===
### [Demo Website](http://rahman-asifur.github.io/) 

Purpose
---
This README file will demonstrate a quick tutorial on how to host a formatted resume as a static site generator on github using Markdown, Github and Jekyll by following some of the key principles of Andrew Etter's book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

Prerequisites
---
1. You will need a resume formatted in [markdown](https://www.markdownguide.org/getting-started/). Here is a [resume template](https://github.com/rahman-asifur/rahman-asifur.github.io/blob/main/resume_rahman_asifur.pdf).
2. I have used [Visual Studio Code](https://code.visualstudio.com/) for mardown editor.
3. Installing Jekyll and follow this [setup guideline](https://jekyllrb.com/docs/installation/#requirements) if you are using macOS operating system.
4. Creating a github account and setting up [Github desktop](https://desktop.github.com/) for working locally.

Instructions
---
2. **Create a GitHub account.**
	1. Click on Sign up button on [GitHub](https://github.com) if you do not have an account.
	2. Follow the instructions on github to complete signup process.
3. **Create a repository on GitHub.**
	1. Open the repositories section from your github profile.
	2. Click on green colored button New to create a new repository.
	![This is create repo Gif](https://github.com/rahman-asifur/rahman-asifur.github.io/blob/main/images/new_repository.gif)
	3. Name the repository as your username.github.io.
	4. Make your repository public by selecting the public option.
	5. Scroll down to check add a README file for now.
	6. Scroll down to choose a licence.
	7. Click on create repository. 
	![New Repo](https://github.com/rahman-asifur/rahman-asifur.github.io/blob/main/images/create_repository.png)
4. **Setting up your reository locally with Github Desktop**
	1. Go to to your **username.github.io**
	2. Clink on the green button Code to copy the link of your repository
	![Clone Repo](https://github.com/rahman-asifur/rahman-asifur.github.io/blob/main/images/copy_repository.gif)
	3. Open the Github desktop tool
	4. Click on Add button and follow the process of the posted video below:
	![Add repo on github desktop](https://github.com/rahman-asifur/rahman-asifur.github.io/blob/main/images/clone_github.gif)
5. **Creating a Jekyll project for the repository**
    1. Click on **Open in Visual Studio Code** from GitHub Desktop.
	2. Click on Terminal to check the file path is same when you clone your remote repository locally with GitHub Desktop.
	3. Run the following command in the terminal which will create a Jekyll project with necessary files and folder.

5. **Add your files to your repository in Visual Studio Code.**
    1. Click on to create a file named index.md as this will be home page of the website.
	2. Copy the content of your resume.md in index.md file.
	  - Markdown is used to format the resume as MarkDown is the best lightweight markup language.
        >Andrew Etter mentioned the benefits of using *Markdown* language. It can always sync with your latest version of work. It can have multiple version control for your resume to be updated and formatted. It makes contribution very convenient. It is commonly used by developers.
	3. Edit the _config.yml to setup the Jekyll theme of the website.
6. **Push your changes to the remote repository**
    1. Open GitHub Desktop
	2. Select your repository to view all the changed files.
	3. Write a comment to commit to main.
	4. Click Push origin to upload the files in github.
	



**Your final resume should look like this website.**\

More resources
---
* [Markdown Tutorial](https://www.markdownguide.org/getting-started/)
* [Modern technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Dinky Jekyll Theme](https://pages-themes.github.io/dinky/)


Authors and Acknowledgments
---
* Etter, Andrew. [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS), 2016.

FAQs
---
1. Why is Markdown better than a word processor?
> Markdown is free to use. It has a cleaner syntax and is simply making developers interested in contributing. It can always stay up-to-date by syncing. Moreover, it allows the separation of content and style, of HTML and CSS.
2. Why is my resume not showing up?
> GitHub pages, sometimes, take time to generate. You might verify if the username or the link provided are correct and check again for the published site after some time. Refresh the page to see the updates.