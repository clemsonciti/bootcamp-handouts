
# Introduction to the Unix Shell

This workshop will introduce you to the basics
of the Linux/Unix shell (or command-line).
The lesson materials for this workshop can be found at:

http://clemsonciti.github.io/linux-workshop/

and are adopted from the Software Carpentry
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

### Downloading workshop data

The first commands you enter will download
some research data which we will analyze using the Unix shell.
Don't worry if you don't understand these commands,
we will go over them in detail through the course of the workshop:
Type in the commands exactly, and remember **not** to include
the dollar sign (`$`):

~~~
$ cd
$ wget https://github.com/clemsonciti/linux-workshop/raw/gh-pages/data/shell-novice-data.zip
$ unzip shell-novice-data.zip
~~~

## Summary of Basic Commands

| Action      | Files | Folders      |
|-------------|-------|--------------|
| Inspect     | ls    | ls           |
| View content| cat   | ls           |
| Navigate to |       | cd           |
| Move        | mv    | mv           |
| Copy        | cp    | cp -r        |
| Create      | nano  | mkdir        |
| Delete      | rm    | rmdir, rm -r |

