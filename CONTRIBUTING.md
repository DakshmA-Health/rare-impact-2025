# Contributing to Rare Impact 2025

Thank you for your interest in contributing to Rare Impact 2025! This guide will help you understand how to contribute to the hackathon repository.

## 📋 Table of Contents
- [Code of Conduct](#code-of-conduct)
- [Development Workflow](#development-workflow)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Documentation](#documentation)
- [Getting Help](#-getting-help)

## Code of Conduct

Please read and adhere to our [Code of Conduct](./CODE_OF_CONDUCT.md). We are committed to providing a welcoming and inclusive environment for all participants.

## Development Workflow

### For Hackathon Teams (Submissions)

If you're submitting a hackathon project, follow the detailed workflow in [Submission Guidelines](./SUBMISSION_GUIDELINES.md#-git-workflow-for-teams).

**Quick Summary:**
1. Team leader forks the repository
2. Create a branch: `submission/your-team-name` (or `your-team-name`)
3. Team members collaborate on the leader's fork
4. Create your submission in `submissions/your-team-name/`
5. Submit PR from your branch (NOT from `main`)

### For General Contributions

If you're contributing improvements to the hackathon repository itself (not submitting a project):

#### 1. Fork the Repository
```bash
git clone https://github.com/your-username/rare-impact-2025.git
cd rare-impact-2025
git remote add upstream https://github.com/DakshmA-Health/rare-impact-2025.git
```

#### 2. Create a Feature Branch
```bash
git checkout -b feature/your-feature-name
```

#### 3. Make Your Changes
- Follow the coding standards below
- Write clear commit messages
- Keep changes focused and atomic

#### 4. Keep Your Fork Updated
```bash
git fetch upstream
git merge upstream/main
```

## Pull Request Process

1. Ensure your fork is up to date with the main repository
2. **Create a new pull request from your feature/submission branch** (never from `main`)
3. Fill out the pull request template completely
4. Ensure all CI checks pass
5. Request reviews from team members if needed

## Coding Standards

### General
- Use clear, descriptive variable and function names
- Follow the principle of least privilege
- Write self-documenting code with comments when necessary
- Keep functions small and focused on a single responsibility

### Documentation
- Document all public APIs and interfaces
- Include examples in your documentation
- Keep documentation up to date with code changes
- Use consistent formatting in markdown files

### Testing
- Write tests for new features
- Ensure all tests pass before submitting a PR
- Include test instructions in your PR description

## 🛠️ Development Tools

### Recommended Tools
- [GitHub CLI](https://cli.github.com/)
- [Pre-commit Hooks](https://pre-commit.com/)
- [EditorConfig](https://editorconfig.org/)

### VS Code Extensions
- ESLint
- Prettier
- Markdown All in One
- GitLens

## 📝 Reporting Issues

When creating an issue, please include:
1. A clear title and description
2. Steps to reproduce the issue
3. Expected vs. actual behavior
4. Screenshots if applicable
5. Browser/OS version if relevant

## 🆘 Getting Help

If you need assistance:
- **Email:** support@dakshamahealth.org

## 🙏 Acknowledgments

- Thank you to all our contributors and participants
- Special thanks to our partners and sponsors
- Inspired by the open source community

---

*Last updated: November 2025*
