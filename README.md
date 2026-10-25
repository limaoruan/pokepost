# PokéPost 1.4

Gerador de posts para o Instagram da PokéBottons. Site estático (PWA, mobile first) feito por Ruan Oliveira Lima, hospedado no **GitHub Pages**. **Não usa banco de dados nem login**: tudo roda no navegador.

Esta pasta é a **raiz de um repositório** no GitHub (`pokepost`).

---

## O que faz

Gera a imagem do post (PNG 1080×1350) com a foto escolhida em um círculo no estilo botton, a logo da PokéBottons e o versículo João 3:16.

## Como usar
1. Toque no círculo para escolher a foto.
2. A logo da PokéBottons já vem carregada (toque em **Trocar** para usar outra).
3. Toque em **Baixar post** para salvar o PNG.
4. Use **Trocar imagem** para recomeçar.

## Instalar
1. Em `index.html`, `robots.txt` e `sitemap.xml`, troque `limaoruan` pelo seu usuário do GitHub.
2. **Publicar**: crie o repositório público `pokepost`, envie o conteúdo desta pasta, e em **Settings**, **Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Endereço: https://limaoruan.github.io/pokepost/
4. **App (opcional)**: no celular, abra o endereço e use **Adicionar à tela inicial**.

Não precisa de Supabase nem de `config.js`.

## Manutenção
Para atualizar o site, edite os arquivos no repositório; o GitHub Pages publica sozinho em alguns minutos.

## Arquivos
- `index.html`: o site inteiro (HTML, CSS e JavaScript)
- `service-worker.js`, `manifest.webmanifest`: PWA
- `logo.png`, `pokebottons-logo.png`, `icon-*.png`, `favicon*`, `apple-touch-icon.png`, `og-image.jpg`: imagens
- `robots.txt`, `sitemap.xml`, `.nojekyll`

---

© 2026 Ruan Oliveira Lima · Instagram: https://www.instagram.com/ruanoliveiralima_/
Licença: CC BY-NC-ND 4.0
