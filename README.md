

# How to host a resume on Github Pages
## Purpose
This README describes the steps on how to host and format a resume using Markdown, VS Code, GitHub Pages, and Jekyll.

## Additional Purpose
This README will also introduce and demonstrate general principles of technical writing, as explained by Andrew Etter in _Modern Technical Writing

> According to Etter, documentation as such should be open-source and be written with an aim for other people to contribute to it.

Here is link to this book  [more resources.](#more-resources)

---

## Prerequisites
Here are some of the things you would require before you proceed with anything:
- A resume formatted in Markdown.
- A Github account.
- Install Jekyll on your computer(Download ruby installer in order first).

Check for [more resources](#more-resources) and links to Markdown tutorial and other stuff related to Github, Jekyll installation.

---

## Instructions
### 1) Here are steps on setting up a Github Account.
If you have github account then go to 2) directly. 
  1. Serch <https://github.com/> to your browser.
  2. To create new account, click on `Sign up` button, if you have account then `Sign in`.
  3. Assume that you signed on or created account.
  4. There will be authntication link will sent out to email address to verify email address you have provided. Verify your email address by clicking the link.
 
### 2) Find your choice of static website themes.
Once you learn about Markdown and Github,and set up github account successfullly, you can find static website themes and its Github pages and Jekyll over the internet.
You can find this themes on [rubygems](https://rubygems.org) and serch `jekyll-resume-theme` in search bar.
I have attached some sample themes in [more resources.](#more-resources)

> Etter mentioned in chap17 that using a complex content management system (CMS) that requires a server-side database and scripting language, one could use a static site generator like Jekyll or Hugo, which converts Markdown files into HTML pages. This approach eliminates the need for server-side dependencies and reduces the attack surface of the website, making it less vulnerable to security threats.

### 3) Fork choosen resume theme from 1).

  1.  Click the `Fork` button on top-right part of the screen in selected theme's repo.  
  2.  It will ask to write repository's name.
  3.  Keep formate for naming repository-`username.github.io`, and keep everything as it is.
  4.  By clicking on `create fork` append that theme to given name' repo.
  
  > Etter mentioned in chap 8 how forking allows multiple contributors to work on the same project simultaneously without interfering with each other's work, and how changes made to a forked repository can be merged back into the original repository when ready. we will fork this theme and make changes and it will be very helpful to us.

### 4) Make changes to resume theme to make it yours.

- Go to `_config.yml` file in selected Resume-theme's repository. 
- Replaces content with your content and make changes in `_config.yml` file (Edit file by clicking on pencil icon at right top which will give you option to edit file.)   
-  Finalize the chnage and commit to master branch, by clicking `Commit changes` button

> This can be related to Etter's advice to host documentation on a website and use version control systems to keep the content up-to-date and in sync with the latest updates.

### 4) Hosting a resume.
Now that you have successfully complemted all things on Github pages your static website `https://username.github.io/`
We can go to brower and search for `https://username.github.io/` which will show all changes made with our resume and successfully sync changes made from `_config.yml`.

#### Below is an animated GIF demo of the hosted resume:
![](./images/demo.gif)


### More Resources
1. Learn how to use [Markdown.](https://www.markdowntutorial.com/)
2. Some of useful Markdown editor [Typora](https://typora.io/),[HedgeDoc](https://hedgedoc.org/) etc.
3. To purchase Andrew Etter's _Modern Technical Writing_ follow [this link.](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
4. To learn about Github, follow through [Github Tutorial](https://docs.github.com/en).
5. Here is how to [Jekyll Installation.](https://jekyllrb.com/docs/)
6. Some of the sample resume-theme's links given below to help you get started:
   - [jekyll-cv-theme](https://github.com/aleksnyder/jekyll-cv)
   - [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)

---

## Authors and Acknowledgements
- [James Grant](https://github.com/sproogen/modern-resume-theme) did great job in designing modern-resume-theme using _Jekyll_ and _Github pages_ which i used to implement for mine.
- List of group members who assisted in making improvements to the README file: 
 1. Martin Popper
 2. Aditya Kashyap
 3. Saif Mahmud

---
## FAQs 

#### Why is Markdown better than a word processor?
- Markdown is batter becuase it's simple and lightweight markup language which is good and easy to edit 
- Markdown files are portable and platform-independent. This means they can be opened and edited in any text editor
- Markdown files are easy to version control.This means changes made to the document can be tracked over time, and previous versions can be restored if needed.

#### Why is my resume not showing up?
- Make sure that your Github repository name is `username.github.io` (Steps to change if you don't have that formate **Inside your repo go to option Settings, Under General section > Repository name**
- Make sure Github repository is `public`.(Steps for that **Inside your repo go to option Settings -> General -> Danger Zone -> Change respository Visibility**)
- Make sure your Github pages is built from `master` branch. (Steps for that **Inside your repo go to option Settings > Pages > Build and deployment > Branch**)




- As simple as that, the website can now be viewed locally on `http://localhost:4000` or on `http://127.0.0.1:4000/`
