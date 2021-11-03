## Applying Etter's Modern Technical Writing Principles to Host an Online Resume

## Purpose

The purpose of this README is to explain the practical steps of how to host and format a resume online while also relating these steps to the principles of technical writing described in Andrew Etter's book _Modern Technical Writing_.

## Prerequisites

* Markdown resume.
* [GitHub](https://github.com/) account.
* [Github Desktop.](https://desktop.github.com/)

## Instructions

I will be demonstrating a number of principles of technical writing as described in Andrew Etter's book _Modern Technical Writing_ by explaining how to host a resume online.

The main principles I will be demonstrating are as follows,

* Consistency.
* Using Markdown.
* Using Distributed Version Control.
* Using Static Websites instead of PDFs.

I will be showcasing consistency by keeping the formatting of these instructions as consistent as possible. Consistency is important as it allows a reader to know what to expect and properly follow along a reading without frustration.

Caution: These instructions are for Windows machines and may not be applicable for Mac or Linux based systems.

### Formatting a Resume in Markdown to be hosted online

Reasons for using Markdown include,

* Easily converted to HTML for online use.
* Lightweight.
* Widely used throughout the World.

A Markdown tutorial and resume guide can both be found in the More Resources section.

1) Create a resume using Markdown.

2) At the top of the file include, 

   ​	\---

   ​	permalink: index.html

   ​	theme:

   ​	\---

3) Save your resume as index.md.

Result: You will have a resume formatted in Markdown that is properly setup to host on a static website.

### Create a GitHub Repository

Github is a form of Distributed Version Control (DVC). DVC is used so a student can work offline and in groups. A DVC system can store files online so you can access them from anywhere. Github is widely used through out the computer science industry so we will be using that.

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
9. Press **Commit to main**.
10. Press **Publish branch**.

Result: Your resume is stored in your online Github repository.

### Creating a Static Website using Github Pages

Github allows for the hosting of a static website for free through Github Pages. A static website is a simple website that doesn't have any fancy code like javascript running in the background that updates the website dynamically. Static websites are lightweight and quick to edit. They can also be better than PDFs as you can update a website whenever you want but you can't update a PDF that is already stored on someone else's computer.

Follow the below instructions to setup Github Pages.

1. Open your repository on Github.com.
2. Press **Settings**.
3. Press **Pages** on the sidebar.
4. Choose main as your source.
5. Press **Save**.
6. Press **Choose a Theme**.
7. Select a theme.
8. Press the **<> Code** button.
9. Go to _config.yml.
10. Copy everything after _theme:_.
11. Press **<> Code**.
12. Go to index.md.
13. Press the **pencil** icon to edit the file.
14. Paste everything after *theme:*.
15. Press **Commit changes**.

Here is a gif of the process.
![A gif showing how to make a static website using Github](https://github.com/appleyat/resume/blob/main/gifs/First%20Gif.gif)

Result: Your website is now hosted on Github pages with a proper theme. You can now access it at `https://username.github.io/repositoryName/` replacing username and repository name with your username and repository's name.

## More Resources

* [Markdown Tutorial](https://www.markdowntutorial.com/)
* [Andrew Etter's book _Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Resume Guide](https://umanitoba.ca/student/careerservices/media/Resume.pdf)

## Authors and Acknowledgements

* Gurtej Boparai
* Yucong Nie
* Jordan Unger
* Dean Pistorius
* Timothy Appleyard

## FAQs

* Why is Markdown better than a word processor?
  * Markdown is better than a word processor because it can be easily converted to HTML for hosting online and is free to use. Word on the other hand you have to pay large fees to use and is very clunky to convert to HTML for online hosting.
* Why is my resume not showing up on my website?
  * Make sure your resume is named index.md and that permalink: index.html is at the beginning. This tells Github Pages to convert that page to html and host it. Also Github Pages sometimes takes awhile to upload, sometimes up to 20 minutes.
