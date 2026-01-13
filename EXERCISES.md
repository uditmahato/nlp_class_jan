# GitHub Exercises for NLP Class

This file contains hands-on exercises to help you learn GitHub collaboration.

## Exercise 1: Making Your First Contribution (Beginner)

**Objective:** Learn basic Git operations and make your first commit.

**Steps:**
1. Assign yourself to one of the student files (student1.txt through student8.txt)
2. Open your assigned file
3. Fill in your information:
   - Your name
   - Your favorite NLP topic (e.g., sentiment analysis, machine translation, chatbots)
   - A brief description of your interest in NLP
4. Stage your changes: `git add studentX.txt`
5. Commit with a clear message: `git commit -m "Add [YourName]'s profile to studentX.txt"`
6. Push to your branch
7. Create a pull request

**Success Criteria:**
- ✅ Clear commit message
- ✅ Only modified your assigned file
- ✅ Pull request has a description

---

## Exercise 2: Collaborative Document Editing (Intermediate)

**Objective:** Learn to work on shared files and handle basic conflicts.

**Steps:**
1. Open `team_collaboration.md`
2. Add your name and GitHub username to the Team Members section
3. Add one NLP topic you're interested in to the topics list
4. Add one project idea under "Group Project Ideas"
5. Commit your changes
6. If there's a conflict, resolve it (keep both changes when appropriate)
7. Create a pull request

**Success Criteria:**
- ✅ Successfully merged changes with others
- ✅ Resolved any conflicts properly
- ✅ All team members' contributions are preserved

---

## Exercise 3: Reviewing Code (Intermediate)

**Objective:** Learn to review others' pull requests.

**Steps:**
1. Go to the repository's Pull Requests tab
2. Choose a pull request from another student
3. Review their changes:
   - Check if the commit message is clear
   - Verify they followed the instructions
   - Look for any typos or errors
4. Leave constructive feedback:
   - If everything looks good: "LGTM! (Looks Good To Me)" or approve the PR
   - If there are issues: Politely suggest improvements
5. Approve or request changes

**Success Criteria:**
- ✅ Reviewed at least one pull request
- ✅ Provided constructive feedback
- ✅ Used respectful language

---

## Exercise 4: Creating and Managing Branches (Intermediate)

**Objective:** Understand Git branching strategy.

**Steps:**
1. Create a new branch: `git checkout -b feature/your-name-nlp-project`
2. Create a projects directory: `mkdir projects`
3. Create a new file: `projects/your-name-project-idea.md`
4. Write a brief project proposal for an NLP project:
   - Project title
   - Problem statement
   - Proposed approach
   - Expected outcomes
5. Commit and push your branch
6. Create a pull request from your feature branch

**Success Criteria:**
- ✅ Branch name follows naming convention
- ✅ New file is well-structured
- ✅ Pull request clearly describes the project

---

## Exercise 5: Working with Issues (Advanced)

**Objective:** Learn to use GitHub Issues for project management.

**Steps:**
1. Create a new issue for a potential NLP project or improvement
2. Use a clear title and description
3. Add labels if available (e.g., "enhancement", "question", "good first issue")
4. Reference the issue in your commit: `git commit -m "Add project proposal (closes #X)"`
5. Link your pull request to the issue

**Success Criteria:**
- ✅ Issue has clear title and description
- ✅ Commit references the issue number
- ✅ Issue closes automatically when PR is merged

---

## Exercise 6: Resolving Merge Conflicts (Advanced)

**Objective:** Master conflict resolution in collaborative projects.

**Scenario:** Two students edit the same section of `team_collaboration.md`

**Steps:**
1. Coordinate with another student to both edit the same section
2. First student merges their PR
3. Second student encounters a merge conflict
4. Second student resolves the conflict:
   ```bash
   git pull origin main
   # Resolve conflicts in the file
   git add .
   git commit -m "Resolve merge conflict in team collaboration"
   git push
   ```
5. Complete the merge

**Success Criteria:**
- ✅ Both students' changes are preserved
- ✅ No conflict markers remain in the file
- ✅ File is properly formatted after merge

---

## Exercise 7: Project Workflow Simulation (Advanced)

**Objective:** Simulate a real-world collaborative project workflow.

**Steps:**
1. Form groups of 2-3 students
2. Choose an NLP topic for a mini-project
3. Create a project structure (create these directories and files as part of the exercise):
   ```
   projects/
     team-name/
       README.md          (project description)
       proposal.md        (project proposal)
       code/              (for code files)
       docs/              (for documentation)
   ```
4. Each team member:
   - Creates a feature branch
   - Works on a different component
   - Creates a pull request
   - Reviews teammates' PRs
5. Merge all PRs to complete the project

**Success Criteria:**
- ✅ Clear project structure
- ✅ All team members contributed
- ✅ Pull requests were reviewed before merging
- ✅ Project documentation is complete

---

## Bonus Challenges

### Challenge 1: Use GitHub's Web Interface
Complete Exercise 1 using only GitHub's web interface (no command line).

### Challenge 2: Write a Git Hook
Create a pre-commit hook that checks for common issues (e.g., large files, sensitive data).

### Challenge 3: GitHub Actions
Set up a simple GitHub Action to automatically greet new contributors.

### Challenge 4: Fork and Contribute
Find another NLP repository on GitHub, fork it, fix a typo or improve documentation, and submit a PR.

---

## Tips for Success

1. **Commit Often:** Make small, frequent commits rather than large, infrequent ones
2. **Pull Before Push:** Always pull the latest changes before pushing your work
3. **Branch Names:** Use descriptive names like `feature/add-profile` or `fix/typo-readme`
4. **Descriptive Messages:** Write commit messages that explain WHY, not just WHAT
5. **Review Carefully:** Take time to review your own changes before creating a PR
6. **Communicate:** Use PR descriptions and comments to explain your changes
7. **Be Patient:** Learning Git takes time; don't get discouraged by mistakes

---

## Common Issues and Solutions

### Issue: "Your branch is behind origin/main"
**Solution:** 
```bash
git pull origin main
git push
```

### Issue: "Merge conflict"
**Solution:** 
1. Open the file with conflicts
2. Look for `<<<<<<<`, `=======`, `>>>>>>>`
3. Edit to keep the correct changes
4. Remove the conflict markers
5. `git add .` and `git commit`

### Issue: "Permission denied"
**Solution:** Check that you've forked the repository and are pushing to your fork, not the original repo.

### Issue: "Nothing to commit"
**Solution:** Make sure you've saved your file changes and used `git add` to stage them.

---

## Grading Rubric (Optional for Instructors)

| Criteria | Points | Description |
|----------|--------|-------------|
| Commits | 20 | Clear, descriptive commit messages |
| Pull Requests | 20 | Well-described PRs with proper formatting |
| Code Reviews | 20 | Constructive feedback on others' work |
| Collaboration | 20 | Active participation in team activities |
| Best Practices | 20 | Following GitHub workflow and conventions |

**Total: 100 points**

---

Good luck with your GitHub learning journey! Remember, everyone makes mistakes when learning Git – it's part of the process. 🎓
