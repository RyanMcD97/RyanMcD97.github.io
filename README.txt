This is my teaching profile, within the folio you will find informatioon about me, my teaching philosophy, my teaching areas, along with project ideas you can do with your own classes.
There is a section to get into contact with me, alternativly you can access my linkedin via the button on the about me page. 

In order to run this file locally on github you must unzip your file so that files are seperate, the index.html file needs to be seperate, the rest of the files can be in an unzipped folder
To upload your HTML and CSS files to GitHub, you'll need to follow these steps:

Step 1: Create a GitHub Repository

1. Sign in to GitHub: Go to [GitHub](https://github.com/) and log in to your account. If you don't have an account, create one.
   
2. Create a New Repository:
   - Click the "+" icon in the top right corner and select "New repository."
   - Fill in the repository name (e.g., "my-website").
   - Add a description (optional).
   - Choose the repository type: **Public** (anyone can see it) or **Private** (only you and collaborators can see it).
   - You can initialise the repository with a README file, but it is optional.
   - Click "Create repository".

 Step 2: Set Up Git on Your Computer

1. Download and Install Git:
   - If you haven't installed Git yet, download it from [git-scm.com](https://git-scm.com/) and install it.

2. Configure Git:
   - Open your terminal (Mac/Linux) or Git Bash (Windows).
   - Set your username and email (these will appear in your commits):
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

Step 3: Upload Your Files to the Repository

1. Navigate to Your Project Folder:
   - Open your terminal or Git Bash.
   - Use the `cd` command to navigate to the folder where your HTML and CSS files are located:
     ```bash
     cd path/to/your/project
     ```

2. Initialize a Git Repository:
   - If this is a new project, initialize a local Git repository:
     ```bash
     git init
     ```

3. Add Your Remote Repository:
   - Connect your local repository to the GitHub repository you created:
     ```bash
     git remote add origin https://github.com/your-username/my-website.git
     ```

4. Add Your Files:
   - Add all files in your project folder to the staging area:
     ```bash
     git add .
     ```

5. Commit Your Changes:
   - Commit the changes with a message describing what you did:
     ```bash
     git commit -m "Initial commit: Upload HTML and CSS files"
     ```

6. Push Your Changes to GitHub:
   - Push the changes from your local repository to GitHub:
     ```bash
     git push -u origin main
     ```
   - If your repository's default branch is `master`, replace `main` with `master`.

Step 4: Verify Your Upload

1. Check Your Repository on GitHub:
   - Go back to your GitHub repository in your web browser.
   - Refresh the page; you should see your HTML and CSS files listed.

Tips:

- If you update your files in the future, repeat Steps 3.4 to 3.6 (add, commit, and push).
- Consider using a `.gitignore` file to exclude unnecessary files or directories from being uploaded.

