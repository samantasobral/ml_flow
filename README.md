# ml_flow
Repositório do Projeto do Aluno da matéria Gestão de Algoritmo de Machine Learning com MLFlow

Versão do Python: 3.10.20

## Projeto do Aluno:
Você trabalha na Delivery Fast, uma empresa que tem como foco levar o alimento do 
restaurante para casa do cliente no menor tempo possível, portanto você foi 
escolhido para realizar a predição do tempo de entrega que é mostrada ao cliente. É 
de suma importância dessa predição ser o mais correta possível para a experiência 
seja agradável para o usuário.
Neste cenário, você deverá prever para um determinado pedido de delivery o tempo 
total de entrega em segundos.

Os dados contém entregas realizadas pela Delivery Fast no ano de 2015, cada 
linha do arquivo é referente a uma entrega única, todos os valores monetários 
são em dólares e todos os de duração estão em segundos.

| Nome da coluna                             | Tipo do dado | Descrição                                                                                     |
|--------------------------------------------|--------------|-----------------------------------------------------------------------------------------------|
| market_id                                  | Inteiro      | A cidade/região na qual a empresa atua                                                        |
| created_at                                 | Data e Hora  | Momento em que o pedido foi realizado pelo cliente                                            |
| actual_delivery_time                       | Data e Hora  | Momento em que o pedido foi entregue ao cliente                                               |
| store_id                                   | Inteiro      | Identificador do restaurante onde o pedido foi realizado                                      |
| store_primary_category                     | Texto        | Categoria principal do restaurante                                                            |
| order_protocol                             | Inteiro      | Modo pelo qual o restaurante recebe pedidos da empresa                                        |
| total_items                                | Inteiro      | Total de itens do pedido                                                                      |
| subtotal                                   | Inteiro      | Valor total do pedido (em centavos)                                                           |
| num_distinct_items                         | Inteiro      | Número de itens distintos no pedido                                                           |
| min_item_price                             | Inteiro      | Preço do item mais barato no pedido (em centavos)                                             |
| max_item_price                             | Inteiro      | Preço do item mais caro no pedido (em centavos)                                               |
| total_onshift_dashers                      | Inteiro      | Número de entregadores disponíveis em até 16 km do restaurante no momento da criação do pedido |
| total_busy_dashers                         | Inteiro      | Subconjunto de `total_onshift_dashers` que está atualmente trabalhando em um pedido           |
| total_outstanding_orders                   | Inteiro      | Número de pedidos em um raio de 10 milhas que estão sendo processados atualmente              |
| estimated_order_place_duration             | Inteiro      | Tempo estimado para o restaurante receber o pedido da Delivery Fast (em segundos)             |
| estimated_store_to_consumer_driving_duration | Inteiro    | Tempo estimado de viagem entre o restaurante e o consumidor (em segundos)                     |

- Solução esperada:

Portanto se espera que você construa um modelo para prever a duração total da 
entrega em segundos.

- Dicas:

Atenção, a variável alvo não foi criada, portanto encontre a forma de como criá-la;

Atenção para os possíveis preprocessamento e tratamento das variáveis

Planeje antes de codificar e como a predição será utilizada

Entenda qual a natureza do problema a ser resolvido

Interligue os conhecimentos dos cursos da Comunidade DS
