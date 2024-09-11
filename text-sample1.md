# Test File One  
Clone the Repository Locally:
First, clone your existing repository to your local machine using the following command:
git clone https://github.com/your-username/your-repo.git

Replace your-username with your GitHub username and your-repo with the name of your existing repository.
Create a New Repository on GitHub:
Go to GitHub and create a new repository by clicking the “+” icon in the top-right corner and selecting “New repository.”
Give your new repository a name and configure any other settings you’d like.
Update the Remote URL:
Change the remote URL of your local repository to point to the new repository you just created:
cd your-repo
git remote set-url origin https://github.com/your-username/new-repo.git

Replace new-repo with the name of your new repository.
Push to the New Repository:
Push your local changes to the new repository:
git push origin master

This will upload your existing code to the new repository.
Optional: Set Up Upstream (Original Repository) as Remote:
If you want to keep track of changes in the original repository, you can add it as an upstream remote:
git remote add upstream https://github.com/your-username/your-repo.git

Now you can fetch updates from the original repository using git fetch upstream.
