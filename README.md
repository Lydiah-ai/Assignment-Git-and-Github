Fundamental Concepts of Version Control & GitHub's Popularity
•	Version control tracks changes in code over time, allowing collaboration and rollback to previous versions.
•	Git is a distributed version control system, meaning every developer has a complete history of the project.
•	GitHub is widely used because it provides cloud storage, collaboration tools, and integration with CI/CD pipelines.
•	It ensures project integrity by preventing data loss, enabling collaboration, and managing multiple development branches.
2. Setting Up a New Repository on GitHub
Key Steps:
1.	Sign in to GitHub and click on New Repository.
2.	Choose a repository name and add a description.
3.	Decide between public (visible to everyone) or private (restricted access).
4.	Initialize with a README (optional but recommended).
5.	Choose a license and .gitignore (optional, helps manage ignored files).
6.	Click Create Repository and start working on your project.
3. Importance of a README File
•	A README provides essential information about the project.
•	A well-written README includes:
o	Project name and description
o	Installation and setup instructions
o	Usage examples
o	Contribution guidelines
o	License and author information
•	It helps in collaboration by guiding contributors and users.
4. Public vs. Private Repositories
Feature	Public Repository	Private Repository
Visibility	Open to everyone	Restricted access
Collaboration	Anyone can contribute via pull requests	Only invited users can contribute
Security	Less secure, code is public	More secure, code is private
Best Use Case	Open-source projects	Proprietary or confidential projects
5. Making Your First Commit
Steps:
1.	Clone or initialize a Git repository (git init).
2.	Add a file (e.g., README.md).
3.	Stage the file (git add README.md).
4.	Commit the change (git commit -m "Initial commit").
5.	Push to GitHub (git push origin main).
•	Commits track changes, making it easier to revert to earlier versions.
6. Branching in Git
•	Branches allow multiple people to work on different features without affecting the main project.
•	Steps to create and use branches:
1.	Create a new branch (git branch feature-branch).
2.	Switch to it (git checkout feature-branch or git switch feature-branch).
3.	Work on your changes and commit them.
4.	Merge back to main (git merge feature-branch).
5.	Delete the branch (git branch -d feature-branch).
7. Role of Pull Requests (PRs)
•	PRs allow reviewing changes before merging into the main branch.
•	Steps to create a PR:
1.	Push changes to GitHub.
2.	Navigate to the repository and open a pull request.
3.	Request reviews from teammates.
4.	Reviewers provide feedback and approve changes.
5.	Merge the PR into the main branch.
8. Forking vs. Cloning
•	Forking: Creates a personal copy of someone else's repository on GitHub.
•	Cloning: Creates a local copy of a repository on your computer.
•	When to fork? Useful for contributing to open-source projects without affecting the original repository.
9. Issues & Project Boards in GitHub
•	Issues: Used for bug tracking, feature requests, and task discussions.
•	Project Boards: Organize work with Kanban-style tracking.
•	Example: A team working on a software project can assign issues to developers and track progress using project boards.
10. Common Challenges & Best Practices
Challenges:
•	Merge conflicts
•	Forgetting to commit frequently
•	Pushing sensitive data
Best Practices:
•	Use meaningful commit messages
•	Regularly pull updates before pushing
•	Use .gitignore to exclude unnecessary files
•	Follow a structured branching strategy (e.g., GitFlow)
