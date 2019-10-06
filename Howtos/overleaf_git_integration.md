# Integrating git with overleaf

There are multiple ways to have git integration. First we describe the case where you are using overleaf for your thesis:

There are two ways to have git integration with overleaf. 
1. **Linking overleaf account  to Github:**
- Log into your overleaf account and go to the thesis project. Your screen should look like the following:


- In the upper left corner, click on the menu button, it should bring up side bar.

![ ](/images/1.png)

- Around the middle of the side bar, there should be three options under the heading sync, Dropbox, git, github. 

![ ](/images/2a.png)

- Click on Github. It should trigger a popup window with button 'Link to your Github account'. Click on it. It should open a new window where you should be able to log into your github account.

![ ](/images/5a.png)

- Log into your github account, and you will see 'Authorize overleaf' button. Clicking on the buttong gives overleaf the access to your public and private repositories. In case you are not comfortable with that, please see the secodn method with which you can connect github and overleaf. If you are okay, please click on the button to link github and overleaf.



- You will be taken back to overleaf where you will see "create a Github repository" button

![ ](/images/8a.png)

- If you want to contribute your thesis to ship of thesis, you will need to make the repository public.

![ ](/images/9a.jpg)

- You can always make a private repository public but making a public repository, private is not allowed.

2. **Using git with overleaf** If do not want to give overleaf access to your github account, you can still use all the editing on overleaf and push the changes to github. Following are the steps to acheive this:
- Log into your account on overleaf and click on the menu, it should bring up a side bar.

![ ](/images/1.png)

- Around the middle of the side bar, you will see the button 'git' under the heading 'Sync'. Click on it.

- It should bring up a pop up window that give you the command you will need to run on your computer terminal. Copy the command.

- Now, the following steps depend on the OS you have:

For linux/MacOS:

    open the terminal and `cd` into the folder where you would like the repository and paste the command.

For windows:

     If you do not have git bash installed, then you will need to inst all it first. You can get it here.

    ```https://git-scm.com/download/win```

    - After installation, open the git scm ad run the command that you copied from overleaf.

- You now have the git repository for your project on overleaf. You can refer to [git guide](Resources/git_guide.md) to learn, how to keep your local repository insync with overleaf.

