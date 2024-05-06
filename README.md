# GitHub template for small projects

This is a GitHub template designed for small projects that is independent of the programming language used. It uses various GitHub features to manage issues and pull requests, while enforcing best practices for small projects.

[![GitHub issues](https://img.shields.io/github/issues/maehr/github-template.svg)](https://github.com/maehr/github-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/github-template.svg)](https://github.com/maehr/github-template/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/github-template.svg)](https://github.com/maehr/github-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/maehr/github-template.svg)](https://github.com/maehr/github-template/blob/main/LICENSE.md)

## Why use a template (even for small projects)

- Write better [documentation](#documentation) for you and the community
- Write more [consistent](#consistency) code and foster collaboration
- Increase [security](#security)
- Follow recognized [ethical principles](#ethics)
- Promote [Free and Open-source software](#foss)

## How this template helps you

### Documentation

- [README.md](README.md) according to [www.makeareadme.com](https://www.makeareadme.com/)
- [CHANGELOG.md](CHANGELOG.md) according to [keepachangelog.com](https://keepachangelog.com/)
- Automated [CHANGELOG.md](CHANGELOG.md) via [git-cliff](https://github.com/orhun/git-cliff)
- [package.json](package.json) according to [npm docs](https://docs.npmjs.com/cli/v7/configuring-npm/package-json)
- Accessible documentation via [gh-pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages)

### Consistency

- Consistent formatting via [Prettier](https://prettier.io/)
- Consistent commit messages according to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) via [husky](https://github.com/typicode/husky)
- Consistent versioning via [Semantic Versioning](https://semver.org/spec/v2.0.0.html)
- Consistent [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow via [GitHub branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule)
- Consistent issues via [issue templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)

### Security

- [SECURITY.md](SECURITY.md) according to [GitHub](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)
- [GitHub security alerts](https://github.blog/2017-11-16-introducing-security-alerts-on-github/)
- Integrity via [GitHub branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule)

### Ethics

- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) according to [Contributor Covenant](https://www.contributor-covenant.org/)
- Friendly first interactions via [greetings](https://github.com/actions/starter-workflows/blob/main/automation/greetings.yml)

### FOSS

- [LICENSE.md](LICENSE.md) according to [choosealicense.com](https://choosealicense.com/)

## Installation

To initialize the template, [generate](https://github.com/maehr/github-template/generate) or [clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) the repository to your local machine and follow this guide.

1. Install [Node.js](https://nodejs.org/en/) and run the following commands in the root directory of the repository:

```bash
npm install
npm run prepare
```

2. Complete the following checklist of tasks to customize the template for your project:

- [ ] enable [GitHub security alerts](https://github.blog/2017-11-16-introducing-security-alerts-on-github/)
- [ ] [protect](https://help.github.com/en/articles/configuring-protected-branches) the main branch to enforce a [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow
- [ ] search and replace `FULLNAME`, `USERNAME`, `REPO_NAME`, `SHORT_DESCRIPTION` `[INSERT CONTACT METHOD]` in [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md), [package.json](package.json), [README.md](README.md), [SECURITY.md](SECURITY.md), [config.yml](.github/ISSUE_TEMPLATE/config.yml)
- [ ] add favicons to `./`, e.g. via [favicon.io](https://favicon.io/)
- [ ] search for `TODO` in the project (mostly documentation) and fix it
- [ ] delete [README.md](README.md)
- [ ] rename [README.template.md](README.template.md) to [README.md](README.md)
- [ ] run `npm run format` to format all files
- [ ] run `npm run commit` to commit all changes
- [ ] run `npm run changelog` and include the output in [CHANGELOG.md](CHANGELOG.md)
- [ ] enable [gh-pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages)

## Usage

Check that all files are properly formatted.

```bash
npm run check
```

Format all files.

```bash
npm run format
```

Run the wizard to write meaningful commit messages.

```bash
npm run commit
```

Run the wizard to create a CHANGELOG.md.

```bash
npm run changelog
```

## Support

This project is maintained by [@maehr](https://github.com/maehr). Please understand that we won't be able to provide individual support via email. We also believe that help is much more valuable if it's shared publicly, so that more people can benefit from it.

| Type                                   | Platforms                                                                  |
| -------------------------------------- | -------------------------------------------------------------------------- |
| 🚨 **Bug Reports**                     | [GitHub Issue Tracker](https://github.com/maehr/github-template/issues)    |
| 📚 **Docs Issue**                      | [GitHub Issue Tracker](https://github.com/maehr/github-template/issues)    |
| 🎁 **Feature Requests**                | [GitHub Issue Tracker](https://github.com/maehr/github-template/issues)    |
| 🛡 **Report a security vulnerability** | See [SECURITY.md](SECURITY.md)                                             |
| 💬 **General Questions**               | [GitHub Discussions](https://github.com/maehr/github-template/discussions) |

## Roadmap

No changes are currently planned.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors and acknowledgment

- **Moritz Mähr** - _Initial work_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/maehr/github-template/graphs/contributors) who participated in this project.

## License

This project is licensed under the GNU Affero General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details.
