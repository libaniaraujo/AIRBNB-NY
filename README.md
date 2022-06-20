# SPACE SALES (AIRBNB NOVA YORK)


<img src = "https://user-images.githubusercontent.com/94937578/172832122-c30207f4-8470-40d1-a5c3-4bcb6490c95e.PNG" width="1000px" />
</div>


## 1. Resumo

- [<b>Código no Jupyter Notebook</b>]
- [<b>Dashboard no Power BI</b>]

## 2. Contexto

Supondo que nos juntamos ao time de dados de uma empresa de aluguel de espaços chamada Airbnb. Atualmente o foco da empresao é sua expansão na cidade de Nova York, Estados Unidos. Apesar de muito importante para a Airbnb, essa expansão também é muito arriscada pois qualquer decisão errada pode levar a um grande prejuízo.
Para diminuir o risco desse projeto, o seu chefe pediu para você auxiliar o CEO utilizando dados para responder algumas perguntas que o ajudarão a tomar decisões comerciais e de marketing.
  
## 3. Problema de negócio

<b>As perguntas do CEO:</b>
- Qual o valor médio do aluguel na cidade de Nova York?
- Quais os nomes das regiões que existem na cidade de Nova York?
- Qual é o valor do aluguel mais caro da cidade de Nova York?
- Quais são as categorias de imóveis que estão cadastradas dentro da base de dados da cidade de Nova York?
- Existem quantos usuários (hosts) únicos cadastrados dentro da base de dados da cidade de Nova York?
- Como é a variação dos preços dos imóveis em Nova York?
- Existem mais imóveis baratos ou caros?
- Qual a distribuição do número de reviews? Existem imóveis com muitos e outros com poucos reviews?
- Conseguimos saber onde estão localizados os imóveis com o valor do aluguel mais caro na cidade de Nova York?
- Conseguimos saber onde estão localizados os imóveis pelo seu tipo?
- Conseguimos visualizar esses resultados em um mapa?

## 4. Planejamento da solução:

- <b>Passo 1:</b> Coletar os dados (Kaggle). 
- <b>Passo 2:</b> Descrever os dados.
- <b>Passo 3:</b> Limpar os dados e criar novos atributos (Feature Engineering).
- <b>Passo 4:</b> Realizar a análise exploratória dos dados e obter a partir disso alguns insights.
- <b>Passo 5:</b> Apresentar os dados referentes aos imóveis selecionados em um dashboard no Power BI.

## 5. Dados:

- Os dados foram obtidos na plataforma do Kaggle: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

- Os atributos dos imóveis apresentados no conjunto de dados são descritos na tabela abaixo.

**Atributo** | **Descrição**
--- | --- 
`id`| Identificador do registro na base de dados.
`name`| Nome do anúncio na plataforma do Airbnb.
`host_id`| Identificador do host (dono do imóvel).
`host_name`| Nome do host.
`neighbourhood_group`| Região da cidade de Nova York.
`neighbourhood`| Bairro (dentro de uma das regiões).
`latitude`| Ponto geográfico da latitute.
`longitude`| Ponto geográfico da longitude.
`room_type`| Tipo da locação (quarto, casa inteira, etc).
`price`| Preço do aluguel (diária).
`minimum_nights`| Diárias mínimas para locação.
`number_of_reviews`| Quantidade de avaliações.
`last_review`|  Data da última avaliação.
`reviews_per_month`| Quantidade de revisões mensais.
`calculated_host_listings_count` | Quantidade de anúncios do host do imóvel.
`availability_365` | Tempo (dias) que o anúncio está disponível na plataforma - 0 significa apartamento indisponível.
 
 
 ## 6. Pressupostos:

<b>Algumas suposições foram definidas previamente pelo time de negócio:</b>
- Devem ser descondiderados os imóveis indisponíveis para locação, mesmo que estejam presentes 
- As variáveis que contém a identificação (nome) do host ou do imóvel não devem ser consideradas na análise, com o intuito de preservar a anonimidade. 


## 7. Principais resultados:

<b>Insights obtidos a partir da análise dos dados relativos ao ano de 2019:</b>

- O preço médio do aluguel dos imóveis da Airbnb em Nova York é US$162,05.

- O aluguel mais caro entre os imóveis da Airbnb na cidade de Nova York é US$10.000,00.

- O preço do aluguel diário da maior parte dos imóveis da Airbnb em Nova York está entre US$50 e U$99.
                                                                                                                           
<img src = "https://user-images.githubusercontent.com/94937578/174607354-5a0cef18-4832-4ccb-a6bb-df97e25f30e0.png"  width="800px" />
</div>                                                                                                                        

- A região com o preço médio do aluguel mais caro é Manhattan (US$214.20) e a região com preço do aluguel mais barato é Bronx (US$89,01).

<img src = "https://user-images.githubusercontent.com/94937578/174611409-12a050be-665e-41ac-9b85-c32f737f3262.png" />
</div>

- Há três tipos de imóveis: apartamento inteiro (entire home/apt), quarto privado (private room) e quarto compartilhado (shared room). A quantidade de imóveis de cada uma dessas categorias é:

<img src = "https://user-images.githubusercontent.com/94937578/174605956-da81da0e-390f-4eee-aac1-7acd69e8b3dc.png" />
</div>

- O preço médio dos imóveis de cada uma dessas categorias é:

<img src = "https://user-images.githubusercontent.com/94937578/174611651-424fb9bf-cc24-45ce-b44c-a1976d1e9fdd.png" />
</div>

- Há 21809 anfitriões (hosts) cadastrados na base de dados da Airbnb na cidade de Nova York.

- A quantidade máxima de avaliações recebida por um host é 629 e a quantidade mínima é 0.

- A quantidade máxima de anúncios publicados por um host é 327 e a quantidade mínima é 1.

- O maior tempo (dias) em que o anúncio está disponível na plataforma é 365 dias e o menor tempo é 1 dia.

- O número médio de diárias mínimas para locação é 8.

- A maior parte dos imóveis alugados pela Airbnb apresenta diárias mínimas entre 2 e 3 noites.

<img src = "https://user-images.githubusercontent.com/94937578/174608643-93573c3b-fdc2-480e-afbb-fe006e6251c3.png"  width="800px" />
</div>

- Distribuição espacial dos imóveis por tipo:

<img src = "https://user-images.githubusercontent.com/94937578/174604089-9c56cc6e-32b9-40f1-b44c-5676d017c0ac.png" />
</div>


## 9. Produto final (dashboard):

<img src = "" />
</div>

<img src = "" />
</div>

<img src = "" />
</div>

