# Comp 3040 A2
## How to Host your Resume on GitHub Pages
By Ben Clark

---
#### Purpose
By the end of this tutorial, you will be able to host your own resume on github pages. 

For this tutorial, we will be using documents formatted with Markdown language.
Andrew Etter, author of the best selling book _Modern Technical Writing_, reccomends the use of markdown for technical doccuments because of it is lightweight, easy to learn and universially used. 

#### Prerequisites
Before beginning, you should have the following:
- A resume in markdown format. You can find a tutorial on how to use markdown [here](https://www.markdowntutorial.com/)
- An account on GitHub. If you do not have an account, you can create one [here](https://github.com/signup)

#### Terminology
Throughout this tutorial, a number of terms are used that may not be accesible to all users. To remedy this, I have descibed them here:
- Repository: A repository is place to store files online

---

### Step 1 - Creating a Repository
The first thing that will need to be done to host your resume online is to set up your github account. In order to store your resume online, you will need a repository, (a place online to store your files)
1. Sign into your account on [Github](https://github.com/)
2. Click the green button labeled new on the left hand side of the screen
![CreateRepo](assets/CreateRepo.jpg) 

This will take you to the **Create a new repository** page, from here we can continue

3. Enter ``` username.github.io ``` into the repository name feild (where username is your username on GitHub)

Naming your repository in this way lets Github know that you want to create a website from this repository

4. Click the checkbox next to _Add a README file_
5. Lastly click the _Create repository button_ at the bottom of your screen. 

Your repo is now setup and ready for use.

At this point in the tutorial, your site can already be viewed. 
Navigate to ```https://YourUserName.github.io/```
Currently, the only thing displayed will be the default Reame.md that Guthub created for you.
In order to display your resume on the site, you will need to upload files to the repository

---

### Step 2 - Uploading files to your Repository
Now that the respoitory is set up, the next step is to upload your resume to the repository.
- Click the button labeled 'Add file'
- Select Upload files and select your resume

From here there are 2 options
Github pages will use ```readme.md``` as the homepage of your site unless your provide a file named ```index.md```

1. Using the resume as the homepage
If you want your resume to be used as the homepage of the site, the file name will need to be changed.
To use your resume as the homepage for your site:
- Rename your resume to ```index.md```

2. Using another page for the homepage
The other option allows for more flexiblity, giving you the option to host multiple pages on your site.
To use another file other than your resume as the homepage for your site:
- Create a new file named ```index.md```
- You can then add a link from your home page to your resume by adding the following line to index.md
``` This code creates a link to your resume -> [Link](Resume.md) ```

---

### Step 3 - Choosing a theme for your site
Github pages gives its users alot of options to customize their sites.
Here are some popular themes that can easily be added to your site
- Slate - Slate is a simple theme that is clean and easy to read,  [Preview](https://pages-themes.github.io/slate/)
- Merlot - Merlot ......,  [Preview](https://pages-themes.github.io/merlot/)
- Time Machine - Time Machine ......,  [Preview](https://pages-themes.github.io/time-machine/)

There are many other themes available for Github pages, a more extensive list can be found [here](https://pages.github.com/themes/)
In this tutorial we will be using the theme Slate

To add the the theme to your site:
- Return to the screen showing the files in your repository
- Create a new file named ```_config.yml```
- add the following block of code to your file

```
    theme: jekyll-theme-slate
    title: Your Name
    description: Digital Resume
```

- This will tell the software that you want your theme to be set to slate

---

### Conclusion
This tutorial outlines only the basics of hosting your resume on gitlab. If you found this helpful I encourage you to explore the other customizability options that Github offers

--- 

#### FAQ

**Q:** "Why is Markdown better than a word processor?"
**A:**  Answer

**Q:**  "Why is my resume not showing up?"
**A:**  There are a number of possible reasons your resume isn't showing up, I will outline a few of them below:

1. Your resume is in the wrong folder.
    - A
2. Your file names are incorrect
    - Github pages will be looking for one of the following pages to use as the homepage of your site: (index.html, readme.md).
    - Navigate to 
3. A
    - A