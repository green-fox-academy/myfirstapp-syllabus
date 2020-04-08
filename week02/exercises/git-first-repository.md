---
layout: default
---
# Your first repository

## Help

- [Questions to this exercise](http://askbot.greenfox.academy/questions/tags:first-repository/)

## Step by step

Run the downloaded GitHub Desktop application and sign in with your GitHub account

![GitHub Desktop sign in](../assets/my-first-repository/git-desktop-signin.png)

The repository seems to be a complicated word, but it is actually just a folder or directory. A special folder on your computer that will have a matching pair on GitHub. The two folders will have the same content, so if you create files and other folders in the repository, you will be able to sync the GitHub version of it so they will have the same contents again. These folders will be on the web too, so only put code of exercises and related images or files in them. And also they should not contain spaces and accent characters (`á`, `é`, `ž`, etc...) in their names (just like web url-s will not either). The best is to use the english alphabet and dashes `-` instead of spaces.

### Create a new repository and name it as `my-first-repository`

![GitHub Desktop new repo](../assets/my-first-repository/git-create-repository-1.png)

![GitHub Desktop new repo](../assets/my-first-repository/git-create-repository-2.png)

Now the repository (aka. the folder) is created on your computer. You can check the location and the `my-first-repository` directory should be there. It'll be empty or if you can see the hidden files, you'll see one hidden file: `.gitattributes`. (Maybe a hidden folder is there too, that's okay as well)

### Publish this repository to GitHub, untick 'Keep this code in private'!

![publish the repo](../assets/my-first-repository/git-desktop-publish.png)

### Visit [GitHub](https://github.com/)

- Sign in if it is necessary
- Check your fresh and new repository
- It should have 1 commit, and just an `.gitattributes` file

![github landing page](../assets/my-first-repository/git-github.png)

![first repo without text](../assets/my-first-repository/git-github-repository-1.png)

Now go back to the Github Desktop app, and open the repository's folder with Visual Studio Code.

![open with vscode](../assets/my-first-repository/git-desktop-vscode.png)

> Note: if this button is not there you can find the Open with Visual Studio Code in the Repository menu or clicking on the Current Repository and then right click on the my-first-repository

- Create a new file
  - Name it as `text.txt`
  - Type in your favourite movie's title and save it

In the Github Desktop app you can see the changes that were made to the previously synced version. So the changes compared to what's in the folder on GitHub.

![commit](../assets/my-first-repository/git-desktop-changes.png)

Commit the changes to the master

Push that commit to the origin

![push](../assets/my-first-repository/git-desktop-push.png)

Check your origin repository again (on GitHub in the browser), and make sure your text file is there

![first repo with text](../assets/my-first-repository/git-github-repository-2.png)

This last few steps are the way you can always sync the modifications or changes you've made on your computer to the GitHub version. Programmers do this regularly during a simple working day: commit changes and push them.
