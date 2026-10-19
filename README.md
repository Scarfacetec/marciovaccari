# Márcio Vaccari — Cinema, palavra e invenção

Site estático em português, feito com HTML, CSS e JavaScript puro. Não necessita de instalação de dependências nem compilação. A pasta `dist` está pronta para qualquer hospedagem estática, inclusive Apache/Laragon.

## Abrir localmente

Na pasta deste projeto, execute `node serve.mjs` e acesse http://127.0.0.1:4173.

Pelo Laragon, acesse o caminho `/Marcio%20Vaccari/marcio-vaccari/dist/` a partir do seu domínio local.

## Arquivos

- `dist/index.html`: apresentação, biografia, música, livros e fontes.
- `dist/styles.css`: identidade visual e adaptações para celular.
- `dist/script.js`: 12 entradas do acervo, filtros, menu e diálogos com fontes.
- `dist/assets/`: duas imagens fornecidas na pasta original e favicon.
- `PESQUISA.md`: escopo, critérios e referências editoriais.

Os dados do acervo podem ser editados no array `works`, em `script.js`. O restante dos textos fica no HTML.

Os cartazes e as peças de livros são composições tipográficas originais para o site; não representam cartazes oficiais nem capas reais. Não foram inventados depoimentos, contatos, pinturas ou créditos em novelas. As fotos foram copiadas dos arquivos existentes no projeto; a autoria fotográfica não foi informada.

O servidor Node serve apenas para prévia local. Ele não faz parte do site publicado. A hospedagem Sites começa privada, para revisão.

## Prévia do WhatsApp

O HTML usa tags Open Graph para WhatsApp e redes sociais: og:title, og:description, og:url, og:image, og:image:width, og:image:height e twitter:card. A URL prevista é https://marciovaccari.pages.dev/. Se o domínio do Cloudflare Pages for diferente, substitua marciovaccari.pages.dev nas tags de dist/index.html antes de publicar.
