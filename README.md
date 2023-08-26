<b>HexColor Generator</b>
<br>
<a href="https://hex-color-generator.vercel.app/">Link do Projeto</a>

<b>Introdução</b><br>
O programa HexColor Generator é uma aplicação que gera cores aleatórias em formato hexadecimal. Ele permite que os usuários obtenham combinações de cores únicas para uso em projetos de design, desenvolvimento web e muito mais.

<b>Instalação</b><br>
Para utilizar o programa HexColor Generator, siga as instruções abaixo:

Faça o download dos arquivos do programa ou copie o código-fonte fornecido.

Certifique-se de ter um ambiente de desenvolvimento JavaScript adequado configurado, como um navegador da web.

Crie um arquivo HTML em branco ou abra um arquivo HTML existente em seu editor de código.

Copie o código do programa HexColor Generator para dentro do arquivo HTML.

Salve o arquivo HTML com a extensão ".html".

Abra o arquivo HTML em seu navegador da web para executar o programa.

<b>Uso</b><br>
O programa HexColor Generator possui uma interface simples de botão e visualização da cor gerada. Para utilizar o programa, siga os passos abaixo:

Clique no botão fornecido na interface.

O programa irá gerar aleatoriamente uma sequência hexadecimal de 6 dígitos.

A cor correspondente será aplicada como plano de fundo do corpo (elemento <body>) da página.

A sequência hexadecimal gerada será exibida na área de visualização.

Cada vez que o botão for clicado, uma nova cor será gerada e aplicada.

<b>Estrutura do código</b><br>
O programa HexColor Generator consiste em um código JavaScript que utiliza manipulação do DOM (Document Object Model) para alterar a cor de fundo da página. O código é dividido em duas partes principais: a função getRandomNumber() e o evento de clique do botão.

<b>Função getRandomNumber()</b><br>
A função getRandomNumber() retorna um número aleatório com base no comprimento do array hex. Ela é utilizada para obter um índice aleatório no array e, consequentemente, gerar dígitos aleatórios para a sequência hexadecimal.

Evento de clique do botão
O evento de clique é associado ao botão através do método addEventListener(). Quando o botão é clicado, o programa executa as seguintes etapas:

Inicializa uma variável hexColor com o valor inicial "#".

Utiliza um loop para adicionar 6 dígitos aleatórios, obtidos através da função getRandomNumber(), à variável hexColor.

Altera a cor de fundo do corpo da página (document.body.style.backgroundColor) para a cor hexadecimal gerada.

Atualiza o texto do elemento com a classe .color com a sequência hexadecimal gerada.

<b>Configuração</b><br>
Não são necessárias configurações adicionais para utilizar o programa HexColor Generator.

<b>Contribuição</b><br>
Atualmente, o programa HexColor Generator não possui um processo formal de contribuição estabelecido. No entanto, você pode entrar em contato com o desenvolvedor para fornecer sugestões, relatar problemas ou colaborar de outras formas.

<b>Documentado pelo ChatGPT</b><br>


![Screenshot_2](https://github.com/SmallCityProgrammer/Hex-generator/assets/130911203/143fd87b-8e9a-466f-9baa-35cb6691cbe8)
