Step 1: Create a New Repository on GitHub
1. Go to GitHub and log in.
2. Click on the '+' sign in the top right corner and select "New repository."
3. Enter the repository name as 'new-project' and add a short description if needed.
4. Choose whether the repository should be public or private.
5. Check the box that says "Initialize this repository with a README."
6. Click on "Create repository."

Step 2: Clone the Repository Locally
1. Open your terminal or command prompt.
2. Use the git clone command to clone the repository to your local machine (git clone https://github.com/your-username/new-project.git). Replace your-username with your GitHub username.

Step 3: Create a Development Branch
1. Move into the project directory (cd new-project).
2. Create a new branch named 'development' (git checkout -b development). This command creates and switches you to the new 'development' branch.

Step 4: Push the Development Branch to GitHub
1. Add your changes (git add .).
2. Commit the changes (git commit -m "Creating development branch").
3. Push the development branch to GitHub (git push origin development).