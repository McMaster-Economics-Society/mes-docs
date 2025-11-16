---
sidebar_position: 1
---

# Introduction

Let's get you set up **in less than 5 minutes**.

## Getting Started

This guide will walk you through setting up the MES website on your computer.

### What you'll need
All Free resources:
- **GitHub account**
  - Create a new account at [GitHub](https://github.com/) or use an existing one. Students can get extra features with the [GitHub Student Developer Pack](https://education.github.com/pack).
- Download a code editor (pick one):
  - [Visual Studio Code](https://code.visualstudio.com/) (most popular, great for beginners)
  - [Zed](https://zed.dev/)
- Node.js (version 18 or higher recommended) 
  - Download from [Node.js website](https://nodejs.org/en/download/)
  - This also installs ```npm```, which manages the website's dependencies.
- Git
  - Download from [Git website](https://git-scm.com/downloads)
  - This is needed for downloading the code and tracking changes.
  
## Clone the repository
1. Visit the [MES website repository](https://github.com/McMaster-Economics-Society/mes-website).

2. Open your **Terminal** (Mac/Linux) or **Command Prompt** (Windows)
   - On Mac: Search for "Terminal" in Spotlight
   - On Windows: Search for "Command Prompt" or "PowerShell"
   - Or use the built-in terminal in your code editor (Highly recommended)
3. Navigate to the directory where you want to clone the repository with `cd`

4. Run this command:
```bash
git clone https://github.com/McMaster-Economics-Society/mes-website.git
```
This will download all the website files to your computer. 

## Run the website locally
1. Navigate to your project folder:

```bash
cd your_directory_name
```
The `cd` command changes the directory you're working with. In order to work with the repository, you'll need to navigate the terminal there.

2. Install the necessary dependencies:
```bash
npm install
```
This downloads all the packages the website needs to run (may take a minute or two).

3. Start the development server:
```bash
npm run dev
```

4. View the website:
- The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.
- The page will automatically refresh when you save changes to files

Tip: Keep the terminal open while you work on the website. This will allow you to see any errors or warnings that may occur.

## You're all set! 🎊

Now you can start editing the website. Changes you make to the code will show up immediately in your browser.

<!--**Need help?** Reach out to the dev team at [econ@themsss.com](mailto:econ@themsss.com)-->
