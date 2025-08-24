# IMAGINATION — Hub (IA + Spotify)
Landing unificada com identidade visual, abas para **IA** (geração automática) e **Spotify** (playlist embed).

## Como publicar no GitHub Pages (zero instalação)
1. Faça um repositório no GitHub e suba estes arquivos.
2. Em **Settings → Pages**, ative o GitHub Pages para a branch `main`.
3. Edite `config.json` e coloque a URL do seu backend IA (ex.: `https://seu-projeto.vercel.app`).

## Como conectar a IA
- Faça deploy do backend serverless (ex.: o pacote `vercel-ia-api` que já gerei).
- Copie a URL (ex.: `https://seu-projeto.vercel.app`) e preencha em `config.json` → `API_BASE`.

## Spotify
- A aba Spotify usa o embed oficial para a playlist fixa definida no HTML.
- Se quiser mudar a playlist, altere o `src` do `<iframe>` para outro ID.
