# fundamentos-DDD


Entidades de Domínio
As entidades de domínio identificadas a partir do diálogo são:

Produto

Identificação única
Informações adicionais (tamanho, cor)
Estoque

Quantidade atual
Quantidade mínima
Alerta

Meio de notificação (e-mail, sistema)
Venda

Quantidade vendida
Período de venda
Lucro gerado por produto
Ordem de Compra

Baseada em quantidades mínimas de estoque
Tendências de vendas
Fornecedor

Atualizações automáticas sobre prazos de entrega
Casos de Uso
Os casos de uso para a aplicação de gerenciamento de estoque são:

Rastrear Produto

Atribuir um número de identificação único a cada produto.
Adicionar informações adicionais (tamanho, cor).
Gerenciar Estoque

Definir quantidade mínima de estoque para cada produto.
Atualizar a quantidade atual de estoque.
Receber Alertas

Enviar alertas por e-mail.
Enviar notificações pelo sistema de gerenciamento de estoque.
Visualizar Histórico de Vendas e Estoque

Visualizar quantidade de produtos vendidos em um determinado período.
Ver lucro gerado por produto.
Identificar produtos mais vendidos em cada período.
Observar tendências de estoque ao longo do tempo.
Gerenciar Ordens de Compra

Criar ordens de compra automaticamente com base nas quantidades mínimas de estoque e nas tendências de vendas.
Integrar com Fornecedores

Receber atualizações automáticas sobre os prazos de entrega de novas remessas dos fornecedores.
Essas funcionalidades e entidades ajudam a criar um sistema robusto e eficiente de gerenciamento de estoque, atendendo às necessidades detalhadas pelo Domain Expert.
