[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15255934&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

    1. System Requirements
Ensure your system meets the following requirements for Windows 11:
Processor: 1 gigahertz (GHz) or faster with at least 2 cores on a compatible 64-bit processor or system on a chip (SoC).
RAM: 4 GB or more.
Storage: 64 GB or larger storage device.
System Firmware: UEFI, Secure Boot capable.
TPM: Trusted Platform Module (TPM) version 2.0.
Graphics Card: DirectX 12 compatible graphics / WDDM 2.x.
Display: >9” with HD Resolution (720p).
Internet Connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

   2. Backup Your Data
Before proceeding, back up all important data to avoid any potential data loss during the installation process.

   3. Download Windows 11
Go to the Official Windows 11 Download Page:
Open your browser and visit the Windows 11 download page.
Download the Installation Media:
You can either download the Windows 11 Installation Assistant or create a bootable USB drive.
For most users, the Installation Assistant is the easiest way to upgrade.

   4. Use Windows 11 Installation Assistant
Run the Installation Assistant:
Download and open the Windows 11 Installation Assistant.
Follow the on-screen instructions to start the upgrade process.

   5. Create a Bootable USB Drive (if needed)
Download the Media Creation Tool:
On the Windows 11 download page, select "Create Windows 11 Installation Media."
Download and run the Media Creation Tool.

Create Installation Media:
Choose the USB drive you want to make bootable (at least 8 GB of space).
Follow the prompts to create the bootable USB drive.

   6. Install Windows 11
Using the Installation Assistant:
If you’re using the Installation Assistant, it will guide you through the upgrade process automatically.

Using the Bootable USB Drive:
Insert the bootable USB drive into your PC.
Restart your PC and boot from the USB drive (you might need to adjust the BIOS settings to boot from USB).
Follow the on-screen instructions to perform a clean installation.

   7. Complete the Installation
Follow the Setup Process:
Choose your language, time, and keyboard preferences.
Click "Install Now."
Enter your product key (if required).
Select the edition of Windows 11 you purchased.
Choose the installation type (Upgrade or Custom).
Follow the prompts to complete the installation.

Set Up Windows 11:
After installation, go through the initial setup process, including setting up your Microsoft account, configuring privacy settings, and personalizing your 

installation.
   8. Install Drivers and Updates
Check for Updates:
Go to Settings > Windows Update and check for any available updates.
Install all recommended updates to ensure you have the latest features and security patches.

Install Drivers:
Ensure all hardware drivers are installed and up to date. Check the manufacturer’s website for the latest drivers for your system.

   9. Restore Your Data
If you performed a clean installation, restore your backed-up data.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   To download and install Visual Studio Code (VS Code), follow these steps:
Visit the Visual Studio Code website:
Go to https://code.visualstudio.com.

Download the Installer:
Click the download button for your operating system (Windows, macOS, or Linux).

Install Visual Studio Code:
Windows:
Run the downloaded VSCodeSetup.exe file.
Follow the installation prompts, and choose the desired options (such as adding VS Code to your PATH for command line usage).

Launch Visual Studio Code:
Open VS Code from your application menu or command line (type code if added to PATH).

Install Extensions (Optional):
Once VS Code is open, you can install extensions for additional features and language support. Click on the Extensions icon on the sidebar or use the shortcut Ctrl+Shift+X.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   1. Install Git
For Windows:
Go to the Git for Windows website.
Download the installer and run it.
Follow the on-screen instructions to complete the installation.

2. Configure Git
Once Git is installed, you need to set up your user name and email address. Open a terminal (or Git Bash on Windows) and run the following commands:
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

3. Create a GitHub Account
Go to GitHub.
Click on "Sign up" and follow the instructions to create a new account.
After creating your account, you can create new repositories and manage your projects.

4. Initialize a Git Repository
Open a terminal and navigate to your project directory:
cd /path/to/your/project
Initialize a new Git repository:
git init

5. Make Your First Commit
Add your project files to the staging area:
git add .
Commit the files to the repository:
git commit -m "Initial commit"

6. Create a Repository on GitHub
Go to your GitHub account.
Click on the "+" icon in the top right corner and select "New repository".
Fill in the repository name and description, and click on "Create repository".

7. Push Your Local Repository to GitHub
Add the remote URL for the GitHub repository:
git remote add origin https://github.com/your-username/your-repository.git
Push the changes to GitHub:
git push -u origin master


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Download Python Installer:
Visit the official Python website.
Navigate to the Downloads section.
Download the latest stable release for Windows.

Run the Installer:
Double-click the downloaded .exe file to run the installer.
Ensure you check the box that says "Add Python to PATH" before clicking "Install Now".
Follow the prompts to complete the installation.

Verify Installation:
Open Command Prompt and type:
python --version

Install pip (if not included):
If pip is not installed, follow the instructions mentioned in the previous response to download and run get-pip.py.

Additional Tools:
Virtual Environment:
To manage dependencies for your projects, it is recommended to use virtual environments.
python3 -m venv myenv
source myenv/bin/activate  # For macOS/Linux
myenv\Scripts\activate  # For Windows

IDE or Text Editor:
Install a code editor like Visual Studio Code or an IDE like PyCharm.

Building and Running Code:
Write Python code in a .py file.
Execute Python code:
python myscript.py

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Check if pip is already installed:
   pip --version

   If pip is not installed: Download and install get-pip.py using curl or wget and then run it with Python.
   Using curl:
   curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

   Run the script to install pip:
   python get-pip.py

   Verify the Installation
   After installation, verify that pip is installed correctly by checking its version again:
   pip --version


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Installing MySQL on your system involves several steps. I'll guide you through the process for both Windows and Linux (Ubuntu). Please let me know which operating system you're using, or if you need instructions for a different OS.

   For Windows:
   Download MySQL Installer:
   Go to the MySQL downloads page.
   Choose "MySQL Installer for Windows" and download the installer.

   Run the Installer:
   Open the downloaded file to run the installer.
   Choose the setup type. "Developer Default" is recommended for a complete installation.
   Follow the prompts to proceed with the installation.

   Configuration:
   When prompted, configure the MySQL server. Set the root password and create any additional user accounts.
   Configure the server to start automatically if desired.
   
   Complete Installation:
   Complete the installation process and finish the setup.

   Post-Installation:
   Create a Database and User:
   CREATE DATABASE your_database_name;
   CREATE USER 'your_username'@'localhost' IDENTIFIED BY 'your_password';
   GRANT ALL PRIVILEGES ON your_database_name.* TO 'your_username'@'localhost';
   FLUSH PRIVILEGES;

   Connect to MySQL:
   mysql -u your_username -p your_database_name
   Enter the password for the user you created.



7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
   Using virtualization tools like Docker or virtual machines (VMs) is an excellent way to isolate project dependencies and ensure consistent environments across different machines. Here’s a breakdown of how each tool can help and their respective advantages:

Docker
What is Docker?
Docker is a platform that allows you to automate the deployment of applications inside lightweight, portable containers. Containers bundle an application with all of its dependencies and libraries, ensuring consistency across different environments.

Benefits of Docker:
Isolation: Each container runs in its own isolated environment, which prevents conflicts between dependencies.
Consistency: Containers guarantee that the application will run the same way regardless of where they are deployed (e.g., development, testing, production).
Portability: Docker containers can run on any system that supports Docker, making it easy to move applications between different environments.
Efficiency: Containers share the host OS kernel, making them more lightweight compared to VMs. This results in faster startup times and less overhead.
Reproducibility: Docker images can be versioned, ensuring that the same environment can be recreated exactly as it was.
Example Use Case:
You can create a Dockerfile that specifies the environment and dependencies for your application. Here’s a simple example for a Python application:
# Use an official Python runtime as a parent image
FROM python:3.9-slim
# Set the working directory
WORKDIR /app
# Copy the current directory contents into the container at /app
COPY . /app
# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
# Make port 80 available to the world outside this container
EXPOSE 80
# Define environment variable
ENV NAME World
# Run app.py when the container launches
CMD ["python", "app.py"]

Virtual Machines (VMs)
What are Virtual Machines?
VMs are emulations of physical computers, running a full operating system (OS) and virtual hardware. Each VM is isolated from others and from the host machine.

Benefits of VMs:
Complete Isolation: Each VM runs a full OS, providing complete isolation from the host and other VMs.
Versatility: VMs can run different operating systems and are not limited to the host’s OS.
Environment Consistency: VMs ensure that your application runs in the same environment across different stages (development, testing, production).
Security: VMs provide a high level of security as they are completely isolated environments.
Example Use Case:
Using Vagrant, a tool for building and managing VMs, you can define a VM configuration in a Vagrantfile:
Vagrant.configure("2") do |config|
  # Use a specific box (a pre-packaged base image)
  config.vm.box = "ubuntu/bionic64"
  # Provision the VM with a shell script
  config.vm.provision "shell", inline: <<-SHELL
    apt-get update
    apt-get install -y python3 python3-pip
    pip3 install -r /vagrant/requirements.txt
  SHELL
  # Sync the current directory to /vagrant on the VM
  config.vm.synced_folder ".", "/vagrant"

Choosing Between Docker and VMs
Docker is ideal for applications that require consistent deployment environments, are microservices-oriented, and benefit from fast startup times and resource efficiency.
VMs are better suited for applications that need full OS environments, complete isolation, or are dependent on specific OS features.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   
   Choosing a text editor or IDE (Integrated Development Environment) depends on personal preference, project requirements, and specific needs. Popular text editors and IDEs include Visual Studio Code (VS Code), JetBrains' IntelliJ IDEA, PyCharm, and Sublime Text. Below, I will explore extensions, plugins, and add-ons for these editors to enhance functionality in areas like syntax highlighting, linting, code formatting, and version control integration.

Visual Studio Code (VS Code)
   VS Code is a highly customizable and widely used code editor with a vast marketplace for extensions.

Syntax Highlighting
   Rainbow Brackets: Provides rainbow colors for brackets to help visually distinguish nested code.
   Better Comments: Improves comment readability with different colors for different types of comments.

Linting
   ESLint: Integrates ESLint into VS Code, allowing real-time linting for JavaScript, TypeScript, and other languages.
   Python: The official Python extension provides linting support for Python with Pylint, Flake8, etc.

Code Formatting
   Prettier - Code formatter: An opinionated code formatter that supports many languages and integrates with various linting tools.
   Beautify: Allows for beautification of code for HTML, CSS, JavaScript, and other languages.

Version Control Integration
   GitLens: Enhances Git capabilities in VS Code, showing code authorship, commit history, and more.
   GitHub Pull Requests and Issues: Integrates GitHub workflows into VS Code, allowing you to review pull requests and issues directly in the editor.
   JetBrains IntelliJ IDEA / PyCharm
   IntelliJ IDEA and PyCharm are powerful IDEs with extensive plugin support, particularly strong in Java and Python development, respectively.

Syntax Highlighting
   Rainbow Brackets: Similar to the VS Code extension, it helps distinguish different levels of nested code with colors.
   .ignore: Provides syntax highlighting for .gitignore and other ignore files.
   Linting
   CheckStyle-IDEA: Integrates CheckStyle with IntelliJ IDEA, allowing real-time Java code linting.
   SonarLint: Provides on-the-fly code quality and security feedback for Java, JavaScript, Python, and other languages.

Code Formatting
   Save Actions: Automatically formats and optimizes imports on file save.
   Eclipse Code Formatter: Uses the Eclipse code formatter within IntelliJ IDEA.
   Version Control Integration
   GitToolBox: Adds various Git features, including blame annotations, status display, and more.
   GitHub: Provides direct integration with GitHub, making it easier to manage repositories and pull requests.
   Sublime Text
   Sublime Text is known for its speed and simplicity, with a rich ecosystem of packages to enhance its functionality.

Syntax Highlighting
   SublimeLinter: A framework for linting code with support for various languages through additional plugins.
   Babel: Provides syntax highlighting for ES6+ JavaScript and React JSX.
   Linting
   SublimeLinter-eslint: Integrates ESLint with Sublime Text for JavaScript linting.
   SublimeLinter-pylint: Adds Pylint support for Python linting.
   Code Formatting
   JsPrettier: A Sublime Text plugin for Prettier, allowing code formatting for JavaScript and other languages.
   HTML-CSS-JS Prettify: Formats HTML, CSS, and JavaScript files.
   Version Control Integration
   GitGutter: Shows information about file changes in the gutter, including modified, added, and deleted lines.
   Sublime Merge Integration: Integrates Sublime Merge, a Git client from the same developers as Sublime Text.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
   This document provides a comprehensive guide to setting up a developer environment. It covers the installation and configuration of necessary tools, customizations, and troubleshooting steps encountered during the process.

   System Specifications
Operating System: Windows 10 
Processor: Intel Core i7-9700K
RAM: 16GB
Storage: 512GB SSD
Installation of Essential Tools
Operating System
Windows 10 Installation
Download the ISO image from the official Windows website.
Create a bootable USB drive using Rufus (Windows) or dd (Linux).
Boot from the USB drive and follow the on-screen instructions to install Ubuntu.

Version Control System (Git)
   Git Installation
   Open a terminal.
   Run the following commands:
   sudo apt update
   sudo apt install git

   Git Configuration
   Set up your name and email: 
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"

Programming Languages and Runtimes
   1. Python
   Python 3 is pre-installed on Windows. Verify by running:
   python3 --version
   Install pip:
   sudo apt install python3-pip

Integrated Development Environment (IDE)
   Visual Studio Code
   Download and install Visual Studio Code from the official website.
   Install VS Code via terminal:
   sudo snap install --classic code

Configuration and Customization
Environment Variables
   Setting Environment Variables
   Open the .bashrc file:
   nano ~/.bashrc
   Add your environment variables:
   export MY_VARIABLE="my_value"
   Apply changes:
   source ~/.bashrc

IDE Customization
   Visual Studio Code Extensions
   Install extensions via the Extensions view (Ctrl+Shift+X) or command line:
   code --install-extension ms-python.python
   code --install-extension esbenp.prettier-vscode

   Setting Up Python Environment in VS Code
   Open a Python file in VS Code.
   Select the Python interpreter by clicking on the Python version in the status bar or using the command palette (Ctrl+Shift+P) and typing Python: Select Interpreter.

Troubleshooting
Common Issues and Solutions
   Git: Permission Denied (Publickey)
   Ensure your SSH key is added to your GitHub account:
   ssh-keygen -t rsa -b 4096 -C "your.email@example.com"
   ssh-add ~/.ssh/id_rsa
   cat ~/.ssh/id_rsa.pub
   Copy the content of id_rsa.pub to your GitHub SSH keys settings.

   Python: Module Not Found
   Ensure the module is installed:
   pip3 install module_name

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
