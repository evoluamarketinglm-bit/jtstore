# JT STORE — Catálogo esportivo

Site estático completo, responsivo, pronto para GitHub Pages e Vercel. Base: GTwelveStore.

## Como publicar

1. Extraia o ZIP.
2. Suba os arquivos de `JT_STORE_SITE/` para a raiz do repositório GitHub (sem mudar a estrutura).
3. No Vercel, importe o repositório e escolha "Other" ou deploy estático (sem comando de build).
4. No GitHub Pages, habilite a publicação da branch principal e pasta `/ (root)`.

## Onde trocar as URLs

Edite `configuracao.js`: `loja` contém a logo, o WhatsApp, o banner do meio, seu link de destino e o banner final. `ligas` contém os banners desktop/mobile e os links dos clubes. `loja.outrasColecoes` contém o banner e os catálogos dessas coleções.

### Banner do Campeonato Brasileiro

Banner definitivo configurado nas versões Desktop e Mobile da liga `liga-02`: https://ik.imagekit.io/verlcwgen/Banner%20Esportivo%20Brasileiro%20em%20Vermelho%20Neon.png?updatedAt=1794260598541

## Design

- Cabeçalho branco com logo ao centro, menu e pesquisa escuros.
- Cores pretas, brancas e vermelhas (#F11935).
- Apenas botão flutuante de WhatsApp, para `https://wa.me/5541987302112`.
- Nenhum banner inicial.
- Banner quadrado no meio, depois do Campeonato Italiano, com link clicável para o grupo informado.
- Banner quadrado ao fim da página, depois de Outras Coleções.
- Preservados os carrosséis, escudos, fotos, e os links originais dos catálogos.

Não exige Node, npm ou backend; hospedagem estática é suficiente.

## Atualização — Coritiba

Coritiba incluído no carrossel do **Campeonato Brasileiro** (logo depois do Athletico Paranaense), com escudo oficial fornecido e link do catálogo:

- Escudo: https://www.footylogos.com/dls/logo/rgba-v1/coritiba.png
- Catálogo: https://photos.app.goo.gl/cH83s3n1nHFnUC3H7

Todos os outros clubes e URLs foram mantidos.
