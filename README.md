# plistlint - it's an utility for validatating of .plist files

[![Build Status](https://github.com/baleyko/plistlint/workflows/Test/badge.svg)](https://github.com/baleyko/plistlint/actions?query=workflow%3ATest) [![Dependency Status](https://img.shields.io/david/baleyko/plistlint.svg)](https://david-dm.org/baleyko/plistlint) [![NPM version](https://img.shields.io/npm/v/plistlint.svg)](https://www.npmjs.com/package/plistlint) [![Downloads](https://img.shields.io/npm/dm/plistlint.svg)](https://www.npmjs.com/package/plistlint) [![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg)](http://opensource.org/licenses/MIT)

## Installation

You can install plistlint utility using npm:

```bash
$ npm install plistlint --save-dev
```
or yarn:
```bash
$ yarn add plistlint --dev
```

## Usage

After installation, you can run ```plistlint``` on any file or directory like this:

```bash
$ ./node_modules/.bin/plistlint file1.plist file2.plist fileN.plist
```

piped to ```stdin```

```bash
$ cat file1.plist | ./node_modules/.bin/plistlint --stdin
```

or even combined

```bash
$ cat file1.plist | ./node_modules/.bin/plistlint --stdin file1.plist file2.plist fileN.plist
```

## License

[MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](https://github.com/baleyko/vscode-b-syntax-highlighting/blob/master/LICENSE.md) for more details.
