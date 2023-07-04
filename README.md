<h1 align="center">
    <img alt="Full-Stack GitHub README" src="https://github.com/jonypeixoto/jonypeixoto/blob/main/assets/gitcores.gif" />
    <br>
    GitCores
</h1>

<h4 align="center">
 GitCores is a repository of the project involving Git, Git Bash, GitHub and Git Desktop that every programmer in the world should know on the internet.
</h4>

<br/> 

<p align="center">
  <a href="#information_source-repositories">Preview</a>&nbsp;&nbsp;&nbsp;• &nbsp;&nbsp;&nbsp;
  <a href="#warning-prerequisites">Prerequisites</a>&nbsp;&nbsp;&nbsp;• &nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-use">How to Use</a>&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>&nbsp;&nbsp;&nbsp;•&nbsp;&nbsp;&nbsp;
  <a href="#star2-author">Author</a>
</p>

##  :information_source: Preview

![App Screenshot](https://github.com/jonypeixoto/jonypeixoto/blob/main/assets/GIF-gitcores.gif)<br/>

<br/>

## :warning: Prerequisites

Follow the instructions in each folder in each README and if necessary check the official website for each documentation:

You should know about these technologies:

<br/>

- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS](https://www.w3schools.com/cssref/)
- [CSS3](https://www.w3schools.com/css/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [PHP](https://www.php.net/docs.php)
- [MySQL](https://www.mysql.com/)
- [Responsive Design](https://developers.google.com/search/mobile-sites/mobile-seo/responsive-design)
- [UX/UI](https://www.adobe.com/br/creativecloud/ui-ux.html)
- [Adobe XD](https://www.adobe.com/br/products/xd.html)
- [Adobe Photoshop](https://www.adobe.com/br/products/photoshop.html)

<br/>

## :information_source: How to Use

## Here, you will find the step by step to run this project
In this project, follow the commands:

<br/>
<br/>

This project aims to document my experiences with Git and make your life easier when using it. All the experiences I've acquired throughout my life as a programmer, computer engineer:

</br>

I divided this project into 3 parts:

<br/>

- THE ESSENTIAL GIT(LEVEL 1)
- MOVING FORWARD WITH GIT(LEVEL 2)
- TO INFINITY AND BEYOND WITH GIT(LEVEL 3)

<br/>

Study sources:

<br/>

- [GitHub Docs](https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources)

<br/>

- [FreeCodeCamp](https://www.freecodecamp.org/news/introduction-to-git-and-github/#:~:text=Git%20is%20a%20version%20control,folders%20easily%20on%20its%20platform.)

<br/>
<br/>

<h2>THE ESSENTIAL GIT:</h2>

<br/>
<br/>
<h3>Prerequisites:</h3>

<br/>

- Install Git and run the program [Git](https://git-scm.com/);
- Install [Xampp](https://www.apachefriends.org/pt_br/download.html);

<br/>

To avoid errors, we will do it in 3 simple steps to optimize your local repository connection with the online repository on GitHub:

<br/>

1) Start Git and go to your project folder directory:

<br/>

cd FOLDERPATH

<br/>

cd /d/Dev/cdftv/

<br/>

2) Launch VS Code from Git:

<br/>

code .

<br/>

NOTE: Git Bash does not accept the "CTRL + V" command when you are going to set your folder path. Then, use:

<br/>

SHIFT + INSERT

<br/>

The "cd" command (without the folders) will help you point to the directory of the folder you created.

</br>

3) After entering VS Code, go to SOURCE CONTROL or CTRL + SHIFT + G and click "INITIALIZE REPOSITORY"

<br/>

3.1) Go to Git Bash and configure the repository so that you can insert the local repository into the online repository:

<br/>

git remote add origin git@github.com:yournicknameongithub/yourrepositoryname.git

git remote add origin git@github.com:jonypeixoto/GitCores.git

3.2) In the Source Control menu of your VS Code, press Commit and Push and Okay!

<br/>

Check out your GitHub profile to confirm your VS Code changes.

<br/>
<br/>

OBSERVATIONS - COMMANDS OUTSIDE VS CODE ON GIT BASH OR POSSIBLE ERRORS:

<br/>
<br/>

1) The command verifies that the Git installation was successful and lists the main commands of the tool:

<br/>

git

<br/>

2) Put your name in the repository:

<br/>

git config --global user.name "YOUR NAME HERE"

<br/>

3) Check if the username was created successfully:

<br/>

git config --global user.name

<br/>

Git Bash will return your username confirming your registered username

<br/>

4) To check the actions log in Git Bash, launch the command:

<br/>

git status

<br/>

5) Do not forget to request that all hidden folders appear, if you are using Windows (so that you can see the .git folder created in your main folder.

</br>

[More about showing hidden Windows folders - official Microsoft website](https://support.microsoft.com/en-us/windows/show-hidden-folders-and-files-in-windows-97fbc472-c603-9d90-91d0-1166d1d9f4b5)

<br/>

6) To add your "index.php" (with quotes in the command below) to your repository, use:

<br/>

git add "index.php"

<br/>

7) If your project has several files, use the command to add all your project files directly to the repository:

