[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# Making your first contribution using the command line

## 1. Complete steps 1-3 in README.MD

Be sure you have completed steps 1 - 3 in the [README.MD](README.md) file.

## 2. Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

<img style="left" src="assets/fork.png" alt="fork this repository" width="200" />

## 3. Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the _copy to clipboard_ icon.

<img style="left"  src="assets/clone.png" alt="clone this repository" width="200" />

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/hacktoberfest_2020.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the hacktoberfest_2020 repository on GitHub to your computer.

## 4. Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd hacktoberfest_2020
```

Now create a branch using the `git checkout` command:

```
git checkout -b <add-your-new-branch-name>
```

For example:

```
git checkout -b add-alonzo-church
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## 5. Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## 6. Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## 7. Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> PR_ workflow that you'll encounter often as a contributor!

## Additional info:

[More info on git installation and setup](https://docs.github.com/en/github/getting-started-with-github/set-up-git)
