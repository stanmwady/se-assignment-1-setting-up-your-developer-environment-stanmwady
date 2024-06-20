
 Developer Environment Setup Documentation

 1. Operating System Installation

Steps and Screenshots of Windows 11 Installation:

1. Download Windows 11:
   - Visit the official Microsoft website: [Windows 11 Download](https://www.microsoft.com/software-download/windows11).
   - Download the Windows 11 Installation Assistant.
   - Run the downloaded file and follow the on-screen instructions to upgrade or install Windows 11.
 

2. Installation Process:
   - Ensure your PC meets the minimum system requirements.
   - Back up your important files.
   - Follow the installation steps, including selecting the installation type, partitioning your hard drive if necessary, and configuring initial settings.

    

3. Post-Installation Setup:
   - Configure your user account, regional settings, and privacy settings.
   - Install necessary drivers and updates.

   NB: MY PC DOES NOT SUPPORT WINDOWS 11

 



2. IDE Installation

Steps and Screenshots of Visual Studio Code Installation:

1. Download VS Code:
   - Visit the Visual Studio Code download page: [VS Code Download](https://code.visualstudio.com/Download).
   - Select the appropriate version for Windows and download the installer.

    


2. Installation Process:
   - Run the downloaded installer.
   - Follow the installation wizard, accepting the license agreement and choosing the installation location.
   - Select additional tasks such as adding to PATH and creating a desktop icon.

    

3. First Launch and Setup:
   - Launch VS Code and install recommended extensions like Python, GitLens, and Docker.

    

 







3. Version Control Setup

Steps for Installing Git, Creating a GitHub Account, Initializing a Repository, and Making the First Commit:

1. Install Git:
   - Download Git from the official site: [Git Download](https://git-scm.com/downloads).
   - Run the installer and follow the setup instructions, choosing your preferred options for PATH, line endings, and other settings.

    



2. Create a GitHub Account:
   - Visit [GitHub](https://github.com) and sign up for a new account if you still need to get one.

    

3. Initialize a Git Repository:
   - Open Git Bash or the terminal in VS Code.
   - Navigate to your project directory or create a new one:
 	```bash
 	mkdir my_project
 	cd my_project
 	```
   - Initialize a Git repository:
 	```bash
 	git init
 	```
   - Create a README file:
 	```bash
 	echo "# My Project" >> README.md
 	```
   - Add the README file to the staging area:
 	```bash
 	git add README.md
 	```
   - Commit the changes:
 	```bash
 	git commit -m "Initial commit"
    



4. Programming Languages and Runtimes

Steps for Installing Python:

1. Download Python:
   - Visit the official Python website: [Python Download](https://www.python.org/downloads/).
   - Download the latest version of Python for Windows.

   
2. Installation Process:
   - Run the installer, ensure you check the option to add Python to PATH.
   - Follow the installation wizard.
 

   

3. Verify Installation:
   - Open Command Prompt and type:
 	```bash
 	python --version
 	```
   - Verify pip installation:
 	```bash
 	pip --version
 	```

    

5. Package Managers

Verification of pip Installation:

1. Verify pip:
   - Open Command Prompt and type:
 	```bash
 	pip --version
 	```

    

6. Database Configuration

Steps for Installing MySQL:

1. Download MySQL:
   - Visit the MySQL download page: [MySQL Download](https://dev.mysql.com/downloads/windows/installer/5.7.html).
   - Download the MySQL Installer for Windows.
 
2. Installation Process:
   - Run the MySQL Installer and follow the setup wizard.
   - Choose the setup type (e.g., Developer Default).
   - Configure MySQL Server settings, including the root password.

   NB: MYSQL IS ALREADY CONFIGURED WITH PASSWORD

3. Verify Installation:
   - Open MySQL Workbench or MySQL Shell and connect to your MySQL server.

   

7. Development Environments and Virtualization (Optional)

Optional Steps for Installing and Setting Up Docker:

1. Download Docker:
   - Visit the Docker Desktop download page: [Docker Download](https://www.docker.com/products/docker-desktop).
   - Download and run the Docker Desktop installer.

   ![Docker Download](images/docker-download.png)

2. Installation Process:
   - Follow the installation instructions.
   - Start Docker Desktop and follow the setup wizard.

   NB: NOT OPTED FOR

3. Verify Installation:
   - Open Command Prompt or PowerShell and type:
 	```bash
 	docker --version
 	```

   NB:NOT OPTED FOR



8. Extensions and Plugins

List of Installed Extensions for VS Code:

1. Install Extensions:
   - Open VS Code.
   - Go to the Extensions view (`Ctrl+Shift+X`).
   - Search for and install the following extensions:
 	- Python
 	- GitLens — Git supercharged
 	- Docker
 	- Prettier - Code formatter
 	- ESLint
 	- MySQL

   
9. Challenges and Solutions

1. Challenge: Installing MySQL and Configuring the Root Password
   - Solution: Followed a step-by-step tutorial and used the official MySQL documentation for troubleshooting.

2. Challenge: Initializing a Git Repository and Making the First Commit
   - Solution: Used Git documentation and GitHub guides to understand the commands and workflow.





Deliverables

1. Setup Documentation:
   - This document with detailed steps and screenshots.

2. GitHub Repository:  https://github.com/stanmwady/Wildgittrials.git 
3. Reflection:
	The software engineering has been a success so far despite some challenges here and there. Below is a list of challenges I have generally faced
I.	Balancing between classes and work time challenge. I was initially prepared to attend one session per day that would best fit my schedule. My challenge comes in when I have to join all three classes in a day.
II.	Timetable confusion. From time to time it has been challenging to access meeting links due to some mix-up with the timetable schedule. Kindly fix that.
