# moritzmaehr.ch

Digital tales: personal weblog of Moritz Mähr.

[![GitHub issues](https://img.shields.io/github/issues/maehr/moritzmaehr.ch.svg)](https://github.com/maehr/moritzmaehr.ch/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/moritzmaehr.ch.svg)](https://github.com/maehr/moritzmaehr.ch/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/moritzmaehr.ch.svg)](https://github.com/maehr/moritzmaehr.ch/stargazers)
[![Code license](https://img.shields.io/github/license/maehr/moritzmaehr.ch.svg)](https://github.com/maehr/moritzmaehr.ch/blob/main/LICENSE-AGPL.md)
[![Data license](https://img.shields.io/github/license/maehr/moritzmaehr.ch.svg)](https://github.com/maehr/moritzmaehr.ch/blob/main/LICENSE-CCBYSA.md)

## Installation

Install [Quarto](https://quarto.org/) and [Node.js](https://nodejs.org/) and run the following commands in the root directory of the repository:

```bash
npm install
npm run prepare
```

## Usage

Check that all files are properly formatted.

```bash
npm run check
```

Format all files.

```bash
npm run format
```

Run Quarto to preview the website.

```bash
quarto preview blog
```

Run Quarto to build the website.

```bash
quarto render blog
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

| Type                                   | Platforms                                                                 |
| -------------------------------------- | ------------------------------------------------------------------------- |
| 🚨 **Bug Reports**                     | [GitHub Issue Tracker](https://github.com/maehr/moritzmaehr.ch/issues)    |
| 📚 **Docs Issue**                      | [GitHub Issue Tracker](https://github.com/maehr/moritzmaehr.ch/issues)    |
| 🎁 **Feature Requests**                | [GitHub Issue Tracker](https://github.com/maehr/moritzmaehr.ch/issues)    |
| 🛡 **Report a security vulnerability** | See [SECURITY.md](SECURITY.md)                                            |
| 💬 **General Questions**               | [GitHub Discussions](https://github.com/maehr/moritzmaehr.ch/discussions) |

## Roadmap

No changes are currently planned.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/maehr/moritzmaehr.ch/tags).

## Authors and acknowledgment

- **Moritz Mähr** - _Initial work_ - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/maehr/moritzmaehr.ch/graphs/contributors) who participated in this project.

## License

This project is licensed under the GNU Affero General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details.
