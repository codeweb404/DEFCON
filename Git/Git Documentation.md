<div align="center">
  <h1> DEFCON Git Documentation</h1>

<sub>Author:
<a href="https://www.linkedin.com/in/changun-jeong-765106277/" target="_blank">Changun Jeong,</a>
<a href="https://www.linkedin.com/in/sangyeon-moon-30212b2b8/" target="_blank">Kenneth Moon</a><br>
<small> First Edition: 27 July, 2024</small>
</sub>

</div>

## Table of Contents
- [What is Git?](#what-is-git)
- [Installing Git](#installing-git)
- [Configuring Git](#configuring-git)

## What is Git?

## Installing Git

To install Git, first head to the [Git downloads page](https://git-scm.com/downloads) and download Git in accordance with your operating system. 

## Configuring Git
First, configure your name and email. 
```
git config --global user.name "Yourname"

git config --global user.email "Youremail"
```
Next, configure your default editor. We recommend VSCode, but you can use any editor of your choice. 
```
git config --global core.editor "code --wait"
```
Finally, you have to configure a thing called autocrlf(which we don't understand exactly), so just copy and paste the following line onto your terminal depending on your operating system.
```
// Windows:
git config --global core.autocrlf true
// Mac or Linux:
git config --global core.autocrlf input
```
