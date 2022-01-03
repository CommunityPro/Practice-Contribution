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

<p>This is a preview of what the contribution looks like. <a href="https://github.com/CommunityPro/Practice-Contribution/blob/main/Contributors.md">Preview</a></p>
<a href="https://github.com/CommunityPro/Practice-Contribution/blob/main/Contributors.md"><img src="https://user-images.githubusercontent.com/62628408/147907346-1422e6a4-9616-4ac6-b4fd-d67952870a99.png"></a>

<h1 align="center">How to Contribute</h1>
<p align="center">Follow this tutorial to contribute.</p> 
 
 
### 1. Install git
<a href="https://git-scm.com/" target="_blank"><img src="https://git-scm.com/images/logo@2x.png" width="150px" alt="Git logo"></a>

Git is a version control system that is used for tracking changes in a file. Git is an imporant tool we'll be using to work on our github projects. 
If you want to learn how to install git without any errors, follow this <a href="https://git-scm.com/downloads">tutorial</a>, if not, install it and move on to the next step.

<br>

### 2. Fork this repository.
<img src="https://user-images.githubusercontent.com/62628408/147513059-5b617b8d-5fcb-4f8c-8563-17ba03aec352.png" width="100%">
Fork this repository using the fork button on the top right of this page, or the pencil icon on the right. 
This will create a copy of the project with your name.   

<br>

### 3. Clone your fork.

<img src="https://user-images.githubusercontent.com/62628408/147514033-5f96da6e-4318-4fe8-85ad-3176e1e01600.png" width="100%">
Cloning a project is simply taking that project and making a copy on your local machine. 
To clone this project, click the button on green that says code and on the drop down box, copy the URL of the project in the box and open up your git bash terminal and type in the following command `git clone "URL you just copied`

It should look like this:

```
git clone https://github.com/your_name/Practice-Contribution.git 
```
Where **"your_name"** will be your username on GitHub. Running this command will clone the project in your local machine.

<br>

### 4. Switch directory
Next switch into the folder of the repo we just cloned by typing this command in your bash terminal:

```
cd <repository name>
```

cd stands for "change directory" and the **repository name** is the name of the project repo: **practice-contribution**
therefore the command will be `cd practice-contribution`

<img src="https://user-images.githubusercontent.com/62628408/147890070-4a6413e6-15a5-4223-9fc3-bd94f1e5f708.png" widt="100%" alt="change directory screenshot of git">
You can see from the image above, we switched into a new directory called practice-contribution

<br>

### 5. Point origin branch to upstream 
We need to point our forked repo(origin) to the upstream(source) repo: To do that, type the command

```
git remote add upstream <URL of source repo>
```

```git remote add upstream https://github.com/CommunityPro/Practice-Contribution.git```

<br>

### 6. Create branch
Now we have successfully pointed our origin repo to upstream, we can now create a new branch which we'll be making our changes from.
To create a branch, type the command:

```
git checkout -b <branch name>
```

You can name the branch anything you want, but for the sake of this project, name your branch `add-yourname` (replace yourname with your own name). 
**E.g** `git checkout -b add-bruce` 

<br>

### 7. Make your changes.
Copy the code below, edit it with your own information and then paste it into the <a href="https://github.com/CommunityPro/Practice-Contribution/edit/main/Contributors.md">Contributors</a> file of this repo

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
<br>

### A few things to change:
- Replace the link with your own profile link 
```<a href="your link here"></a>```


- Right click on your github profile image and copy the image link and paste inside the `img` tag. Leave the `width=""` property

```html
<img src="your profile image link here" width="100px">
```

Just go to your GitHub profile page to get your profile image and link.

<img src="https://user-images.githubusercontent.com/62628408/147896530-f94c17f7-f064-4e8d-8bc1-af2c1f63559d.png" width="100%" alt="profile_page">

- Repalce the sub tag with your own name.

```html
<sub>Your Name</sub>
```

Then save your changes. 

<br>

### 8. Make a commit
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

Now we can write our commit message.

```
git commit -m 'Add bruce wayne'
```

Change Bruce Wayne to your own name.

<br>

### 9. Push changes to GitHub
Now we have sucessfully added our profile, we can now push the changes to GitHub. Use the command below to do that.

```
git push origin <branch name>
```

Replace the `<branch name>` with the name of the branch you created earlier. E.g `git push origin add-bruce`. 
  
Our changes should get pushed to the main repository and we can now do a pull request.
  
<br>  
  
### 10. Make a pull request(PR)
Now when you check the repo your forked, you should see the changes we just pushed to GitHub

<img src="https://user-images.githubusercontent.com/62628408/147897806-bfeeb6a0-9370-47e4-81be-1e735dda402d.png" alt="pull_request">

<br>

- Next click the `compare and Pull request` button which will open up the pull request in a new tab.
<img src="https://user-images.githubusercontent.com/62628408/147908216-86212e5a-6ba4-4d77-9815-1395be82e6ec.png" width="100%" alt="open pull request">

<br>

- Guidelines on how to add your profile will be automatically pre-populated for you, follow the instructions and fill in the right details and click create pull request.
<img src="https://user-images.githubusercontent.com/62628408/147913633-a841c880-5b05-4cbd-a05e-8d715a4069e1.png" width="100%" alt="create-pull-request">

You have successfully made a pull request(PR) the standard way for most GitHub projects. Congratulations! 🤩
Just sit back and relax as your changes gets merged immediately.
    
Thank you for taking the time to check out this tutorial, do you need any help, question or feedback, or do you find any step in this tutorial confusing, feel free to contact any of the repo managers on our <a href="https://github.com/CommunityPro/Practice-Contribution/discussions/15" target="_blank">discussions</a> to drop your questions and we'll attend to you as soon as possible. 

<img src="https://user-images.githubusercontent.com/62628408/147913211-e2e7c011-e196-4255-9cec-bed3f6a65813.png" width="100%" alt="motivational banner">
