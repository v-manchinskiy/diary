---
title: "How To Create New Hugo Site"
date: 2021-11-19T20:01:56+02:00
draft: false
tags: ["Hugo", "Tutorial"]
---

## ✔️ Preparing to create a new site

Instal Hugo Extended last version as stated here: [Hugo Docs](https://gohugo.io/getting-started/installing/).

Below I describe my version of this process **for Windows 10 users**.

1. Go to the Hugo releases page: [GitHub](https://github.com/gohugoio/hugo/releases). 
2. Find and download the latest release of **Hugo Extended** for your operating system, the 32-bit or 64-bit file depending on whether you have 32-bit or 64-bit Windows.
3. Move the dowloaded ZIP file into your Hugo bin folder: `C:\Hugo\bin` and extract it into the current folder. Now you're supposed to have three new files here: `hugo` (executable), `LICENSE`, `README`.
![extract zip in hugo bin](extract-hugo-bin.jpg)
4. Add Hugo to your Windows PATH settings:
    - Right click on the Start button.
    - Click on System.
    - Click on Advanced System Settings on the left.
    - Click on the Environment Variables… button on the bottom.
    - In the User variables section, find the row that starts with PATH (PATH will be all caps).
    - Double-click on PATH.
    - Click the New… button.
    - Type in the folder where `hugo.exe` was extracted, which is `C:\Hugo\bin` if you went by the instructions above. The PATH entry should be the folder where Hugo lives and not the binary. Press Enter when you’re done typing.
    - Click OK at every window to exit.

👍 So, all the preliminary preparations are done.

## 💡 Now you will create a new Hugo site

Run [VS Code](https://code.visualstudio.com/) app. In Terminal tab write: `hugo new site hugo-test` . Words "hugo-test" you can replace with your own site name.

![create new hugo site](create-new-site.jpg)

Further click "Enter".

✨🎓 Get your congratulations 😊👍:

![new hugo  site was created](create-new-site-2.jpg)

Your new Hugo site was created in a moment!

## ➕ Create new GitHub repository for existing Hugo site local folder

1. Run [GitHub Desktop](https://desktop.github.com/) app, click "File"->"Option" and connect to you GitHub account.
![github desktop options](github-desktop-options.jpg)
![github desktop account](github-desktop-account.jpg)
2. On the top left corner, click "File"->"Add local repository"
![add to gitgub repository](add-repository.jpg)
3. In modal dialog set "Local path" to your new Hugo site folder by clicking "Choose..." button. Then click to link "create a repository" (don't click "Add repository" button).
![add new Hugo site to github](add-repository-2.jpg)
4. Publish new repository to GitHub by clicking on "Publish repository" button and confirmation in the next dialog.
![publish new repository on GitHub](publish-repository.jpg)