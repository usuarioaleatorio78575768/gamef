# Deploy rápido na Vercel

Este pacote foi organizado para funcionar com `index.html` na raiz do projeto.

## O que precisa estar na raiz do GitHub

```text
index.html
README.md
LICENSE
package.json
vercel.json
netlify.toml
.gitignore
.nojekyll
```

Não deixe esses arquivos dentro de uma pasta tipo `space-rush-github-ready/`, senão a Vercel pode publicar a pasta errada e mostrar `404 NOT_FOUND`.

## Configuração recomendada na Vercel

Em Project Settings:

- Framework Preset: **Other**
- Root Directory: **./**
- Build Command: vazio
- Output Directory: vazio ou `.`
- Install Command: vazio

Depois clique em **Redeploy**.
