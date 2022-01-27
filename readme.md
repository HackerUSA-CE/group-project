# Hey! Let's learn about GitHub commands! 
ontributed to by Joseph Lee

## Follow this sequence in order to correctly fork and clone this repository:

1. Fork the repository via the fork button at the top left of the repository page
2. Click the code button *making sure* that you're using your own personal forked link.
3. Head back to your own terminal and navigate to the folder where you'd like to save this repository on your local machine
4. Use the `git clone` command, followed by the personal link that was created with your fork like this: `git clone https://github.com/my_github_username/personal_link`

**If you followed all these steps correctly, you should now have your own personal version of this repository associated with your own personal GitHub account.**


## When you have your own personal repository set up, follow this sequence in order to make, stage and save changes to your repository using GitHub commands:

1. Make a change within your repository. (Something as small as a comment is sufficient to create a change)
2. Then make GitHub aware of your change by running the command `git add -A`. This will **stage** all the changes you've made in your repository.
3. Make sure that GitHub is aware of your change by running the `git status` command. If your changes were added successfully by GitHub, you should a log of the changes you made in your console. 
4. Once you've confirmed that GitHub is aware of your staged changes, use the command `git commit -m` followed by a descriptive commit message in order to save your changes.
5. Now that your changes have been saved, you can move them to the main branch of your repository and make them official. In order to do this used the command `git push origin main`. This will make the version of your repository saved on GitHub.com identical to the version on your local machine, including your new changes. 
6. If there are changes to the repository which have been pushed to main, but don't exist on your local machine yet, you can pull them down to your local machine by running the command `git pull origin main` or more simply `git pull`.

**That's all! This is all it takes to use GitHub to save progress on your projects!**

Azhar was here.
