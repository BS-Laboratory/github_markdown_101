# GitHub Workflow and Markdown Mastery

## Materials Needed

* Computer with internet access
* GitHub account
* Text editor (e.g., VS Code, Sublime Text, Atom, Notepad++)

## Project Overview (for Students)

In this project, you will become familiar with the essential steps of using GitHub, a widely used platform for collaboration and version control in software development and beyond. You will create your own repository, practice making changes to files, keep track of those changes using Git, and then share your work online using GitHub. You will also learn how to use Markdown, a simple and powerful language for formatting text, to create clear and organized documentation for your project. This project will give you hands-on experience with tools that are crucial for many collaborative and individual projects in computer science and related fields.

## Detailed Instructions (for Students)

1.  **Create a New Repository on GitHub:**
    * Go to the GitHub website ([https://github.com/](https://github.com/)) and log in to your account.
    * Click the "+" button in the top right corner and select "New repository."
    * Give your repository a descriptive name (e.g., "github-practice").
    * You can choose to make it public or private. For this exercise, either is fine.
    * **Crucially, check the box to "Add a README file."** This will automatically create a basic Markdown file in your repository.
    * Leave the other options (Add .gitignore, Add a license) unchecked for now.
    * Click the "Create repository" button.

2.  **Explore Your Repository:**
    * Once your repository is created, take a look at the main page. You should see the README.md file listed. Click on it to view its contents. You'll notice it contains some default text.

3.  **Clone Your Repository Locally:**
    * On your repository's main page, click the green "Code" button.
    * Make sure the "HTTPS" option is selected. Copy the URL provided.
    * Open a terminal or command prompt on your computer.
    * Navigate to a directory where you want to store your project files using the `cd` command (e.g., `cd Documents`).
    * Type the command `git clone` followed by the URL you copied (e.g., `git clone https://github.com/your-username/github-practice.git`) and press Enter.
    * This will create a folder with the same name as your repository on your local machine.

4.  **Create and Modify Files Locally:**
    * Open the newly created repository folder on your computer.
    * Using a text editor, open the `README.md` file.
    * Practice using Markdown syntax to edit this file. Include the following:
        * A main heading (using `#`).
        * A subheading (using `##`).
        * A bulleted list (using `*` or `-`).
        * A numbered list (using `1.`, `2.`, etc.).
        * A block of sample code (using triple backticks ```). You can write a simple code snippet in any language or just some placeholder text.
    * Create a new text file within your repository folder using your text editor. Name it `practice.txt`.
    * In `practice.txt`, write a few sentences about what you've learned about GitHub so far.

5.  **Stage and Commit Your Changes:**
    * Open your terminal or command prompt again and navigate into your repository folder using the `cd` command (e.g., `cd github-practice`).
    * To see the changes you've made, type `git status` and press Enter. You should see your modified `README.md` file and your new `practice.txt` file listed under "Untracked files" or "Changes not staged for commit."
    * To stage your changes (prepare them for commit), type `git add .` (this adds all changes in the current directory) and press Enter.
    * Type `git status` again. Now your files should be listed under "Changes to be committed."
    * To commit your staged changes (save them with a message), type `git commit -m "Added README content and practice file"` and press Enter. Replace the message with something descriptive about the changes you made.

6.  **Push Your Local Repository to GitHub:**
    * To send your local commits to your remote repository on GitHub, type `git push origin main` and press Enter. You might be asked to enter your GitHub username and password.

7.  **Verify Your Changes on GitHub:**
    * Go back to your repository page on the GitHub website and refresh the page.
    * You should now see your updated `README.md` file with the Markdown formatting you added, as well as the new `practice.txt` file.

8.  **Reflect in Your README:**
    * Edit your `README.md` file again (either locally and then stage, commit, and push, or directly on the GitHub website using the "Edit" button).
    * Add a new section (using a subheading) titled "Reflection."
    * In this section, briefly describe the steps you took in this project and what you learned about the GitHub workflow (create, modify, stage, commit, push) and using Markdown.

9.  **Final Push:**
    * If you edited the `README.md` file locally, remember to stage your changes (`git add .`), commit them (`git commit -m "Added reflection"`), and push them to GitHub (`git push origin main`).

Your final GitHub repository should contain a well-formatted `README.md` file demonstrating your use of Markdown and including your reflection on the GitHub workflow, as well as the `practice.txt` file you created. This will serve as evidence of your ability to initiate a repository, manage files locally, track changes with Git, push to a remote repository, and utilize Markdown for documentation.
