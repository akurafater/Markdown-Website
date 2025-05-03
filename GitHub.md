- **[Back](index.md)**

# GitHub

**GitHub** is a widely-used, proprietary developer platform that enables developers to create, manage, and share code collaboratively. It is built on top of **Git**, a distributed version control system created by Linus Torvalds. GitHub enhances Git's capabilities by providing a web-based interface, access control, issue tracking, feature request management, continuous integration, project documentation (via wikis), and more. Since 2018, GitHub has been a subsidiary of **Microsoft**, headquartered in California.

---

## What is GitHub Used For?

GitHub is a cloud-based hosting service that lets you manage **Git repositories**. It is especially popular among developers for both open-source and private software projects.

### Key Uses:
- **Version Control:** Keep track of changes in code across different versions.
- **Collaboration:** Work with multiple developers on the same project efficiently.
- **Open Source Sharing:** Share your repositories with the world or contribute to others.
- **Project Management:** Use tools like issues, milestones, and projects to manage tasks and track progress.
- **Documentation:** Use README files and wikis to document your project clearly.
- **CI/CD Integration:** Automate workflows like testing and deployment with GitHub Actions.

---

## Key Benefits of GitHub

Here are some of the main advantages of using GitHub:

- **User-Friendly Interface:** Clean graphical UI that simplifies Git operations.
- **Team Collaboration:** Coordinate, review code, and manage contributions easily.
- **Change Management:** Track changes efficiently with version history.
- **Learning and Inspiration:** Explore public repositories to learn or get inspired.
- **Contribute to Projects:** Fork and contribute to existing repositories.
- **Integration Ecosystem:** Works with tools like Slack, Trello, VS Code, Jenkins, etc.

---

## Getting Started with GitHub

To start using GitHub:

1. **Create an account** at [github.com](https://github.com)
2. **Install Git** on your machine.
3. **Create or clone** a repository.
4. **Commit**, **push**, and **pull** code with Git or GitHub Desktop.
5. Use **branches** and **pull requests** to manage and review features.

---

## GitHub Workflow

The typical GitHub workflow includes:

- Creating a repository  
- Creating a branch  
- Committing changes  
- Making a pull request  
- Reviewing changes  
- Deploying changes  
- Merging to the main branch

---

## Creating a Repository

A **repository** is where your project’s files, folders, and metadata are stored. You can include:

- `README` file – Describes your project. Formats:
  - `README`
  - `README.md`
  - `README.asciidoc`

- `.gitignore` file – Lists untracked files Git should ignore (e.g., logs, cache, secrets).

- `LICENSE` file – Specifies the usage rights and restrictions of your code.

---

## Creating a Branch

- A **branch** allows you to work on features or fixes separately.
- The default branch is usually `main` or `master`.
- Changes in a branch do **not** affect the main branch until merged.
- Branching lets you safely test and build features.

---

## Committing Changes

- A **commit** saves a snapshot of your changes.
- Each commit has a message describing the change.
- Commits help track history and easily fix bugs by reverting changes.

---

## Adding Collaborators

- You can **add collaborators** to work on your project.
- Collaborators have read/write access.
- You must send an invitation; once accepted, they can contribute.
- Permissions can be modified or revoked anytime.

---

## Forking a Repository

**Forking** means creating your own copy of someone else's repository.

Common use cases:
- Use someone’s project as a base for your own.
- Suggest changes to another repository.

After forking:
- You get a copy under your account.
- You can edit it without affecting the original repository.

---

## Working with Remote Repositories

A **remote repository** is hosted on a server (like GitHub) and accessed over the internet.

### Key Commands:
- Clone a remote repository:
  ```bash
  git clone <repository_url>
