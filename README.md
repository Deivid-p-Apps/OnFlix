# On Flix - Criando o JSON da Nuvem

O On Flix é um aplicativo de streaming de filmes onde os usuários fornecem o conteúdo a partir de fontes em nuvem, como Google Drive e MediaFire. Este guia ajudará você a criar o arquivo JSON necessário para compartilhar seus filmes com outros usuários.

## Estrutura do JSON

O JSON deve ter a seguinte estrutura:

```json
[
  {
    "nome": "Nome do Filme 1",
    "link": "URL do Filme 1"
  },
  {
    "nome": "Nome do Filme 2",
    "link": "URL do Filme 2"
  },
  ...
]
