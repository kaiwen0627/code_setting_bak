### vscode配置：


```json
{
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "yzhang.markdown-all-in-one"
  },
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "auto-close-tag.SublimeText3Mode": true,
  "auto-close-tag.fullMode": true,
  "bracketPairColorizer.showBracketsInGutter": true,
  "bracketPairColorizer.showBracketsInRuler": true,
  "breadcrumbs.enabled": true,
  "editor.accessibilitySupport": "off",
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.fontFamily": "'Fira Code',Consolas",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.formatOnType": true,
  "editor.lineHeight": 24,
  "editor.mouseWheelZoom": true,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.quickSuggestions": {
    "comments": true,
    "other": true,
    "strings": true
  },
  "editor.renderLineHighlight": "none",
  "editor.renderWhitespace": "none",
  "editor.smoothScrolling": true,
  "editor.snippetSuggestions": "top",
  "editor.tabCompletion": "on",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.wordWrapColumn": 200,
  "emmet.includeLanguages": {
    "jsx-sublime-babel-tags": "javascriptreact",
    "wxml": "html"
  },
  "emmet.showSuggestionsAsSnippets": true,
  "emmet.syntaxProfiles": {
    "javascript": "javascriptreact",
    "vue": "html",
    "vue-html": "html",
    "xml": {
      "attr_quotes": "single"
    }
  },
  "emmet.triggerExpansionOnTab": true,
  "eslint.alwaysShowStatus": true,
  "eslint.autoFixOnSave": true,
  "eslint.options": {
    "extensions": [
      ".js",
      ".vue"
    ]
  },
  "eslint.provideLintTask": true,
  "eslint.quiet": true,
  "eslint.validate": [
    "javascriptreact",
    "vue",
    {
      "autoFix": true,
      "language": "vue"
    },
    {
      "autoFix": true,
      "language": "javascript"
    }
  ],
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 500,
  "files.eol": "\n",
  "files.simpleDialog.enable": true,
  "files.trimFinalNewlines": true,
  "files.trimTrailingWhitespace": true,
  "git.autofetch": true,
  "gitlens.advanced.messages": {
    "suppressCommitHasNoPreviousCommitWarning": false,
    "suppressCommitNotFoundWarning": false,
    "suppressFileNotUnderSourceControlWarning": false,
    "suppressGitVersionWarning": false,
    "suppressLineUncommittedWarning": false,
    "suppressNoRepositoryWarning": false,
    "suppressResultsExplorerNotice": false,
    "suppressShowKeyBindingsNotice": true,
    "suppressUpdateNotice": true,
    "suppressWelcomeNotice": false
  },
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "javascript.implicitProjectConfig.experimentalDecorators": true,
  "javascript.suggestionActions.enabled": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "merge-conflict.autoNavigateNextConflict.enabled": true,
  "prettier.arrowParens": "always",
  "prettier.disableLanguages": [],
  "prettier.eslintIntegration": true,
  "prettier.jsxSingleQuote": true,
  "prettier.singleQuote": true,
  "prettier.stylelintIntegration": true,
  "python.linting.enabled": false,
  "scss.lint.duplicateProperties": "warning",
  "search.exclude": {
    "**/.DS_Store": true,
    "**/.git": true,
    "**/.gitignore": true,
    "**/.idea": true,
    "**/.svn": true,
    "**/.vscode": false,
    "**/build": true,
    "**/dist": true,
    "**/elehukouben": true,
    "**/tmp": true,
    "**/yarn.lock": true
  },
  "sync.askGistName": true,
  "sync.autoDownload": true,
  "sync.autoUpload": true,
  "sync.gist": "a93fa6d1e1a630ccaf18a44954274572",
  "sync.quietSync": false,
  "terminal.integrated.confirmOnExit": true,
  "terminal.integrated.copyOnSelection": true,
  "terminal.integrated.enableBell": true,
  "terminal.integrated.fontWeightBold": "400",
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "typescript.validate.enable": true,
  "vetur.experimental.templateInterpolationService": true,
  "vetur.format.defaultFormatter.html": "prettier",
  "vetur.format.defaultFormatter.js": "prettier-eslint",
  "vetur.format.defaultFormatterOptions": {
    "js-beautify-html": {
      "wrap_attributes": "force-expand-multiline"
    },
    "prettyhtml": {
      "printWidth": 100,
      "singleQuote": true,
      "sortAttributes": true,
      "wrapAttributes": true
    }
  },
  "vetur.format.styleInitialIndent": true,
  "window.openFilesInNewWindow": "on",
  "window.restoreWindows": "none",
  "workbench.colorCustomizations": {
    "editorIndentGuide.activeBackground": "#ff4e4e"
  },
  "workbench.colorTheme": "One Dark+ (Sublime)",
  "workbench.editor.enablePreview": false,
  "workbench.iconTheme": "vscode-icons",
  "workbench.settings.useSplitJSON": true,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.tree.indent": 12,
  "workbench.tree.renderIndentGuides": "always"
}
```
### 2  插件列表

```
  auto-close-tag v0.5.6
  auto-rename-tag v0.1.0
  beautify v1.5.0
  bracket-pair-colorizer v1.0.61
  code-runner v0.9.12
  code-settings-sync v3.4.1
  debugger-for-chrome v4.11.7
  docthis v0.7.1
  es7-react-js-snippets v2.4.0
  full-react-snippets v1.3.0
  gitlens v9.9.3
  html-snippets v0.2.1
  indent-rainbow v7.4.0
  intellij-idea-keybindings v0.2.34
  JavaScriptSnippets v1.7.2
  language-stylus v1.11.0
  LiveServer v5.6.1
  markdown-all-in-one v2.4.2
  markdown-preview-enhanced v0.4.3
  material-icon-theme v3.8.1
  Material-theme v2.26.3
  npm-intellisense v1.3.0
  path-autocomplete v1.13.3
  path-intellisense v1.4.2
  prettier-vscode v1.9.0
  python v2019.8.29288
  rainbow-brackets v0.0.6
  remote-wsl v0.39.2
  simple-react-snippets v1.2.2
  sort-js-object-keys v1.0.6
  theme-onedark-sublime v0.3.7
  vetur v0.22.0
  vscode-color v0.4.5
  vscode-edge-devtools v1.0.2
  vscode-eslint v1.9.0
  vscode-icons v9.2.0
  vscode-language-pack-zh-hans v1.37.5
  vscode-markdownlint v0.30.1
  vscode-npm-script v0.3.8
  vscode-react-refactor v1.0.4
  vscode-sort-json v1.14.0
  vue-peek v1.0.2
  vue-vscode-snippets v1.7.1
  vuejs-extension-pack v1.1.5
```