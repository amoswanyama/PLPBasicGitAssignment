Task 1: GitHub Repository Creation
Log in to GitHub:

Visit GitHub and log into your account.
Create a New Repository:

Click on the "+" sign in the upper-right corner and select "New repository".
Enter a repository name (e.g., "PLPBasicGitAssignment").
Optionally, add a description.
Select "Public" or "Private" as per your preference.
Check the box to "Initialize this repository with a README".
Click on "Create repository".
Task 2: Local Setup
Local Folder Setup:

Create a new folder on your local machine. You can name it "PLPBasicGitAssignment".
Git Initialization:

Open a terminal or command prompt.
Navigate to the folder you created (cd path/to/PLPBasicGitAssignment).
Initialize a new Git repository by running:
bash
Copy code
git init
Connecting to GitHub:

Link your local repository to the GitHub repository you created in Task 1. Replace <repository-url> with your repository's URL (you can find this on the GitHub page of your repository):
bash
Copy code
git remote add origin <repository-url>
Task 3: Making Changes
Create a File:

Inside your local folder (PLPBasicGitAssignment), create a new text file. You can name it hello.txt.
Add a simple text message to hell.txt, for example:
Copy code
Hello, Git!
Committing Changes:

Stage the changes (add hello.txt to the staging area):
bash
Copy code
git add hell.txt
Commit the changes with a descriptive message:
bash
Copy code
git commit -m "Add hell.txt with a greeting"
Task 4: Pushing to GitHub
Pushing to GitHub:
Push the committed changes from your local repository to your GitHub repository's main branch (main or master depending on your GitHub repository settings):
bash
Copy code
git push -u origin main
You might be prompted to enter your GitHub username and password/token for authentication.
Task 5: Verification
Verify on GitHub:
Visit your GitHub repository in a web browser.
Confirm that the hello.txt file is present.
Check that your commit message ("Add hell.txt with a greeting") is visible in the commit history.
