# Monorepo Workshop - Etappe 1

Diese README wird dich durch den Workshop begleiten und immer die nützlichen **Snippets** für die jeweils nächste Etappe bereitstellen.

## Snippets für Etappe 2

`package.json` im Root-Verzeichnis:

```json
{
  "name": "my-repo",
  "workspaces": ["apps/*", "packages/*"]
}
```

Löschen der `node_modules`-Ordner und der `package-lock.json`-Dateien:

```bash
rm -rf landing-page/node_modules web-app/node_modules
rm -rf landing-page/package-lock.json web-app/package-lock.json
```

Installieren der Abhängigkeiten im Root-Verzeichnis:

```bash
npm install
```
