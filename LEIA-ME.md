# SITE_FORMULARIO_ARVE

Pasta publicável do formulário de participante do treinamento da ARVE.

- `index.html` é a página inteira num arquivo só, com o logo embutido em base64.
  Não depende de nenhuma imagem ou arquivo externo.
- `.nojekyll` impede o GitHub Pages de processar a pasta.
- A página nasce com `noindex, nofollow`, como todo material do Voz do Ser.

Antes de publicar, a linha `ENDPOINT` dentro do `index.html` precisa ter a URL do
Apps Script publicado. Enquanto ela estiver com `COLE_AQUI_A_URL_DO_APPS_SCRIPT`,
o formulário funciona mas não envia.

A documentação completa, o template e o código do Google estão em
`Claude outputs/FORMULARIO_ARVE_BUILD/`.
