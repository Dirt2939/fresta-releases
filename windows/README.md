# Windows

`latest.json` aponta para o instalador mais novo (`Fresta-Setup.exe`, release `windows-vX.Y.Z`):

```json
{ "version": "0.18.0", "date": "2026-10-15", "notes": "…", "url": "https://github.com/Dirt2939/fresta-releases/releases/download/windows-v0.18.0/Fresta-Setup.exe", "sha256": "…", "size": 0 }
```

Ele é escrito por `npm run publish:installer` no projeto. O app compara `version` com a sua, baixa `url` só quando o usuário clica em Update e confere o `sha256` antes de instalar.
