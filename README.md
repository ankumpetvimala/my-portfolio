# Task 1: Installing and Setting Up Git for Version Control

##  Objective

- To install and configure Git on a local machine and push a simple project to a remote repository (GitHub or GitLab) for version control and collaboration.

---

![Home1](https://github.com/user-attachments/assets/61003763-b693-4c33-a74a-3ef5976d62bd)


## Tools Used

- Git
- GitHub

---

## ✅ Steps Completed

### 1. Git Installation

   Download and install Git from the official site:  
    [https://git-scm.com/downloads](https://git-scm.com/downloads)

   Verify installation:

     git --version

### 2. Git Configuration

#### Configure Git with username and email:

    git config --global user.name "Your Name"

    git config --global user.email "your.email@example.com"

#### Check configuration:

    git config --list

### 3. 📁 Project Setup
   
#### Create a new directory and a basic HTML file:

      mkdir my-portfolio

      cd my-portfolio

### 4. Initialize Git Repository
   
     git init

     git add index.html

     git commit -m "Initial commit - added index.html"

### 5. Push to GitHub

#### Create a repository on GitHub:

   Go to: https://github.com/new

   Name it: my-portfolio

   Don't initialize with README (empty repo)

#### Add remote and push:

    git remote add origin https://github.com/your-username/my-portfolio.git

    git branch -M main

    git push -u origin main

