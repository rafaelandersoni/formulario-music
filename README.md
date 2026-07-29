# Investigação e Reflexão

## Investigação

### Diferença entre GET e POST

Os métodos **GET** e **POST** são utilizados para enviar dados de um formulário para um servidor, porém possuem finalidades diferentes.

* **GET:** envia os dados pela URL, tornando as informações visíveis na barra de endereços do navegador. É indicado para pesquisas, consultas e formulários que não lidam com dados confidenciais.
* **POST:** envia os dados no corpo da requisição (*body*), sem exibi-los na URL. Por isso, é o método mais recomendado para cadastros, logins e formulários que envolvem informações pessoais ou sensíveis.

Neste projeto, foi utilizado o método **GET**, definido na tag `<form>` com `method="get"`, pois o formulário tem apenas a finalidade de coletar preferências musicais para fins de demonstração.

## Codificação

O formulário utiliza a codificação **UTF-8**, definida pela linha:

```html
<meta charset="UTF-8">
```

Essa codificação garante a exibição correta de caracteres especiais da língua portuguesa, como **á, é, ç** e **ã**, além de suportar diversos outros símbolos e caracteres.

## Reflexão

O tema **"Sua Música Favorita"** foi escolhido por ser simples, acessível e fazer parte do cotidiano da maioria das pessoas, tornando o formulário fácil de compreender e responder.

O método **GET** foi adotado por atender às necessidades da atividade, já que o formulário não coleta informações pessoais ou dados sensíveis.

Durante o desenvolvimento, o foco foi criar um formulário organizado, intuitivo e de fácil utilização, utilizando os elementos HTML adequados para cada tipo de informação solicitada.

Como melhorias futuras, seria possível adicionar validações em **JavaScript** para verificar o preenchimento dos campos antes do envio, aprimorar a responsividade para diferentes dispositivos e incluir novas funcionalidades para tornar a experiência do usuário ainda melhor.
