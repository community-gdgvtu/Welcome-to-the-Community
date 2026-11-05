# Contributing

Thank you for contributing! This repository is designed for beginner-friendly Git and GitHub practice.

## Contribution rules

- Add **one new file**: `contributors/YOUR-GITHUB-USERNAME.md`.
- Do not edit or overwrite another contributor's profile.
- Use a simple filename: lowercase GitHub username, with no spaces.
- Keep your profile respectful, concise, and relevant to the developer community.
- Do not include private contact information, passwords, access tokens, API keys, or other secrets.
- Do not add files unrelated to the activity.

## Suggested profile format

```markdown
# Your Name

- GitHub: https://github.com/YOUR-GITHUB-USERNAME
- Interests: AI, web development, open source
- Fun fact: One sentence about yourself
```

## Fork-and-pull-request workflow

1. Click **Fork** on the repository page.
2. Clone your own fork:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Welcome-to-the-Community.git
   cd Welcome-to-the-Community
   ```

3. Create a branch:

   ```bash
   git switch -c add-YOUR-USERNAME
   ```

4. Add your profile at `contributors/YOUR-USERNAME.md`.
5. Inspect and stage your change:

   ```bash
   git status
   git add contributors/YOUR-USERNAME.md
   ```

6. Commit and push:

   ```bash
   git commit -m "Add YOUR-USERNAME to community"
   git push -u origin add-YOUR-USERNAME
   ```

7. Open your fork on GitHub and select **Contribute** / **Open pull request** or **Compare & pull request**.
8. Make sure the base repository is the original project and the base branch is `main`.
9. Give the pull request a clear title and description. Respond politely to review feedback.

## Review and merge

A maintainer will check your contribution. They may request changes. A pull request is merged only after review and when the contribution meets the repository guidelines.
