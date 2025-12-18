set:
git config --global user.name "USERNAME"
git config --global user.email GMAIL@gmail.com
git config --list

unset:
git config --global --unset user.name
git config --global --unset user.email


cd demo1 
git add .
git commit -m "msg"
git push origin main


git branch
git branch <branch name>
git checkout <branch name>
  

git branch
git branch devlopment  
git branch
git checkout devlopment  


git init 
git remote add origin https://github.com/vidhi28vaghela05/SmartServe-Solutions.git
git add .
 git commit -m "msg"
git push origin master










-----------------------------------------------------------------------------------------------

🔹 Git User Setup

git config --global user.name "rupaprajapati082"
→ Sets your Git username globally.

git config --global user.email rupsprajapati823@gmail.com
→ Sets your Git email globally.

git config --list
→ Shows all Git configuration settings.

🔹 Remove Git User Details

git config --global --unset user.name
→ Deletes the global Git username.

git config --global --unset user.email
→ Deletes the global Git email.

🔹 Git Basic Commands

git add .
→ Adds all changed files to staging.

git commit -m "msg"
→ Saves changes with a message.

git push origin main
→ Sends code to the main branch on GitHub.

git push origin master
→ Sends code to the master branch on GitHub.

🔹 PowerShell Command (Windows)

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
→ Allows running scripts on your system.

🔹 Tailwind Config File

export default {
→ Starts Tailwind configuration.

content: ["./src/**/*.{html,js}"],
→ Tells Tailwind where files are located.

theme: { extend: {}, },
→ Used to customize Tailwind styles.

plugins: [],
→ Used to add Tailwind plugins.

🔹 Tailwind CLI Install

npm install tailwindcss @tailwindcss/cli
→ Installs Tailwind CSS and CLI.

🔹 Node Modules Missing

npm i
→ Installs all project dependencies.

🔹 Run Project

npm run start
→ Runs the project.

🔹 Git Branch Commands

git branch
→ Shows all branches.

git branch branch_name
→ Creates a new branch.

git checkout branch_name
→ Switches to another branch.

🔹 New GitHub Repository Setup

echo "# tailwind-cli" >> README.md
→ Adds text to README file.

git init
→ Creates a new Git repository.

git add README.md
→ Stages README file.

git commit -m "first commit"
→ Saves the first commit.

git branch -M main
→ Renames branch to main.

git remote add origin URL
→ Connects local repo to GitHub.

git push -u origin main
→ Pushes code and sets default branch.