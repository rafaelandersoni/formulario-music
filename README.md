# Investigação e Reflexão

## Investigação

### Diferença entre GET e POST

Os métodos **GET** e **POST** são responsáveis por enviar os dados de um formulário para um servidor, mas cada um é utilizado em situações diferentes.

* **GET:** envia as informações pela URL, permitindo que os dados fiquem visíveis na barra de endereços do navegador. É indicado para pesquisas, consultas e formulários que não trabalham com informações sigilosas.
* **POST:** envia os dados no corpo da requisição (*body*), sem que apareçam na URL. Por esse motivo, é o método mais utilizado em cadastros, logins e formulários que armazenam informações pessoais.

Neste projeto, foi utilizado o método **GET**, pois o formulário tem apenas o objetivo de registrar preferências musicais, sem coletar dados que exijam maior segurança.

## Codificação

Para garantir a correta exibição dos caracteres especiais da língua portuguesa, o formulário utiliza a codificação **UTF-8**, definida pela seguinte linha de código:

```html id="m1g7ve"
<meta charset="UTF-8">
```

Com essa configuração, caracteres como **á**, **é**, **ç** e **ã** são exibidos corretamente em diferentes navegadores e sistemas operacionais.

## Reflexão

O tema **"Sua Música Favorita"** foi escolhido por ser simples, familiar e de fácil compreensão. Dessa forma, qualquer pessoa consegue responder ao formulário de maneira rápida e intuitiva.

Durante o desenvolvimento, procurei organizar os campos de forma clara, mantendo uma estrutura simples e fácil de utilizar. Também busquei aplicar corretamente os conceitos estudados sobre formulários em HTML, tornando o projeto funcional e bem organizado.

Como forma de aprimorar o projeto, seria interessante adicionar validações com **JavaScript** para verificar os dados antes do envio, melhorar ainda mais a responsividade em dispositivos móveis e incluir novos recursos que tornem a interação com o formulário mais prática e agradável para o usuário.
