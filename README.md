# Projeto Menu Bancário

Este é um programa simples de menu bancário que permite aos usuários realizar operações básicas em uma conta bancária, como depósito, saque, visualização de extrato e sair.

## Funcionalidades

O programa oferece as seguintes funcionalidades:

- **Depositar (d):** Permite ao usuário fazer um depósito na conta. O valor do depósito é adicionado ao saldo da conta e registrado no extrato.

- **Sacar (s):** Permite ao usuário fazer um saque da conta. O valor do saque é subtraído do saldo da conta e registrado no extrato. Existem algumas restrições para o saque: o usuário deve ter saldo suficiente, o valor do saque não pode exceder um limite pré-definido e o número máximo de saques permitidos também é limitado.

- **Extrato (e):** Permite ao usuário visualizar o extrato da conta. O extrato exibe todas as transações realizadas, incluindo depósitos e saques, bem como o saldo atual da conta.

- **Sair (q):** Encerra o programa.

## Utilização

Ao executar o programa, o usuário será apresentado a um menu com as opções disponíveis. Ele pode selecionar uma opção digitando a letra correspondente. Em seguida, dependendo da opção selecionada, serão solicitadas informações adicionais, como o valor do depósito ou saque. O programa validará as informações fornecidas pelo usuário e executará a operação solicitada ou exibirá uma mensagem de erro, caso ocorra algum problema.

O extrato será atualizado a cada transação realizada, exibindo todas as operações anteriores.

## Variáveis

- **saldo:** Variável que armazena o saldo atual da conta.
- **limite:** Variável que define o limite máximo de saque.
- **extrato:** Variável que armazena o histórico de transações (depósitos e saques) da conta.
- **numero_saques:** Variável que conta o número de saques realizados.
- **LIMITE_SAQUES:** Constante que define o número máximo de saques permitidos.

## Observações

- O programa assume que o usuário insere os valores corretos e segue as instruções apresentadas. Caso contrário, serão exibidas mensagens de erro apropriadas.

- O programa não utiliza um sistema de autenticação ou armazenamento persistente de dados. É apenas uma demonstração simples das funcionalidades básicas de um menu bancário.
