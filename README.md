# RPG Maker Game 1

## Overview
This repository contains a project created with RPG Maker MZ. It is designed for practicing and developing RPG games. Below are detailed instructions for setting up the repository, contributing to the project, and using tools like GitHub Copilot.

---

## Cloning the Repository

To clone this repository, you can use either the GitHub Desktop application or Git Bash. Follow the steps below:

### Using GitHub Desktop
1. Download and install [GitHub Desktop](https://desktop.github.com/).
2. Open GitHub Desktop and sign in with your GitHub account.
3. Click on `File > Clone Repository`.
4. Enter the repository URL: `https://github.com/Lokinious/rpg-maker-game-1`.
5. Choose a local directory to clone the repository.
6. Click `Clone`.

### Using Git Bash
1. Download and install [Git Bash](https://git-scm.com/).
2. Open Git Bash.
3. Run the following command:
   ```bash
   git clone https://github.com/Lokinious/rpg-maker-game-1.git
   ```
4. Navigate to the cloned directory:
   ```bash
   cd rpg-maker-game-1
   ```

---

## Creating a New Branch

Before making changes, create a new branch to keep your work organized and avoid conflicts.

### Steps to Create a New Branch
1. Open Git Bash or your preferred Git client.
2. Run the following command to create and switch to a new branch:
   ```bash
   git checkout -b your-branch-name
   ```
3. Replace `your-branch-name` with a descriptive name for your branch (e.g., `feature/add-new-character`).

### Good Practices for Branching
- Use descriptive branch names that reflect the purpose of the changes.
- Keep your branch focused on a single feature or fix.

---

## Opening the Project in RPG Maker MZ

1. Open RPG Maker MZ.
2. Click on `File > Open Project`.
3. Navigate to the cloned repository directory.
4. Select the `game.rmmzproject` file and click `Open`.
5. You can now begin working on the project.

---

## Good Commit Practices

### Writing Meaningful Commit Messages
- Use the present tense (e.g., "Add new character" instead of "Added new character").
- Keep the message concise but descriptive.
- Include a brief explanation of why the change was made if necessary.

### Example Commit Messages
- `Fix: Resolve issue with character animations`
- `Feat: Add new battle system mechanics`
- `Docs: Update README with setup instructions`

---

## Merging Code Safely

### Steps to Merge Code
1. Ensure your branch is up-to-date with the `main` branch:
   ```bash
   git fetch origin
   git merge origin/main
   ```
2. Resolve any merge conflicts (see below).
3. Push your branch to the remote repository:
   ```bash
   git push origin your-branch-name
   ```
4. Open a Pull Request (PR) on GitHub.
5. Request reviews from team members and address any feedback.
6. Once approved, merge the PR into the `main` branch.

### Resolving Merge Conflicts
1. Open the conflicting file(s) in a text editor like Visual Studio Code.
2. Look for conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).
3. Edit the file to resolve the conflict.
4. Mark the conflict as resolved:
   ```bash
   git add resolved-file
   ```
5. Commit the resolution:
   ```bash
   git commit
   ```

---

## Using GitHub CLI (Optional)

The GitHub CLI is a powerful tool for interacting with GitHub directly from your terminal. It can simplify tasks like cloning repositories, creating pull requests, and more.

### Installation
1. Download and install the GitHub CLI from the [official website](https://cli.github.com/).
2. Follow the installation instructions for your operating system.

### Setting Up
1. Authenticate with your GitHub account:
   ```bash
   gh auth login
   ```
2. Follow the prompts to log in using your GitHub credentials.

### Common Commands
- Clone a repository:
  ```bash
  gh repo clone Lokinious/rpg-maker-game-1
  ```
- Create a new branch:
  ```bash
  git checkout -b your-branch-name
  ```
- Open a pull request:
  ```bash
  gh pr create --fill
  ```

For more information, refer to the [GitHub CLI documentation](https://cli.github.com/manual/).

---

## Using GitHub Copilot

GitHub Copilot is an AI-powered code assistant that can help you write code faster and with fewer errors.

### Steps to Try GitHub Copilot
1. Install the [GitHub Copilot extension](https://github.com/features/copilot) for Visual Studio Code.
2. Open Visual Studio Code and sign in with your GitHub account.
3. Open a file in the repository and start typing code.
4. GitHub Copilot will suggest code completions and snippets.

---

## Additional Resources

Explore more guides and tutorials to enhance your RPG Maker MZ skills:

- [GitHub Development Guide](./guide-readmes/github-guide.md): Learn about GitHub workflows, including pulling changes, creating branches, and opening pull requests.
- [Starter Tutorials](./guide-readmes/starter-tutorials.md): A collection of helpful tutorials for getting started with RPG Maker MZ.

---

By following these guidelines, you can contribute effectively to the project and collaborate with other developers. Happy coding!

---

```
      ._________________.
     | ._____________. |
     | |             | |
     | |   Welcome   | |
     | |     to      | |
     | | RPG Maker!  | |
     | |_____________| |
     |_________________|
    /                 /\
   /_________________/  \
   \_________________\  /
    \_________________\/
```
