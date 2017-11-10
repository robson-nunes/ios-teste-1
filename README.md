# Teste para candidatos à vaga de desenvolvedor iOS

[![WebGados](https://webgados.com.br/v2_assets/img/logo-webgados-cel.png)](https://webgados.com.br)

Esse teste é público. Candidatos para o teste devem implementar a aplicação solicitada e criar uma issue com um link para um repositório com a solução do mesmo.

### Objetivo do teste
Implementar em Swift 3/4 um aplicativo nativo para iOS que consulte uma API e mostre uma lista de anuncios (com foto).

### Requisitos
  - Seguir as diretrizes do iOS Human Interface Guidelines
  - Fazer cache das imagens
  - Se não houver internet, continuar exibindo os anuncios ja baixados e mostrar uma label indicando falta de conexao
  - Tela responsiva
  - Touch feedback (ao clicar em um anuncio abrir uma nova tela contedo uma label com o "_id" do anuncio selecionado)

### Tela (Lista de Anuncios)

Deve ser feita uma lista, em que cada elemento tenha a imagem, o titulo, idade, peso, preço e informaçoes do vendedor conforme abaixo:

![Lista de Anuncios](https://i.imgur.com/bXF4PhR.png)

### API:
Endpoint para pegar anuncios

> Link: https://webgados.com.br/anuncios-example

### Propriedades do anuncio na API:

- Titulo to anúncio -> "title"
- Idade: "years" e "months"
- Peso: "average_weight"
- Tipo de peso: "weight_type"
- Valor: "unit_value" (o valor contem um inteiro ja com centavos, dividindo por 100 voce obtem o valor real, exemplo: 120000 = R$ 1.200,00
- Nome do vendedor: "seller_name"
- Tipo do vendedor: Deixa sempre "corretor" (sem chave definida na api)
- Avaliaçao do vendedor: "seller_rating"
- Nome da cidade: "farm.city"
- Sigla da estado: "farm.state"
- Distancia: Deixa sempre "30km"  (sem chave definida na api)


### Critérios de avaliação:
- Organização do código: desacoplamento e legibilidade contam;
- Flexibilidade do sistema para adição/remoção de funcionalidades;

### Como vamos avaliar:
O código do aplicativo será clonado de algum repositório público e será executado através do XCode sobre diferentes dispositivos iOS emulados (a partir do iPhone 5);
Vamos ler o código;

### Dúvidas?
Envie um e-mail para: gabriel.stein@webgados.com.br
