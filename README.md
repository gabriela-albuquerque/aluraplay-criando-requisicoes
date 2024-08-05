### Alura Play - Criando Requisições

Página inicial e formulário de cadastro de vídeos da AluraPlay, uma plataforma de compartilhamento de vídeos.

O projeto Alura Play trata de uma plataforma que exibe vídeos educacionais onde é possível fazer a inserção de novos vídeos sem precisar manipular o código, apenas inserindo a url, o título do vídeo e a imagem de capa através de um formulário.

Para seu desenvolvimento foi feito o consumo de uma API externa através de requisição GET e, na inserção de novos vídeos, requisição do tipo POST. Também é possível fazer uma busca através da barra de pesquisa para a qual foi criada uma requisição GET e feita uma checagem dinâmica na rota que filtra os vídeos que possuem o termo pesquisado em suas propriedades.

O projeto também inclui captura e tratamento de erros no sentido de fornecer um feedback ao usuário da aplicação e sinalizar algum tipo de erro que venha a acontecer.

    `json-server --watch db.json`

Usando o argumento —watch no comando json-server através do terminal do programa de manipulação de código, indicamos ao servidor que deve ficar observando o arquivo json informado no final da linha de comando.

Dessa forma, o JSON Server será iniciado e começará a servir uma API REST fake com os dados do arquivo informado, permitindo o consumo destes dados para o projeto.

<hr>





## Screenshots
![Screenshot da tela inicial do AluraPlay](https://imgur.com/aymxEsh.png)
![Screenshot da tela do formulário do AluraPlay](https://imgur.com/ShNADf2.png)
