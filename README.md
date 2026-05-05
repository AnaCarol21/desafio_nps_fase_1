# Tech Challenge Fase 1
Desafio da primera fase da pós-tech
# Objetivo do projeto
Apresentar informações, por meio da análise de dados, que ajudem a entender o que está impactando negativamente o NPS de um e-commerce durante e após a jornada de compra.

# Descrição da base de dados
Exemplos de informações disponíveis:
- Dados do pedido (valor, quantidade de itens, forma de pagamento);
- Dados logísticos (tempo de entrega, atraso, tentativas);
- Dados de atendimento (contatos, tempo de resolução);
- Indicadores internos de negócio.

### Dicionário de Dados
- customer_id: Identificador único do cliente.
- order_id: Identificador único do pedido.
- customer_age: Idade do cliente.
- customer_region: Região geográfica do cliente.
- customer_tenure_months: Tempo de relacionamento do cliente com a
empresa (em meses).
- order_value: Valor total do pedido.
- items_quantity: Quantidade de itens no pedido.
- discount_value: Valor de desconto aplicado ao pedido.
- payment_installments: Número de parcelas do pagamento.
- delivery_time_days: Tempo total de entrega (em dias).
- delivery_delay_days: Quantidade de dias de atraso na entrega.
- freight_value: Valor do frete.
- delivery_attempts: Número de tentativas de entrega.
- customer_service_contacts: Número de contatos do cliente com o
atendimento.
- resolution_time_days: Tempo para resolução de problemas (em dias).
- complaints_count: Número de reclamações registradas pelo cliente.
- repeat_purchase_30d: Indica se houve recompra em até 30 dias após o
pedido (0 = não, 1 = sim).
- csat_internal_score: Score interno de satisfação do cliente.
- nps_score: Nota de satisfação do cliente (NPS), variando de 0 a 10, coletada
após a experiência de compra.

# Metodologia utilizada
Baseada em Crisp DM: 
- Entendimento do problema de negócio.
- Exploração da base e das variáveis.
- Tratativa dos dados.
- Interpretação dos resultados.
- Recomendações.
  
# Como reproduzir os resultados
Neste repositório contém o link do Google Collab, a base de dados em arquivo .csv e também a apresentação em slides. </br>
Basta abrir o Google Collab, inserir a base de dados e executar.
