
# Introduction to Git and GitHub

This workshop will introduce you to the basics
of Git and GitHub for tracking and sharing research work.
The lesson materials for this workshop are available at:

http://clemsonciti.github.io/git-workshop

and are adapted from the Software Carpentry
(https://software-carpentry.org/) curriculum.

## Setup

### Running a remote command line on your web browser

All work will be done on your web browser - no need to
install any additional software. 
You will enter commands remotely into the Palmetto cluster - the
University's high-performance computing (HPC) resource.
After the workshop, we will discuss how to install/use
the command-line on your own computer and OS.

To open a remote command-line on Palmetto:

1. Visit [palmetto.clemson.edu/jupyterhub](palmetto.clemson.edu/jupyterhub)
on your web browser

2. Log-in with your Palmetto account. If you don't have a Palmetto
account, you can log-in using a guest account. Ask the instructor
for credentials.

3. Once logged-in, click on **Start My Server**.

4. On the next page, use the default values for all options,
but change the **Walltime** to **4 hours**. Click on "Spawn".

5. You may have to wait a few seconds before seeing the next page,
Try refreshing the page if you see errors about "redirection".

6. Click on **New** (on the right) and then **Terminal** to open
a terminal.

## Summary of Basic Commands

| Command       | Action                                            |
| `git config`  | Configure username, e-mail address, editor, etc., |
| `git init`    | Initialize a repository                           |
| `git status`  | Show the status of a repository                   |
| `git add`     | Put files in staging area                         |
| `git commit`  | Save the staged content as a commit               |
| `git diff`    | Display differences between commits               |
| `git checkout` | Recover old versions of files                    |
| `git remote`  | Add a remote repository                           |
| `git push`    | Push changes in local repository to remote repository |
| `git pull`    | Pull changes from remote repository to local repository |
| `git clone`   | Copy a remote repository to create a local repository |

