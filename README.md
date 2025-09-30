# A02: Step-by-step tutorial on how to install and connect Git, Webstorm, and GitHub.

## Required applications: 
1. Git Bash
- Step 1: Install Git Bash
- Download **Git** from the official site: https://git-scm.com/downloads
- Install using default settings.
- Open Git Bash (installed with **Git**) to verify by typing:
  "git --version"

2. Webstorm
- Download WebStorm: https://www.jetbrains.com/webstorm/download
- Choose your operating system (Windows, macOS, Linux).
  
3. GitHub 
- Create a GitHub account: https://github.com/

  ## Setting up git and connecting to GitHub
  Step 1: Configure your **Git** username and email
  - git config --global user.name "Your Name"
  - git config --global user.email "your.email@example.com"
  Step 2: Generate an SSH key to connect securely to **GitHub**:
  - ssh-keygen -t ed25519 -C "your.email@example.com"
  Step 3: Add the key to **GitHub**:
  - Go to **GitHub** > Settings > SSH and GPG keys > New SSH key > paste the key
 
  ## GitHub Basics
  1. Setting up a **Repository**
  - Sign in at github.com.
  - In the upper right, click the + icon > New **repository**.
  - Name your repo. Choose Public or Private.
  - (Optional) Check Add a README file so you can **commit** immediately.
  - Click Create **repository**.
    
  2. Create a new **Branch**
  - Open your repo on GitHub.
  - Click the **branch** picker that shows main.
  - Type a new name like feature/readme-tutorial and press Enter to create and switch to it

  3. Making a Commit
  - With your new branch selected on GitHub, click a file to edit or click Add file → Create new file.
  - Make your changes in the editor.
  - In the Commit changes box, write a short message, for example: "Adding Instructions on making a repo".
  - Click Commit changes. GitHub records your change on this branch.
    
  ## Connecting GitHub to WebStorm
  - Open WebStorm > Go to File > Settings > Version Control > Git.
  - Set the **Git** path (usually C:\Program Files\Git\bin\git.exe on Windows).
  - Click Test to confirm WebStorm recognizes **Git**.
  - Log in to **GitHub** in WebStorm:
  - Go to File > Settings > Version Control > **GitHub**.
  - Click Add Account > Log In via **GitHub**.
  - **Clone** a **repository** from **GitHub** in WebStorm:
  - Go to File > New > Project from Version Control > **Git**.
  - Enter the **GitHub** **repository** URL.
  - Choose a local folder and click **Clone**.
  - Now you can use WebStorm to **commit**, **push**, and **pull** changes directly.
 
  ## Glossary
  **Branch** – A separate line of development in a project, allowing you to work on features independently.
  **Clone** – A copy of a GitHub repository downloaded to your computer.
  **Commit** – A saved snapshot of your project’s files at a certain point in time.
  **Fetch** – A command that downloads new changes from the remote without merging them.
  **Git** – A version control system that tracks file changes and project history.
  **GitHub** – An online platform that hosts Git repositories and enables collaboration.
  **Merge** – The process of combining changes from one branch into another.
  **Merge** Conflict – An issue that happens when Git cannot automatically merge file changes.
  **Push** – Sending your local commits to the remote GitHub repository.
  **Pull** – Getting the latest changes from GitHub and merging them into your local copy.
  **Remote** – The online version of your repository stored on GitHub.
  **Repository** – A project folder tracked by Git that contains files, history, and branches.

  
