[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285893&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

# Assignment: Setting Up Your Developer Environment

# Objective

This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

# Tasks

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. <https://www.microsoft.com/software-download/windows11>
   ![Go to https://www.microsoft.com/software-download/windows11 and click on the Download now button for Windows 11 Installation Assistant.](<Screenshot 2024-06-17 104104.png>)
   Go to Downloads or your default path for downloaded items and locate your .exe file and run it as an administrator.
   Once the tool confirms the device hardware is compatible, you will be presented with the license terms. Select Accept and Install.
   Click the Restart Now button to complete installation on your computer and make sure that the PC is not turned off during the restart process.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. <https://code.visualstudio.com/Download>
   ![Go to https://code.visualstudio.com/Download and click on the Download button on your top right corner or click on the Windows button if you are using Windows and the same for other OS.](<Screenshot 2024-06-17 105613.png>)
   Once it is downloaded got to downloads and locate the VS Code installer, click on it to run the installer.
   By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. <https://github.com>
   ![Go to https://www.git-scm.com/download/win to download git for windows and click on "Click here to download" and install.](<Screenshot 2024-06-17 111141.png>)
   Set up your username by running the git bash terminal and typing the following command, git config --global user.name "Nambwa04" (It should be the same username that you'll use on your github account)
   Set up your email by typing this command on the git bash terminal, git config --global user.email "<bnambwa@kabarak.ac.ke>"(It should be the same email that you'll use on your github account)
   To create a github account, visit <https://github.com> then select SIGN UP and use the credentials that you used to set up your git.
   To create a new repository, open the gitbash terminal, navigate to the directory of your project and type the following commands; git init (To initialise your repository) then press enter; git add . (Adds the files in the local repository and stages them for commit.) and press enter finally git commit -m 'Your message' (Commits the tracked changes and prepares them to be pushed to a remote repository.)
   Go to your github account and create a new repository and clone it.
   On your gitbash, run the following command git remote add origin "link copied" then press enter.
   Then git push -u origin master to push the files to your repository.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from <http://wwww.python.org> programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  ![Go to https://www.python.org/ and go to downloads](<Screenshot 2024-06-17 120426.png>)
  ![Click on the "Python 3.12.4" button to download the installer](<Screenshot 2024-06-17 120448.png>)
  Go to your downloads and locate the installer.
  Click on it to install Python.
  To check that python is install correctly, go to your cmd and type this command, python --version. It should display the version of the python you installed.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   To install pip, go to your command prompt and type this command, python -m pip install pip.
   To check if pip is installed correctly, run this command on your command prompt, pip –version.

6. Configure a Database (MySQL):
   Download and install MySQL database. <https://dev.mysql.com/downloads/windows/installer/5.7.html>
   ![Go to https://dev.mysql.com/downloads/installer/ and select the (mysql-installer-community-8.0.37.0.msi and download)](<Screenshot 2024-06-17 122209.png>)
   Follow the steps in <https://phoenixnap.com/kb/install-mysql-on-windows> to install the mysql database.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   ![To install docker go to https://docs.docker.com/desktop/install/windows-install/ and click the download button](<Screenshot 2024-06-17 123003.png>)
   Follow the steps in <https://www.geeksforgeeks.org/how-to-install-docker-on-windows/> to install Docker on windows.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   ![Extensions on VS Code](<Screenshot 2024-06-17 130952.png>)

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.
    [Documentation of my setup](<../Desktop/Power Learn Project/DOCUMENTATION OF MY SETUP.docx>)

# Deliverables

- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

# Submission

Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

# Evaluation Criteria:**

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
