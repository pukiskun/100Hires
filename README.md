# Portfolio Project Initial Setup

This repository was created as the first step of the portfolio project. Below is the documentation of the initial environment setup and tool installations.

## 🛠 Tools Installed

- **[Cursor IDE](https://cursor.com/):** The primary code editor utilized for this project.
- **Claude Code:** AI assistant extension installed via the web browser.
- **Codex:** AI code generation extension installed via the web browser.

## 🚀 Steps Completed

1. **Installed Cursor IDE:** Downloaded and installed the application locally.
2. **Configured Claude Code:** Searched for the official Claude Code add-on via the web browser, installed it into Cursor, and successfully authenticated/logged in.
3. **Configured Codex:** Searched for the official Codex add-on via the web browser, installed it into Cursor, and successfully authenticated/logged in.
4. **Repository Creation:** Created this public repository on GitHub.
5. **Workspace Setup:** Cloned the repository locally and opened the project directory in Cursor.
6. **Documentation:** Drafted this `README.md` file to document the tools, steps, and problem-solving process.
7. **Version Control:** Committed the `README.md` file and pushed the changes to the remote GitHub repository.

## 💡 Issues Encountered and Solutions

> **Note:** Here is how I resolved the issues I ran into during the setup process:

- **Issue:** The "Claude Code" and "Codex" extensions were not showing up in Cursor's built-in extensions marketplace.
- **Solution:** I bypassed the built-in marketplace and searched for the official extensions directly through my web browser (Visual Studio Marketplace). I then routed the installation from the browser directly into the Cursor IDE.

- **Issue:** Pushing the first commit to GitHub prompted an authentication error in the terminal (`Permission denied (publickey)`).
- **Solution:** Git was attempting to connect via SSH without an established key. I resolved this by changing the remote URL to HTTPS (`git remote set-url origin`) and authenticating via the web browser popup (Git Credential Manager).

- **Issue:** Encountered a `Cannot read properties of undefined (reading 'activeEditor')` error notification in Cursor when trying to install the extensions.
- **Solution:** I figured out that the error occurred because I was attempting the installation while focused on the AI "Agent Window". I resolved this by switching my focus to the main "Editor Window" and ensuring a file was actively open, which allowed the extensions to initialize correctly.
