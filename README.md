## Minha configuracao do VS Code

```json
{
  "workbench.iconTheme": "symbols",
  "explorer.compactFolders": false,
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "notebook.defaultFormatter": "esbenp.prettier-vscode",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "symbols.hidesExplorerArrows": false,
  // format font size
  "editor.fontSize": 14,
  "editor.lineHeight": 1.8,
  // ativando o Fira Code
  "editor.fontFamily": "Fira Code",
  // espacamento da identacao
  "editor.tabSize": 2,
  // Ativa ligaduras de fonte se suportadas pela fonte
  "editor.fontLigatures": true,
  "editor.fontWeight": "normal",
  // Ativa a quebra de linha automática
  "editor.wordWrap": "on", 
    
  "javascript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.rulers": [80, 120],
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
  // remove status bar
  "workbench.statusBar.visible": false,
  "explorer.sortOrder": "foldersNestsFiles",
  // cursor
  "editor.hideCursorInOverviewRuler": true,
  "editor.minimap.enabled": false,
  "workbench.colorTheme": "Min Dark",

  // configuracao do EsLint para arrumar os erros
  "editor.codeActionsOnSave": {
    "source.fixAll.esLint": true,
  }
}
