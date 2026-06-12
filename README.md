# Monorepo Workshop - Etappe 2

Diese README wird dich durch den Workshop begleiten und immer die nützlichen **Snippets** für die jeweils nächste Etappe bereitstellen.

## Snippets für Etappe 3

`package.json` für das `ui`-Paket:

```json
{
  "name": "@my-repo/ui",
  "version": "1.0.0",
  "type": "module",
  "exports": {
    "./*": "./*"
  }
}
```

Installation des `ui`-Pakets als Abhängigkeit in den Apps:

```bash
npm install @my-repo/ui -w apps/landing-page
npm install @my-repo/ui -w apps/web-app
```

Starten der Entwicklungsumgebung (benutze zwei Terminals):

```bash
npm run dev -w apps/landing-page
npm run dev -w apps/web-app
```
