# Desafio de Gerenciamento de Sessões de Votação

Este é um projeto que visa criar uma solução back-end para gerenciar sessões de votação em um contexto cooperativista. O projeto oferece uma API REST que permite:

- Cadastrar uma nova pauta;
- Abrir uma sessão de votação em uma pauta (com um tempo limite definido ou um padrão de 1 minuto);
- Receber votos dos associados em pautas (votos limitados a 'Sim' ou 'Não');
- Contabilizar os votos e fornecer o resultado da votação na pauta.

## Requisitos

Para executar este projeto, você precisará de:

- Java (versão 8 ou superior)
- Maven
- Postgresql
- Postman ou outra ferramenta para testar a API

## Como executar

1. Clone o repositório para o seu ambiente:


      git clone https://github.com/seu-usuario/desafio-cooperativismo.git


2. Navegue até o diretório do projeto:
   cd dbc-desafio


3. Compile e inicie o projeto:
   mvn spring-boot:run


4. O aplicativo será executado em `http://localhost:8080`. Você pode acessar a documentação da API e testar as chamadas usando um cliente como o Postman.

## Documentação

A documentação da API está disponível no Swagger pelo link:

http://localhost:8080/swagger-ui/index.html