# The Terminal (Bash)

> The guide will use **\*nix** to refer to both **Linux** and **Unix(Mac)**.

> Note that this is a guide for the **Bash** version of the terminal.
> On **\*nix**, it is likely that you are already using bash.
> On **Windows**, using the native terminal may not always work.
> Instead, use **Git Bash** that was installed with Git.

## File paths

The terminal uses file paths quite a bit, so it is important to understand how to use them.

The **root directory** is the parent directory that contains your entire file system of your computer. On **\*nix**, it is `/` and on **Windows**, it is `C:/`

The **working directory** is the current directory the terminal is operating in. You can refer to it as `./`.

An **absolute path** is the full path from the **root directory**. For example: `/home/adrian/Repos/test/.gitignore`.

A **relative path** is relative to the **relative directory**. It starts directly with the name of the file or sub directory. For example: `test/.gitignore`.

The **home directory** is the directory the terminal will start in. On **\*nix**, it is likely `/home/<username>`. On **Windows**, it is `C:/Users/<username>`. You can reference your home directory as `~/` from anywhere else in the file system.

You can refer to the **parent directory** of the **working directory** as `../`.

## Navigation

To view the absolute path to the working directory, run `pwd`.

To view the contents of the working directory, run `ls`. If you want to include hidden files, run `ls -a`.

To navigate to a new directory, run `cd <directory name>`. For example, `cd ~/` will navigate to your home directory from any where in the file system, and `cd ../` will navigate one directory up the tree.
