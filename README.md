# Relm4 Snippets for VSCode

This extension for Visual Studio Code adds snippets for Relm4.

![Usage](https://github.com/Relm4/vscode-relm4-snippets/blob/main/images/usage.gif?raw=true)

# Usage
| Syntax      | Description |
| ----------- | ----------- |
| `relm-component`| Create a new `Component` widget |
| `relm-async-component`| Create a new `AsyncComponent` widget |
| `relm-simple-component`| Create a new `SimpleComponent` widget |
| `relm-simple-async-component`| Create a new `SimpleAsyncComponent` widget |
| `relm-factory`| Create a new `Factory` widget |
| `relm-async-factory`| Create a new `AsyncFactory` widget |
| `relm-template`| Create a new `WidgetTemplate` widget |
| `relm-worker`| Create a new `Worker` structure |

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
- Open in browser: `vscode-test-web --extensionDevelopmentPath=. .`
