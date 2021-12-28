# Snowball - Bot
 Want to contribute to this repo? Follow the steps below to set-up the project in your local system, making changes and making a pull request.

## How to contribute (overall process)

1. Fork the project, using the gray `Fork` button in the top right of this page
2. Make any changes in your forked repo
3. On this repo, click `Pull Requests` (which is the third option at the top of this page after the options `Code` and `Issues`) and raise a Pull Request by clicking the green `New Pull Request` button and selecting your fork from the right drop down field.

If you have a new feature or encountered a bug, You can raise an [Issue](https://github.com/Kira272921/snowball-bot/issues).

## How to clone repo and make changes locally after forking

- Click on the green `Code` button, then either the HTTPS or SSH option and click the icon to copy the URL. This will give you a copy of the project, so you can play around with it locally on your computer.

- Using Git on your local machine and paste in the URL. Do this to download the forked copy of this repo to your computer (Replace the mentioned field with your Github username).

```
  git clone https://github.com/yourGithubUsername/snowball-bot.git
```

- Switch to the cloned folder. This can be done with Gitbash.

```
  cd snowball-bot
```

- Make a new branch and checkout to that branch.

```
  git checkout -b <name-of-new-branch>
```

## Making desired changes

Now this is your copy of project. 
1. You can find the folder name `snowball-bot` in one of your local drives. Open that folder in your Code Editor/IDE.
2. Make the desired changes according to the issue that you have chosen to solve from the `Issues` section on the github repo.
3. Now, to be able see the changes that you have made in your forked copy of repo, follow the steps below.

## Getting changes to appear on forked github repo

- Stage your changes.

Note - the below command will add all the files to git. If you want to only add specific files replace the `.` with the name of the file

```
  git add .
```

- Commit the changes.

```
  git commit -m "<your-commit-message>"
```

- Check the status of your repository.

```
  git status
```

- The response should be like this:


```
--On branch <name-of-your-branch>
nothing to commit, working tree clean--
```

- Pushing your changes to GitHub.

```
  git push origin <name-of-your-branch>
```

In case you get an error message like the one below, its likely you forgot to fork the repo before cloning it. To fix this, its best to start over with the How to Contribute section above, and fork the project repo first.

```
--ERROR: Permission to Kira272921/snowball-bot.git denied to <your-github-username>.
fatal: Could not read from remote repository.
Please make sure you have the correct access rights and the repository exists.--
```

## Making a pull request

 On the GitHub website, navigate to your forked repo - on the top of the files section you'll notice a new section containing a `Compare & Pull Request` button!

- Click on that button and this will load a new page, comparing the local branch in your forked repo, against the main branch in the `snowball-bot` repo. 
  Note: A pull request allows your changes to be merged with the original project repo.

- Wait for your changes to be merged.

Hurray! You successfully made a contribution! 🎉

---

## Creating an issue in the repo

1. Navigate to [Issues page](https://github.com/Kira272921/snowball-bot/issues)
2. Click `New issue`
4. Select the category of the issue
5. Type a title of the issue 
6. Now ,the instructions to describe the issue will be mentioned there fill it accordingly
7. When you're finished, click `Submit new issue`.
