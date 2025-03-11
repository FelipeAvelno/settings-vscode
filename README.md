### Minhas configurações do Visual Studio Code

> [!NOTE]
> Algumas configurações podem estar atualizadas ou dessincronizadas, ou incompatíveis com algumas versões do Visual Studio Code (principalmente as configurações apc electron)

```bash
{
    "files.autoSave": "afterDelay",
    "explorer.confirmDragAndDrop": false,
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontSize": 15,
    "editor.lineHeight": 1.8,
    "workbench.startupEditor": "none",
    "editor.fontLigatures": false,
    "breadcrumbs.enabled": false,
    "workbench.activityBar.location": "default",
    "editor.scrollbar.vertical": "hidden",
    "explorer.fileNesting.patterns": {
        "*.ts": "${capture}.js",
        "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
        "*.jsx": "${capture}.js",
        "*.tsx": "${capture}.ts",
        "tsconfig.json": "tsconfig.*.json",
        "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
        "*.sqlite": "${capture}.${extname}-*",
        "*.db": "${capture}.${extname}-*",
        "*.sqlite3": "${capture}.${extname}-*",
        "*.db3": "${capture}.${extname}-*",
        "*.sdb": "${capture}.${extname}-*",
        "*.s3db": "${capture}.${extname}-*"
    },
    "git.autofetch": true,
    "security.workspace.trust.untrustedFiles": "open",
    "explorer.compactFolders": false,
    "apc.electron": {
        "titleBarStyle": "hiddenInset"
    },

    "apc.header": {
        "height": 36
    },

    "apc.listRow": {
        "height": 24
    },
    "apc.font.family": "Inter",
    
    "workbench.layoutControl.enabled": false,
    "chat.commandCenter.enabled": false,
    "workbench.navigationControl.enabled": false,
    "terminal.integrated.fontSize": 14,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Darcula - WebStorm Edition",
}
```
