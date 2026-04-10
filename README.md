# Sistema de Gerenciamento de Estoque - Armazém

Este projeto consiste em um sistema web completo para a gestão de itens em estoque, desenvolvido individualmente para o Trabalho 5. A aplicação implementa um CRUD funcional integrado a um banco de dados relacional, seguindo as diretrizes técnicas de arquitetura modular e separação de responsabilidades.

**Aluno:** Antonio Bernardo Zilio Tomasi

---

## Tecnologias e Ferramentas

* **Frontend:** React
* **Backend:** Node.js e Express
* **Banco de Dados:** MySQL
* **Comunicação:** Axios

---

## Estrutura do Projeto

O sistema foi organizado para garantir a compatibilidade e a facilidade de instalação na máquina de avaliação:

* /backend: Servidor RESTful, conexões com o banco de dados e validações de dados.
* /frontend: Interface do usuário contendo listagem com paginação, cadastro, edição e visualização detalhada.
* armazem.sql: Script para criação da estrutura do banco de dados e inserção de dados iniciais.

---

## Instruções para Execução

### 1. Configuração do Banco de Dados
* Importe o arquivo armazem.sql no seu servidor MySQL.
* O script criará a tabela produtos contendo os campos obrigatórios: id, nome, descricao, categoria, quantidade_estoque e preco_unitario.

### 2. Configuração do Servidor (Backend)
1. Acesse o diretório do backend: cd backend
2. Instale as dependências necessárias: npm install
3. Configure o arquivo .env com as credenciais locais do seu banco de dados.
4. Inicie o servidor: npm start

### 3. Configuração da Interface (Frontend)
1. Acesse o diretório do frontend: cd frontend
2. Instale as dependências necessárias: npm install
3. Inicie a aplicação React: npm run dev
4. O sistema estará disponível em: http://localhost:5173/

---

## Critérios de Avaliação Atendidos

* **CRUD Completo:** Implementação das quatro operações básicas de dados (Create, Read, Update, Delete).
* **Paginação:** Sistema de listagem otimizado com controle de páginas.
* **Identificação:** Nome do aluno visível em todas as telas do sistema.
* **Tratamento de Erros:** Validações implementadas tanto no frontend quanto no backend.
* **Originalidade:** Código desenvolvido de forma individual, respeitando as normas contra plágio.

---

**Observação:** Certifique-se de que o servidor backend esteja ativo antes de iniciar a navegação no frontend para permitir o consumo correto da API.
