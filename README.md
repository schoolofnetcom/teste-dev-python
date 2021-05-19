
# Faça parte do nosso time de experts 

## Descrição
O projeto consiste na criação de uma pequeno serviço para transferência de valores através de um sistema de validação de Hash.

## Tecnologias
- Python com Django Framework
- Banco de dados PostgreSQL
- Docker

## Tarefas

### 1. Criação da pessoa
O dominio pessoa será responsável pelo registro dos clientes que irão participar do processo de transferência. Cada pessoa deverá obrigatóriamente ter seus dados pessoais cadastrado no sistema: Nome, sobrenome, nome completo, email, telefone, nascimento, CPF, saldo (valor gerado randomico e fictico). 

### 2. Criação de chaves
Para cada usuário que irá fazer uma transação, obrigatóriamente deverá existir uma chave única responsável que liga o usuário. O processo de transação poderá ser feita por email e ou chave única do usuário.

### 3. Criação do processo de transferência
Para cada transação, é necessário salvar em um banco de dados um histórico da transação, seu status (FINALIZADO, EM PROCESSO, PENDENTE) juntamente com uma chave única de validação da transação. Certifique-se que o cliente possua saldo suficiente para realizar a transação e não se esqueça de descontar o saldo após processo de transação efetuada com sucesso.

*Sugestão: Pesquise alguma biblioteca de geração de hash única no padrão SHA-256 .*

### 3. Testes
O projeto deve conter testes em todas as etapas do desenvolvimento, não sendo necessário utilizar TDD para implementação. É importante a presença de testes de unidade e integração no projeto. 

### 4. Documentação
Ao final do projeto, documente através de um README como realizar o build, testes e iniciar o servidor localmente.

*Plus: Documentação através do Swagger ou similar*
