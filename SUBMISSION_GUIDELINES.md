# 📋 Submission Guidelines

## 🎯 What to Submit

### Required Components
1. **Project Documentation** (`README.md`)
   - Problem statement and solution overview
   - Team information
   - Technical implementation details
   - Setup and usage instructions

2. **Demo Materials**
   - Demo video link
   - Screenshots or screen recordings
   - Live demo link (if applicable)

3. **Source Code**
   - Well-documented code
   - Clear directory structure
   - Dependencies list (e.g., `requirements.txt` for Python)

## 📂 Project Structure

**Simple Structure:** Create ONE folder with your team name. All your submission files go directly in this folder.

```
submissions/
└── your-team-name/       # Use hyphens, no spaces (e.g., "team-innovators")
    ├── README.md         # REQUIRED: All project documentation here
    ├── [your source code files]  # All code files directly in this folder
    ├── [screenshots/images]       # Demo materials directly in this folder
    └── [any other files]         # Everything in one place
```

> 💡 **Keep it simple:** Put everything (code, docs, images, etc.) directly in your team folder. No subfolders needed!

## 🔀 Git Workflow for Teams

### Step-by-Step Submission Process

1. **Team Leader Forks the Repository**
   - Go to the main repository: `https://github.com/DakshmA-Health/rare-impact-2025`
   - Click "Fork" button to create your own copy

2. **Create a Submission Branch** (Recommended)
   ```bash
   git clone https://github.com/your-username/rare-impact-2025.git
   cd rare-impact-2025
   git checkout -b submission/your-team-name
   ```
   > 💡 **Why use a branch?** It keeps your main branch clean, allows easy updates, and follows Git best practices.

3. **Set Up Team Collaboration**
   - **Option A:** Leader adds team members as collaborators to their fork (Settings → Collaborators)
   - **Option B:** Team members clone the leader's fork and work on the same branch
   
   For team members joining:
   ```bash
   git clone https://github.com/leader-username/rare-impact-2025.git
   cd rare-impact-2025
   git checkout submission/your-team-name
   ```

4. **Create Your Submission Folder**
   ```bash
   mkdir -p submissions/your-team-name
   cd submissions/your-team-name
   # Add all your files here: README.md, source code, images, etc.
   # Everything goes directly in this folder - no subfolders needed!
   ```

5. **Commit and Push Your Work**
   ```bash
   git add .
   git commit -m "Add submission for team-name"
   git push origin submission/your-team-name
   ```

6. **Create Pull Request**
   - Go to your fork on GitHub
   - Click "New Pull Request"
   - **Source:** `your-username/rare-impact-2025:submission/your-team-name`
   - **Target:** `DakshmA-Health/rare-impact-2025:main`
   - Fill out the [Pull Request Template](../PULL_REQUEST_TEMPLATE.md)

### ⚠️ Important Notes

- **Always create a branch** - Do NOT submit PRs directly from `main` branch
- **Branch naming:** Use `submission/team-name` or just `team-name` (use hyphens, no spaces)
- **Updating your submission:** Push new commits to the same branch - your PR will automatically update
- **Keep fork updated:** Periodically sync with the main repository:
  ```bash
  git remote add upstream https://github.com/DakshmA-Health/rare-impact-2025.git
  git fetch upstream
  git merge upstream/main
  ```

## 📝 README.md Template

```markdown
# [Project Name]

## 👥 Team
- [Team Member 1] (Role, Contact)
- [Team Member 2] (Role, Contact)

## 🎯 Problem Statement
[1-2 paragraphs about the problem you're solving]

## 💡 Solution
[Detailed explanation of your solution]

## 🛠️ Technical Implementation
- **Tech Stack**: [List technologies used]
- **Key Features**: [List main features]
- **Architecture**: [Brief system architecture]

## 🚀 Getting Started
[Setup and installation instructions]

## 📹 Demo
[Link to video demo and description of screenshots]

## 📈 Future Work
[Potential improvements or next steps]
```

## ⚙️ Technical Requirements

### Code Quality
- Follow language-specific best practices
- Include clear, concise comments
- Document all public APIs and functions

### Version Control
- Use meaningful commit messages
- Keep commits focused and atomic
- Follow Git branching best practices

### Dependencies
- List all third-party libraries and tools
- Include version numbers
- Document any setup requirements

## 🚫 Common Pitfalls to Avoid

1. **Incomplete Submissions**
   - Missing demo video link
   - Incomplete documentation
   - No clear setup instructions

2. **Technical Issues**
   - Broken dependencies
   - Missing environment variables
   - Platform-specific assumptions

3. **Documentation Gaps**
   - Unclear problem statement
   - Missing architecture diagrams
   - No user guides

## 🆘 Getting Help

If you encounter issues:
- **Email:** support@dakshamahealth.org

> ⏰ **Remember**: Submit early and test thoroughly before the deadline!

## 📜 License

By submitting your project, you agree that your submission will be made available under the same license terms as this repository. All participants retain ownership of their intellectual property.
