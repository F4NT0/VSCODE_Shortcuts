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
    "editor.inlineSuggest.enabled": true,
    "files.autoSave": "afterDelay",
    "git.openRepositoryInParentFolders": "never",
    "git.confirmSync": false,
    "accessibility.dimUnfocused.opacity": 1,
    "git.enableSmartCommit": true,
    "workbench.colorTheme": "Bearded Theme Monokai Black",
    "workbench.iconTheme": "bearded-icons",
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontSize": 13,
    "editor.fontLigatures": true,
    "editor.minimap.enabled": false,
    "security.workspace.trust.untrustedFiles": "open",
    "workbench.activityBar.location": "hidden",
    "explorer.compactFolders": false,
    "workbench.startupEditor": "newUntitledFile",
    "window.commandCenter": false,
}
```

O comando "workbench.activityBar.location": "hidden" = remove a barra da esquerda, pode ser acessado com `Ctrl` + `Q`.



