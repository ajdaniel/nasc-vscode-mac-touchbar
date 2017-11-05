# Nasc's Macbook Pro Touch Bar features for VSCode

This adds a few useful features to your Macbook Pro's touch bar while you are working in VSCode.

## Features

This is how your touchbar will look like:

![Touchbar visualization](nasc-macbook-pro-vscode-touch-bar.jpg)

The list of features are:

- Go to definition
- Add cursor above
- Add cursor bellow
- Run command
- Toggle side bar
- Toggle Pannel/terminal
- Rename/replace all
- Duplicate lines

## Settings

You can choose the buttons by setting the following settings.  
Please have in mind the limit of 6 active buttons (if you have the OS controll strip enabled, 9 buttons if you don't) . More than that will break the layout and the buttons will not be visible.

- "nasc-touchbar.goToDefinition": (default _true_) Go to the function or variable definition
- "nasc-touchbar.addCursorAbove": (default _false_) Add a cursor in the line above
- "nasc-touchbar.addCursorBellow": (default _true_) Add a cursor in the line bellow
- "nasc-touchbar.selectNext": (default _true_) Adds a selection to the 
- "nasc-touchbar.toggleSidebar": (default _false_) Toggles the sidebar
- "nasc-touchbar.togglePanel": (default _true_) Toggles the panel in the bottom of the editor
- "nasc-touchbar.showCommands": (default _true_) Shows the _run command_ prompt
- "nasc-touchbar.rename": (default _true_) Rename (replace all) variable or function names
- "nasc-touchbar.copyLineDown": (default _false_) Duplicates the current line (or selected lines) 
- "nasc-touchbar.goToNext": (default _false_) Go to next match

## NOTES:

Important, if the buttons don't fit in the bar, they will not be shown (this is a current bug in VSCode support for the TouchBar and soon to be fixed).  
If the bar disappeared, see the options (ctrl+, or cmd+,), filter by "nasc" e adjust the settings.

Usually, if your are not using the "Strip" group of buttons, you can fit **9** buttons on it. If you have the OS's _Strip_ buttons enabled, you can fit **6** buttons.
