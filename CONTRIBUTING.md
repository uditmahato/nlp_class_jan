# Contributing to NLP Class Repository

Welcome to the NLP Class! This guide will help you learn how to contribute using GitHub.

## Getting Started

### 1. Fork and Clone the Repository
```bash
# Fork the repository on GitHub first, then clone your fork
git clone https://github.com/YOUR-USERNAME/nlp_class_jan.git
cd nlp_class_jan
```

### 2. Create a New Branch
Always create a new branch for your changes:
```bash
git checkout -b your-name-feature
```

Example: `git checkout -b john-add-profile`

### 3. Make Your Changes
- Edit your assigned student file (student1.txt, student2.txt, etc.)
- Add your name and favorite NLP topic
- Write something about your interest in NLP

### 4. Commit Your Changes
```bash
git add .
git commit -m "Add [Your Name]'s profile information"
```

**Good commit messages:**
- "Add John's profile to student1.txt"
- "Update team collaboration with project ideas"
- "Fix typo in student3.txt"

**Bad commit messages:**
- "update"
- "changes"
- "fix"

### 5. Push Your Changes
```bash
git push origin your-name-feature
```

### 6. Create a Pull Request
1. Go to the original repository on GitHub
2. Click "New Pull Request"
3. Select your branch
4. Add a clear description of your changes
5. Submit the pull request

## GitHub Best Practices

### Do's ✅
- Write clear, descriptive commit messages
- Keep commits focused on one change
- Pull the latest changes before starting work
- Review your own changes before submitting
- Be respectful in code reviews

### Don'ts ❌
- Don't commit large binary files
- Don't make unrelated changes in the same commit
- Don't force push to shared branches
- Don't commit sensitive information (passwords, API keys)

## Common Git Commands

```bash
# Check status of your files
git status

# See what changes you've made
git diff

# Pull latest changes from main
git pull origin main

# View commit history
git log --oneline

# Undo changes to a file (before commit)
git checkout -- filename

# View all branches
git branch -a
```

## Handling Merge Conflicts

If you encounter a merge conflict:

1. Don't panic! Conflicts are normal in collaborative work
2. Open the conflicting file
3. Look for conflict markers: `<<<<<<<`, `=======`, `>>>>>>>`
4. Decide which changes to keep
5. Remove the conflict markers
6. Commit the resolved changes

## Exercise Workflow

### Exercise 1: Your First Commit
1. Clone the repository
2. Create a branch: `git checkout -b firstname-lastname`
3. Edit your assigned student file
4. Commit: `git commit -m "Add [name]'s information"`
5. Push and create a pull request

### Exercise 2: Team Collaboration
1. Update the `team_collaboration.md` file
2. Add your name and a project idea
3. Submit a pull request
4. Review another student's pull request

### Exercise 3: Resolving Conflicts
1. Intentionally create overlapping changes
2. Practice resolving merge conflicts
3. Learn to communicate about conflicting changes

## Getting Help

If you're stuck:
1. Check this guide first
2. Use `git status` to see what's happening
3. Search for error messages online
4. Ask your classmates or instructor
5. GitHub has excellent documentation at https://docs.github.com

## Resources

- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)

Happy coding! 🚀
