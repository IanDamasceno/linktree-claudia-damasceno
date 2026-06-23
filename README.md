# Linktree — Claudia Damasceno Advocacia

Página única e independente (HTML puro, sem build) com botões de WhatsApp por assunto.
Ideal para usar na bio do Instagram.

## Como usar / deploy
É só hospedar esta pasta em qualquer serviço de site estático (Netlify, Vercel,
GitHub Pages, etc.) ou abrir o `index.html` direto no navegador. Não precisa de
instalação nem build.

## Onde editar
Tudo fica no bloco `<script>` no fim do `index.html`:
- **Número do WhatsApp:** variável `WHATSAPP_NUMBER`
- **Botões e mensagens:** lista `LINKS`

## Foto
Salve a foto de perfil como `claudia-damasceno.jpg` nesta pasta (mesma do site).
Se o arquivo não existir, aparece um ícone no lugar.
