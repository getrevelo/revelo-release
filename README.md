# revelo. 

[![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/getrevelo/revelo-release?include_prereleases)](https://github.com/getrevelo/revelo-release/releases/tag/v0.0.1-beta.1)

A powerful VS Code extension designed by revelo. to streamline your project management and Git workflow directly within your editor. Automate commits and integrate seamlessly with your GitHub repositories.


## Features

-   **Automated Project Commits**: Stage all changes in your current project, commit them, and push to the configured GitHub repository and branch with a single command.
-   **Secure GitHub Token Configuration**: Securely store your GitHub Personal Access Token (PAT) within VS Code's Secret Storage for protected API interactions.
-   **Effortless Repository Connection**: Link your local Git repositories to specific branches on GitHub, enabling targeted automation.
-   **Intuitive Setup UI**: User-friendly webview panels guide you through the initial configuration process.

## Commands

Access all Revelo commands via the Command Palette:

-   **Open the Command Palette**: Press `Ctrl + Shift + P` (Windows/Linux) or `Cmd + Shift + P` (macOS).
-   **Available Commands:**
    -   `Revelo: Open Panel`: Opens the main Revelo welcome and command dashboard panel.
    -   `Revelo: Configure GitHub Token`: Guides you through setting up your GitHub Personal Access Token.
    -   `Revelo: Connect Repository`: Helps you link a local repository to a remote GitHub branch for Revelo's operations.
    -   `Revelo: Auto-Commit Project`: Automatically stages all pending changes in the current project, creates a commit, and pushes to the configured GitHub repository and branch.

## Requirements

-   Git installed and configured on your system.
-   A GitHub account.
-   A GitHub Personal Access Token (PAT) with the `repo` scope (needed for Revelo to interact with your repositories).

## How to Get Started (Installing the Beta VSIX)

Since Revelo is currently in beta and distributed via a VSIX package on GitHub, follow these steps to install it:

1.  **Download the VSIX Package**:
    * Locate the latest beta release (e.g., `v0.0.1-beta.1`).
    * Under "Assets", download the `revelo-X.Y.Z.vsix` file (e.g., `revelo-0.0.1-beta.1.vsix`).

2.  **Install in VS Code**:
    * Open **Visual Studio Code**.
    * Go to the **Extensions view** (`Ctrl+Shift+X` on Windows/Linux or `Cmd+Shift+X` on macOS).
    * Click on the **"..." (More Actions)** menu (three dots or a gear icon) at the top of the Extensions sidebar.
    * Select **"Install from VSIX..."**.
    * Navigate to where you downloaded the `.vsix` file and select it.
    * VS Code will install the extension. You may need to reload your VS Code window for the extension to fully activate (VS Code usually prompts you).

3.  **Configure Revelo**:
    * Open any folder in VS Code that contains a Git repository.
    * Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`).
    * Run `Revelo: Configure GitHub Token` and follow the instructions in the panel to securely store your PAT.
    * Run `Revelo: Connect Repository` to link your local project to a specific remote branch.

4.  **Automate Your Workflow**:
    * Make some changes in your project files.
    * Open the Command Palette and run `Revelo: Auto-Commit Project` to automatically stage, commit, and push your changes.

## License

This software is proprietary and is not open-source. All rights reserved by **revelo. and Dev Sehgal**. Unauthorized copying, modification, or distribution is strictly prohibited.


