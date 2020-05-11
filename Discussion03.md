[Home](https://jennjoyce.github.io/learning-journal/)

# Revisions and the Cloud


## I am currently working in VS on my computer. I will attempt to A-C-P to Git with Module 3 Assignement.


## Cloning a repository from the Cloud to your machine:

1 Open GitHub and find your selected repository and copy it.  (There's a gree rectangle button that says: "Copy or Download")
2 Once you have your link open your terminal and find out where you are on the command line by using: `pwd`
3 Once you know where you are, use the `ls` command to show your files.
4 You can change directories by using `cd` into your desired directory
5 Then you use the command `git clone FILENAME.md` to clone your repository,
6 After your repository has been cloned, you can open it by using this command: `code .`
7 When you are done editing your repository, you will have to "save" or A-C-P to get your local repository back to GitHub.
8 Use the command `git status` to see if all the software recognizes that changes have been made.
9 In your terminal (or in the View mode of your VS), use the command: `git add FILENAME.md`
10 Some red words should pop up indicating that changes are made. At this point you can commit to changes or decline the changes.
11 To commit: `git commit -m` + "describe your changes here...essentially a little caption of what you are changing"
12 Some words will turn green 
13 Command: `git push origin master`
14 Command: `git status`
15 Hopefully all the words are black and you will see a message that is boring to read but is very important.  It should say: "nothing to commit, working tree is clean"
16 Pop over to your URL and see if your changes updated.  Sometimes updating can take a minute so don't stress.


## Other tidbits and factoids I learned from the video and Module 3:
*  Craig likes coffee, Craig does not like blisters. Break in your hiking boots well before you agree to eating lunch w/ the CEO of Codefellows. 
*  GitHub is similar to a shared Google drive among employees, a collection of people can access code files and make changes
*  A-C-P is a really fancy and complicated way of saving something on the Cloud. A-C-P means: Add, Commit, Push.
*  To make a check mark on MD use this: `[x]`
*  Delta V instructors are extremely fast and helpful!

## Comments/Questions/Concerns I hope to have answered in the next videos and classes:
*  What's the benefit of using VS on my computer vs working in the Cloud?
    *  Currently I think I prefer using the Cloud b/c I can push that little `preview` button and see immediate changes in how things looks. 
    *  Is there a preview button on VS code? I really want to see how things look before I commit to them. It's making me nervous not to see what the front side looks like. 

*  What happens if I use the cloud but I need to update my local files? 
    *  I am guessing this is where `pull`, `fetch`, and `merge` come into play?
*  What happens if you don't want someone messing w/ your code on Github? Do you just make your repository private? For instance I have a friend who works for a company that is in    a lawsuit over some open source software. They make software for the insurance and financial industry....Surely not everything is up for grabs? 



