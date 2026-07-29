# Investigação e Reflexão

## Investigação

### Diferença entre GET e POST

Os métodos **GET** e **POST** são utilizados para enviar informações de um formulário para um servidor, mas cada um possui uma finalidade diferente.

* **GET:** envia os dados pela URL, deixando as informações visíveis na barra de endereços do navegador. É mais indicado para pesquisas, consultas e formulários que não utilizam informações confidenciais.
* **POST:** envia os dados no corpo da requisição (*body*), sem exibi-los na URL. Por isso, é o método mais recomendado para cadastros, logins e formulários que envolvem dados pessoais ou sensíveis.

No meu formulário, utilizei o método **GET**, definido na tag `<form>` com `method="get"`, porque o objetivo é apenas coletar preferências musicais para fins de demonstração, sem o envio de informações confidenciais.

### Codificação

O formulário utiliza a codificação **UTF-8**, definida pela linha:

<meta charset="UTF-8">

Essa codificação garante que caracteres especiais da língua portuguesa, como **á, é, ç, ã**, além de emojis e outros símbolos, sejam exibidos corretamente no navegador.

## Reflexão

Escolhi o tema **"Sua Música Favorita"** porque a música está presente no dia a dia da maioria das pessoas, tornando o formulário mais leve, interessante e fácil de responder.

A escolha do método **GET** foi feita porque o formulário tem apenas a finalidade de coletar preferências musicais, sem solicitar informações pessoais ou sensíveis. Dessa forma, esse método atende perfeitamente ao objetivo da atividade.

Durante o desenvolvimento, precisei decidir entre utilizar os controles **select** e **radio**. Para a pergunta sobre a frequência com que a pessoa escuta música, escolhi o **select**, pois havia poucas opções e ele deixa o formulário mais organizado. Já para a escolha do gênero musical, utilizei o **radio**, porque o usuário deve selecionar apenas uma alternativa e todas as opções ficam visíveis, facilitando a escolha.

Se tivesse mais tempo para aprimorar o projeto, adicionaria validações em **JavaScript** para melhorar a experiência do usuário, deixaria o formulário ainda mais responsivo para dispositivos móveis, incluiria mais opções de gêneros musicais e plataformas de streaming e faria com que o valor escolhido no controle deslizante (**range**) fosse exibido em tempo real.
