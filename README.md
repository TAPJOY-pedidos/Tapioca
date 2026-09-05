# Tap Joy — Cardápio

Site de cardápio da tapiocaria Tap Joy, com a logo oficial, abas por categoria, link do Instagram e pedidos via WhatsApp.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (pode ser público), por exemplo `tapjoy-cardapio`.
2. Suba **todos os arquivos desta pasta** para a raiz do repositório: `index.html`, `logo.jpg` e `.nojekyll`.
   - Pelo site do GitHub: abra o repositório → **Add file** → **Upload files** → arraste os arquivos → **Commit changes**.
   - Importante: `logo.jpg` precisa ficar na mesma pasta que `index.html`, senão a imagem não aparece.
3. No repositório, vá em **Settings** → **Pages** (menu lateral).
4. Em **Build and deployment** → **Source**, selecione **Deploy from a branch**.
5. Em **Branch**, selecione `main` (ou `master`) e a pasta `/ (root)` → **Save**.
6. Aguarde 1–2 minutos. O GitHub vai mostrar o link do site, algo como:
   `https://SEU-USUARIO.github.io/tapjoy-cardapio/`

## Atualizar o cardápio depois

Os itens, preços e descrições ficam no início do `<script>` dentro do `index.html`, no objeto `menu`. Basta editar esse trecho, salvar e subir o arquivo atualizado no GitHub (o site atualiza sozinho a cada commit).

Para trocar a logo, basta substituir o arquivo `logo.jpg` por outro com o mesmo nome (ou trocar o nome no `<img src="...">` do `index.html`).

## Arquivos

- `index.html` — o site completo (HTML, CSS e JS)
- `logo.jpg` — a logo do Tap Joy usada no topo do site
- `.nojekyll` — impede o GitHub Pages de processar o site com Jekyll (mantém tudo funcionando como está)
