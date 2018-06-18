---
layout: post
title: Part 2&#58; Editing Your Own Website
---

[Part 1 of this series covered setting up a default website through GitHub]({{site.baseurl}}/tutorial-part-1/). This post covers editing files on GitHub, one way to make the website truly your own.

### What This Post Covers

* Replacing the default text on a few pages
* Editing a file on GitHub
* Saving edits by making a *commit* to your *repository*.
* Uploading a picture

## Step 1: Edit the _config.yml file

The _config.yml file partly tells GitHub how to build your site (more on that later) and partly contains information displayed. We want to replace the default title of our site.

Click the _config.yml file to go to that file's information page. You can start editing by clicking the pencil icon, just above the file's contents to the right.

![GitHub Edit Button Screenshot]({{site.baseurl}}/images/2018-06-18-github-edit-button.png "GitHub Edit Button Screenshot")

Change the text next to name from "First Last" to what you want your site title to be. This can be anything, not just your personal name!

## Step 2: Save your edit.

*Commit* is a term that effectively means to save a change. *Commiting* a change to a *repository* helps keep a record of the many different versions your site will go through.

Scroll down to the bottom of a file when you are done editing to the *commit* options.

![Commit Screenshot]({{site.baseurl}}/images/2018-06-18-commit-screenshot.png "GitHub Commit Screenshot")

You can provide a description of the changes you've made, or accept the defaults. Click the green button to commit. It may take a minute for the site to update.

## Step 3: Upload an image

Navigate to the images folder, which already contains some files. Click the upload files button and choose an image on your computer to upload, then click the *commit* button just like edits. Make sure you have permission to use anything you put on your website! You're responsible for respecting the work others have done.

![Upload files Screenshot]({{site.baseurl}}/images/2018-06-18-upload-image.png "GitHub Upload Screenshot")

Underneath the hood, images displayed on a page are always linked to a file. [Look at the URL for the above screenshot]({{site.baseurl}}/images/2018-06-18-upload-image.png). Notice how it ends with a familiar pattern: /images/filename. Try to find the address for the image you just uploaded.

## Step 4: Fill out other parts of the _config.yml file

There are many other parts of the config file you may want to change. Go ahead and experiment with some of files. Perhaps your own social media? A custom avatar? Anything as long as you get some practice editing files!

## Step 5: Fill out the about.md file

This file controls everything on your about page. The default text is pretty lame, so let's replace it!

![About Markdown Screenshot]({{site.baseurl}}/images/2018-06-18-about-markdown-screenshot.png "About Markdown Screenshot")

