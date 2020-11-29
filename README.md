# VS Code Extension Pack for Uniform Developers

The repository contains a [VS Code Extension Pack](https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup) for working with the [Uniform.Dev](https://github.com/uniformdev) code base.

## Installation

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```text
ext install uniform-developer-extension-pack
```

## Building the Extension Pack

[vsce](https://github.com/microsoft/vsce), short for "Visual Studio Code Extensions", is a command-line tool for packaging, publishing and managing VS Code extensions.

Make sure you have [Node.js](https://nodejs.org/) installed. Then run:

```shell
# install dependencies
npm install

# create a .vsix package
npm run package

# publish uniform-developer-extension-pack-Major.Minor.Patch.vsix to VS Code MarketPlace
npm run publish
```

## For more information

* [uniform-developer-extension-pack GitHub repository](https://github.com:kevinobee/uniform-developer-extension-pack)
* [Uniform.Dev GitHub](https://github.com/uniformdev)
* [Extension Packs](https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup)

**Enjoy!**
