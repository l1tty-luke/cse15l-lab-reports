# **Lab Report 1 - Remote Access and FileSystem**
Hello!

![Image](https://tse1.mm.bing.net/th?id=OIP.8LZXRf13eYIi-g6nxSfghgAAAA&pid=Api&rs=1&c=1&qlt=95&w=157&h=97)

This is a tutorial for CSE 15L students for how to log into a course-specific account on **ieng6**.

## Step 1 - Finding your CSE15L Account

Your account username should be in the form `cs15lsp23zz` where the "zz"'s are specific to your account.

Follow this link: [Account Lookup](https://sdacs.ucsd.edu/~icc/index.php). If you've already reset your password, great! 

If not, here's a tutorial: [How to Change Password](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view?usp=share_link)

**Write down your password! You'll need it later!**

## Step 2 - Download Visual Studio Code

I personally already had this code editor for CSE 11, so I didn't need to download it. 

However, if you don't have it downloaded already here's the link: [VSCode](https://code.visualstudio.com/) and follow its directions.

After it's installed, it should look like this:

![Image](vscode1.png)

Mine may look different then yours because I changed VSCode's appearance based on my preferances.

## Step 3 - Downloading Git and Remotely Connecting

Download [here](https://gitforwindows.org/). Don't worry about changing any of the download options, just use the defaults.

Afterwords, open a new terminal in VSCode and click on the "+" at the top right of the terminal. There, a dropdown menu should open and then click on "bash"

![Image](gitbash.png)

Now, in the bash terminal, type: `ssh cs15lsp23zz@ieng6.ucsd.edu` If a message appears asking for confirmation to connect to host "ieng6.ucsd.edu", click YES. Then, type in your password.

![Image](bashlogin.png)

Now, two things will happen:

One:

![Image](loginsuccess.png) (Courtesy of Nathalie)

If this happens, continue to Step 5!

Two:

![Image](closedhost.png)

This is personally what happened to me the first several times. It's okay if this happens, because you just need to keep trying periodically and eventually it will work.

## Step 5 - Try some commands!

Try the commands: `cd`, `ls`, `pwd`, `mkdir`, and `cp`.

Example, `ls`, or "List", which lists the file and folders in the given path.

![Image](ls.png) (Courtesy of Luca)

From here, you can `cd` or "Change Directory", this can switch the current working directory to the given path. You can view the different commands and see examples from the worksheet from Week 1 lectures.

In order to sign out, type in the command `exit`. 

Thats the end of the tutorial!



