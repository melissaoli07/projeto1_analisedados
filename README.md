# projeto1_analisedados
Projeto desenvolvido no Bootcamp de Análise de Dados da Laboratória


Ficha Técnica: Projeto de Análise de Dados - Segmentação de Clientes
Título do Projeto: Segmentação de Clientes
Início: 25.3.25
Duração: 2 sprints (semanas)
Equipe: Individual

✅ Descrição do objetivo:
O objetivo desta análise é segmentar a base de clientes da empresa O Mercado com base em seu comportamento de compra, utilizando a técnica RFM (Recência, Frequência e Valor Monetário).
 As perguntas que busco responder são:
Quem são os melhores clientes?


Quais clientes têm potencial de crescimento em valor de compra?


Espero, ao final, obter grupos de clientes bem definidos que ajudem a empresa a direcionar ações mais eficientes de marketing, retenção, upsell e cross-sell.

🔧 Pré-processamento de dados:
Os dados foram obtidos de uma base contendo informações demográficas e transacionais dos clientes, como idade, filhos, estado civil, e registros de compras (vinhos, frutas, carnes, etc.).
 As principais etapas de pré-processamento foram:
Tratamento de valores ausentes e dupliacdos


Conversão de datas para o formato adequado


Criação de novas variáveis como:


Idade do cliente


Dias desde a última compra


Pontuação RFM (Recência, Frequência, Valor Monetário)


Segmentação baseada em regras de negócios



📊 Métodos e técnicas:
Análise RFM: Recência (dias desde última compra), Frequência (número de transações), Valor Monetário (gasto total)


Classificação RFM em pontuações de 1 a 5, seguida de criação de segmentos via regras condicionais (ex: Campeões, Em risco, Perdidos)


Análise descritiva geral: idade média, número de filhos, ticket médio, entre outras


Gráficos e visualizações para facilitar insights e tomada de decisão



✅ Conclusões:
Clientes classificados como "Campeões" representam 6,2% da base e são responsáveis por 10% do faturamento total.


Uma parte da base está concentrada em segmentos intermediários, com potencial para ações de reengajamento.


Há oportunidades claras de upsell entre os clientes fiéis e de cross-sell com base nos produtos mais consumidos por segmento.


A segmentação permite que a empresa personalize suas campanhas, aumentando a eficácia do marketing.



⚠️ Limitações:
A base de dados considera apenas compras em um determinado período, o que pode não refletir o comportamento de longo prazo. Caso dos clientes ‘fora do periodo analisado’


Não há informação de devoluções, cancelamentos ou feedbacks de clientes.






💬 Comentários e anotações:
Foi decidido usar a soma do Valor Monetário como base para cálculo de faturamento, pois representa melhor o valor em dinheiro movimentado, em vez de quantidade de produtos.


A pontuação RFM foi feita com base em quartil (valores de 1 a 5), permitindo uma classificação equilibrada.


Segmentação textual foi criada com lógica condicional baseada na pontuação (ex: “Campeões” = R≥4, F≥4, M≥4).
Texto: São sequências de caracteres que representam strings de texto. Eles são usados para rotular ou descrever dados. Exemplo: "Olá", "Nome", "Descrição", etc. DICA: Uma maneira rápida de identificar se uma variável está formatada como texto ou número em uma planilha é verificando o alinhamento na célula, por exemplo, muitas vezes os números estarão alinhados à direita e os textos à esquerda.



🛠 Ferramentas e Tecnologias:
Google Sheets: Para limpeza de dados, fórmulas, visualizações e análise RFM


Google Apresentações: Criação da apresentação


Looker Studio: Dashboard
Loom: Vídeo



Link Looker: https://lookerstudio.google.com/reporting/0acbbc67-2a6e-45ad-8f99-d9766b2af988
Link Loom: https://www.loom.com/share/15f7448720f44efbb871359c6596ffa1?sid=b6edd004-830c-422d-bbad-05be7d2a3907	
