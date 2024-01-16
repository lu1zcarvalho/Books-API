# API com MongoDB e Express

Este é um projeto de API construído com MongoDB e Express. A API fornece endpoints para realizar operações CRUD (Create, Read, Update, Delete) em uma coleção de dados.

## Configuração do Ambiente

Certifique-se de ter o Node.js e o MongoDB instalados em sua máquina.

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-projeto-api.git
   cd seu-projeto-api
   npm start
   
A API estará disponível em http://localhost:3000.

Estrutura do Projeto

src/: Contém o código-fonte da aplicação.
models/: Define os modelos de dados MongoDB.
routes/: Contém as rotas da API.
controllers/: Gerencia a lógica de negócios da aplicação.
config/: Configurações do projeto.

Endpoints da API

GET ("/livros", LivroController.listarLivros); Lista todos livros.
GET ("/livros/busca", Lista livros pelo ID da Editora.
GET ("/livros/:id", Lista livros pelo ID do Livro.
POST ("/livros", Cadastra Livro.
PUT ("/livros/:id", Atualiza Livro.
DELETE ("/livros/:id", Exclui Livro.

