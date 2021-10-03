# AL Variable Quickfix
[![License: MIT](https://img.shields.io/github/license/himanshu2599/AL-Quickfix-?label=License%20&logo=MIT)](https://github.com/himanshu2599/AL-Quickfix-/blob/main/LICENSE)
[![Typescript: 100%](https://img.shields.io/badge/Typescript-100%25-blue)](https://www.typescriptlang.org/)
[![Share the feedback](https://badgen.net/ctan/stars/pgf-pie)](https://marketplace.visualstudio.com/items?itemName=HimanshuSharma.vscode-al-variable-quickfixes&ssr=false#review-details)

VS Code extension for variable quickfix in AL. 

![Demo](https://media.giphy.com/media/KvmTh1ACIWKl9rCAZf/giphy.gif)

Variable name update  
![Demo](https://media.giphy.com/media/5tkb1bdYTXlXocjGAw/giphy.gif)

## Features

* Removed unused global/local variables.
* Rearrange the global/local variables as per the recommended datatype sequence in AL.
* Add suffix in local/global variables and update references at all respective places.
* Add prefix in temporary variables and update references at all respective places.
* Update all keywords casing.
* Ignore prefix while renaming variable.

## Extension Settings

This extension contributes the following settings:

* `al.quickFix.globalvariablesuffix`: set to `G`
* `al.quickFix.localvariablesuffix`: set to `L`
* `al.quickFix.tempvariableprefix`: set to `Temp`
* `al.quickFix.updatelabelandtextconstsuffix`: `Check` or `Uncheck`
* `al.quickFix.updatevariablename`: `Check` or `Uncheck`
* `al.quickFix.ignorevariableprefix`: `Array` of `String`

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** Here are some useful editor keyboard shortcuts:

* Remove unused variables, Sort variables and add Suffix in variables (`Shift+CMD+Q` on macOS or `Ctrl+Shift+Q` on Windows and Linux)
* Sort local/global variables (`Shift+CMD+V` on macOS or `Ctrl+Shift+V` on Windows and Linux)
* Only remove unused variables (`Shift+CMD+T` on macOS or `Ctrl+Shift+T` on Windows and Linux)
* Add suffix in variables (`Shift+CMD+A` on macOS or `Ctrl+Shift+A` on Windows and Linux)
* Update variables (`CMD+I` on macOS or `Alt+I` on Windows and Linux)

### For more information

* [Create issues at Git] (https://github.com/himanshu2599/AL-Quickfix-/issues)

**Enjoy!**
