# Sistema Bancário Simples em POO com Python

Este repositório contém a implementação de um sistema bancário simples em Python. O sistema permite que os usuários realizem diversas operações bancárias, como depositar fundos, sacar fundos, visualizar extratos de conta, criar novas contas, listar contas existentes e cadastrar novos usuários.

## Funcionalidades
- **Depositar**: Os usuários podem depositar fundos em suas contas.
- **Sacar**: Os usuários podem sacar fundos de suas contas, levando em consideração o saldo da conta e os limites de saque.
- **Extrato de Conta**: Os usuários podem visualizar o extrato de suas contas, incluindo o histórico de transações.
- **Criar Conta**: Novas contas podem ser criadas e associadas a usuários existentes.
- **Listar Contas**: As contas existentes podem ser listadas, exibindo detalhes da conta e as informações do usuário associado.
- **Cadastrar Usuário**: Novos usuários podem ser cadastrados com suas informações pessoais.
- **Interface de Menu**: O sistema fornece uma interface simples baseada em menu para os usuários interagirem.

## Como usar?
1. **Clonar Repositório**: Baixe ou clone este repositório em sua máquina local.

2. **Execute o Programa**: Execute o script Python `Criando um Sistema Bancário em POO com Python.py`


3. **Seguir as Instruções do Menu**: Siga as instruções do menu exibidas no console para realizar várias operações bancárias.

## Exemplo de Uso

```

================ MENU ================
[1]Depositar
[2]Sacar
[3]Extrato
[4]Novo usuário
[5]Nova conta
[6]Listar contas
[7]Sair
=> 1
Informe o CPF do cliente: 34976411036    

@@@ Cliente não encontrado! @@@       


================ MENU ================
[1]Depositar
[2]Sacar
[3]Extrato
[4]Novo usuário
[5]Nova conta
[6]Listar contas
[7]Sair
=> 4
Informe o CPF (somente número): 34976411036    
Informe o nome completo: Leonardo Felício Massaro
Informe a data de nascimento (dd-mm-aaaa): 29-02-2000
Informe o endereço (logradouro, nro - bairro - cidade/sigla estado): 

=== Cliente criado com sucesso! ===


================ MENU ================
[1]Depositar
[2]Sacar
[3]Extrato
[4]Novo usuário
[5]Nova conta
[6]Listar contas
[7]Sair
=> 5
Informe o CPF do cliente: 34976411036

=== Conta criada com sucesso! ===


================ MENU ================
[1]Depositar
[2]Sacar
[3]Extrato
[4]Novo usuário
[5]Nova conta
[6]Listar contas
[7]Sair
=> 1
Informe o CPF do cliente: 34976411036
Informe o valor do depósito: 500

=== Depósito realizado com sucesso! ===


================ MENU ================
[1]Depositar
[2]Sacar
[3]Extrato
[4]Novo usuário
[5]Nova conta
[6]Listar contas
[7]Sair
=> 2
Informe o CPF do cliente: 34976411036  
Informe o valor do saque: 453

=== Saque realizado com sucesso! ===


================ MENU ================
[1]Depositar
[2]Sacar
[3]Extrato
[4]Novo usuário
[5]Nova conta
[6]Listar contas
[7]Sair
=> 3
Informe o CPF do cliente: 34976411036  

================ EXTRATO ================

Deposito:
        R$ 500.00
Saque:
        R$ 453.00

Saldo:
        R$ 47.00
==========================================


================ MENU ================
[1]Depositar
[2]Sacar
[3]Extrato
[4]Novo usuário
[5]Nova conta
[6]Listar contas
[7]Sair
=>