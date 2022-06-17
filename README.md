# ✈️ Dados relativos ao AirBnB no Concelho do Porto de 2020

🧠 **Contexto**

Este projeto foi realizado no ambito da cadeira Programação e Algoritmos II do curso de CDM, e tem como objetivo a aprendizagem de metodos de ciencias de dados.

🤓 **Contexto**

Neste trabalho analisaremos dados referentes ao Airbnb na região norte de Portugal. Utilizando os dados coletados no inside AirBnB, faremos uma limpeza nas informações tornando a visualização das questões relacionadas mais simplificada.

Os dados provêm da Inside AirBnB - A AirBnB não disponibiliza a sua API publicamente/ gratuitamente, pelo que optamos por usar a Inside AirBnB, a API 3rd party mais popular, que tem acesso à API oficial e disponibiliza os dados para o público.

🔐 A Inside AirBnB não está associada com a AirBnB. Os dados são obtidos através da API oficial da AirBnB e devidamente verificados, analisados, limpos e agregados pela Inside AirBnb.
A integridade e precisão dos dados são por isso dependentes da manipulação dos dados de ambas das entidades, dos utilizadores do serviço e ainda de outros possíveis fatores intervenientes (condições de privacidade, servicos/servidores intermediários, metodologias etc.)

Para a escolha da fonte de dados, foi principalmente tido em consideração a diversidade dos dados disponibilizados de modo a ter mais opções na representação da mesma.

🗄 **Contexto Histórico**
O Airbnb é um serviço online comunitário para as pessoas anunciarem, descobrirem e reservarem acomodações e meios de hospedagem.
Outubro de 2007 -
Brian e Joe recebem os primeiros hóspedes de Airbed & Breakfast (Nome inicial da plataforma).
Março de 2008 -
O Airbed & Breakfast é lançado oficialmente durante o festival SXSW, obteve duas reservas.
Agosto de 2008 -
O site do Airbed & Breakfast é lançado antes da Convenção Nacional Democrata e recebe 80 reservas.
No mesmo mês é lançado também o Airbnb Payments, plataforma própria de pagamentos que em 2019 processou cerca de 70 bilhões de dólares em transações de hospedes e anfitriões em mais de 40 moedas.
Inside Airbnb é um site de investigação/vigilância lançado por Murray Cox em 2016. Ele relata e visualiza dados raspados na empresa de aluguel de imóveis Airbnb, com foco em destacar o aluguel ilegal no site e a gentrificação causada por proprietários que compram propriedades para alugar no Airbnb.
Murray Cox, ativista comunitario, analisando alguns dados do airbnb de 2014, junto com o canadiano Tom Slee, descobriram que a empresa havia removido 1000 anúncios que violavam a lei de residências múltiplas de Nova York, a publicação de fevereiro de 2016 intitulada de “Como os dados do Airbnb ocultam os factos na cidade de NovaYork”, fez com que a empresa mudasse sua politica de anfitriões. Depois de receber inicialmente o Airbnb com pouca regulamentação, o governo australiano usou os dados do inside Airbnb após preocupações com a pressão sobre a oferta de moradia e acessibilidade. A partir de 2019, o site fornece dados sobre 80 cidades ao redor do mundo.

 **💻 Bibliografia**

Python Libraries
Dython - https://github.com/shakedzy/dython
Ferramenta de análise de dados que permite criar correlações com valores categóricos

TQDM - https://github.com/tqdm/tqdm
Barra de progresso

NLTK - https://www.nltk.org/
Ferramenta de análise de linguagem

NumPy - https://numpy.org/
Ferramenta que permite funções, operações e cálculos matemáticos

Matplotlib - https://matplotlib.org/
Criação de gráficos e visualizações de dados

GeoPandas - https://geopandas.org/en/stable/
Manipulação de dados geográficos

 🧱 **Estrutura**
O repositório está organizado da seguinte forma

- Concelhos
- listings.csv

 ⚙️ **API’s usados – notas técnicas**

Inside AirBnB
http://insideairbnb.com/get-the-data/

📊 **Dicionario de Dados**

| listing_id |            |
| ---------- | ---------- |
| comments   | críticas em formato de texto, da qual se obterá uma pontuação em formato numérico |
| latitude   | dados que permitem a representação geográfica |
| longitude  | dados que permitem a representação geográfica |
| room_type  | dados com valores representáveis |
| 	price    | dados com valores representáveis |
| listing_id | corresponde à coluna ‘id’ do .csv anterior e permitirá o futuro .merge dos dataframes |

