# Monorepo Workshop - Start

Diese README wird dich durch den Workshop begleiten und immer die nützlichen **Snippets** für die jeweils nächste Etappe bereitstellen.

## Snippets für Etappe 1

Lege zwei neue Projekte an:

```bash
npm create astro@latest web-app -- --no-git --yes
npm create astro@latest landing-page -- --no-git --yes
```

Starte diese Projekte jeweils (benutze zwei Terminals):

```bash
cd web-app
npm run dev

cd landing-page
npm run dev
```

Beispiel für die `src/components/Button.astro`:

```astro
<button>
  <slot />
</button>

<style>
  button {
    padding: 8px 16px;
    background-color: blue;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1em;
  }
</style>
```
