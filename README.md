# GitHub template for small projects

This GitHub template is agnostic to the programming language used, uses GitHub Actions to manage issues and pull requests, and helps enforce best practices for small projects.

[![GitHub issues](https://img.shields.io/github/issues/maehr/github-template.svg)](https://github.com/maehr/github-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/github-template.svg)](https://github.com/maehr/github-template/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/github-template.svg)](https://github.com/maehr/github-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/maehr/github-template.svg)](https://github.com/maehr/github-template/blob/main/LICENSE.md)

## Why use a template (even for small projects)

- Write better [documentation](#documentation)
- Write more [consistent](#consistency) code
- Increase [security](#security)
- Follow recognized [ethical principles](#ethics)
- Foster collaboration and the [community](#community)
- Promotion of the [Free and Open-source software](#foss)

## How this template helps you with this

### Documentation

- [README.md](README.md) according to [www.makeareadme.com](https://www.makeareadme.com/)
- [CHANGELOG.md](CHANGELOG.md) according to [keepachangelog.com](https://keepachangelog.com/)
- Automated documentation via [git-cliff](https://github.com/orhun/git-cliff)
- [package.json](package.json) according to [npm docs](https://docs.npmjs.com/cli/v7/configuring-npm/package-json)
- Accessible documentation via [gh-pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages)

### Consistency

- Install [Prettier](https://prettier.io/) and [husky](https://github.com/typicode/husky)
- cz [conventionalcommits](https://www.conventionalcommits.org/en/v1.0.0/) and

- [ ] add [GitHub actions](https://docs.github.com/en/actions) in `.github/workflows/` according to [starter-workflows](https://github.com/actions/starter-workflows)

### Security

- [ ] [protect](https://help.github.com/en/articles/configuring-protected-branches) the main branch to enforce a [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow
- [ ] activate [GitHub security alerts](https://github.blog/2017-11-16-introducing-security-alerts-on-github/) and change [SECURITY.md](SECURITY.md) accordingly

### Ethics

- [ ] change `[INSERT CONTACT METHOD]` in [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) according to [Contributor Covenant](https://www.contributor-covenant.org/)

### Community

- [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow

### FOSS

- Choose an open source license via [choosealicense.com](https://choosealicense.com/).

_further readings_

- [_Defining a Distinguished Engineer_ by Jessie Frazelle](https://web.archive.org/web/20210814040522/https://blog.jessfraz.com/post/defining-a-distinguished-engineer/)
- [_Leadership CI_ by Jessie Frazelle & Kathy Simpson](https://web.archive.org/web/20211108095148/https://blog.jessfraz.com/post/leadership-ci/)

## Installation

To initialize the template, [generate](https://github.com/maehr/github-template/generate) a new project and follow this guide:

- [ ] Install the [latest LTS version or higher of Node](https://nodejs.org/en/download/) and all dependencies via [npm](https://www.npmjs.com/), or via [pnpm](https://pnpm.io/) or via [yarn](https://yarnpkg.com/).

```bash
# npm
npm install
npm run prepare

# pnpm
pnpm install
pnpm run prepare

# yarn
yarn
yarn run prepare
```

- [ ] add `FULLNAME`, `USERNAME`, `REPO_NAME` and `SHORT_DESCRIPTION` to [README.template.md](README.template.md)
- [ ] add `USERNAME` and `REPO_NAME` to [package.json](package.json)
- [ ] change `[INSERT CONTACT METHOD]` in [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

- [ ] activate [gh-pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages)
- [ ] add favicons to `./`, for example via [favicon.io](https://favicon.io/)

- [ ] delete [README.md](README.md)
- [ ] rename [README.template.md](README.template.md) to [README.md](README.md)

## Usage

```bash
npm run check
npm run commit
npm run format
```

## Support

This project is maintained by [@maehr](https://github.com/maehr). Please understand that we won't be able to provide individual support via email. We also believe that help is much more valuable if it's shared publicly, so that more people can benefit from it.

| Type                                  | Platforms                                                               |
| ------------------------------------- | ----------------------------------------------------------------------- |
| 🚨 **Bug Reports**                    | [GitHub Issue Tracker](https://github.com/maehr/github-template/issues) |
| 🎁 **Feature Requests**               | [GitHub Issue Tracker](https://github.com/maehr/github-template/issues) |
| 🛡 **Report a security vulnerability** | [GitHub Issue Tracker](https://github.com/maehr/github-template/issues) |

## Roadmap

No changes are currently planned.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors and acknowledgment

- **Moritz Mähr** - _Initial work_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/maehr/github-template/graphs/contributors) who participated in this project.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details
