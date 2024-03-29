# Comp 3040 A2
## How to Host Your Resume on GitHub Pages
By Ben Clark

---
### Purpose
By the end of this tutorial, you will be able to host your own resume on GitHub pages. 
An example of the finished product is available [here](https://clarkb2uofm.github.io).

For this tutorial, we will be using documents formatted with Markdown language. Andrew Etter, author of the best selling book _Modern Technical Writing_, recommends the use of markdown for technical documents because of it is lightweight, easy to learn and universally used. 

### Prerequisites
Before you begin, you should have the following:
- A resume in markdown format. You can find a [tutorial](https://www.markdowntutorial.com/) on how to use markdown.
- An account on GitHub. If you do not have an account, you can [create](https://github.com/signup) one.

#### Terminology
Throughout this tutorial, a number of terms are used that may not be familiar to all users:
- Repository: A repository is a place to store files online.
- Commit: A commit is work saved online. Commiting files is saving those files to Github.

---
### Instructions
#### Step 1 - Creating a Repository
The first step in hosting your resume online is to set up your Github account. In order to store your resume online, you will need a repository.
1. Sign into your account on [Github](https://github.com/).
2. Click the green  **'Create repository'** button on the left hand side of the screen.
![CreateRepo](assets/CreateRepo.jpg) 

This loads the **Create a new repository** page.

3. Enter ``` YourUserName.github.io ``` into the repository name field (where YourUserName is your username on GitHub).

Naming your repository in this way lets Github know that you want to create a website from this repository.

4. Click the checkbox next to **'Add a README file'**.
5. Click the **'Create repository'** button at the bottom of your screen. 

Your repository is now set up and ready for use.

---

#### Step 2 - Uploading files to your Repository
Now that the repository is set up, the next step is to upload your resume to the repository.
1. Click the **'Add file'** button.
2. Click **'Create new file'** in the drop down menu.
3. Type `index.md` into the field labeled **'Name your file...'**.

Github pages is set up to use `index.md` as the homepage of your site.

4. Paste your resume into the text box below.

Your resume must be formatted as markdown text, _see the prerequisites listed above_.

5. Click **'Commit changes...'** to continue.

A window will open up asking for details regarding your commit. All of the pre-selected commit options on the screen will work for our purposes today.

- _Optionally_, if you expect to edit your resume in the future, you can add information in the box labeled 'Extended description' detailing the current state of your resume.

6. Click the green **'Commit changes'** button in the bottom right.

Your resume has now been added to the repository.

![AddingFiles](assets/AddingFiles.gif) 
---

#### Step 3 - Choosing a theme for your site
Github pages offers many options to customize your site.
Here are some popular themes that can easily be added to your site:
- Slate - Slate is a simple theme that is clean and easy to read. Here is a [Preview](https://pages-themes.github.io/slate/)
- Merlot - Merlot is a more stylized theme with more color than some of the other options. Here is a [Preview](https://pages-themes.github.io/merlot/)
- Time Machine - Time Machine provides a theme resembling a blog or newpaper article. Here is a [Preview](https://pages-themes.github.io/time-machine/)

There are many other themes available for Github pages, a more extensive list can be found [here](https://pages.github.com/themes/).
In this tutorial we will be using the theme **Slate**.

To add the the theme to your site:
1. Click the **'Add file'** button.
2. Click **'Create new file'** in the drop down menu.
3. Type `_config.yml` into the field labeled **'Name your file...'**.

_config.yml is a file that Github uses to generate your site. It contains the properties that are used to style and customize your pages.

4. Paste the following block of code into your file:

```
    theme: jekyll-theme-slate
    title: Your Name
    description: Your Contact Info
```
This will tell Github that you want your theme to be set to Slate.

5. Click **'Commit changes...'** to continue.

This displays the commit options menu. As before, all of the default settings will be alright for our purposes right now.

6. Click **'Commit changes'** to save your work.

---

At this point, your site is set up. You can view the finished product by going to `https://YourUserName.github.io/`. This site is built with Jekyll, a static site generator. In Modern Technical Writing, Etter explains that static site generators make creating simple sites simple, efficent and easy to maintain. You can change your resume later on at any time and Github will change your website accordingly.

---
#### Step 4 - Supporting your site into the future
Your resume is now set up and hosted on Github pages.
In _Modern Technical Writing_, Etter mentions how site built in this way are easy to modify. If you want to edit your resume in the future, the easiest way to do so is by editing the file directly in Github.
1. Click on the file containing your resume (index.md)
2. Click on the **pencil icon** in the top right-hand corner of the file to begin editing the file.
3. Click the **'Commit Changes...'** to save your work.

This again displays the commit options menu. The default options in this menu will still suit our purposes.

4. Click **'Commit Changes'** to save your updated resume.

---

### More Resources
 - Github has their own [Quickstart](https://docs.github.com/en/pages/quickstart) guide that explains how to host a site on Github pages.
 - Andrew Etter's book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) explains the concepts of good technical writing in more detail.
- This is an interactive [markdown tutorial](https://www.markdowntutorial.com/) that teaches all the important concepts of the format.

--- 
### Example finished Website

![Demo](assets/Demo.gif) 

---
### Authors and Acknowledgements
- Written by **Ben Clark**
- Special thanks to **Ethan Ducharme** and **Lyle Arcinas** for their constructive feedback in class.
- Credit to **Andrew Etter**, author of _Modern Technical Writing_.

---
### FAQ

**Q:** "Why is Markdown better than a word processor?"
**A:**  Markdown is simple and easy to learn. It provides consistent a format and can be written in any text editor. It can be converted to other formats much easier than the documents written in a word processer.

**Q:**  "Why is my resume not showing up?"
**A:**  There are a number of possible reasons your resume isn't showing up:

1. Your resume is in the wrong folder.
    - By default, Github will look for your resume outside of any folders. If it is in a folder, remove it and try again.
2. Your file names are incorrect
    - Github pages will be looking for the following file name to use as the homepage of your site: `index.md`.
