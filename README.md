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
  // define colunas verticais para ajudar a manter o código dentro de uma largura desejada
  "editor.rulers": [80, 120],
  // especifica onde a linha atual deve ser destacada
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
  // define a visibilidade da barra de status no VS Code
  "workbench.statusBar.visible": false,
  "explorer.sortOrder": "foldersNestsFiles",
  // controla a exibição do cursor na régua de visão geral
  "editor.hideCursorInOverviewRuler": true,
  // controla a exibição do minimapa no editor
  "editor.minimap.enabled": false,
  // define o comportamento da barra de rolagem vertical
  "editor.scrollbar.vertical": "hidden",
  // controla se uma confirmação é solicitada ao excluir arquivos ou pastas no Explorer
  "explorer.confirmDelete": true,
  "terminal.integrated.showExitAlert": true,
  // controla a funcionalidade de aninhamento de arquivos
  "explorer.fileNesting.enabled": true,

  // configuracao do EsLint para arrumar os erros
  "editor.codeActionsOnSave": {
    "source.fixAll.esLint": "explicit"
  },
  "workbench.colorTheme": "Min Dark",

  // definindo o tratamento do js no pelo emmet
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  // especificando como o Emmet deve interpretar a sintaxe do JS/JSX
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  }
}
