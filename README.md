# VSCode setup

### Extensions
`Auto Close Tag` to automatically close HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

`Auto Rename Tag` to automatically change matching HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

`Color Highlight` to, as the name says, highlight colors in CSS. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

`Paste and Indent` to automatically indent pasted code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)

`Path Intellisense` to autocomplete filenames. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

`Prettier` to automatically format code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Other extensions
`Project Manager` to switch between windows. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

### Settings
```
{
  "workbench.colorTheme": "Hub Contrast (rainglow)",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.statusBar.visible": true,
  "workbench.editor.tabCloseButton": "off",
  "workbench.editor.tabSizing": "shrink",
  "workbench.activityBar.visible": true,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.editor.enablePreview": true,
  "workbench.editor.enablePreviewFromQuickOpen": true,
  "workbench.colorCustomizations": {
    "statusBar.background": "#079ae4",
    "statusBar.noFolderBackground": "#079ae4",
    "statusBar.debuggingBackground": "#079ae4",
    "editorWarning.foreground": "#98c5e9",
    "editorError.foreground": "#98c5e9",
    "editorWarning.border": "#98c5e9",
    "editorError.border": "#98c5e9"
  },
  "window.openFilesInNewWindow": "off",
  "window.zoomLevel": 0,
  "window.closeWhenEmpty": true,
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
  "editor.showFoldingControls": "always",
  "editor.matchBrackets": true,
  "editor.scrollBeyondLastLine": true,
  "editor.useTabStops": true,
  "editor.formatOnPaste": false,
  "editor.autoIndent": true,
  "editor.find.seedSearchStringFromSelection": true,
  "eslint.enable": true,
  "eslint.autoFixOnSave": true,
  "eslint.workingDirectories": ["./client", "./server"],
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "extensions.ignoreRecommendations": false,
  "path-intellisense.extensionOnImport": true,
  "html.format.preserveNewLines": true,
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "search.location": "panel",
  "todohighlight.isEnable": true,
  "git.ignoreMissingGitWarning": true
}
```
