## Reusable workflows for my personal projects

### Github
- Rust Pull Request - includes pre-commit, formatting, tests
- Rust Release - includes updating Cargo.toml version, compiling binary for Mac and Windows, creates GitHub release
- Pre-Commit checks in the pipeline

### Reference
This project uses semantic versioning and gets tagged on merge event.

This project uses pre-commit hook for static code analysis
Steps:
1. Step 1: Install [pre-commit]()
2. Step 2: Run `pre-commit install` to add hook to .git/hooks/pre-commit - from now on git commit event staged files will be checked
3. Step 3: To run pre-commit on all files `pre-commit run --all-files`
