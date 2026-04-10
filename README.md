# Sistema de Gerenciamento de Estoque - Armazém

[cite_start]Este projeto consiste em um sistema web completo para a gestão de itens em estoque, desenvolvido individualmente para o Trabalho 5[cite: 1, 2]. [cite_start]A aplicação implementa um CRUD funcional integrado a um banco de dados relacional, seguindo as diretrizes técnicas de arquitetura modular e separação de responsabilidades[cite: 3, 46].

[cite_start]**Aluno:** Anton [cite: 4]

---

## Tecnologias e Ferramentas

* [cite_start]**Frontend:** React (Vite) [cite: 8, 9]
* [cite_start]**Backend:** Node.js e Express [cite: 17]
* [cite_start]**Banco de Dados:** MySQL [cite: 26]
* [cite_start]**Comunicação:** Axios [cite: 15]

---

## Estrutura do Projeto

O sistema foi organizado para garantir a compatibilidade e a facilidade de instalação na máquina de avaliação:

* [cite_start]`/backend`: Servidor RESTful, conexões com o banco de dados e validações de dados[cite: 18, 25].
* [cite_start]`/frontend`: Interface do usuário contendo listagem com paginação, cadastro, edição e visualização detalhada[cite: 11, 12, 13, 14].
* [cite_start]`armazem.sql`: Script para criação da estrutura do banco de dados e inserção de dados iniciais[cite: 31, 44].

---

## Instruções para Execução

### 1. Configuração do Banco de Dados
* [cite_start]Importe o arquivo `armazem.sql` no seu servidor MySQL[cite: 35, 44].
* [cite_start]O script criará a tabela `produtos` contendo os campos obrigatórios: id, nome, descricao, categoria, quantidade_estoque e preco_unitario[cite: 28, 29].

### 2. Configuração do Servidor (Backend)
1. Acesse o diretório do backend: `cd backend`
2. [cite_start]Instale as dependências necessárias: `npm install` [cite: 35]
3. Configure o arquivo `.env` com as credenciais locais do seu banco de dados.
4. Inicie o servidor: `npm start`

### 3. Configuração da Interface (Frontend)
1. Acesse o diretório do frontend: `cd frontend`
2. [cite_start]Instale as dependências necessárias: `npm install` [cite: 35]
3. Inicie a aplicação React: `npm run dev`
4. O sistema estará disponível em: `http://localhost:5173/`

---

## Critérios de Avaliação Atendidos

* [cite_start]**CRUD Completo:** Implementação das quatro operações básicas de dados (Create, Read, Update, Delete)[cite: 3, 23].
* [cite_start]**Paginação:** Sistema de listagem otimizado com controle de páginas[cite: 12].
* [cite_start]**Identificação:** Nome do aluno visível em todas as telas do sistema[cite: 4].
* [cite_start]**Tratamento de Erros:** Validações implementadas tanto no frontend quanto no backend[cite: 16, 25].
* [cite_start]**Originalidade:** Código desenvolvido de forma individual, respeitando as normas contra plágio[cite: 2, 5].

---

**Observação:** Certifique-se de que o servidor backend esteja ativo antes de iniciar a navegação no frontend para permitir o consumo correto da API.
