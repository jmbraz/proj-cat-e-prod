🛍️ Sistema de Cadastro de Produtos - Spring Boot
📋 Descrição

Projeto desenvolvido em Java com Spring Boot para gerenciar o cadastro de produtos.
Permite criar, listar, atualizar e excluir produtos, além de cadastrar usuários
O sistema utiliza o MySQL (produção) e o H2 Database (testes locais).

🧰 Funcionalidades

✅ Cadastrar produtos
🔍 Listar todos os produtos
✏️ Atualizar produtos
❌ Deletar produtos
🧱 Integração com MySQL ou H2

🧪 Testando a API no Isonomia
🔍 GET — Listar todos os produtos ou categoria

Endpoint:

GET http://localhost:8080/categoria


Descrição:
Retorna a lista completa de produtos cadastrados no banco de dados.
Use este método para verificar se os produtos foram salvos corretamente.

<img width="1070" height="547" alt="Captura de tela 2025-11-09 115034" src="https://github.com/user-attachments/assets/1c377d74-56ec-44d8-97aa-723222b4dd1e" />

-------------------------------------------------------------------------
➕ POST — Cadastrar novo produto ou categoria

Endpoint:

POST http://localhost:8080/categoria

Descrição:
Cria um novo produto no banco de dados.
É obrigatório informar o nome, preço e uma categoria existente.

<img width="1062" height="515" alt="Captura de tela 2025-11-09 114722" src="https://github.com/user-attachments/assets/033ceae4-a9f0-4967-8513-f68d991f0150" />

-------------------------------------------------------------------------
❌ DELETE — Excluir produto ou categoria

Endpoint:

DELETE http://localhost:8080/produtos/{id}

Descrição:
Remove o produto do banco de dados de forma permanente.

<img width="1067" height="548" alt="Captura de tela 2025-11-09 120009" src="https://github.com/user-attachments/assets/ce70cce4-6530-454e-8f20-93ff41830814" />

<img width="1053" height="509" alt="Captura de tela 2025-11-09 120034" src="https://github.com/user-attachments/assets/7741bfb9-3f6a-415f-9afd-f39cdfd98930" />

-------------------------------------------------------------------------
✏️ PUT — Atualizar produto ou categoria existente

Endpoint:

PUT http://localhost:8080/produtos/{id}

Descrição:
Atualiza as informações de um produto existente.
Você pode alterar nome, preço e categoria.
Se a categoria não for enviada, a atual será mantida.

<img width="1066" height="508" alt="Captura de tela 2025-11-09 122122" src="https://github.com/user-attachments/assets/4479ea51-ff8f-4c6a-a514-f31442f01b72" />
