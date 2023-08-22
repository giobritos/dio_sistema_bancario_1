# Sistema Bancário - Versão 1

Este é um programa simples de simulação de sistema bancário com base no template do professor Professor Guilherme Arthur de Carvalho da DIO. Ele permite realizar operações de depósito, saque, visualização de extrato e sair do sistema.

## Funcionalidades

### Menu

O programa apresenta um menu com as seguintes opções:

- [d] Depositar
- [s] Sacar
- [e] Extrato
- [q] Sair

O usuário pode selecionar uma das opções digitando a letra correspondente e pressionando Enter.

### Depósito

Ao escolher a opção "d" do menu, o usuário pode realizar um depósito. O programa solicitará o valor a ser depositado. O valor deve ser maior que zero. O saldo da conta será atualizado e um registro do depósito será adicionado ao extrato.

### Saque

Ao escolher a opção "s" do menu, o usuário pode realizar um saque. O programa verifica se o número máximo de saques diários não foi excedido. O usuário deve informar o valor desejado para saque. O valor deve ser maior que zero, menor ou igual ao limite de saque e menor ou igual ao saldo disponível. Se as condições forem atendidas, o saldo será atualizado, o número de saques será incrementado e um registro do saque será adicionado ao extrato. Caso contrário, uma mensagem de erro será exibida.

### Extrato

Ao selecionar a opção "e" do menu, o usuário pode visualizar o extrato da conta. Será exibida uma listagem das operações de depósito e saque realizadas durante a sessão, juntamente com o saldo atual.

### Sair

Ao escolher a opção "q" do menu, o usuário pode sair do programa.

## Variáveis

- `menu`: String que contém o menu de opções.
- `saldo`: Variável que armazena o saldo da conta.
- `limite`: Limite máximo para saques.
- `extrato`: String que armazena o registro das operações para exibição posterior.
- `numero_saques`: Número de saques realizados na sessão atual.
- `LIMITE_SAQUES`: Número máximo de saques permitidos por dia.

## Uso

1. Execute o programa `sistema_bancario_1.py`.
2. Escolha uma opção do menu digitando a letra correspondente.
3. Siga as instruções na tela para realizar as operações desejadas.

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue neste repositório. Caso queira contribuir com código, por favor, abra um pull request para revisão.

## Agradecimentos

Agradeço ao Professor Guilherme Arthur de Carvalho da DIO pelas aulas e ensinamentos. 

**Desenvolvido com :heart: e Python.**
