# VSCode setup

### Extensions used in course videos

For each of the extensions, read the overview page in order to learn how to use it.

`Auto Close Tag` to automatically close HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

`Auto Rename Tag` to automatically change matching HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

`Color Highlight` to, as the name says, highlight colors in CSS. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

`Paste and Indent` to automatically indent pasted code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)

`Path Intellisense` to autocomplete filenames. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

`Prettier` to automatically format code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Other extensions I use (will keep it updated) 

`Project Manager` to easily switch between projects. One of the most useful extensions. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

### Settings

If you want your editor to work and look exactly the same way as mine does in the course videos, you can copy these settings to your own settings file. Just go to settings in VSCode, and on the right side, you can paste this code.

```
{
  "workbench.colorTheme": "Hub Contrast (rainglow)",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.statusBar.visible": true,
  "workbench.editor.tabCloseButton": "off",
  "workbench.editor.tabSizing": "shrink",
  "workbench.activityBar.visible": true,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.colorCustomizations": {
    "statusBar.background": "#079ae4",
    "statusBar.noFolderBackground": "#079ae4",
    "statusBar.debuggingBackground": "#079ae4",
    "editorWarning.foreground": "#98c5e9",
    "editorError.foreground": "#98c5e9",
    "editorWarning.border": "#98c5e9",
    "editorError.border": "#98c5e9"
  },
  "html.format.preserveNewLines": true,
  "files.trimTrailingWhitespace": true,
  "editor.minimap.showSlider": "always",
  "editor.snippetSuggestions": "top",
  "editor.fontSize": 13,
  "editor.lineHeight": 22,
  "editor.quickSuggestionsDelay": 7,
  "editor.letterSpacing": 0.5,
  "editor.detectIndentation": true,
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.formatOnType": false,
  "editor.minimap.enabled": false,
  "editor.colorDecorators": true,
  "editor.cursorStyle": "line",
  "editor.accessibilitySupport": "off",
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "eslint.enable": true,
  "eslint.autoFixOnSave": true,
  "eslint.workingDirectories": ["./client", "./server"],
  "extensions.ignoreRecommendations": false,
  "path-intellisense.extensionOnImport": true,
  "window.zoomLevel": 0,
  "search.location": "panel",
  "todohighlight.isEnable": true,
  "git.ignoreMissingGitWarning": true,
  "editor.find.seedSearchStringFromSelection": true,
  "window.openFilesInNewWindow": "off",
  "workbench.editor.enablePreview": true,
  "editor.scrollBeyondLastLine": true,
  "editor.useTabStops": true,
  "editor.formatOnPaste": false,
  "editor.autoIndent": true,
  "window.closeWhenEmpty": true,
  "files.insertFinalNewline": true,
  "editor.showFoldingControls": "always",
  "editor.matchBrackets": true,
  "workbench.editor.enablePreviewFromQuickOpen": true
}

```
