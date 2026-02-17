# Project Setup Checklist

Complete the following steps after creating your project from this template to customize and finalize your project.

## Essential Setup Tasks

- [ ] **Enable GitHub Security Alerts**: Navigate to your repository's "Security" tab on GitHub and enable Dependabot alerts and security updates to monitor vulnerabilities in dependencies.
- [ ] **Protect the Main Branch**: In repository settings under "Branches", add a branch protection rule for `main` to require pull request reviews before merging and prevent force pushes.
- [ ] **Update Project Details**: Replace all placeholder values in the following files with your actual project information:
  - `FULLNAME` → Your full name (e.g., "Jane Doe")
  - `USERNAME` → Your GitHub username (e.g., "janedoe")
  - `REPO_NAME` → Your repository name (e.g., "my-awesome-project")
  - `SHORT_DESCRIPTION` → Brief description of your project (e.g., "A template for small GitHub projects")
  - `[INSERT CONTACT METHOD]` → Your contact email or preferred method
  - Files to update: `.github/ISSUE_TEMPLATE/config.yml`, `CITATION.cff`, `CODE_OF_CONDUCT.md`, `package.json`, `README.template.md`, and `SECURITY.md`
- [ ] **Add Favicons**: Generate and add favicon files to the root directory using [favicon.io](https://favicon.io/) or a similar service. Include `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png`, and Android icons.
- [ ] **Address TODO Comments**: Search for `TODO` comments throughout all project files using `grep -r "TODO" .` and complete or remove each task as appropriate for your project.
- [ ] **Finalize README**: Once all customization is complete, delete the template README.md and rename `README.template.md` to `README.md` to make it your project's main README.
- [ ] **Format Files**: Run `npm run format` to apply consistent formatting to all files using Prettier before committing changes.
- [ ] **Commit Changes**: Use `npm run commit` to create a properly formatted commit message following Conventional Commits standards (e.g., "chore: initial project setup").
- [ ] **Generate Changelog**: Run `npm run changelog` to generate changelog entries from your commit history, then copy the output into `CHANGELOG.md`.
- [ ] **Enable GitHub Pages**: In repository settings under "Pages", set the source to "Deploy from a branch" and select the `gh-pages` branch and `/ (root)` folder (if using GitHub Pages for your project documentation).

## Optional Enhancements

- [ ] **Update Citation File**: Customize `CITATION.cff` with complete citation metadata including authors, version, DOI (after first release), and keywords relevant to your project.
- [ ] **Add Zenodo Integration**: Follow the [GitHub guide for Zenodo integration](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content) to enable automatic archiving and obtain a DOI for your repository. Update `.zenodo.json` with custom metadata if needed.
- [ ] **Customize Issue Templates**: Modify the existing issue templates or add new ones in `.github/ISSUE_TEMPLATE/` to match your project's specific needs.
- [ ] **Add GitHub Actions**: Consider adding custom workflows for automated testing, linting, or deployment specific to your project's technology stack.
- [ ] **Setup Project Board**: Create a GitHub project board to track issues and pull requests for better project management.

## Verification Steps

After completing the checklist:

1. Run `npm run check` to verify all files are properly formatted
2. Review your GitHub Pages site to confirm it displays as expected (if applicable)
3. Test that all links in your README work correctly
4. Verify that security alerts and branch protection are active
5. Create a test issue and pull request to ensure templates work correctly
6. Check that commit hooks are working by making a test commit
