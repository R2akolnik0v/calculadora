O código implementa uma calculadora simples que permite ao usuário realizar operações matemáticas básicas. Aqui está uma explicação detalhada:

Entrada de Dados: O programa solicita que o usuário insira dois números.


   Exibição do Menu: Um menu de opções é apresentado ao usuário, com as operações disponíveis:

Adição (1)

Subtração (2)

Multiplicação (3)

Divisão (4)

Potência (5)


Execução da Operação: Com base na escolha do usuário, o programa executa a operação matemática correspondente.

 Tratamento de Erros:

Se o usuário inserir um valor inválido, o programa exibe uma mensagem de erro e solicita uma nova entrada.

Se a opção escolhida for inválida, o programa alerta o usuário.

Se a divisão for por zero, uma mensagem de erro específica é exibida.


Loop Contínuo: O programa continua rodando até que o usuário decida sair, digitando 0.


Para a execução do arquivo sh:

Para executar o script, você precisa ter um sistema operacional baseado em Unix (Linux ou macOS) ou um terminal compatível (como o WSL no Windows).

Passos para execução

1. Acesse o diretório do script:
Abra o terminal e navegue até o local onde está o arquivo:

cd /caminho/para/o/script


2. Dê permissão de execução ao arquivo:
Se o arquivo ainda não tem permissão para ser executado, conceda-a com o seguinte comando:

chmod +x calculadora.sh


3. Execute o script:
Agora, basta rodar o comando:

./calculadora.sh


4. (Opcional) Executar com um interpretador específico:
Se necessário, você pode rodar o script especificando o interpretador bash:

bash calculadora.sh
