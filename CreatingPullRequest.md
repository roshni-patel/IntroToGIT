# Creating Pull Request

A pull request is how you combine all of the changes from every team member into the project. This quick exercise will help you get familiar with creating pull requests, reducing merge conflicts and divide the work effectively.

## Step by step

The steps for Windows and MacOS are different.

### MacOS

1. Open a terminal window
2. change to folder where you cloned IntroToGit repository
3. run "git pull" to get the latest changes
4. In VSCode open the project
5. Edit the file named edit_this_shared_file.txt
6. Save the changes
7. Click on the git menu icon on the left
8. Click the + icon next to edit_this_shared_file.txt
9. Enter a commit message at the top
10. Push the changes to github by clicking sync
11. Open a browser and go to your github page
12. At the top, click "Pull requests"
13. Click the green "New Pull Request" button to create a pull request
14. Click create pull request button

At this point, a new pull request has been created. The team lead will approve the changes. Each team member should create a pull request and the team leader will approve them.


### Windows

1. Click the windows icon
2. type "powershell" and start it
3. change to folder where you cloned IntroToGit repository
4. run "git pull" to get the latest changes
5. In VSCode open the project
6. Edit the file named edit_this_shared_file.txt
7. Save the changes
8. Click on the git menu icon on the left
9. Click the + icon next to edit_this_shared_file.txt
10. Enter a commit message at the top
11. Push the changes to github by clicking sync
12. Open a browser and go to your github page
13. At the top, click "Pull requests"
14. Click the green "New Pull Request" button to create a pull request
15. Click create pull request button

### Approve PR

This step is done by the team lead or anyone with permission to approve pull requests.

1. Open the github page
2. Click on Pull Requests
3. Select the pull request to view the details
4. Click merge to merge the changes and provide a comment
5. Click confirm merge
6. Click Code at the top menu and refresh the page

## Conflicts

1. if multiple people changed the same file, there could be merge conflicts. The pull request will show any conflicts
2. resolve the conflicts before merging the changes

## Updating your fork

An important part of GIT is getting the latest code from the main. The easiest way to do this is with GIT command line.

1. Open a terminal in MacOS or powershell in Windows
2. change to folder where the repository is located
3. run git pull https://theURLWhereTheLatestCodeLives
4. View the changes in VSCode to verify you have the latest

## Best Practices

1. alway get the latest code with git pull before pushing the changes to github
2. try to update your clone with recent changes
3. when you need to work on the same file as someone else, have a quick chat with your teammate to keep each other in sync
