# Graphiti custom theme

## What's in the folder

* This folder contains all of the files necessary for this color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/Graphiti-color-theme.json` - the color theme definition file.

## Install this color theme extension

* To start using the extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* Press `F5` to open a new window with the extension loaded.
* Open `File > Preferences > Color Themes` and pick the color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.
* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.
