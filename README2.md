![Github cat waving logo](https://github.blog/wp-content/uploads/2024/05/Collaboration-LightMode-2-1.png?w=1200)

# How to Clone a Repository on GitHub

Cloning a repository from GitHub allows you to create a local copy of a project on your computer. Here’s how to do it:

## Prerequisites

* Git: Make sure Git is installed on your computer. You can download and install it from git-scm.com.
* GitHub Account: Ensure you have a GitHub account and are logged in.

## Steps to Clone a Repository
1. Find the Repository URL
    * Navigate to the GitHub repository you want to clone. For example, visit 
`https://github.com/username/repository`

    * Click on the green "Code" button located at the top right of the repository page.
    * Copy the repository URL from the dropdown. It will look something like 
`https://github.com/username/repository.git1`

2. Open Your Terminal or Command Prompt
    * On Windows, you can open Command Prompt or Git Bash.
    * On macOS or Linux, open the Terminal.
3. Navigate to the Desired Directory
    * Use the cd command to change to the directory where you want to clone the repository. For example:

``` javascript
cd path/to/your/directory
```
4. Clone the Repository
    *  In the terminal, type the following command and press Enter.
    *  Replace https://github.com/username/repository.git with the URL you copied in step 1.

``` javascript
git clone https://github.com/username/repository.git
```
5. Access the Cloned Repository
    * Once cloning is complete, navigate into the newly created directory:
``` javascript
cd repository

```