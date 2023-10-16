# Projeto Bank Rest API ![image](https://github.com/vthifane/desafio-backend-modulo-02-sistema-bancario-b2b-ifood-t09/assets/131800429/409f5a8d-271a-4062-a00d-6a8ecb608028)
## Projeto backend: Constuindo uma API Rest funcional de um sistema bancário, executando as funcionalidades a seguir: 

    ◽ Criar uma conta bancária
    ◽ Listar contas bancárias
    ◽ Atualizar dados do usuário da conta bancária
    ◽ Excluir conta bancária
    ◽ Depositar em uma conta bancária                                              
    ◽ Sacar de uma conta Bancária
    ◽ Fazer transferências entre contas bancárias
    ◽ Consultar saldo de conta Bancária
    ◽ Emitir extrato de conta bancária

## Para construí-lo serão nescessários: 
    
    ◽ JavaScript
    ◽ Node.js            
    ◽ Express.js
    ◽ Date fns
    
![image](https://github.com/vthifane/desafio-backend-modulo-02-sistema-bancario-b2b-ifood-t09/assets/131800429/51b9ccbc-13b3-4daf-969c-65e0e06a222d) ![image](https://github.com/vthifane/desafio-backend-modulo-02-sistema-bancario-b2b-ifood-t09/assets/131800429/e0a61029-0757-48b1-8200-137de6c70168) ![image](https://github.com/vthifane/desafio-backend-modulo-02-sistema-bancario-b2b-ifood-t09/assets/131800429/bf8a746f-2102-4e24-8b04-c7c0508d9ff8) ![image](https://github.com/vthifane/desafio-backend-modulo-02-sistema-bancario-b2b-ifood-t09/assets/131800429/e1370499-455a-4814-a510-e15c296d8593)

## Como Configurar:

1. Realize o fork deste repositório para seu github
2. Clone este reposiório para seu repositório remoto
3. Instale as depenências ultilizando o comando $npm install
4. Ultilize a url: http://localhost:3000. Seu programa estará sendo executado nesta porta.

## Exemplos de Endpoints:

### Criar uma conta bancária:

#### URL:

        POST http://localhost:3000/contas
        
#### Requisição:

    {
        "nome": "Exemplo",
        "cpf": "12345678910",
        "email": "exemplo@email.com",
        "senha": "12345"
    }
    
### Transferir: 

#### URL:

    POST http://localhost:3000/transacoes/transferir
    
#### Requisição:

    {
        "numero_conta_origem": "01",
        "numero_conta_destino": "02",
        "senha": "12345",
        "valor": 10000
    }

### EXtrato: 

#### URL:

    GET https://localhost:3000/contas/extrato?numero_conta=123&senha=123

#### Requisição: 

    {
        "numero_conta":"01",
        "senha": "12345"
    }

## Let's Code!!
