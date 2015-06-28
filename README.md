# is-git-url [![NPM version](https://badge.fury.io/js/is-git-url.svg)](http://badge.fury.io/js/is-git-url)  [![Build Status](https://travis-ci.org/jonschlinkert/is-git-url.svg)](https://travis-ci.org/jonschlinkert/is-git-url)

> Regex to validate that a URL is a git url.

See [http://git-scm.com/book/ch4-1.html](http://git-scm.com/book/ch4-1.html) for more info.

## Install

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i is-git-url --save
```

## Usage

```js
var isGitUrl = require('is-git-url');

isGitUrl('git://github.com/jonschlinkert/is-git-url.git');
//=> true

isGitUrl('https://github.com/jonschlinkert/');
//=> false
```

Edit on [debuggex](https://www.debuggex.com/r/WeYxcD7Ghp5ekrPR/0#cheatsheet)

[![image](https://cloud.githubusercontent.com/assets/383994/2627089/bd37da5c-bdf9-11e3-9c26-d2b02f46bc24.png)](http://git-scm.com/book/ch4-1.html)

## Related

* [git-repo-name](https://github.com/jonschlinkert/git-repo-name): Get the repository name from the git remote origin URL.
* [git-username](https://github.com/jonschlinkert/git-username): Get the username from a git remote origin URL.
* [github-contributors](https://github.com/jonschlinkert/github-contributors): Generate a markdown or JSON list of contributors for a project using the GitHub API.
* [git-branch](https://github.com/jonschlinkert/git-branch): Get the current branch for a local git repository.
* [parse-github-url](https://github.com/jonschlinkert/parse-github-url): Parse a github URL into an object.

## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/is-git-url/issues/new)

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on June 28, 2015._