<br/>

git add -A

<br/>

NOTE:

<br/>

8) Regarding Windows, Linux and MacOS terminals, there are some MacOS commands that are not the same as Windows as well as Linux.

<br/>

If you need to go back 1 directory from a folder:

<br/>

CD ../

<br/>
<br/>

9) The "clear" command (without the quotes) clears all code started from your prompt (or terminal that is currently being used)

<br/>

You can also know in detail the modifications based on the latest changes in the terminal. The diff will be reset as soon as you commit to your main repository.

<br/>

git diff

<br/>
<br/>

10) How does a commit work?

<br/>

Commit is a way to save it to your Git repository so it stays online and you can refer to it and show it to others if needed.

<br/>

11) To perform a commit, write (don't forget to do "git add -A" - without the quotes - to add all the files in your repository):

<br/>

git commit -m YOUR NAME PROJECT

<br/>

12) To check all the commits in all your branches, in detail in your terminal, that you performed in the repository you are working on (it is worth mentioning that your "git status" command - without quotes - will be reset every time you make a commit to the branch - the main repository with the official files that are in place in your application):

<br/>

git log

<br/>

Branch is the workspace where you currently work your code, it is where your main project is located. There are 2 types of branches: master branch (the main branch) and the secondary branch.

<br/>

13) How to create a branch? Just enter the code:

<br/>

git branch "BRANCHNAMEHERE"

<br/>

14) To check the branches you have already created or check the current branch, just enter:

<br/>

git branch

<br/>

15) To create a branch and/or be automatically directed to this secondary branch, simply enter:

<br/>

git checkout "BRANCHNAMEHERE"

<br/>

OBSERVATION

<br/>

16) With each new branch created, you must add your files again to that branch with the following command (check the inserted files with - git status):

<br/>

git add -A

<br/>

17) How to commit in other branches?

<br/>

In the same way that you commit to the master branch with the command:

<br/>

git commit -m YOUR NAME PROJECT

<br/>

18) How to connect GitHub to your Git?

<br/>

18.1) Create (generate) your github key so you can connect to Git
<br/>

To do this, just enter: github key on Google or your search engine and see it on the [official GitHub documentation website](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

<br/>

18.2) Go to settings in your GitHub profile, search for SSH and GPG keys and click on New SSH key (to insert your previously generated SSH key according to the instructions in the official GitHub documentation):

<br/>

I used the command below, but it can happen to be changed. So, follow the official GitHub documentation above that will help you in the best way:

<br/>

ssh-keygen -t ed25519 -C "YOUREMAILHERE"

<br/>

19)To add all files, including new files that you added directly to MASTER:

<br/>

19.1 - Step 1) git config --global alias.coa '!git add -A && git commit -m'

<br/>

19.2 - Step 2) git coa "YOURCOMMITNAMEHERE"

<br/>

19.3 - Step 3) You check up the commit on command: git log

<br/>

