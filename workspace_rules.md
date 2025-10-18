Workspace Rules
Naming Conventions
• Branch Names: `feature/` (e.g., `feature/profile-setup`)
• Commit Messages: Present tense, concise, and descriptive (e.g., `Add profile creation
form`)
• File Naming: Use lowercase_with_underscores for Dart/Markdown files.
• Folder Structure: Organized by function (e.g., `/lib/screens/`, `/lib/widgets/`,
`/assets/audio/`).

Commit Guidelines
• Commit frequently — one logical change per commit.
• Always include a clear commit message that reflects the purpose.
• Avoid vague messages like 'update' or 'fix stuff'.
• Use `git add .`, `git commit -m ''`, and `git push` workflow.

Branching Strategy
• `main` – stable release branch; used for final project submissions.
• `dev` – active development branch; integrates tested features before merging into `main`.
• `feature/*` – temporary branches for individual feature development.
• All feature branches must be merged via pull requests after peer review.
Pull Request & Review Process
• Each pull request (PR) should include a short description of what was changed.
• Teammates must review and approve a PR before merging.
• If issues arise, feedback should be documented as GitHub comments before merge.
• All merges into `main` must pass linting and build tests.

Coding Workflow
• Follow Dart/Flutter formatting guidelines using `flutter format.`
• Use meaningful variable names and include inline comments for logic-heavy code.
• Document functions briefly using DartDoc comments (///).

Collaboration Rules
• All team members must pull the latest changes before starting new work (`git pull`).
• Avoid working directly on the `main` branch.
• Use GitHub Issues to track bugs or feature requests.
• Sync changes daily to prevent merge conflicts.

Documentation Standards
• Maintain up-to-date README with new features and file structure.
• Include detailed commit messages when major architecture or features change.
• Use Markdown (.md) for documentation files and keep them versioned with the project.
