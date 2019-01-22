# Angular Bare Essentials for VS Code
This extension pack for Visual Studio Code adds a bare minimum of useful tools for Angular development.

Install [Angular Bare Essentials](https://marketplace.visualstudio.com/items?itemName=brain.angular-bare-essentials) now.

## Why make this fork?

This extension is a fork of the "[Angular Essentials](https://github.com/johnpapa/vscode-angular-essentials)" by John Papa.

Some extensions in the Angular Essentials package is sometime a bit problematic, and they cannot be individually uninstalled or disabled when the pack is installed.

## Changes

See the [CHANGELOG](CHANGELOG.md) for the latest changes

Note: Original source was not properly licensed, only mention of license was to look at the non-existing LICENSE.md. Any additional changes to the original fork, is licensed under MIT.

> As web tools evolve, the usefulness of extensions come and go. I reserve the right to update the extension pack's contents up to my own discretion.

Here is the list of extensions the pack includes:

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
* [tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
* [Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)
* [Angular v5 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
* [EditConfig](https://marketplace.visualstudio.com/items?itemName=editorconfig.editorconfig)
* [Angular2-Inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
* [Debugger For Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome) 

## Development

First install the publish tool:

```
npm install -g vsce
```


Publish command:

```
vsce publish
```

Package without publish command:

```
vsce package
```

More information: https://code.visualstudio.com/docs/extensions/publish-extension
