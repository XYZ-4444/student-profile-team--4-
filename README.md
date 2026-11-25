# Student Profile Team Repository

A starter project for the Web Development Lab activity on Git and GitHub. The team will combine one README and three student-created HTML pages in a shared repository.

## Team assignments

| Student | Responsibility | Branch | File to add to the repository root |
|---|---|---|---|
| Student 1 | Team lead and reviewer | `main` | `README.md` |
| Student 2 | Profile developer | `feature/profile` | `profile.html` |
| Student 3 | Skills developer | `feature/skills` | `skills.html` |
| Student 4 | Contact developer | `feature/contact` | `contact.html` |

For a team of three, one developer also takes on the team lead and reviewer responsibilities. Keep all three developer assignments so each page is contributed through its own feature branch.

## Prepare the repository

1. Replace `<team-number>` in the repository name with your team's number. Create a **public** GitHub repository named `student-profile-team-<team-number>`.
2. Student 1 adds this README as the repository's `README.md`, invites the team members as collaborators, then shares the repository URL.
3. Each student clones the repository to their own computer:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

4. Before a developer starts, make sure the latest `main` branch contains the README:

   ```bash
   git switch main
   git pull origin main
   ```

## Developer workflow

Each developer works individually in their own clone. Copy the assigned starter page from this bundle into the repository root, using the filename in the table above.

### Student 2: profile page

```bash
git switch -c feature/profile
# Copy student-2/profile.html from this bundle into the repository root as profile.html.
git add profile.html
git commit -m "Add student profile page"
git push -u origin feature/profile
```

### Student 3: skills page

```bash
git switch -c feature/skills
# Copy student-3/skills.html from this bundle into the repository root as skills.html.
git add skills.html
git commit -m "Add student skills page"
git push -u origin feature/skills
```

### Student 4: contact page

```bash
git switch -c feature/contact
# Copy student-4/contact.html from this bundle into the repository root as contact.html.
git add contact.html
git commit -m "Add student contact page"
git push -u origin feature/contact
```

After pushing, each developer opens a Pull Request from their feature branch to `main`. The team lead reviews each PR and merges approved changes. Do not have one person run another student's Git commands or submit their contribution for them.

## Personalize before publishing

Replace bracketed prompts such as `[Your name]`, `[Add a short introduction]`, and `[Skill 1]` with details the student is comfortable sharing. These files go in a public repository: do not add home addresses, personal phone numbers, passwords, private account details, or other sensitive information. For the contact page, use a school-approved public email or portfolio link only if appropriate; leaving the optional links as placeholders is fine.

## Final repository checklist

The `main` branch should contain:

- `README.md`
- `profile.html`
- `skills.html`
- `contact.html`

Before the class demonstration, confirm that all three PRs are merged. Be ready to show the repository URL, feature branches, each student's commits, and the merged PRs. Update the activity completion tracker linked in the worksheet only after your team has verified the repository and PRs.
