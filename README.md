   
1. Create a Local Repository:
    - Open your terminal.
    - Create a new directory and navigate into it:
      mkdir my-repo
      cd my-repo
    - Initialize the directory as a git repository:
      git init

2. Create and Add Files:
    - Create a `README.md` file:
      echo. > README.md
    - Open the `README.md` file in a text editor and add some content.

3. Stage and Commit Files:
    - Add the files to the staging area:
      git add .
     
    - Commit the files with a descriptive message:
      
      git commit -m "Initial commit with README.md"

4. Create a GitHub Repository:
    - Go to GitHub(https://github.com) and log in.
    - Click on the **New button** to create a new repository.
    - Enter the repository name and description.
    - Click **Create repository**.

5. Link Local Repository to GitHub:
    - In your terminal, add the GitHub repository as a remote:
      git remote add origin https://github.com/your-username/my-repo.git

6. Push Changes to GitHub:
    - Push the local commits to the GitHub repository:

      git branch -M main
      
      git push -u origin master

