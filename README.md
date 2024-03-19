# AOP2-DEV-WEB
Desenvolvimento Web - Back End Atividade Online Pontuada 02

GRUPO: Andre de Oliveira Gasparoni Pinto e Daniel Corona da Silva

EMAIL 1
Assunto: Explicação do processamento assíncrono de dados utilizando o objeto XMLHttpRequest

Olá pessoal,

Precisaremos implementar o processamento assíncrono de dados utilizando o objeto XMLHttpRequest. Esta abordagem permitirá trocar requisições na página principal do nosso e-commerce, facilitando a interação com diversas APIs REST assíncrona.

Aqui está um resumo do processo passo a passo de como o processamento assíncrono de dados por meio do objeto XMLHttpRequest ocorrerá:

Ativação da requisição pelo usuário (ação do Usuário): O ciclo começa quando um usuário interage com a página do nosso e-commerce, como clicar em um botão para carregar mais produtos ou fazer uma pesquisa. Esse evento aciona a função JavaScript que cria e envia a requisição XMLHttpRequest.

Criação do objeto XMLHttpRequest: Ao detectar a ação do usuário, nosso código JavaScript cria uma instância do objeto XMLHttpRequest utilizando o construtor new XMLHttpRequest().

Configuração da requisição: O próximo passo é configurar preenchendo a requisição, especificando o método HTTP (GET, POST, PUT, DELETE, etc.), o URL do servidor e outras opções relevantes, como cabeçalhos adicionais.

Envio da requisição: Uma vez configurada, a requisição é enviada para o servidor utilizando o método do objeto XMLHttpRequest chamado "send()". Neste ponto, a requisição é disparada e o código JavaScript continua a ser executado sem esperar pela resposta do servidor.

Processamento Assíncrono: Enquanto a requisição está em andamento, o navegador continua a executar outras tarefas. Não é necessário esperar pela resposta do servidor antes de continuar o processamento do código JavaScript.

Recepção da Resposta: Quando o servidor processa a requisição e envia uma resposta de volta, o navegador recebe os dados. 


Tratamento da Resposta: Uma vez que a resposta é recebida, o código JavaScript trata os dados de acordo com a lógica da aplicação. Isso pode envolver atualizar a interface do usuário, armazenar os dados em variáveis, ou executar outras ações dependendo do contexto da aplicação.

Conclusão da Requisição: Após o tratamento da resposta, a requisição é concluída. Podemos então limpar recursos, encerrar conexões ou realizar outras operações necessárias para finalizar o ciclo.

Abraços.

EMAIL 2


Assunto: Instruções para clonar o projeto via GitHub

Olá pessoal,

Vamos tornar nossa colaboração no projeto ainda mais fácil usando o GitHub, a fim de tornar nosso código do e-commerce colaborativo, permitindo mudanças no código do projeto de forma organizada e compartilhada enquanto mantêm um registro detalhado do seu progresso por meio do seu controle de versões. Aqui está um guia rápido para clonar o projeto em seus computadores:

1. Acesso ao repositório no GitHub na web: Acesse o repositório remoto, vocês podem encontrá-lo aqui nesse link https://github.com/ANDREOGP33/AOP2-DEV-WEB.

2. Clone do repositório: No terminal ou prompt de comando, naveguem até o diretório local onde desejam que o projeto seja clonado e executem o seguinte comando para criar o repositório local: git clone https://github.com/ANDREOGP33/AOP2-DEV-WEB.git

3. Configuração do ambiente de desenvolvimento: Depois de clonar o repositório, verifiquem o arquivo README.md para as instruções sobre como configurar o ambiente de desenvolvimento.

 4. Colaboração e desenvolvimento: Com o projeto clonado, vocês podem começar a trabalhar em suas tarefas. Lembrem-se de criar uma branch separada para cada nova funcionalidade ou correção de bug.

  5. Envio de alterações: Após concluir suas alterações, façam o commit e enviem as mudanças para o repositório remoto usando os comandos git add, git commit e git push.


    Abraços.



