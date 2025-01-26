Projeto: E-Commerce 📦

Descrição
Este projeto visa a modelagem de um banco de dados para um sistema de E-Commerce, com foco na venda de produtos. A plataforma permite a venda por terceiros, cadastra clientes e gerencia pedidos, fornecedores e estoque.

Modelagem de Dados
Entidades Principais
Produto 📦

Produtos vendidos por diferentes vendedores através da plataforma.

Cada produto possui um fornecedor.

Um ou mais produtos podem compor um pedido.

Cliente 🧑‍💼🏢

Clientes podem se cadastrar com CPF (Pessoa Física) ou CNPJ (Pessoa Jurídica).

O endereço do cliente determina o valor do frete.

Clientes podem realizar múltiplos pedidos, com um período de carência para devolução.

Pedido 📋

Pedidos são criados pelos clientes e contêm informações de compra, endereço e status da entrega.

Um ou mais produtos compõem o pedido.

Pedidos podem ser cancelados.

Fornecedor e Estoque 🏭📦

Fornecedor recebe a informação do pedido e verifica a quantidade em estoque.

Produtos são passados para a transportadora que gera o código de rastreio e faz a confirmação da entrega.



