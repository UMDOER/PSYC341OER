# PSYC341OER
## Table of Contents
* Introduction
* Contributors 
* Become a Contributor
* Navigating the Repository
* Making Changes

# Introduction

The goal of this project is to provide an open-source, ever-expanding body of information for PSYC341: Introduction to Memory and Cognition. This platform, Github, allows many users to contribute to the main site or make their own variations. Ideally, this site will provide a mix of written and multimedia information to encourage learning through several mediums.    

The site falls under Creative Commons Zero v1.0 Universa licensure. 

# Contributors
* Bob Slevc
* Camille Burns
* Sam Santomartino

# Become a Contributor
### Forking

The current site--called the "repository"--is the center for editing and branching. Changes to the main branch, or the "master" branch, will be pushed to the published site: https://umdoer.github.io/PSYC341OER/.

When editing, you can commit your changes to the master branch, or fork to a new seperate branch. Forking is essentially making a copy; editing your seperate branch will not affect the master branch. You will be able to access your site through the URL provided under the "Settings" tab:

<figure>
    <img src="https://UMDOER.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 11.54.38 AM.png" style="width:20%">
</figure>

For more information on how to fork, click [here.](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/working-with-forks)

### Pull Requests

To propose a change without editing directly, you can issue a pull request. This request will allow you to add comments and discuss the changes with collaborators before the edits are published. 

For more information on how to create a pull request, click [here.](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)


# Navigating the Repository

The repository is organized into several folders on the main page:

<figure>
    <img src="https://UMDOER.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 11.49.38 AM.png" style="width:20%">
</figure>

* **_data** holds the .nav page, which creates the sidebar of links
* **_pages** holds the multiple pages for each subject and is divided by subject
* **_sass** holds the _variables page, which dictages fonts and format
* **images** holds every image used on the site; it is necessary to upload images here before they can be used

Additionally, there are several lone pages:
* **.gitignore and Gemfile** have information about the current theme
* **LICENSE** has more information about Creative Commons Zero v1.0 Universa
* **README.md** is this!
* **_congig.yml** has information on the theme and layout
* **index.md** is the main page of the website

# Making Changes

### Editing in Markdown

Pages that end with **.md** can be edited using Markdown, an easy way of editing Github pages. Editing in markdown is simple; [this page](https://guides.github.com/features/mastering-markdown/) outlines the basics.

### Changing the Sidebar

If you want to add or delete a page from the sidebar, follow these steps:

**1)** Add a page to the **_pages** folder, or delete the selected page by clicking the trashcan icon in the top right corner:

<figure>
    <img src="https://UMDOER.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.23.31 PM.png" style="width:20%">
</figure>

**2)** In **_data**, go to navigation.yml. 

Each sidebar is organized in the same format:

<figure>
    <img src="https://UMDOER.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.35.55 PM.png" style="width:30%">
</figure>

For example, here is the beginning of the sidebar for the Sensation and Perception pages:

<figure>
    <img src="https://UMDOER.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.30.39 PM.png" style="width:20%">
</figure>

Which, when published, leads to this:

<figure>
    <img src="https://UMDOER.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.31.19 PM.png" style="width:20%">
</figure>

Therefore, when adding or deleting a page, you must also add or delete the code for that page in the sidebar. 

**3)** If your page is referenced in the Table of Contents on the **index.md** page, you must add or delete it there. 

### Adding Images

To add images to your .md page, follow these steps:

**1)** Upload your image to the **images** folder.

**2)** Insert your image using the following format:

<figure>
    <img src="https://UMDOER.github.io/PSYC341OER/images/Screen Shot 2021-01-02 at 12.41.50 PM.png" style="width:20%">
</figure>

* The **figure style** can be edited to change the alignment, margins, and size of the photo
* The **img src** is the URL, linking to the uploaded photo in the **images** folder
* The **fig caption** refers to the text underneath the photo
