# Relm4 Snippets for VSCode

This extension for Visual Studio Code adds snippets for Relm4.

![Usage](https://github.com/Relm4/vscode-relm4-snippets/blob/b9fe30e19846cff6603164556d1d39fd358f0680/images/usage.gif)

# Dependencies
- nodejs
- npm

## `npm` dependencies
- yo 
- generator-code
- @vscode/vsce

# Build
Use the provided scripts.
- Package: `npx vsce package`
- Publish: `npx vsce publish`
- Post Install: `node ./node_modules/vscode/bin/install`
- Open in browser: `vscode-test-web --extensionDevelopmentPath=. .`
