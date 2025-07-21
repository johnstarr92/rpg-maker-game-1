# GitHub Development Guide

This guide provides step-by-step instructions for standard GitHub development workflows, including pulling changes, creating branches, and opening pull requests (PRs). It also includes best practices for effective collaboration.

---

## Pulling Changes from the Main Branch

1. Open your terminal or Git client.
2. Ensure you are on the `main` branch:
   ```bash
   git checkout main
   ```
3. Pull the latest changes:
   ```bash
   git pull origin main
   ```

---

## Creating a New Branch

1. Create and switch to a new branch:
   ```bash
   git checkout -b your-branch-name
   ```
   Replace `your-branch-name` with a descriptive name (e.g., `feature/add-new-feature`).

2. Push the branch to the remote repository:
   ```bash
   git push -u origin your-branch-name
   ```

---

## Making Changes and Committing

1. Make your changes in the codebase.
2. Stage the changes:
   ```bash
   git add .
   ```
3. Commit the changes with a meaningful message:
   ```bash
   git commit -m "Your commit message"
   ```

### Example Commit Messages
- `Fix: Resolve issue with login functionality`
- `Feat: Add user profile page`
- `Docs: Update README with setup instructions`

---

## Opening a Pull Request (PR)

1. Push your branch to the remote repository (if not already pushed):
   ```bash
   git push
   ```
2. Go to the repository on GitHub.
3. Click on the `Pull Requests` tab.
4. Click `New Pull Request`.
5. Select your branch and compare it with the `main` branch.
6. Add a title and description for your PR.
7. Click `Create Pull Request`.

---

## Resolving Merge Conflicts

1. If there are conflicts, GitHub will notify you in the PR.
2. Pull the latest changes from `main`:
   ```bash
   git pull origin main
   ```
3. Open the conflicting files in your text editor.
4. Resolve the conflicts by editing the file and removing conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).
5. Stage and commit the resolved files:
   ```bash
   git add resolved-file
   git commit
   ```
6. Push the changes:
   ```bash
   git push
   ```

---

## Best Practices

- **Write clear commit messages**: Use the present tense and be concise.
- **Keep branches focused**: Work on one feature or fix per branch.
- **Request reviews**: Always request a review for your PRs.
- **Test your changes**: Ensure your changes work as expected before committing.

---


By following this guide, you can collaborate effectively and maintain a clean and organized workflow.
