# Relm4 Snippets for VSCode

This extension for Visual Studio Code adds snippets for Relm4.

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