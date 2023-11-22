Contributing  on our open source projects
You can contribute to our open source with these through these guildlines
Visit the Repository:
Go to the GitHub page of our open-source repository you want to fork. The repository's URL will typically be in the format https://github.com/username/repository.
Find the "Fork" button:
Look for the "Fork" button in the upper right corner of the repository page. Click on it
To Fork the Repository
A dialog will appear, asking where you want to fork the repository. 
GitHub will now create a copy of the repository under your account. This process may take a moment, so be patient
Once the forking process is complete, open your forked repository on GitHub. Click on the "Code" button, and copy the URL of your repository
Open a terminal on your local machine and navigate to the directory where you want to clone the repository
You can clone using this format "git clone https://github.com/your-username/repository.git"
Ensure You replace your-username with your GitHub username and repository with the name of the repository

Configure Remote Upstream:
To keep your fork synced with the original repository, you should set up a remote named "upstream." Navigate to your local repository directory using the terminal.
Using the "cd" command Eg. cd "repository name"
Add the original repository as the upstream remote
Using this format "git remote add upstream https://github.com/original-username/original-repository.git"
Ensure you replace original-username with organization's name that owns the original repository and original-repository with the name of the original repository
Verify Remotes:
Confirm that the remotes are set correctly by running:
Using this format "git remote -v"
Make Changes and Create Pull Requests:
Now, you can make changes to your local copy of the repository. Create a new branch, make changes, commit them, and push the changes to your fork.
Ensure you follow this format 
git checkout -b feature-branch
# Make changes
git add .
git commit -m "Description of changes"
git push origin feature-branch
