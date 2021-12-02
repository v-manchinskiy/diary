---
title: "Create New Hugo Theme With Bootstrap 5"
date: 2021-11-18T12:02:10+02:00
draft: false
tags: ["Hugo", "Bootstrap", "Tutorial"]
---

![How to Create New Hugo Theme](how-to-create-new-hugo-theme.jpg)

## Pre-requisites

To create a new Hugo theme from scratch you must have:

1. Installed Hugo on the local machine.
2. Your own working Hugo test site.

If it is not, you need [install Hugo and create a new Hugo site](/posts/create-new-hugo-site/).

## Get started

1. So, your Hugo site has the following basic folder structure:
![theme folder in Hugo structure](folder-structure.jpg)
2. In the Terminal tab go into your Hugo test site folder: `cd test-site` If you need to go up in the folder tree you can use the command `cd ..`
3. Now create a new theme with a name you like. In Your Terminal tab write the command: `hugo new theme my-theme`
![create a new hugo theme](create-new-hugo-theme.jpg)
4. Download Bootstrap 5 and unzip it. 
5. Copy, paste and rename the Bootstrap `scss` folder into `assets` directory in your theme.
6. Create `my-theme.scss` file in `themes/my-theme/assets/` directory.

Creating a Hugo Theme From Scratch described here: [Retrolog](https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/)

Samples of the design elements for my theme were taken from [Bootstrap](https://getbootstrap.com/docs/5.1/examples/)

Start Hugo server to view your website on localhost:
![hugo server command in terminal](hugo-server.webp)
