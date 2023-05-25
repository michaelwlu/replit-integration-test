# replit-integration-test

This repository was created to test and document the steps involved in connecting a Replit project to a GitHub repository. 
 This integration is used in Code Nation's intro to web development curriculum for high-school students so that they can export their unit projects into a GitHub account.

(Updated May 2023)

1. Navigate to GitHub, sign in, and create a new repository, giving it a name that represents the Replit project that will be imported.
![](/screenshots/01-create-new-github-repo.png)

2. Copy the link ending in `.git`.
![](/screenshots/02-copy-git-link.png)

3. Navigate to Replit and the project to be exported.  In the left panel, under “Tools”, click “Git”.  This will bring up the Git tab in the middle or right panel.
![](/screenshots/03-open-git-tab-in-replit.png)

4. Click "Initialize Git Repository."
![](/screenshots/04-initialize-git-repository.png)

5. Click the gear icon to the right of “Repository” to access “Settings.”
![](/screenshots/05-git-tab.png)

6. Paste the `.git` link into the “Remote” field and save.
![](/screenshots/06-paste-git-link-and-connect-to-github.png)

7. Below that, under “Commit author” and “GitHub Account”, if not already connected, click “Connect to GitHub”. This will open up GitHub and ask for “Install & Authorize” permission, which should be granted.
![](/screenshots/07-install-and-authorize-integration.png)

8. Go back to the Replit project page and refresh it. If both the remote address addition and GitHub connection were successful, there should now be a button to “Publish branch as 'origin/main'.”
![](/screenshots/08-publish-branch.png)

9. Click this (multiple times if necessary) until a pop-up asking to “Pass GitHub Credentials” appears. Click “Confirm for this session.”
![](/screenshots/09-pass-credentials.png)

10. If successful, the Git tab should now reflect synchronization with the remote GitHub repository.
![](/screenshots/10-successful-synchronization.png)

11. Navigate to the GitHub repository page to confirm. Congratulations, your Replit project is now on GitHub!
![](/screenshots/11-synced-github-repo.png)


