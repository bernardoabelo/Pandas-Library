# Pandas-Library

# 📊 DESCRIÇÃO DO DATASET "VENDAS"

# O dataset "Vendas" contém informações detalhadas sobre compras realizadas em uma plataforma de vendas.
# Ele possui as seguintes colunas:

# - idcompra → Identificação única de cada compra
# - idcanalvenda → Canal de venda utilizado na compra
# - bandeira → Nome da bandeira da transação
# - Data → Data em que a compra foi realizada
# - Preço → Valor do produto sem frete
# - Preço_com_frete → Valor total do produto incluindo frete
# - Nome_Departamento → Categoria ou departamento do produto vendido
# - estado → Estado onde o cliente realizou a compra
# - cliente_Log → Identificação única do cliente

# Além disso, foi incorporado um segundo dataset chamado "Clientes", que contém informações adicionais sobre os clientes:

# - cliente_Log → Identificação única do cliente (usado para unir os datasets)
# - idade → Idade do cliente
# - renda → Renda mensal do cliente

# Os dados foram combinados utilizando um merge pelo cliente_Log, semelhante ao PROCV do Excel.


# 🖥️ DESCRIÇÃO DOS CÓDIGOS

# Os códigos desenvolvidos permitem explorar e visualizar insights do dataset de forma clara e interativa.

# 📌 ANÁLISES REALIZADAS

# 1. Departamentos mais vendidos
#    - Utilizamos groupby para contar a quantidade de vendas por departamento.

# 2. Preço médio com frete por departamento
#    - Média do preço com frete por categoria, exibida em um gráfico de colunas.

# 3. Quantidade de vendas por data completa
#    - Total de vendas por dia, representado em um gráfico de linhas interativo.

# 4. Média de renda por canal de venda
#    - Comparação dos canais de venda com a média de renda dos clientes.

# 5. Média de idade dos clientes por bandeira
#    - Exibido em um gráfico interativo de barras com plotly.express.

# 📌 BIBLIOTECAS UTILIZADAS

# - Pandas → Para manipulação e análise dos dados
# - Matplotlib & Plotly Express → Para criação de gráficos estáticos e interativos
# - Datetime → Para tratamento de datas

# O código foi estruturado para máxima eficiência e visualização intuitiva. 📈🚀
