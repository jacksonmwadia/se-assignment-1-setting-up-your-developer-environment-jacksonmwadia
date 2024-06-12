[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15264871&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:
### Dev_Setup
Setup Development Environment

#### Assignment: Setting Up Your Developer Environment

#### Objective: 
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#### Tasks and Answers:

1. **Select Your Operating System (OS)**: Choose an operating system that best suits your preferences and project requirements. Download and install Windows 11. [Windows 11 Download](https://www.microsoft.com/software-download/windows11)

   - **Answer**: I have chosen to use Windows 11 as my operating system because it is widely supported, user-friendly, and compatible with a variety of development tools and software. I downloaded and installed Windows 11 from [https://www.microsoft.com/software-download/windows11](https://www.microsoft.com/software-download/windows11).

2. **Install a Text Editor or Integrated Development Environment (IDE)**: Select and install a text editor or IDE suitable for your programming languages and workflow. Download and install Visual Studio Code. [Visual Studio Code Download](https://code.visualstudio.com/Download)

   - **Answer**: I selected Visual Studio Code (VS Code) as my IDE because it is lightweight, highly customizable, and supports a wide range of programming languages and extensions. I downloaded and installed Visual Studio Code from [https://code.visualstudio.com/Download](https://code.visualstudio.com/Download).

3. **Set Up Version Control System**: Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. [GitHub](https://github.com)

   - **Answer**: I installed Git to manage version control for my projects. Git is a powerful tool for tracking changes and collaborating with other developers. After installing Git, I created a GitHub account to host my repositories. I initialized a Git repository for my project using the following commands:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     ```
     GitHub account creation and repository initialization were done on [https://github.com](https://github.com).

4. **Install Necessary Programming Languages and Runtimes**: Install Python from [Python Download](https://www.python.org) programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

   - **Answer**: I installed Python, which is necessary for my projects. Python is a versatile language used for web development, data analysis, machine learning, and more. I downloaded and installed Python from [https://www.python.org](https://www.python.org).

5. **Install Package Managers**: If applicable, install package managers like pip (Python).

   - **Answer**: I installed pip, the package manager for Python, to manage and install additional Python libraries and dependencies. Pip was included with the Python installation, and I verified its installation using the command:
     ```bash
     pip --version
     ```

6. **Configure a Database (MySQL)**: Download and install MySQL database. [MySQL Download](https://dev.mysql.com/downloads/windows/installer/5.7.html)

   - **Answer**: I installed MySQL to manage databases for my applications. MySQL is a robust and widely used relational database management system. I downloaded and installed MySQL from [https://dev.mysql.com/downloads/windows/installer/5.7.html](https://dev.mysql.com/downloads/windows/installer/5.7.html).

7. **Set Up Development Environments and Virtualization (Optional)**: Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   - **Answer**: I explored using Python virtual environments to isolate project dependencies and ensure consistent environments across different projects. Virtual environments allow for isolated Python environments that can be easily managed. I created a virtual environment for my project using the following commands:
     ```bash
     python -m venv myenv
     ```
     I activated the virtual environment using:
     ```bash
     myenv\Scripts\activate
     ```

8. **Explore Extensions and Plugins**: Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   - **Answer**: I explored and installed several extensions for Visual Studio Code to enhance its functionality:
     - **Python**: For Python support, including IntelliSense, linting, and debugging.
     - **GitLens**: To improve Git integration within VS Code.
     - **Prettier**: For code formatting to maintain consistent code style.
     - **Live Server**: To launch a development local server with live reload feature for static & dynamic pages.
     These extensions were installed from the Visual Studio Code Marketplace.

9. **Document Your Setup**: Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

   - **Answer**: I documented the entire setup process, including configurations, customizations, and any troubleshooting steps encountered. This document serves as a reference for replicating the environment on other machines or for new team members.

### Documentation of Setup Process

#### Windows 11 Installation
- **Downloaded**: [https://www.microsoft.com/software-download/windows11](https://www.microsoft.com/software-download/windows11)
- **Installed**: Followed the on-screen instructions for a clean installation.

#### Visual Studio Code Installation
- **Downloaded**: [https://code.visualstudio.com/Download](https://code.visualstudio.com/Download)
- **Installed**: Followed the setup wizard.

#### Git and GitHub Setup
- **Installed Git**: Using the official installer.
- **Created GitHub Account**: Signed up on [https://github.com](https://github.com).
- **Initialized Repository**:
  ```bash
  git init
  git add .
  git commit -m "Initial commit"
  ```

#### Python Installation
- **Downloaded**: [https://www.python.org](https://www.python.org)
- **Installed**: Followed the setup instructions and added Python to PATH.

#### Pip Installation
- **Verified pip**: Ensured pip was installed with Python using:
  ```bash
  pip --version
  ```

#### MySQL Installation
- **Downloaded**: [https://dev.mysql.com/downloads/windows/installer/5.7.html](https://dev.mysql.com/downloads/windows/installer/5.7.html)
- **Installed**: Followed the setup wizard and configured the root user and password.

#### Virtual Environment Setup (Optional)
- **Created Virtual Environment**:
  ```bash
  python -m venv myenv
  ```
- **Activated Virtual Environment**:
  ```bash
  myenv\Scripts\activate
  ```

#### VS Code Extensions
- **Installed Extensions**:
  - Python
  - intellicence
  - pylaynce
  - Live Server
- **Configured Extensions**: Customized settings for each extension as per project requirements.


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
