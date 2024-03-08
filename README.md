# Comp 3040 A2
## How to Host Your Resume on GitHub Pages
By Ben Clark

---
#### Purpose
By the end of this tutorial, you will be able to host your own resume on GitHub pages. 
An example of the finished product is available [here](https://clarkb2uofm.github.io).

For this tutorial, we will be using documents formatted with Markdown language. Andrew Etter, author of the best selling book _Modern Technical Writing_, recomends the use of markdown for technical documents because of it is lightweight, easy to learn and universally used. 

#### Prerequisites
Before you begin, you should have the following:
- A resume in markdown format. You can find a tutorial on how to use markdown [here](https://www.markdowntutorial.com/).
- An account on GitHub. If you do not have an account, you can create one [here](https://github.com/signup).

#### Terminology
Throughout this tutorial, a number of terms are used that may not be familiar to all users:
- Repository: A _repository_ is place to store files online.
- Commit: A _commit_ is work saved online. _Commiting_ files is saving those files to Github.

---

### Step 1 - Creating a Repository
The first step in hosting your resume online is to set up your Github account. In order to store your resume online, you will need a repository.
1. Sign into your account on [Github](https://github.com/).
2. Click the green  **'Create repository'** button on the left hand side of the screen.
![CreateRepo](assets/CreateRepo.jpg) 

This loads the **Create a new repository** page.

3. Enter ``` YourUserName.github.io ``` into the repository name field (where YourUserName is your username on GitHub).

Naming your repository in this way let's Github know that you want to create a website from this repository.

4. Click the checkbox next to **'Add a README file'**.
5. Click the **'Create repository'** button at the bottom of your screen. 

Your repository is now setup and ready for use.

---

### Step 2 - Uploading files to your Repository
Now that the repository is set up, the next step is to upload your resume to the repository.
1. Click the **'Add file'** button.
2. Click **'Create new file'** in the drop down menu.
3. Naviate to the window labeled **'Name your file...'** and type ```index.md```.

Github pages is set up to use ```index.md``` as the homepage of your site.
4. Paste your resume into the text box below.
Your resume must be formatted as markdown text, _see the prerequisites listed above_.
5. After entering your resume, click **'Commit changes...'** to continue.

A window will open up asking for details regarding your commit. A commit is a saved file, if you plan on changing your resume in the future, you will still be able to view old versions of your resume by looking at the commits. All of the pre-selected commit options on the screen will work for our purposes today.

- _Optionally_, if expect to edit your resume in the future, you can add information in the box labeled 'Extended description' detailing the current state of your resume.

6. Click the green **'Commit changes'** button in the bottom right.

Your resume has now been added to the repository.

![AddingFiles](assets/AddingFiles.gif) 
---

### Step 3 - Choosing a theme for your site
Github pages offers many options to customize your site.
Here are some popular themes that can easily be added to your site:
- Slate - Slate is a simple theme that is clean and easy to read.  [Preview](https://pages-themes.github.io/slate/)
- Merlot - Merlot ......  [Preview](https://pages-themes.github.io/merlot/)
- Time Machine - Time Machine ......  [Preview](https://pages-themes.github.io/time-machine/)

There are many other themes available for Github pages, a more extensive list can be found [here](https://pages.github.com/themes/).
In this tutorial we will be using the theme Slate.

To add the the theme to your site:
1. Click the **'Add file'** button.
2. Click **'Create new file'** in the drop down menu.
2. This file must be named ```_config.yml```.

_config.yml is a file that Github uses to generate your site. It contains the properties that are used to style and customize your pages.

4. Add the following block of code to your file:

```
    theme: jekyll-theme-slate
    title: Your Name
    description: Your Contact Info
```
This will tell Github that you want your theme to be set to Slate.

5. Click **'Commit changes...'** to continue.

This displays the commit options menu. As before, all the default settings will be alright for our purposes right now.

6. Click **'Commit changes'** to save your work.
---

At this point, your site is set up. You can view the finished product by going to WEBSITE HERE LINK.

---
### Step 4 - Supporting your site into the future
Your resume is now set up and hosted on Github pages.
If you want to edit your resume in the future, the easiest way to do so is by editing the file directly in Github.
1. Click on the file containing your resume (index.md)
2. Click on the **pencil icon** in the top right-hand corner of the file to begin editing the file.
3. Click the **'Commit Changes...'** button after you have finished making changes. 

This again displays the commit options menu. The default options in this menu will still suit our purposes.

4. Click **'Commit Changes'** to save your updated resume.

---
### Conclusion
This tutorial outlines only the basics of hosting your resume on gitlab. If you found this helpful I encourage you to explore the other customizability options that Github offers

--- 
### Example finished Website

![Demo](assets/Demo.gif) 

---
### FAQ

**Q:** "Why is Markdown better than a word processor?"
**A:**  Answer

**Q:**  "Why is my resume not showing up?"
**A:**  There are a number of possible reasons your resume isn't showing up:

1. Your resume is in the wrong folder.
    - By default, Github will look for your resume outside of any folders. If it is in a folder, remove it and try again.
2. Your file names are incorrect
    - Github pages will be looking for the following file name to use as the homepage of your site: `index.md`.

---
### Authors and Acknowledgements
Written by Ben Clark
- Special thanks to Ethan Ducharme and Lyle Arcinas for their constructive feedback in class.
- Credit to Andrew Etter, author of _Modern Technical Writing_.
