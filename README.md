# desafio_e-commerce
Refinando um projeto Conceitual de Banco de Dados - E-COMMERCE
Cadastro: Esta entidade armazena as informações de cadastro dos clientes. Cada cadastro tem um ID Cadastro único, um Tipo de Conta que pode ser Pessoa Física ou Pessoa Jurídica, e campos separados para CPF e CNPJ. Dependendo do Tipo de Conta, apenas um desses campos seria usado. Cada cliente tem um único cadastro e cada cadastro está associado a um único cliente.

Forma de Pagamento: Esta entidade armazena as diferentes formas de pagamento disponíveis. Cada forma de pagamento tem um ID Forma de Pagamento único, uma Descrição e um tipo de pagamento. Cada pedido está associado a uma única forma de pagamento, mas uma forma de pagamento pode estar associada a vários pedidos

Entrega: Esta entidade armazena as informações de entrega dos pedidos. Cada entrega tem um ID Entrega único, Codigo de Rastreio e Status. Cada pedido tem uma única entrega e cada entrega está associada a um único pedido.
