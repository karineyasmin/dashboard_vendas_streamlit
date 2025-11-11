# Dashboard de Vendas

Link de acesso:
https://dashboardvendasapp-cgtl4js3ttcniqschd2vw8.streamlit.app/

## Tecnologias utilizadas
<a href="https://python.org"><img src="https://cdn.simpleicons.org/python" width="24" alt="Python" style="margin-right:8px;"></a>
<a href="https://streamlit.io"><img src="https://cdn.simpleicons.org/streamlit" width="24" alt="Streamlit" style="margin-right:8px;"></a>
<a href="https://pandas.pydata.org"><img src="https://cdn.simpleicons.org/pandas" width="24" alt="Pandas" style="margin-right:8px;"></a>
<a href="https://plotly.com"><img src="https://cdn.simpleicons.org/plotly" width="24" alt="Plotly" style="margin-right:8px;"></a>

Resumo
-----
Aplicação Streamlit que apresenta um dashboard interativo de vendas com métricas, gráficos e um mapa. Permite filtrar por vendedor e navegar entre as abas: Dataset, Receita e Vendedores.

O que o dashboard faz
---------------------
- Exibe o dataset de vendas.
- Mostra receita total e quantidade de vendas.
- Visualiza receita por estado (mapa), receita mensal, receita por categoria.
- Apresenta métricas e gráficos por vendedor (receita e quantidade).
- Permite download dos dados filtrados.

Principais tecnologias
----------------------
- Streamlit — UI e deploy.
- Pandas — tratamento e agregação dos dados.
- Plotly — gráficos interativos.
- (Arquivos do projeto: app.py, dataset.py, utils.py, graphs.py)

Como executar localmente
------------------------
1. Criar e ativar um ambiente virtual (Linux):
   python -m venv .venv
   source .venv/bin/activate

2. Instalar dependências:
   pip install -r requirements.txt

3. Iniciar a aplicação:
   streamlit run app.py

