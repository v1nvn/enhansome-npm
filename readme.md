# Awesome npm [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [<img src="https://github.com/npm/logos/blob/7fb0bc425e0dac1bab065217c4ed595594448db4/npm-transparent.png" width="200" align="right" alt="npm">](https://www.npmjs.com) with stars

> Awesome [npm](https://www.npmjs.com) resources and tips

[npm](https://en.wikipedia.org/wiki/Npm_\(software\)) is a package manager for the JavaScript programming language and comes bundled in the [Node.js](https://en.wikipedia.org/wiki/Node.js) runtime.

*Please read the [contribution guidelines](origin/contributing.md) before contributing.*

## Contents

* [Articles](#articles)
* [Tools](#tools)
* [Packages](#packages)
* [Clients](#clients)
* [Tips](#tips)
* [FAQ](#faq)
* [Community](#community)
* [Documentation](#documentation)
* [Support](#support)
* [Related](#related)

## Articles

* [The Art of Node](https://github.com/maxogden/art-of-node#modules) ⭐ 9,892 | 🐛 15 | 🌐 JavaScript | 📅 2020-08-03 - An introduction to Node.js and client-side development with npm.
* [Install npm packages globally without sudo on macOS and Linux](https://github.com/sindresorhus/guides/blob/main/npm-global-without-sudo.md) ⭐ 2,515 | 🐛 9 | 📅 2024-10-20
* [Small focused modules](https://github.com/sindresorhus/ama/issues/10#issuecomment-117766328) ⭐ 145 | 🐛 154 | 📅 2021-01-24
* [Unix philosophy and Node.js](http://blog.izs.me/post/48281998870/unix-philosophy-and-nodejs) - Write programs that do one thing and do it well.
* [Writing small modules](https://web.archive.org/web/20180302125059/https://substack.net/how_I_write_modules)
* [Semver: A Primer](https://nodesource.com/blog/semver-a-primer/) *(Must read!)*
* [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
* [Offline installation of npm packages](https://addyosmani.com/blog/using-npm-offline/)
* [Task automation with npm run](https://web.archive.org/web/20180302164842/http://substack.net/task_automation_with_npm_run)
* [How to use npm as a build tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
* [Optimizing the footprint of an npm package](https://medium.com/@goldglovecb/npm-needs-a-personal-trainer-537e0f8859c6)
* [Why npm scripts?](https://css-tricks.com/why-npm-scripts/) - An introduction to npm scripts with common packages and scripts, as well as a boilerplate project.

## Tools

### Web

* [npms](https://npms.io) - Superb package search with deep analysis of package quality using a [myriad of metrics](https://npms.io/about).
* [NodeICO](https://nodei.co/) - Package badges.
* [Libraries.io](https://libraries.io/npm) - Package discovery.
* [npm-stat](http://npm-stat.com) - Statistics charts for packages.
* [npmgraph](http://npm.anvaka.com) - Visualization of dependencies.
* [npm trends](http://www.npmtrends.com) - Compare package download counts over time.
* [npm-top](https://gist.github.com/bcoe/dcc961b869bbf6685002) - npm users by downloads.
* [npm semver calculator](http://semver.npmjs.com) - Visually explore what versions of a package a semver range matches.
* [ghub.io](https://ghub.io) - Redirects to the GitHub repo of an npm package.
* [moiva](https://moiva.io) - Discover and compare packages.

### Browser extensions

* [Octo-Linker](https://chrome.google.com/webstore/detail/octo-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension to navigate across npm packages on GitHub with ease.
* [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome extension to explore npm dependencies on GitHub repos.
* [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - View npm download stats on GitHub.
* [npm-search-update](https://chrome.google.com/webstore/detail/npm-search-update/kagpoplamlmaonpddimnnigiojimihnh) - Chrome extension to quickly search for dependencies and monitor changes from the npm registry.

### CLI

* [npkill](https://github.com/voidcosmos/npkill) ⭐ 9,039 | 🐛 15 | 🌐 TypeScript | 📅 2026-01-26 - Easily find and remove old and heavy node\_modules folders.
* [zsh-better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) ⭐ 496 | 🐛 12 | 🌐 Shell | 📅 2024-10-31 - Better ZSH completion for npm.

## Packages

### Publishing

* [semantic-release](https://github.com/semantic-release/semantic-release) ⭐ 23,279 | 🐛 378 | 🌐 JavaScript | 📅 2026-02-08 - Fully automated package publishing.
* [release-it](https://github.com/webpro/release-it) ⭐ 8,830 | 🐛 48 | 🌐 JavaScript | 📅 2026-01-20 - Automate releases for Git repositories and/or npm packages. Changelog generation, GitHub/GitLab releases, etc.
* [np](https://github.com/sindresorhus/np) ⭐ 7,680 | 🐛 1 | 🌐 JavaScript | 📅 2026-01-29 - A better `npm publish`.
* [publish-please](https://github.com/inikulin/publish-please) ⭐ 738 | 🐛 6 | 🌐 JavaScript | 📅 2024-08-24 - Publish packages safely and gracefully.
* [npm-release](https://github.com/phuu/npm-release) ⭐ 103 | 🐛 1 | 🌐 JavaScript | 📅 2025-02-15 - Making releasing to npm so easy a kitten could probably do it™.
* [pkgfiles](https://github.com/timoxley/pkgfiles) ⭐ 85 | 🐛 9 | 🌐 JavaScript | 📅 2022-04-10 - List all files which would be published in a package.

### Registry

* [verdaccio](https://github.com/verdaccio/verdaccio) ⭐ 17,458 | 🐛 51 | 🌐 TypeScript | 📅 2026-02-08 - Lightweight private npm proxy registry.
* [nrm](https://github.com/Pana/nrm) ⭐ 2,998 | 🐛 32 | 🌐 TypeScript | 📅 2025-07-13 - Registry manager.
* [npm-register](https://github.com/dickeyxxx/npm-register) ⚠️ Archived - Easy to set up and maintain npm registry and proxy.
* [npm-name](https://github.com/sindresorhus/npm-name-cli) ⭐ 288 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-15 - Check whether a package name is available on npm.
* [package-json](https://github.com/sindresorhus/package-json) ⭐ 247 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-14 - Get the package.json of a package from the npm registry.
* [npm-cli-login](https://github.com/postmanlabs/npm-cli-login) ⭐ 118 | 🐛 52 | 🌐 JavaScript | 📅 2023-07-20 - Log in to npm.
* [npm-user](https://github.com/sindresorhus/npm-user) ⭐ 58 | 🐛 1 | 🌐 JavaScript | 📅 2024-02-28 - Get user info of an npm user.
* [latest-version](https://github.com/sindresorhus/latest-version-cli) ⭐ 54 | 🐛 1 | 🌐 JavaScript | 📅 2024-02-27 - Get the latest version of an npm package.
* [npm-keyword](https://github.com/sindresorhus/npm-keyword) ⭐ 52 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-26 - Get a list of npm packages with a certain keyword.
* [npm-stats](https://github.com/hughsk/npm-stats) ⭐ 51 | 🐛 6 | 🌐 JavaScript | 📅 2016-03-29 - Get data from an npm registry.
* [npm-email](https://github.com/sindresorhus/npm-email) ⭐ 32 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-29 - Get the email of an npm user.
* [dpn](https://github.com/gillstrom/dpn) ⭐ 27 | 🐛 0 | 🌐 JavaScript | 📅 2017-09-23 - Get the dependents of a user's npm packages.
* [npm-user-packages](https://github.com/kevva/npm-user-packages-cli) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-06 - Get packages by an npm user.
* [cloudsmith](https://cloudsmith.io/l/npm-registry/) - A fully managed package management SaaS with support for public and private npm registries (and many others).
* [RepoFlow](https://www.repoflow.io) - A simple and easy-to-use package management platform, available for both cloud and self-hosted deployments.

### Other

* [npm-check](https://github.com/dylang/npm-check) ⭐ 6,642 | 🐛 233 | 🌐 JavaScript | 📅 2026-02-07 - Check for outdated, incorrect, and unused dependencies, as well as interactive update.
* [npm-run-all](https://github.com/mysticatea/npm-run-all) ⭐ 5,841 | 🐛 112 | 🌐 JavaScript | 📅 2024-08-15 - CLI tool to run multiple npm-scripts in parallel or serial.
* [npm-windows-upgrade](https://github.com/felixrieseberg/npm-windows-upgrade) ⚠️ Archived - Upgrade npm on Windows.
* [emma-cli](https://github.com/maticzav/emma-cli) ⭐ 1,244 | 🐛 47 | 🌐 TypeScript | 📅 2026-02-02 - Interactive CLI package search utility.
* [local-npm](https://github.com/nolanlawson/local-npm) ⭐ 1,170 | 🐛 33 | 🌐 JavaScript | 📅 2020-02-24 - Use npm [offline](https://addyosmani.com/blog/using-npm-offline/).
* [luna](https://github.com/rvpanoz/luna) ⭐ 1,005 | 🐛 12 | 🌐 JavaScript | 📅 2025-07-01 - App to manage npm dependencies.
* [david](https://github.com/alanshaw/david) ⭐ 968 | 🐛 40 | 🌐 JavaScript | 📅 2022-12-10 - Check if your package dependencies are out of date.
* [ntl](https://github.com/ruyadorno/ntl) ⭐ 956 | 🐛 25 | 🌐 JavaScript | 📅 2024-05-23 - Interactive CLI menu to list & run npm tasks.
* [lockfile-lint](https://github.com/lirantal/lockfile-lint) ⭐ 837 | 🐛 3 | 🌐 JavaScript | 📅 2026-01-25 - Lint lockfiles for improved security and trust policies to mitigate malicious package injection and insecure lockfile resources.
* [onchange](https://github.com/Qard/onchange) ⭐ 830 | 🐛 6 | 🌐 TypeScript | 📅 2024-11-09 - Watch files and folders and run a command when something changed.
* [shrinkpack](https://github.com/JamieMason/shrinkpack) ⭐ 805 | 🐛 3 | 🌐 TypeScript | 📅 2023-02-16 - Lock down your dependencies and install offline.
* [synp](https://github.com/imsnif/synp) ⭐ 783 | 🐛 18 | 🌐 JavaScript | 📅 2026-01-21 - Convert yarn.lock to package-lock.json and vice versa.
* [npm-shrinkwrap](https://github.com/uber/npm-shrinkwrap) ⚠️ Archived - A consistent shrinkwrap tool.
* [generator-nm](https://github.com/sindresorhus/generator-nm) ⚠️ Archived - Scaffold out an npm package.
* [package-size](https://github.com/egoist/package-size) ⭐ 426 | 🐛 12 | 🌐 JavaScript | 📅 2022-06-18 - Get the bundle size of an npm package.
* [npm-upgrade](https://github.com/th0r/npm-upgrade) ⭐ 336 | 🐛 23 | 🌐 JavaScript | 📅 2025-05-14 - Update outdated npm dependencies interactively.
* [read-package-up](https://github.com/sindresorhus/read-package-up) ⭐ 268 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-07 - Read the closest package.json file.
* [normalize-package-data](https://github.com/npm/normalize-package-data) ⭐ 204 | 🐛 18 | 🌐 JavaScript | 📅 2026-01-21 - Normalize package metadata.
* [npm-home](https://github.com/sindresorhus/npm-home) ⭐ 201 | 🐛 1 | 🌐 JavaScript | 📅 2024-07-25 - Open the npm page of a package.
* [gh-home](https://github.com/sindresorhus/gh-home) ⭐ 193 | 🐛 1 | 🌐 JavaScript | 📅 2024-07-21 - Open the GitHub page of a package.
* [package-up](https://github.com/sindresorhus/package-up) ⭐ 166 | 🐛 0 | 🌐 JavaScript | 📅 2025-06-05 - Find the closest package.json file.
* [redrun](https://github.com/coderaiser/redrun) ⭐ 127 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-26 - Expand scripts from package.json to improve execution speed.
* [package-config](https://github.com/sindresorhus/package-config) ⭐ 121 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-05 - Get namespaced config from the closest package.json.
* [npm-run-path](https://github.com/sindresorhus/npm-run-path) ⭐ 107 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-28 - Run locally installed binaries in the terminal by name like with global ones.
* [npe](https://github.com/zeke/npe) ⭐ 92 | 🐛 6 | 🌐 JavaScript | 📅 2022-05-25 - CLI for inspecting and editing properties in package.json.
* [cli-error-notifier](https://github.com/micromata/cli-error-notifier) ⭐ 72 | 🐛 9 | 🌐 JavaScript | 📅 2023-07-19 - Sends native desktop notifications when npm scripts fail.
* [npm-issues](https://github.com/seanzarrin/npm-issues) ⭐ 48 | 🐛 0 | 🌐 JavaScript | 📅 2016-01-17 - Search known issues of all your packages at once.
* [john](https://github.com/davej/john) ⭐ 42 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-09 - Make npm3's flat dependencies easier to find and sort.
* [engine-deps](https://github.com/samccone/engine-deps) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2015-12-22 - Manage Node.js version specific dependencies with ease.
* [decheck](https://github.com/egoist/decheck) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2021-12-25 - Explore dependencies of npm packages in the command-line.
* [enpeem-search](https://github.com/amovah/enpeem-search) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2016-01-17 - Search packages by scraping the npm web search.

## Clients

* [yarn](https://github.com/yarnpkg/yarn) ⭐ 41,557 | 🐛 2,061 | 🌐 JavaScript | 📅 2026-02-07 - Fast, reliable, and secure dependency management.
* [pnpm](https://github.com/pnpm/pnpm) ⭐ 33,922 | 🐛 2,100 | 🌐 TypeScript | 📅 2026-02-07 - Fast, disk space efficient package manager.
* [npm](https://github.com/npm/cli) ⭐ 9,499 | 🐛 632 | 🌐 JavaScript | 📅 2026-02-06 - The official client.

## Tips

### Update to the latest npm version

```
$ npm install --global npm
```

*[Windows users, read more.](https://github.com/felixrieseberg/npm-windows-upgrade) ⚠️ Archived*

### Command aliases

* `npm i ` → `npm install`
* `npm i -D` → `npm install --save-dev`
* `npm t` → `npm test`
* `npm it` → `npm install && npm test`
* `npm r` → `npm uninstall`
* `npm un` → `npm uninstall`
* `npm up` → `npm update`

### Shell aliases

Speed up your common npm tasks.

In your `.zshrc`/`.bashrc`:

```sh
alias ni='npm install'
alias nid='npm install --save-dev'
alias nig='npm install --global'
alias nt='npm test'
alias nit='npm install && npm test'
alias nk='npm link'
alias nr='npm run'
alias ns='npm start'
alias nf='npm cache clean && rm -rf node_modules && npm install'
alias nlg='npm list --global --depth=0'
```

### Don't add to package.json when installing

By default npm adds packages you install to the `dependencies` field in package.json (since v5). You can prevent this by specifying the `--no-save` flag. You can add a package to `devDependencies` with `--save-dev`/`-D`:

```
$ npm install --save-dev ava
```

### Run scripts

You can easily [run scripts](https://docs.npmjs.com/cli/run-script) using npm by adding them to the `"scripts"` field in package.json and run them with `npm run <script-name>`. Run `npm run` to see available scripts. Binaries of locally install packages are made available in the [PATH](https://en.wikipedia.org/wiki/PATH_\(variable\)), so you can run them by name.

```json
{
	"name": "awesome-package",
	"scripts": {
		"cat": "cat-names"
	},
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

```
$ npm run cat
Max
```

All package.json properties are [exposed](https://docs.npmjs.com/misc/scripts#packagejson-vars) as environment variables:

```json
{
	"name": "awesome-package",
	"scripts": {
		"name": "echo $npm_package_name"
	}
}
```

```
$ npm run name
awesome-package
```

#### Passing options to commands

You can pass options to the command you are using in your npm script by adding `-- --flag` like in the example below. The `--` [marks the end of options parsing](https://unix.stackexchange.com/questions/11376/what-does-double-dash-mean-also-known-as-bare-double-dash), so `npm run` will just ignore it and pass it to the command.

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo -- --fix",
	}
}
```

*Adding the `-- --fix ` option is like executing `xo --fix`*.

#### Silent option

`npm run` has a `--silent` option which is especially useful when combining npm scripts.

Imagine you have a setup for linting your JavaScript files like the following:

```json
{
	"name": "awesome-package",
	"scripts": {
		"xo": "xo",
		"xo:fix": "npm run xo --silent -- --fix",
	}
}
```

*Using the `--silent` option reduces the output in the terminal. See [this comparison](https://twitter.com/mkuehnel/status/957965749473210369).*

### Lifecycle scripts

npm comes with predefined [lifecyle scripts](https://docs.npmjs.com/misc/scripts) which are excuted under specific conditions if they are defined in your package.json.

```json
{
	"name": "awesome-package",
	"scripts": {
		"prepublishOnly": "nsp check"
	},
	"devDependencies": {
		"nsp": "^3.0.0"
	}
}
```

This will be executed automatically before your npm package is published to the registry via `npm publish` to check for known vulnerabilties in your dependencies.

*Note: **prepublishOnly** is available since npm v4.0.0. See [npm docs](https://docs.npmjs.com/misc/scripts#deprecation-note).*

#### `npm start` and `npm test`

`npm start` and `npm test` are also lifecycle scripts but are not executed automatically.

```json
{
	"name": "awesome-package",
	"scripts": {
		"start": "node server.js",
		"test": "ava"
	},
	"devDependencies": {
		"ava": "^1.0.0"
	}
}
```

Therefore they can be executed simply with:

```console
$ npm test
$ npm start
```

#### `pre` and `post` scripts

These are special lifecycle scripts which can be used to run scripts automatically in sequence.

```json
{
	"name": "awesome-package",
	"scripts": {
		"pretest": "eslint .",
		"test": "ava"
	},
	"devDependencies": {
		"eslint": "^4.19.0",
		"ava": "^1.0.0"
	}
}
```

```console
$ npm test
```

This will lint your files before running your tests. The tests will not run if linting fails. Or more generally spoken: the following script won’t be executed if one of the scripts running in sequence exits with an exit code other than 0.

*Note: `pre` and `post` scripts can also be used for your custom npm scripts. So `npm run foo` will also run `prefoo` and `postfoo` if defined.*

### Run script with `npx`

`npm` [comes bundled](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) with `npx` (Since v5.2.0) — a tool to execute package binaries. Each command is executed either from the local `node_modules/.bin` directory, or from a central cache, installing any packages needed in order for `<command>` to run.

```json
{
	"name": "awesome-package",
	"dependencies": {
		"cat-names": "^1.0.0"
	}
}
```

If the binary is already installed, it will be executed from `node_modules/.bin`.

```
$ npx cat-names
Max
```

But if the binary is missing, it will be installed first.

```
$ npx dog-names
npx: installed 46 in 3.136s
Bentley
```

### Run commands with different Node.js versions

With `npx` (Comes bundled with npm v5.2.0 or newer) and the [`node-bin`](https://www.npmjs.com/package/node-bin) package, you can easily try out code in different Node.js versions without having to use a version manager like [`nvm`](http://nvm.sh), [`nave`](https://github.com/isaacs/nave) ⭐ 1,630 | 🐛 2 | 🌐 Shell | 📅 2026-01-23, or [`n`](https://github.com/tj/n) ⭐ 19,493 | 🐛 3 | 🌐 Shell | 📅 2025-11-27.

```
$ npx --package=node-bin@6.11.0 -- node --version
v6.11.0
```

### Link local packages

Sometimes it can be useful to have a local version of a package as a dependency. You can use `npm link` to link one local package into another. Run `npm link` in the package you want to use. This creates a global reference. Then go into your original package and run `npm link <package-name>` to link in the other package.

```
$ cd rainbow
$ npm link
$ cd ../unicorn
$ npm link rainbow
```

You can now use `rainbow` as a dependency in the `unicorn` package.

### Install a package from GitHub

npm supports using a shorthand for installing a package directly from a GitHub repo:

```
$ npm install sindresorhus/chalk
```

Let's target a specific commit as the main branch is a moving target:

```
$ npm install 'sindresorhus/chalk#51b8f32'
```

Specify either a commit SHA, branch, tag, or nothing.

You can also install Git dependencies with semver: *(Requires npm v5 or newer)*

```
$ npm install 'sindresorhus/chalk#semver:^2.0.0'
```

### Install a specific version of a package

```
$ npm install chalk@1.0.0
```

### List top-level installed packages and their version

```
$ npm ls --depth=0
```

### Command help

Get help docs for a command:

```
$ npm help <command>
```

Example:

```
$ npm help install
```

### Standalone version of a package

Quickly get a standalone version of a package that is browserified and usable in the browser.

```
https://wzrd.in/standalone/<package-name>[@<version>]
```

Examples:

* <https://wzrd.in/standalone/object-assign>
* <https://wzrd.in/standalone/object-assign@4.0.0>

Great for prototyping, but download the file or use Browserify yourself for production.

## FAQ

* [Check in node\_modules vs. shrinkwrap](http://stackoverflow.com/questions/11459733/check-in-node-modules-vs-shrinkwrap)
* [What is the difference between Bower and npm?](http://stackoverflow.com/questions/18641899/what-is-the-difference-between-bower-and-npm)
* [What does `^` mean in package.json versioning?](http://stackoverflow.com/questions/22137778/what-does-mean-in-package-json-versioning)
* [Find the version of an installed npm package](http://stackoverflow.com/questions/10972176/find-the-version-of-an-installed-npm-package)
* [What's the difference between dependencies, devDependencies, and peerDependencies in package.json?](http://stackoverflow.com/questions/18875674/whats-the-difference-between-dependencies-devdependencies-and-peerdependencies)

## Community

* [`#npm` on Freenode](http://webchat.freenode.net/?channels=npm)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/npm)
* [Reddit](https://www.reddit.com/r/npm)
* [Twitter](https://twitter.com/npmjs)
* [Blog](https://blog.npmjs.org)

## Documentation

* [Troubleshooting](https://github.com/npm/npm/wiki/Troubleshooting) ⚠️ Archived
* [Stats API](https://github.com/npm/download-counts) ⚠️ Archived
* [Official](https://docs.npmjs.com)
* [Semantic versioning](https://docs.npmjs.com/getting-started/semantic-versioning)
* [Fixing npm permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)
* [package.json](https://docs.npmjs.com/files/package.json)
* [npm run script](https://docs.npmjs.com/cli/run-script)

## Support

* [npm.community](https://npm.community/c/support)
* [Twitter](https://twitter.com/npm_support)
* [Contact form](https://www.npmjs.com/support)

## Related

* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) ⭐ 64,910 | 🐛 28 | 📅 2026-01-14
