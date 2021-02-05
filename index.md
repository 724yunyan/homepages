																## Welcome to Cruiser World##
Before using this app, you need a github account and a respo.
follow this step:
					
Step 1: Set up a GitHub account
	https://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github-create-github-account.html
	You will need a GitHub account to create a GitHub repository where the revision will be stored. If you already have a GitHub account, 
	skip ahead to Step 2: Create a GitHub repository.
	Go to https://github.com/join.
	Type a user name, your email address, and a password.
	Choose Sign up for GitHub, and then follow the instructions.
Step 2: Create a GitHub repository
	https://docs.aws.amazon.com/codedeploy/latest/userguide/tutorials-github-create-github-repository.html
	You will need a GitHub repository to store the revision.
	If you already have a GitHub repository, be sure to substitute its name for CodeDeployGitHubDemo throughout this tutorial,
	and then skip ahead to Step 3: Upload a sample application to your GitHub repository.
	On the GitHub home page, do one of the following:
	In Your repositories, choose New repository.
	On the navigation bar, choose Create new (+), and then choose New repository.
	In the Create a new repository page, do the following:
	In the Repository name box, enter CodeDeployGitHubDemo.
	Select Public.
	Note
	Selecting the default Public option means that anyone can see this repository. 
	You can select the Private option to limit who can see and commit to the repository.
	Clear the Initialize this repository with a README check box. 
	You will create a README.md file manually in the next step instead.
	Choose Create repository.
	Follow the instructions for your local machine type to use the command line to create the repository.
	Note
	If you have enabled two-factor authentication on GitHub, 
	make sure you enter your personal access token instead of your GitHub login password if prompted for a password. For information, 
	see Providing your 2FA authentication code.
Step 3 get the token 
	https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token