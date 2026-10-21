# +150 Mídias para Hamburguerias

Página de vendas do pack de mídias para hamburguerias.

## Estrutura

- `index.html` — a página (estilos e scripts estão dentro dela)
- `mockup.webp`, `mockup-mini.webp` — mockup do produto
- `video1.mp4`, `video2.mp4` (+ capas `.jpg`) — vídeos de exemplo
- `midias/` — imagens do carrossel e do painel de perfil
- `depoimentos/` — prints dos depoimentos

## Onde mudar as coisas

- **Links de checkout:** no `href` dos botões, em `index.html` (procure por `checkout.wiven`)
- **Imagens do carrossel e nomes:** `LINHA_1` e `LINHA_2` no script, no fim do `index.html`
- **Pixels:** no `<head>` (UTMify e Facebook)

## Publicar na Vercel

Importe este repositório na Vercel como um projeto estático (sem framework, sem build).
