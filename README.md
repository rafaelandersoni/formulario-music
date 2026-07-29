# Investigação e Reflexão

## Investigação

### Diferença entre GET e POST

Os métodos **GET** e **POST** são utilizados para enviar dados de um formulário para um servidor, mas cada um possui características diferentes.

* **GET:** envia as informações pela URL, tornando os dados visíveis na barra de endereços do navegador. É indicado para pesquisas, consultas e formulários que não utilizam informações confidenciais.
* **POST:** envia os dados no corpo da requisição (*body*), sem exibi-los na URL. Por isso, é o método mais adequado para cadastros, logins e formulários que envolvem informações pessoais ou sensíveis.

No meu formulário utilizei o método **GET**, definido na tag `<form>` com `method="get"`, pois ele é suficiente para a finalidade da atividade, que consiste apenas em coletar preferências musicais.

### Codificação

O formulário utiliza a codificação **UTF-8**, definida pela linha:

```html
<meta charset="UTF-8">
```

Essa codificação permite que caracteres especiais da língua portuguesa, como **á, é, ç, ã**, sejam exibidos corretamente, além de oferecer suporte a diversos outros símbolos e caracteres.

## Reflexão

Escolhi o tema **"Sua Música Favorita"** porque é um assunto simples, presente no cotidiano das pessoas e que facilita o preenchimento do formulário.

A utilização do método **GET** foi adequada, já que o formulário não coleta dados pessoais ou informações sigilosas. Seu objetivo é apenas registrar as preferências musicais dos usuários.

Durante o desenvolvimento, procurei organizar os campos de forma clara e objetiva, tornando o formulário fácil de compreender e preencher. Também procurei utilizar os elementos HTML de maneira adequada para deixar a interface simples e agradável.

Se tivesse mais tempo para desenvolver o projeto, implementaria validações em **JavaScript** para verificar o preenchimento dos campos antes do envio, melhoraria a adaptação do formulário para diferentes tamanhos de tela e adicionaria novos recursos para tornar a experiência do usuário mais completa.
