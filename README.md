<h1 align="center">Practice Contribution</h1>

<p align="center">
<img width="110px" height="100%" src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white">
<img width="130px" height="100%" src="https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#white">
<img src="https://forthebadge.com/images/badges/built-by-developers.svg">
<img src="https://forthebadge.com/images/badges/built-with-love.svg">
<img src="https://forthebadge.com/images/badges/ctrl-c-ctrl-v.svg">
<img src="https://forthebadge.com/images/badges/open-source.svg">
</p>



<p align="center">This repo is dedicated to helping individuals contribute to open source for the first time.</p>
<p align="center">Before you contribute, read the following <a href="">Contribution Guidelines</a> before making a pull request(PR). If you have any questions or assistance, you can reach out to the repo maintainers and administrators <a href="">here</a></p>

<br>

<!-- Image of what the contribution looks like -->
<p>This is a preview of what the contribution looks like. <a href="https://github.com/CommunityPro/Practice-Contribution/blob/main/Contributors.md">Preview</a></p>
<a href="https://github.com/CommunityPro/Practice-Contribution/blob/main/Contributors.md"><img src="https://user-images.githubusercontent.com/62628408/146686703-e1ee2159-ccfa-4989-92f9-6471feae19fa.png"></a>

## ⚙️ How to Contribute
<p>Follow this tutorial to contribute.</p>

## 1. Install git.
Git is a version control system that is used for tracking changes in a file. Git is an imporant tool we'll be using to work on our github projects. 
If you want to learn how to install git without any errors, follow this <a href="https://git-scm.com/downloads">tutorial</a>, if not, install it and move on to the next step.

## 2. Fork this repository.
Fork this repository using the fork button on the top right of this page, or the pencil icon on the right. 
This will create a copy with your name. 

<br>

<img src="https://user-images.githubusercontent.com/62628408/147513059-5b617b8d-5fcb-4f8c-8563-17ba03aec352.png" width="100%">

## 3. Clone your fork.
Cloning a project is simply taking that project and making a copy on your local machine. To clone this project, click the button on green that says `code` and on the drop down box, copy the URL of the project in the box, and open up your git bash terminal and type in the following command: `git clone <URL you just copied>`

It should look like this:

```
git clone https://github.com/Evavic44/Practice-Contribution.git 
```
which will clone the project in your local machine.

<br/>
<img src="https://user-images.githubusercontent.com/62628408/147514033-5f96da6e-4318-4fe8-85ad-3176e1e01600.png" width="100%">

## 4. Switch directory
Next switch into the folder of the repo we just cloned by typing this command:
```
cd <repository name>
```
cd stands for "change directory" and the `<repository name>` is the name of the project repo. E.g **practice-contribution**

## 5. Point upstream branch to origin
```
git remote add upstream <URL of main repo>
```

We need to point our forked repo to the origin repo: where origin repo is the URL of the original repo we forked E.g `git remote add upstream https://github.com/CommunityPro/Practice-Contribution.git`

## 6. Create branch
In other to start making our changes, we need to create a new branch to work from.
```
git checkout -b <branch name>
```

You can name the branch anything you want, but for the sake of this project, name your branch `add-yourname` (replace yourname with your own name). E.g `git checkout -b add-bruce` 

## 7. Make your changes.
Copy the code below, edit it with your own information and then paste it into the <a href="https://github.com/CommunityPro/Practice-Contribution/edit/main/Contributors.md">Contributors</a> file of the **Practice Contribution** repo

```html
<!-- Start of column-1 -->
<td align="center">
  <a href="https://github.com/evavic44">
    <img src="https://avatars.githubusercontent.com/u/62628408?v=4" width="100px"> <br/>
    <sub>Victor Eke</sub>
  </a>
</td>
<!-- End of column-1 -->
```


### A few things to change:
- Replace the link with your own profile link 
```<a href="your link here"></a>```

- Right click on your github profile image and copy the image link and paste inside the `img` tag. Leave the `width=""` property

```html
<img src="your profile image link here" width="100px">
```

- Repalce the sub tag with your own name.

```html
<sub>Your Name</sub>
```

Then save your changes. 

## 8. Make a commit
Now we're done adding our profile, we need to make a commit to save that file added.
on the git bash terminal, type

```
git status
```
This will show us a list of all changes made.

Next do a git add .(period) which means, add every changes made.
```
git add .
```

<!--Screenshot of git add .-->

Now we can write our commit message.

```
git commit -m 'Add bruce wayne'
```

Change Bruce Wayne to your own name.

## 9. Push changes to GitHub
Now we have sucessfully added our profile, we can now push the changes to GitHub. Use the command below to do that.

```
git push origin <branch name>
```

Replace the <branch name> with the name of the branch you created earlier. E.g `git push origin add-bruce. 
  
Our changes should get pushed to the main repository and we can now do a pull request.
  
  
## Make a pull request
<!-- Screenshot of PR -->
- Click the PR button and click `create pull request`
- Guidelines on how to add your profile will be automatically pre-populated for you, follow the instructions and fill in the right details and submit.
  
You have successfully made a pull request(PR) the standard way for most GitHub projects. Congratulations! 🤩
Just sit back and relax as I merge you changes immediately.
  
Thank you for taking the time to check out this tutorial, do you need any help, question or feedback, or do you find any step in this tutorial confusing, feel free to contact any of the repo managers on our <a href="https://github.com/CommunityPro/Practice-Contribution/discussions/15" target="_blank">discussions</a> to drop your questions and we'll attend to you as soon as possible. 

 
