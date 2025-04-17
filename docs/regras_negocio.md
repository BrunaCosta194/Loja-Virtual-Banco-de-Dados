Atividade : Formar a equipe e elaborar um conjunto de regras de negócio com base no estudo de caso apresentado. Cada equipe deverá enviar no mínimo  com o contexto analisado. 

Atenção: 

  

É obrigatório o uso de inteligência artificial generativa, porém de forma estratégica e original, evitando respostas meramente reprodutivas. 

Utilizem as dicas e orientações fornecidas em sala de aula para enriquecer a construção das regras. 

Ao final do documento, incluam todos os prompts utilizados como referência, devidamente organizados. 

  

Cada prompt deverá destacar claramente os seguintes elementos: 

Persona 

Conteúdo 

Formato 

Referência (se houver) 

Outros elementos relevantes 

 

1° Cadastro Único de Clientes : Cada cliente deve ser registrado no sistema com um identificador único (id_cliente) e informações obrigatórias, incluindo nome completo, e-mail, telefone e endereço de entrega. O e-mail deve ser único para evitar duplicidade de cadastros. 

2° Gestão de Produtos por Categoria : Cada produto deve ter um código único (id_produto) e ser associado a uma categoria específica (ex.: roupas, eletrônicos, acessórios). As informações obrigatórias incluem nome, descrição, preço unitário e quantidade disponível em estoque. 

3° Controle de Estoque Automático : O sistema deve atualizar automaticamente a quantidade de estoque de um produto após a confirmação de um pedido. Se o estoque de um produto atingir um limite mínimo predefinido (ex.: 5 unidades), o sistema deve gerar um alerta para o setor de pedido. 

4° Registro de Pedidos : Cada pedido deve ser registrado com um identificador único (id_pedido), data e hora da compra, status (ex.: "Em Processamento", "Enviado", "Cancelado") e o id do cliente associado. Um cliente pode ter vários pedidos, mas cada pedido pertence a apenas um cliente. 

5° Itens do Pedido : Cada pedido pode conter múltiplos produtos, registrados na tabela Itens_Pedido. Para cada item, o sistema deve armazenar o id do produto, a quantidade comprada e o preço unitário do produto no momento da compra, garantindo rastreabilidade mesmo se o preço do produto mudar no futuro. 

6° Gestão de Pagamentos : Cada pedido deve ter um pagamento associado, registrado com um identificador único (id_pagamento), valor pago, dados e hora do pagamento, e método de pagamento (ex.: cartão de crédito, boleto bancário, transferência). Um pedido pode ter apenas um pagamento. 

7° Validação de Estoque na Compra : Antes de confirmar um pedido, o sistema deve verificar se há estoque suficiente para todos os produtos solicitados. Caso o estoque seja insuficiente, o sistema deverá impedir a finalização da compra e notificar o cliente. 

8° Status do Pedido : O sistema deve permitir a atualização do status do pedido (ex.: de "Em Processamento" para "Enviado" ou "Cancelado") e registrar o histórico de mudanças para auditorias. Pedidos cancelados devem reverter a redução de estoque realizado no momento da compra. 

9° Relatórios Gerenciais : O sistema deve suportar a geração de relatórios detalhados, incluindo: (a) total de vendas por período, (b) produtos com estoque baixo, (c) pagamentos pendentes ou atrasados, e (d) desempenho de vendas por categoria de produto. 

10° Escalabilidade do Sistema : O banco de dados deve ser projetado para suportar o crescimento da loja, permitindo a inclusão de novos produtos, categorias, métodos de pagamento e clientes sem comprometer o desempenho das consultas ou atualizações. 

 

Prompts Utilizados 

Persona: Estudante do terceiro semestre de Análise e Desenvolvimento de Sistemas, com conhecimentos básicos em banco de dados, aprendendo a criar regras de negócio para um estudo de caso de uma loja virtual. Busca atender às exigências de uma professora que solicita o uso estratégico de IA generativa e documentação detalhada dos prompts. 

Conteúdo: Criar 10 regras de negócio para o sistema de banco de dados da "Loja Virtual", com base no estudo de caso fornecido, que descreve a necessidade de gerenciar clientes, produtos, pedidos, pagamentos e estoque.  

Formato: As regras devem ser concisas, com no máximo 3 frases cada. O prompt deve ser organizado em uma tabela ou lista clara. 

Referência: Estudo de caso "Loja Virtual"  
