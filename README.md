## Applying Etter's Modern Technical Writing Principles to Host an Online Resume

## Purpose

The purpose of this README is to explain the practical steps of how to host and format a resume online while also relating these steps to the principles of technical writing described in Andrew Etter's book _Modern Technical Writing_.

## Prerequisites

* A resume.
* A Markdown editor.
* A [GitHub](https://github.com/) account.
* [Github Desktop](https://desktop.github.com/)

## Instructions

I will be demonstrating a number of principles of technical writing as described in Andrew Etter's book _Modern Technical Writing_ by explaining how to host a resume online.

The main principles I will be demonstrating are as follows,

* Consistency
* Using Markdown
* Using Distributed Version Control
* Using Static Websites instead of PDFs

I will be showcasing consistency by keeping the formatting of these instructions as consistent as possible. Consistency is important as it allows a reader to know what to expect and properly follow along a reading without frustration.

### Format a Resume in Markdown to be hosted online

Reasons for using Markdown include,

* Easily Hosted Online
* Lightweight
* Widely Used throughout the World

A Markdown tutorial and resume guide can both be found in the More Resources section.

1) Create a resume using Markdown.

2) At the top of the file include, 

   ​	\---

   ​	permalink: index.html

   ​	theme:

   ​	\---

3) Save your resume as index.md

Result: You will have a resume formatted in Markdown that is properly setup to host on a static website.

### Create a GitHub Repository

Github is a form of Distributed Version Control (DVC). DVC is used so a student can work offline and in groups. A DVC can store files online so you can access them from anywhere.

Follow the below instructions to setup a Github repository.

1. Login to Github.
2. Press the **Create repository** button.
3. Give the repository a name.
4. Keep the repository public.
5. Press the **Create repository** button.

Result: You have a new Github repository open with nothing in it.

### Uploading a Resume to Github

1. Open Github Desktop.
2. Press the button labeled with the name of your new repository.
3. Press **Clone "repository name"**.
4. Choose a local path to store files on your computer.
5. Press **Clone**.

6. Press **Show in Explorer** or **Ctrl Shift F** hotkey.
7. Move your index.md file into the folder that opened.
8. Go back to Github Desktop.
9. Press **Commit to main**
10. Press **Publish branch**

Result: Your resume is stored in your online Github repository.

### Creating a Static Website using Github Pages

Github allows for the hosting of a static website for free through Github Pages. A student may choose to host a static website for a resume rather than using a PDF. The reason for this is it allows the resume to be updated seamlessly and not have interviewers looking at outdated PDFs.

Follow the below instruction to setup Github Pages

1. Open your repository on Github.com.
2. Press **Settings**
3. Press **Pages** on the sidebar.
4. Choose main as your source.
5. Press **Save**.
6. Press **Choose a Theme**.
7. Select a theme.
8. Press the **<> Code** button.
9. Go to _config.yml.
10. Copy everything after _theme:_.
11. Press **<> Code**.
12. Go to index.md
13. Press the **pencil** icon to edit the file.
14. Paste everything after *theme:*.
15. Press **Commit changes**.

Here is a gif of the process
![A gif showing how to make a static website using Github](gifs/FirstGif.gif)

Result: Your website is now hosted on Github pages with a proper theme. You can now access it at `https://username.github.io/repositoryName/` replacing username and repository name with your username and repositories name.

## More Resources

* [Markdown Tutorial](https://www.markdowntutorial.com/)
* [Andrew Etter's book _Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Resume Guide](https://umanitoba.ca/student/careerservices/media/Resume.pdf)

## Authors and Acknowledgements

* Gurtej Boparai

* Yucong Nie

* Jordan Unger

* Dean Pistorius

## FAQs
