# Configuração minimalista do VSCODE

Baixe as seguintes extensões:
- Bearded Theme
- Bearded Icons

Baixe a seguinte fonte:
- JetBrains mono ExtraLight (coloquei ela aqui no repositório)

Abra o arquivo JSON de configuração do VSCODE
- `Ctrl` + `Shift` + `P`
- Selecione a opção: `Preferences: Open User Settings (JSON)`

Cole o seguinte JSON:

```json
{
    "workbench.colorTheme": "Bearded Theme Vivid Black",
    "files.autoSave": "afterDelay",
    "workbench.iconTheme": "bearded-icons",
    "editor.minimap.enabled": false,
    "editor.fontFamily": "JetBrains mono",
    "editor.fontLigatures": true,
    "editor.fontSize": 14,
    "workbench.startupEditor": "newUntitledFile",
    "editor.renderLineHighlight": "gutter",
    "workbench.editor.labelFormat": "short",
    "explorer.compactFolders": false,
    "editor.semanticHighlighting.enabled": false,
    "breadcrumbs.enabled": false,
    "workbench.activityBar.location": "hidden",
    "editor.scrollbar.horizontal": "hidden",
    "editor.scrollbar.vertical": "hidden",
}
```

O comando "workbench.activityBar.location": "hidden" = remove a barra da esquerda, pode ser acessado com `Ctrl` + `Q`.



