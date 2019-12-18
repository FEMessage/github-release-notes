# `gren` 🤖
> Github release notes and changelog generator

[![Build Status](https://badgen.net/travis/FEMessage/github-release-notes/master)](https://travis-ci.com/FEMessage/github-release-notes)
[![NPM Download](https://badgen.net/npm/dm/@femessage/github-release-notes)](https://www.npmjs.com/package/@femessage/github-release-notes)
[![NPM Version](https://badge.fury.io/js/%40femessage%2Fgithub-release-notes.svg)](https://www.npmjs.com/package/@femessage/github-release-notes)
[![NPM License](https://badgen.net/npm/license/@femessage/github-release-notes)](https://github.com/FEMessage/github-release-notes/blob/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/FEMessage/github-release-notes/pulls)
[![Automated Release Notes by gren](https://img.shields.io/badge/%F0%9F%A4%96-release%20notes-00B2EE.svg)](https://github-tools.github.io/github-release-notes/)

## Forked Features
[support node modules config](https://github.com/FEMessage/github-release-notes/releases/tag/v0.19.0)

## Why

[The motivation](https://www.yuque.com/docs/share/1fb077da-010c-4771-a1c0-e2507e018b9e)

## Installation

```shell
npm i -g @femessage/github-release-notes
```

## Setup

First, generate a `GitHub token`, _with **repo** scope_, at [this link](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/).
Then add this line to  `~/.bash_profile` (or `~/.zshrc`):

```shell
export GREN_GITHUB_TOKEN=your_token_here
```

## Release

```sh
gren release 

# or
gren release --override

# or
GREN_GITHUB_TOKEN=your_token_here gren release 
```

## [See full documentation here](https://github-tools.github.io/github-release-notes)

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/lianghx-319"><img src="https://avatars2.githubusercontent.com/u/27187946?v=4" width="100px;" alt=""/><br /><sub><b>Han</b></sub></a><br /><a href="https://github.com/FEMessage/github-release-notes/commits?author=lianghx-319" title="Code">💻</a></td>
    <td align="center"><a href="https://donaldshen.github.io/portfolio"><img src="https://avatars3.githubusercontent.com/u/19591950?v=4" width="100px;" alt=""/><br /><sub><b>Donald Shen</b></sub></a><br /><a href="https://github.com/FEMessage/github-release-notes/commits?author=donaldshen" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
