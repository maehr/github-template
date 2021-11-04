# HitHub template for small projects

This GitHub template is agnostic to the programming language used, uses GitHub Actions to manage issues and pull requests, and helps enforce best practices for small projects. To use the template, [generate](https://github.com/maehr/github-template/generate) a new project and follow this guide.

[![GitHub issues](https://img.shields.io/github/issues/maehr/github-template.svg)](https://github.com/maehr/github-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/github-template.svg)](https://github.com/maehr/github-template/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/github-template.svg)](https://github.com/maehr/github-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/maehr/github-template.svg)](https://github.com/maehr/github-template/blob/main/LICENSE.md)

## Todo

- [ ] add `FULLNAME`, `USERNAME`, `REPO_NAME` and `SHORT_DESCRIPTION` to [README.md](README.md) and change it according to [www.makeareadme.com](https://www.makeareadme.com/)
- [ ] add `REPO_NAME` to [package.json](package.json) according to [npm docs](https://docs.npmjs.com/cli/v7/configuring-npm/package-json)
- [ ] run `npm install` to install [prettier](https://prettier.io/) and [husky](https://github.com/typicode/husky) via [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) (or [pnpm](https://pnpm.io/))
- [ ] change `[INSERT CONTACT METHOD]` in [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
- [ ] use [www.gitignore.io](https://www.gitignore.io/) to enhance [.gitignore](.gitignore)
- [ ] use [gitattributes.io](https://gitattributes.io/) to enhance [.gitattributes](.gitattributes)
- [ ] add example environment variables to [example.env](example.env)
- [ ] add [GitHub actions](https://docs.github.com/en/actions) in `.github/workflows/` according to [starter-workflows](https://github.com/actions/starter-workflows)
- [ ] activate [gh-pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages)
- [ ] [protect](https://help.github.com/en/articles/configuring-protected-branches) the main branch to enforce a [fork and pull](https://gist.github.com/Chaser324/ce0505fbed06b947d962) workflow
- [ ] activate [GitHub security alerts](https://github.blog/2017-11-16-introducing-security-alerts-on-github/) and change [SECURITY.md](SECURITY.md) accordingly
- [ ] add favicons to `./`, for example via [favicon.io](https://favicon.io/)
- [ ] keep a `CHANGELOG.md` according to [keepachangelog.com](https://keepachangelog.com/) and [git-cliff](https://github.com/orhun/git-cliff)

## Installation

Use the package manager [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) to install [Prettier](https://prettier.io/).

```bash
npm install
```

## Usage

```bash
npm run check
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

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/maehr/github-template/tags).

## Authors and acknowledgment

- **Moritz Mähr** - _Initial work_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/maehr/github-template/graphs/contributors) who participated in this project.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details
