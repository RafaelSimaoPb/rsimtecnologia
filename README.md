# Site RSIM Tecnologia

Site estático de uma página (HTML + CSS, sem build).

## Antes de publicar
No `index.html`, troque os contatos de exemplo:
- `https://wa.me/5500000000000` (aparece 3 vezes): use 55 + DDD + número, só dígitos.
- `contato@seudominio.com.br` (aparece 2 vezes).

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `rsim-site`) e envie estes arquivos para a branch `main`.
2. No repositório: Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save.
3. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/rsim-site/`.

## Domínio próprio (opcional)
Crie um arquivo `CNAME` na raiz contendo só o domínio (ex.: `www.rsim.com.br`),
aponte no seu provedor de DNS um registro CNAME de `www` para `SEU-USUARIO.github.io`
e marque "Enforce HTTPS" em Settings → Pages.

## Estrutura
- `index.html` — conteúdo
- `css/style.css` — visual (cores e fontes do brand kit no topo do arquivo)
- `assets/img/` — logos e favicon
