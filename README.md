# Copa Colombia 2025 - Fixture (HTML)

Proyecto estático (solo HTML/CSS/JS) listo para desplegar en Vercel.

## Archivos

- `index.html`: página principal (Vercel sirve este archivo en `/`).
- `fixture-copa-colombia-2025.html`: copia alternativa del fixture (también accesible directamente).
- `vercel.json`: configuración mínima para hosting estático.

## Desplegar en Vercel (sin CLI)

1. Sube este proyecto a un repositorio (GitHub/GitLab/Bitbucket).
2. En Vercel: **Add New** → **Project** → Importa el repo.
3. En “Framework Preset” selecciona **Other**.
4. Deja vacío “Build Command” y “Output Directory”.
5. Deploy.

## Desplegar en Vercel (con CLI)

1. Instala la CLI:

```bash
npm i -g vercel
```

2. Desde la carpeta del proyecto:

```bash
vercel
```

Si quieres hacer deploy a producción:

```bash
vercel --prod
```
