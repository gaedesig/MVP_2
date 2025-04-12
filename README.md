# MVP_2
Ambiente projeto MVP engenharia de dados

Aluno Gaetano Signorini

## Descrição
Construção um pipeline de dados utilizando tecnologias na nuvem, envolvenodo a busca, coleta, modelagem, carga e análise dos dados.
## Objetivo
Analisar o mercado on-line de forma sintética (Produtos mais vendidos, regiões com mais clientes, faixa etária que mais compra, etc.) e
analítica (vendas por região, produtos por faixa etária e região, formas de pagamento por faixa etária, por período, etc.). 
Por essa análise, pretendo conseguir responder perguntas como:

1.	Qual o produto mais vendido no período registrado?
2.	Como estão divididas as faixas etárias na compra desse produto?
3.	Qual a forma de pagamento mais usada nas transações?
4.	Qual a faixe etária que mais utiliza esse método?
5.	Qual o percentual de cada faixa etária que utilizam esse método?
6.	Qual o percentual de cada categoria de produto nas vendas por estado?
7.	Quais os vendedores com a maior média de avaliações?
8.	Qual o percentual de faturamento de cada categoria sobre o faturamento total no período?
9.	Qual faixa etária mais usa o cartão de crédito para pagar as compras?
10.	Quais os status dos pedidos em determinado período de tempo?
11.	Quais os estados têm mais clientes registrados?
  

## Detalhamento
## 1. Busca pelos dados
Para este MVP, optei por utilizar uma base de dados pública que apresenta maior potencial de conter as informações necessárias para a análise proposta. A base selecionada, disponível no Kaggle, chama-se "Vendas ecommerce pré-pandemia", da Olist. Essa base possui, pelo menos, oito arquivos CSV, os quais agregam dados relevantes e abrangentes sobre o comércio eletrônico, permitindo uma análise detalhada e pertinente aos objetivos do projeto.
# 2. Coleta
Para coletar e tratar os dados da base, disponível no Kaggle, utilizei o ambiente Databricks Community Edition. Este ambiente proporcionou as ferramentas necessárias para manipular e processar os dados, utilizando linguagens Python e SQL. Os arquivos foram armazenados no repositório "MVP_2" em meu ambiente GitHub, inclusive o notebook Databricks chamado "MVP_2_FINAL.ipynb”, com o código desenvolvido para realizar esse processo
# 3. Modelagem
Os dados do projeto estão organizados em tabelas, sendo cada uma gerada a partir dos arquivos CSV da base. Os catálogos de dados, que descrevem os dados contidos em cada uma, bem como os seus respectivos domínios, estão em arquivos PDF , disponíveis no repositório do projeto MVP_2. Exemplo: "CATALOGO_ORDERS.PDF"
# 4. Carga
Todo o processo de carga, tratamento dos dados e análise foi centralizado no notebook "MVP_2_FINAL.ipynb", disponível no repositório do projeto MVP_2
# 5. Análise
Durante a análise da qualidade dos dados, foi constatado que os arquivos CSV originais já estavam bem tratados, apresentando pouquíssimos valores nulos. Esses valores, por sua vez, não prejudicaram nenhuma consulta realizada. Assim, a transição da camada Bronze para a Gold foi praticamente automática, sem a necessidade de alterações nos dados, respeitando as boas práticas associadas ao uso desse padrão.

Um ponto negativo identificado, no entanto, foi a limitação do tipo de dados disponíveis. Por se tratar de informações reais provenientes de operações comerciais, é provável que, por questões de segurança, alguns dados essenciais não foram incluídos nos arquivos fornecidos.

# 7. Autoavaliação  
Ao concluir este trabalho, considero que atingi grande parte dos objetivos delineados no início das etapas. O principal objetivo era compreender quais produtos eram mais negociados na internet, bem como analisar a segmentação do consumidor com base em fatores como faixa etária, renda, nível de educação e localidade. A análise realizada forneceu insights significativos e alinhados com essa proposta.

Entretanto, identifiquei limitações nos dados disponíveis, uma vez que a base utilizada não continha informações suficientes para responder a todas as questões levantadas de maneira completa. 

Como trabalho futuro, planejo buscar novas bases de dados que complementem as informações obtidas neste projeto e aprimorando as soluções apresentadas. 