19.4) In case your commit was wrong and you want to go back to a specific commit from git log. Use the command:

<br/>

git reset --hard SPECIFICCODEOFTHECOMMIT

<br/>

Previously you need to go in command: git log

<br/>

Example: git reset --hard f9ae850d95dde3f90cd9b0b4721b648cde8b6cdf

<br/>

19.5) Step 4) You will connect these local applications to the remote GitHub repository:

<br/>

19.5.1 - Step 4.1) If you are in a repository, you need to restart the repository:

<br/>

19.5.2 - Step 4.1.1) git remote rm origin

<br/>

19.5.3 - Step 4.1.2) git remote -v

<br/>

19.5.3.1 - Step 4.1.3) git remote add origin URLGITHUBOFTHEPROJECT

<br/>

Example - to add the files to the online repository:

<br/>

git remote add origin https://github.com/jonypeixoto/GitCores

<br/>

19.6 - Step 4.1.4) To connect the local repository to the online repository:

<br/>



<br/>

19.7 - Step 4.1.5) To update your local repository from the online repository:

<br/>



<br/>

19.8 - Step 5) To update your online repository from the local repository:

<br/>

19.8.1 - Step 5.1) Commit to local repository and...

<br/>

git commit -m "YOURCOMMITNAME"

19.8.2 - Step 5.2)... and commit to the online repository

<br/>

Depending on the name of your main repository on GitHub, it may be called MAIN (new account on GitHub) or MASTER if you renamed it.

<br/>

git push origin master
<br/>
OR
git push origin main

<br/>
<br/>

20) To facilitate the connection of the local repository with the online repository, you can use [Visual Studio Code - VS Code](https://code.visualstudio.com/)

<br/>

20.1) Log into your GitHub account within VS Code (in the lower right corner there is an avatar icon written Sign in).

<br/>

20.2) Access the gear icon (in the lower left corner of your VS Code), look for the "settings" option and search for git:enabled in the search bar and check the option Git Enabled - Whether git is enabled.

<br/>

20.3) Access the Source Control icon or press the shortcut CTRL + SHIFT + G - it's the VS Code control panel to connect Git to GitHub. Click on "Download Git" or "reload VS Code" and at that moment it will install Git on your machine synchronizing with VS Code.

</br>

- MOVING FORWARD WITH GIT(in production)

- TO INFINITY AND BEYOND WITH GIT(in production)

<br/>
<br/>

<br/>

![](https://github.com/JonyPeixoto/jonypeixoto/blob/main/assets/wow.png)  

## :rocket: Technologies

<br/>

You need to understand the mechanisms that trigger each tool below:

<br/><br/>

- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS](https://www.w3schools.com/cssref/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [PHP](https://www.php.net/docs.php)
- [PHPMyAdmin]()
- [MySQL](https://www.mysql.com/)
- [Windows Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh)
- [Responsive Design](https://developers.google.com/search/mobile-sites/mobile-seo/responsive-design)
- [UX/UI](https://www.adobe.com/br/creativecloud/ui-ux.html)
- [Adobe XD](https://www.adobe.com/br/products/xd.html)
- [Adobe Photoshop](https://www.adobe.com/br/products/photoshop.html)

<br/><br/><br/>

## :memo: License
This project is under the MIT license. See the [LICENSE](https://github.com/jonypeixoto/full-stack-web2-projects/blob/main/LICENSE) for more information.

<br/><br/>

## :star2: Author

<img alt="Jony Peixoto" title="Jony Peixoto" src="https://github.com/jonypeixoto/jonypeixoto/blob/main/assets/Jony-Peixoto-Projects.jpg" height="100" width="100" />

Made with ♥ by Jony Peixoto :wave: [Get in touch!](https://jonypeixoto.com)

<br/>

<a href="https://www.jonypeixoto.com" target="_blank">
  <code><img alt="Jony Peixoto Official Website" height="30" width="130" src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white" /></code>
</a>

<br/>

### LIVES:

YouTube: [Jony Peixoto](https://www.youtube.com/@JonyPeixotoOriginal)
