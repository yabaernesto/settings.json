# settings.json
Minhas configurações do VS Code

```json
{
  "explorer.compactFolders": false,
  "notebook.defaultFormatter": "esbenp.prettier-vscode",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": false
  },
  "symbols.hidesExplorerArrows": false,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  "editor.fontFamily": "Fira Code",
  "editor.tabSize": 2,
  "editor.fontLigatures": true,
  "editor.fontWeight": "normal",
  "editor.wordWrap": "on",
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "terminal.integrated.showExitAlert": true,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "terminal.integrated.env.linux": {},
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.rulers": [80, 120],
  "editor.renderLineHighlight": "gutter",
  "extensions.ignoreRecommendations": true,
  "typescript.tsserver.log": "off",
  "files.associations": {
    ".env.*": "dotenv",
    ".prettierrc": "json",
    "*.css": "css"
  },
  "symbols.files.associations": {
    "*.module.ts": "nest",
    "*.guard.ts": "typescript",
    "*.spec.ts": "ts-test",
    "*.e2e-spec.ts": "ts-test",
    "vitest.config.e2e.ts": "vite",
    ".env.example": "gear"
  },
  "workbench.statusBar.visible": false,
  "explorer.sortOrder": "foldersNestsFiles",
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "editor.scrollbar.vertical": "hidden",
  "explorer.confirmDelete": true,
  "explorer.fileNesting.enabled": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "json",
    "graphql"
  ],
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "postcss": "css"
  },
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "tailwindCSS.experimental.classRegex": [
    [
      "tv\\(([^)]*)\\)",
      "[\"'`]([^\"'`]*).*?[\"'`]"
    ],
    "class:\\s*?[\"'`]([^\"'`]*).*?,"
  ],
  "[prisma]": {
    "editor.defaultFormatter": "Prisma.prisma"
  },
  "console-ninja.featureSet": "Community",
  "workbench.productIconTheme": "fluent-icons",
  "workbench.iconTheme": "symbols",
  "explorer.confirmDragAndDrop": false,
  "markdown-preview-enhanced.previewTheme": "monokai.css",
  "git.autofetch": true,
  "workbench.editorAssociations": {
    "*.sqlite": "default"
  },
  "workbench.colorTheme": "Omni"
}
```
