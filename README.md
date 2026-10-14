# 300-prompts-theaimodelab

Funil estático em **espanhol** — 33 páginas + assets, pronto pra deploy na Vercel.

## Conteúdo

- `index.html` + 33 diretórios de página (uma `index.html` cada)
- `_next/` — bundle JS/CSS do app
- `assets/img/` — imagens em espanhol
- `assets/vendor/` — libs de terceiros
- `assets/video/*/thumbnail.jpg` — só os posters; **os vídeos não estão no repo**
- `assets/noop-pixel.js` — stub que neutraliza o pixel original

## Deploy

Site 100% estático. Na Vercel: framework **Other**, sem build command, output = raiz do repo.

## Antes de rodar tráfego

- [ ] Trocar o `<title>` (hoje ainda é o original)
- [ ] Subir os vídeos próprios e reapontar os 3 players (`5c5p596m6i`, `693g61265l`, `1o3t6x5g2f`)
- [x] UTMify UTMs + Pixel novos (pixelId `6ac17129…`, 14/10); Meta `1223791793200733` mantido
- [x] Checkout trocado em 14/10 pra `checkout.centerpag.com/pay/PPU38CQGMST` ($12.99)
