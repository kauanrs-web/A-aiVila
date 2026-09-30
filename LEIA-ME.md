# Açai da Vila — landing page de demonstração

Abra index.html no navegador, mantendo a pasta assets e os favicons junto dele. O HTML contém todo o CSS e JavaScript da página. A conexão com a internet permite carregar o Tailwind via CDN; o CSS próprio preserva o layout se o CDN estiver indisponível.

Marca, produtos, preços, depoimentos e fotografia são ilustrativos. A página não recebe pedidos ou pagamentos. A fotografia foi gerada por IA.

## Arquivos

- index.html: código completo, com comentários numerados e os três arquivos técnicos transcritos no final.
- assets/: fotografia WebP em duas resoluções, imagem social de 1200 × 630 e logo WebP.
- favicon.ico, favicon-32x32.png, favicon-16x16.png e apple-touch-icon.png: ícones reais nos formatos solicitados. Favicons são a exceção aos arquivos de conteúdo em WebP.
- robots.txt: permite rastreamento e aponta para o sitemap.
- sitemap.xml: lista a única página pública; seções com âncoras não precisam de entradas separadas.
- llms.txt: resumo e caminhos de leitura para IA; não garante treinamento ou indexação.

## As oito configurações

1. Favicon completo, com ICO, PNG 16/32 e Apple 180.
2. Title, description, keywords, canonical, viewport, Open Graph, Twitter Card e verificação do Search Console.
3. JSON-LD Organization com nome, descrição, domínio, logo e campos de redes sociais.
4. Robots, sitemap e llms como arquivos separados e comentários no fim do HTML.
5. Estrutura GA4 via gtag.js no head; G-XXXXXXXXXX é um placeholder inativo.
6. Snippet Microsoft Clarity no head; SEU_CLARITY_ID é um placeholder inativo.
7. Conteúdo visual WebP, picture responsivo, alt detalhado, dimensões explícitas, lazy e decoding async. Preload responsivo da foto principal.
8. Tailwind via CDN, layout mobile-first, header responsivo, hero, CTA, benefícios, depoimentos, accordion JS e footer.

## Personalização antes de publicar

1. Substitua https://acaidavila.example/ por um domínio HTTPS real no HTML, robots.txt, sitemap.xml e llms.txt. O domínio .example é reservado para exemplos.
2. Ajuste nome, receitas, preços, imagens e textos. Substitua os depoimentos fictícios por avaliações reais autorizadas.
3. No JSON-LD, preencha SEU_PERFIL com os perfis reais. Remova as entradas de sameAs se não houver perfis oficiais.
4. Substitua SEU_CODIGO_AQUI pela verificação do Search Console, verifique a propriedade e envie sitemap.xml no painel.
5. Preencha GA4_ID e CLARITY_ID com IDs reais apenas quando quiser ativar medição. O exemplo não carrega esses rastreadores com placeholders. Adapte a ativação à política de privacidade e às escolhas de consentimento do projeto real.
6. Hospede todos os arquivos preservando os caminhos relativos. Os metadados sociais precisam de URLs absolutas públicas; abrir localmente não produz uma prévia social pública.
7. Para ambiente de produção, compile as classes Tailwind em um CSS estático e substitua o script CDN por um link para esse arquivo. O Play CDN é destinado a desenvolvimento segundo o Tailwind. O pedido por CDN foi mantido nesta demonstração.

O loading lazy da imagem principal foi mantido por solicitação. Em um projeto real, considere eager/fetchpriority high para o hero após medir o LCP. Keywords não garantem posição em buscas. Robots permite rastreamento, mas não garante indexação. llms.txt não é uma autorização de treinamento.

## Referências oficiais

- Tailwind Play CDN: https://tailwindcss.com/docs/installation/play-cdn
- Google tag: https://developers.google.com/tag-platform/gtagjs
- Microsoft Clarity: https://learn.microsoft.com/en-us/clarity/setup-and-installation/clarity-setup

## Versão com fotos

Paleta atualizada com roxo vibrante, rosa e verde-lima. Fotografias ilustrativas de açaí no início, nas três opções do cardápio e na janela de detalhes. Todas as fotografias foram geradas por IA e são entregues localmente em WebP.
