# editor-customize
  ```{
  // editor
  "editor.fontSize": 20,
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss04', 'ss05', 'ss06', 'zero', 'onum'",
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "constant",
          "emphasis",
          "entity",
          "invalid",
          "keyword",
          "markup",
          "meta",
          "storage",
          "string",
          "strong",
          "support",
          "variable"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },
  "editor.wordWrap": "on",
  "emmet.triggerExpansionOnTab": true,
  "emmet.showSuggestionsAsSnippets": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.snippetSuggestions": "top",
  // cursor
  "editor.cursorSmoothCaretAnimation": true,
  "editor.cursorBlinking": "expand",
  // config related to code formatting
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.formatOnSave": false,
    "editor.defaultFormatter": null
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.tslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true,
  //terminal
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.fontWeight": "normal",
  "terminal.integrated.fontFamily": "Hack NF",
  "workbench.colorTheme": "Dracula Soft",
  "workbench.iconTheme": "vscode-icons",
  // terminal customization
  "workbench.colorCustomizations": {
    "terminal.background": "#282A36",
    "terminal.foreground": "#A89984",
    "terminalCursor.background": "#A89984",
    "terminalCursor.foreground": "#A89984",
    "terminal.ansiBlack": "#1D202I",
    "terminal.ansiBlue": "#0D6678",
    "terminal.ansiBrightBlack": "#665C54",
    "terminal.ansiBrightBlue": "#0D6678",
    "terminal.ansiBrightCyan": "#8BA59B",
    "terminal.ansiBrightGreen": "#95C085",
    "terminal.ansiBrightMagenta": "#8F4673",
    "terminal.ansiBrightRed": "#FB543F",
    "terminal.ansiBrightWhite": "#FDF4C1",
    "terminal.ansiBrightYellow": "#FAC03B",
    "terminal.ansiCyan": "#8BA59B",
    "terminal.ansiGreen": "#95C085",
    "terminal.ansiMagenta": "#8F4673",
    "terminal.ansiRed": "#FB543F",
    "terminal.ansiWhite": "#A89984",
    "terminal.ansiYellow": "#FAC03B"
  },
  "editor.inlineSuggest.enabled": true,
  "github.copilot.enable": {
    "*": true,
    "yaml": false,
    "plaintext": false,
    "markdown": true
  },
  "turboConsoleLog.includeFileNameAndLineNum": false,
  "turboConsoleLog.logMessagePrefix": "",
  "turboConsoleLog.delimiterInsideMessage": "",
  "git.enableSmartCommit": true,
  "cSpell.userWords": ["Hasan", "Mahamud", "murad", "tailwindcss"],
  "typescript.format.insertSpaceAfterTypeAssertion": true,
  "editor.minimap.enabled": false,
  "editor.tabSize": 2,
  "files.autoSave": "afterDelay",
  "explorer.confirmDelete": false,
  "svelte.enable-ts-plugin": true,
  "svelte.plugin.svelte.note-new-transformation": false,
  "[svelte]": {
    "editor.defaultFormatter": "svelte.svelte-vscode"
  },
  "editor.codeLensFontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.fontWeight": "normal"
}
```
