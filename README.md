# git-user-email [![NPM version](https://badge.fury.io/js/git-user-email.svg)](http://badge.fury.io/js/git-user-email)  [![Build Status](https://travis-ci.org/jonschlinkert/git-user-email.svg)](https://travis-ci.org/jonschlinkert/git-user-email)  

> Get the email address of the current user from git config.

## Install with [npm](npmjs.org)

```bash
npm i git-user-email --save
```

## Usage

```js
var email = require('git-user-email');
console.log(email());
//=> jon.schlinkert@sellside.com
```

## Similar projects
* [git-config-path](https://github.com/jonschlinkert/git-config-path): Resolve the path to the user's global .gitconfig.
* [parse-git-config](https://github.com/jonschlinkert/parse-git-config): Parse `.git/config` into a JavaScript object. sync or async.
* [git-username](https://github.com/jonschlinkert/git-username): Get the username from a git remote origin URL.
* [git-repo-name](https://github.com/jonschlinkert/git-repo-name): Get the repository name from the git remote origin URL.
* [git-branch](https://github.com/jonschlinkert/git-branch): Get the current branch for a local git repository.

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/git-user-email/issues)

## Tests
Install dev dependencies.

```bash
npm i -d && npm test
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014-2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on March 31, 2015._