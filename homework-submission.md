#Instructions for Submitting Homework

Homework and labs will each have their own repository.  These repositories will usually live in the `sf-wdi-27-28` GitHub organization.

Each night, you'll be asked to submit pull requests to one or more repositories.  Check your class's schedule every day for links to the homework for each night. 

## Fork and Pull Request Workflow


1. Create a fork of the class version of a repository by clicking "Fork" on the top right. Make sure you're starting from the class version linked in the schedule.

  ![GitHub "fork" button screenshot](https://cloud.githubusercontent.com/assets/7833470/10625501/b15a2bee-7758-11e5-8b12-2c84b785801b.png)

2. Forking creates a copy of the original class repo on your own GitHub account. You'll see a screen like this while GitHub is forking the repo. 

  ![GitHub fork waiting screen screenshot](https://cloud.githubusercontent.com/assets/7833470/10625502/b422f2e8-7758-11e5-8cf1-09ae4fd7d946.png)

3. Now you have your own copy of the repo! GitHub even redirects you to your new copy on your account! Make sure you're on your GitHub account, and copy the "clone URL" from the top.

  ![GitHub clone URL screenshot](https://cloud.githubusercontent.com/assets/3010270/13687431/17d1d2e6-e6d0-11e5-8a5f-9f1575f03aa9.png)

4. Use the "clone URL" to clone the repo onto your local machine.  Cloning takes a remote repository and makes a local copy.  Start by opening up your Terminal and navigating to your `~/wdi` directory. Then run the following commands, copying and pasting in the correct clone url instead of <clone-url>.  


  ```zsh
  ➜  cd ~/wdi
  ➜  git clone <clone-url>
  ```

5. You should now have a copy of the repo inside your `~/wdi` directory! Change directories into the repo you cloned, and complete the tasks from the homework instructions. 

1. Remember to commit your local changes as you go, and check `git status`!

  ```
  ➜  git add <filename>

  ➜  git commit -m "adds <filename>"
  ```


## Creating Pull Requests


When you're ready to submit your homework (and it's okay if you only have a partial solution, we still want to see it!), you need to push your changes to github and create a pull request:


2. Make sure you've added, committed, and pushed all your updates to your fork of the repo on GitHub. 

    ``` bash
    git push origin master # push your changes to your remote repo
    ```

7. Once you're done with the assignment and have committed and pushed ALL of your changes to GitHub, it's time to make a pull request back to the original repo. Go to your forked copy of the repo on GitHub, and click the "Pull Request" button.

  ![pull request button screenshot](https://cloud.githubusercontent.com/assets/3010270/13687969/7ed9d38c-e6d3-11e5-9510-ac0fbf1f22e9.png)

8. GitHub takes you to a new view and asks if you want to create the pull request. Add this information to the pull request:

	Title: w01 d01

	Description:
		comfort: 3/5
		completeness: 4/5
		Here are my thoughts on how the homework assignment went....



1. Click the green button, and that's it - you've now created a pull request to submit the homework or lab!

  ![screen-shot-2015-10-20-at-17 25 49](https://cloud.githubusercontent.com/assets/7833470/10625507/bc97d38a-7758-11e5-8fe9-e4846e06e454.png)

