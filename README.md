# PokéPost 1.4

Gerador de posts para o Instagram da PokéBottons. Site estático (PWA, mobile first) feito por Ruan Oliveira Lima, hospedado no **GitHub Pages**. **Não usa banco de dados nem login**: tudo roda no navegador e nada é enviado para fora.

Esta pasta é a **raiz de um repositório** no GitHub (`pokepost`).

---

## O que faz

Gera a imagem do post (PNG 1080×1350) com a foto escolhida em um círculo no estilo botton (com a borda dobrada), a logo da PokéBottons e o versículo João 3:16. A prévia na tela tem 800×800 px no círculo; o PNG final sai em 1080×1350.

## Como usar
1. Toque no círculo e escolha a foto (qualquer imagem; tamanho recomendado: 2592 × 2592 px).
2. Ajuste a foto: arraste para mover e use o movimento de pinça com dois dedos (ou a roda do mouse) para dar zoom, de 1× a 4×. Com zoom 1× a foto cobre exatamente o círculo.
3. A logo da PokéBottons já vem carregada. Para usar outra (tamanho recomendado: 1520 × 304 px, proporção 5:1), toque em **Trocar**: a logo atual é removida e volta a caixa "Upload da Logo"; toque nela para escolher o novo arquivo.
   - A logo entra inteira, centralizada e sem distorcer, numa caixa de proporção 5:1.
   - O botão **Trocar** fica cinza e inativo enquanto não há logo.
   - Se o arquivo da logo padrão falhar ao carregar, aparece a caixa "Upload da Logo".
4. Toque em **Baixar post** para salvar o arquivo `pokebottons-post.png`. O botão só fica ativo com a foto e a logo carregadas e mostra "Preparando…" enquanto gera a imagem.
5. Use **Trocar imagem** para tirar a foto e recomeçar. Ele não mexe na logo.

**Foto carregada:** tocar no círculo passa a arrastar a foto e não abre mais o seletor de arquivo. Para escolher outra foto, use **Trocar imagem**.

**Nada fica salvo:** se recarregar a página, a foto e a logo escolhidas se perdem.

**Internet:** o site abre sem conexão, mas a fonte do versículo (Baloo 2) vem do Google Fonts. Sem internet, o texto do PNG pode sair em outra fonte; baixe o post com conexão.

**App:** no celular, abra o endereço do site e use **Adicionar à tela inicial** (Android: menu do navegador; iPhone: Compartilhar).

## Manutenção
Para atualizar o site, edite os arquivos no repositório; o GitHub Pages publica sozinho em alguns minutos.

## Arquivos
- `index.html`: o site inteiro (HTML, CSS e JavaScript)
- `service-worker.js`, `manifest.webmanifest`: PWA
- `pokebottons-logo.png`: logo que já vem carregada no post
- `logo.png`, `icon-*.png`, `favicon*`, `apple-touch-icon.png`, `og-image.jpg`: imagens do site
- `LICENCE.md`: licença do projeto
- `robots.txt`, `sitemap.xml`, `.nojekyll`

---

© 2026 Ruan Oliveira Lima · Instagram: https://www.instagram.com/ruanoliveiralima_/
Licença: CC BY-SA 4.0 (texto completo no `LICENCE.md`)
