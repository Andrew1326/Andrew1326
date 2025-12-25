---
description: Commit all changes with a precise description and push to remote
---

# Commit and Push Workflow

You are committing and pushing code changes. Follow this process carefully.

## Step 1: Analyze Changes

Run these commands in parallel:
- `git status` - See all modified, staged, and untracked files
- `git diff` - See unstaged changes
- `git diff --cached` - See staged changes
- `git log -5 --oneline` - See recent commit style

## Step 2: Verify Clean Staging

Before committing, ensure these are NOT staged:
- `public/uploads/` - User uploads
- `test-results/` - Playwright artifacts
- `playwright-report/` - Test reports
- `.features-gen/` - Auto-generated specs
- Any `.env*` files
- Any temporary or generated files

If unwanted files are staged, remove them:
```bash
git rm -r --cached <unwanted-path>
```

## Step 3: Stage Changes

Stage all relevant code changes:
```bash
git add <files>
```

Be selective - only stage intentional changes.

## Step 4: Write Commit Message

Analyze ALL changes and write a precise commit message:

1. **Type**: Choose the appropriate type
   - `feat` - New feature
   - `fix` - Bug fix
   - `refactor` - Code restructuring
   - `chore` - Maintenance tasks
   - `docs` - Documentation changes
   - `test` - Test changes
   - `style` - Formatting changes

2. **Subject**: Short, imperative description (50 chars max)

3. **Body**: If changes are non-trivial, add bullet points explaining:
   - What was changed
   - Why it was changed
   - Any important details

## Step 5: Commit

Use HEREDOC format for the commit message:
```bash
git commit -m "$(cat <<'EOF'
type: short description

- Detail 1
- Detail 2
EOF
)"
```

## Step 6: Push

Push to the remote repository:
```bash
git push
```

If the branch has no upstream, use:
```bash
git push -u origin <branch-name>
```

## Step 7: Confirm

Report the result:
- Commit hash
- Files changed
- Remote URL if available

---

## Rules

- **Be precise**: The commit message must accurately describe what changed
- **Be concise**: Keep it short but informative
- **Never skip verification**: Always check for unwanted files first
- **Match project style**: Follow the commit message format used in recent commits

Now execute this workflow for the current changes.
