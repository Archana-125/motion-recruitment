 Create a new branch named “feature-gcp-setup.”
Ensure You Are on the main Branch and Up-to-Date:

Update your main branch to ensure you have the latest changes.
git checkout main
git pull origin main
Create the New Branch:

Create and switch to the new branch named feature-gcp-setup.
git checkout -b feature-gcp-setup
b. Add a file named “gcp-setup.md” to this branch.
Create the New File:

Create a file named gcp-setup.md in your project directory.
touch gcp-setup.md
Document the Steps Required:

Open gcp-setup.md in a text editor and document the following steps:

Steps to Create a GCP Account:

Visit the GCP Website.
Sign Up for Google Cloud.
Verify Your Account.
Set Up Billing Information.
Steps to Set Up a Google Compute Engine Instance:

Log In to the GCP Console.
Navigate to the Compute Engine section.
Click on "Create Instance."
Configure the Instance:
Enter instance name.
Choose machine type and region.
Configure other settings as needed.
Set Up Firewall Rules to Allow SSH.
Review and Create the Instance.
Steps to Deploy a Sample Python Script:

Connect to Your GCE Instance via SSH.
Update and Install Necessary Packages (e.g., Python).
Create the Python Script (e.g., add_two_numbers.py).
Run the Python Script.
Save the changes to gcp-setup.md.

c. Commit your changes with a clear message.
Stage the New File:

Add the new file to the staging area.
git add gcp-setup.md
Commit the Changes:

Commit the changes with a descriptive commit message.
git commit -m "Add gcp-setup.md with steps to setup GCP account, GCE instance, and deploy a Python script"
d. Push your changes to the remote repository and create a pull request to merge “feature-gcp-setup” into the main branch.
Push the Branch:

Push the new branch to the remote repository.
git push origin feature-gcp-setup
Create a Pull Request:

Navigate to your repository on GitHub.
Create a new pull request to merge feature-gcp-setup into the main branch.
e. Add a collaborator to review your pull request, address any feedback, and merge the changes once approved.
Assign a Collaborator for Review:

On GitHub, request a review from a collaborator by assigning them to the pull request.
Address Any Feedback:

If your collaborator provides feedback, make the necessary changes.
Commit the changes.
Push the updates to the branch:
git add .
git commit -m "Address review feedback"
git push origin feature-gcp-setup
Merge the Pull Request:

Once approved, merge the pull request into the main branch using GitHub’s interface.
Fetch and Update Local Repository:

Ensure your local repository is up-to-date with the new changes:
git checkout main
git pull origin main

