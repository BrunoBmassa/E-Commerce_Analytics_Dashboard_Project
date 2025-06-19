Dashboard interativo para análise de dados de vendas de um e-commerce utilizando Python e bibliotecas como Pandas, Plotly Express e Dash.
O projeto envolveu todas as etapas do pipeline de dados: extração automatizada de arquivo CSV do Google Drive com gdown, tratamento e limpeza de dados com pandas
e análise exploratória com a criação de diversos gráficos interativos (histograma, dispersão, bolha, barras, pizza, linha e 3D).

Utilizei o Dash para construir uma aplicação web responsiva com foco em visualização de indicadores-chave (KPIs) relacionados a preço, gênero e sazonalidade de produtos. 
O painel proporciona insights visuais para tomada de decisão, destacando padrões de consumo e comportamento por temporada.

Como Executar:

Clone este repositório:

git clone https://github.com/BrunoBmassa/Projeto-dashboard-interativo-de-vendas-em-E-Commerce.git
cd Projeto-dashboard-interativo-de-vendas-em-E-Commerce

Instale os pacotes necessários:
pip install pandas dash plotly gdown

Execute o app:
python dashboard_ecommerce.py
