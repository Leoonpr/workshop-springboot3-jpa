# Projeto Web Services com Spring Boot e JPA / Hibernate

Bem-vindo ao projeto "Web Services com Spring Boot e JPA / Hibernate". Este é um exemplo prático que ilustra a criação de um aplicativo web utilizando Spring Boot, JPA/Hibernate para persistência, e H2 como banco de dados de teste. O projeto implementa operações CRUD (Create, Retrieve, Update, Delete) em um modelo de domínio específico, seguindo uma estrutura de camadas lógicas.

## Tópicos Abordados

1. **Criar Projeto Spring Boot Java:**
   - O projeto foi inicializado usando o Spring Initializr ou outra ferramenta equivalente.
   - Adicionadas as dependências necessárias, incluindo Spring Web, Spring Data JPA e H2 Database.

2. **Implementar Modelo de Domínio:**
   - Definido o modelo de domínio que representa as entidades do sistema.

3. **Estruturar Camadas Lógicas:**
   - **Resource Layer:** Controladores REST para lidar com solicitações HTTP.
   - **Service Layer:** Lógica de negócios e manipulação de dados.
   - **Repository Layer:** Integração com o banco de dados usando JPA/Hibernate.

4. **Configurar Banco de Dados de Teste (H2):**
   - Configurado o banco de dados H2 para testes.
   - As configurações podem ser ajustadas para diferentes ambientes (produção, desenvolvimento, teste).

5. **Povoar o Banco de Dados:**
   - Dados de exemplo são inseridos no banco de dados para fins de teste.

6. **CRUD - Create, Retrieve, Update, Delete:**
   - Operações CRUD implementadas para interagir com o modelo de domínio.

7. **Tratamento de Exceções:**
   - Lidando com exceções apropriadas em diferentes camadas do aplicativo.

## Endpoints Disponíveis

1. **GET /api/entidade: Recupera todas as entidades.
2. **GET /api/entidade/{id}: Recupera uma entidade específica por ID.**
3. **POST /api/entidade: Cria uma nova entidade.**
4. **PUT /api/entidade/{id}: Atualiza uma entidade existente.**
5. **DELETE /api/entidade/{id}: Exclui uma entidade por ID.**

## Pré-requisitos

Certifique-se de ter o Java e o Maven instalados em sua máquina antes de executar o projeto.

## Como Executar o Projeto

1. **Clone este repositório:**
2. **Navegue até o diretório do projeto:**
3.  **Execute o aplicativo usando Maven:**
