# Projeto-logico-para-um-banco-de-dados-E-commerce

Esse projeto foi desenvolvido para fazer parte do desafio proposto pela professora Juliana Mascarenhas, com o objetivo de criar e implementar um cenário de um projeto lógico de banco de dados E-commerce utilizando o MySQL Workbench.
---
# Objetivo proposto

Modelar um banco de dados relacional representando as suas entidades e relacionamentos em um sistema E-commerce contendo clientes, produtos, pedidos, fornecedores, vendedores terceiros, pagamentos e entregas.
---
# Descrição das tabelas que foram criadas.

-cliente: armazena dados de clientes tanto pessoas físicas quanto jurídicas.
-produto: armazena o catálogo de produtos que estão disponíveis.
-estoque: armazena os produtos disponíveis no estoque.
-produto_estoque: mostra a relação existente entre produtos e estoques.
-pedido: armazena os pedidos realizados pelos clientes.
-produto_pedido: armazena os produtos que serão incluidos em cada pedido.
-fornecedor: armazena as empresas que fornecem os produtos.
-produto_fornecedor: armazena a relação entre os produtos e os seus fornecedores.
-terceiro_vendedor: mostra a lista de vendedores externos que disponibilizam os produtos.
-produto_terceiro_vendedor: mostra a relação entre produtos vendedores externos.
-pagamento: mostra a relação de pagamentos realizados para os pedidos.
-forma_pagamento: mostra os tipos de pagamentos que estão disponíveis. 
-entrega: contêm informações de rastreio para que os pedidos sejam acompanhados e status de entrega.
---
# Relacionamentos criados.

-Cada pedido está ligado a um cliente.
-Foram criadas tabelas associativas como: produto_pedido, produto_estoque, produto_fornecedor e produto_terceiro_vendedor representando relacionamentos N:N entre as entidades.
-Cada pagamento está ligado a um pedido e a uma forma_pagamento.
-Cada entrega está devidamente ligada a um pedido.
---
# Os comandos foram executados no MySQL Workbench da seguinte forma:

1. Abra o MySQL Workbench.
2. Clique na conexão local instance MySQL80.
3. Logo em seguida crie um novo script SQL.
4. Depois de criado o conteúdo do arquivo modelo_ecommerce.sql.
5. Clique no ícone de raio ( ⚡ ) para executar.
6. Finalizando a criação do banco de dados ecommerce com todas as suas tabelas e relacionamentos.
   
# 📸 Segue as imagens do projeto.
---
[ecommerce.txt](https://github.com/user-attachments/files/22525391/ecommerce.txt)
<img width="809" height="1280" alt="E_commerce png2" src="https://github.com/user-attachments/assets/60966084-60a6-4c7c-bada-080c082e97b1" />
<img width="1366" height="728" alt="Janela - MySQL Workbench (2)" src="https://github.com/user-attachments/assets/1de6067f-378c-456c-87c6-3c257beb3193" />
<img width="1366" height="728" alt="Janela - MySQL Workbench" src="https://github.com/user-attachments/assets/53c22ca3-a205-436a-85e5-1d5cacab3d23" />
<img width="1366" height="728" alt="Janela - MySQL Workbench (3)" src="https://github.com/user-attachments/assets/c17df07b-4b70-4aff-9e28-74847efa1524" />

