# autark-midia

Hospedagem das imagens dos carrosséis já publicados no Instagram da
[Autark](https://parknow914.github.io/).

Este repositório é público por uma razão técnica: a API de publicação da Meta
**baixa** a imagem por HTTPS — não existe envio de bytes para foto. A URL
precisa responder no momento em que o container do post é criado.

Só entra aqui imagem de post já aprovado, que vai virar pública no Instagram de
qualquer forma. O calendário editorial, os posts não publicados e o código do
pipeline ficam num repositório privado.

Os arquivos são gerados a partir de Markdown, em 1080x1350, e enviados
automaticamente pelo workflow de publicação.
