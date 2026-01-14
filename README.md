# CPDC
Análise do Cartão de Pagamento da Defesa Civil
📊 Análise Exploratória de Dados — CPDC

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) sobre os gastos registrados no Cartão de Pagamento da Defesa Civil (CPDC), utilizando dados públicos.

🛠️ Ferramentas Utilizadas

Python

Pandas

Matplotlib

Jupyter Notebook

🧹 Tratamento e Preparação dos Dados

Antes das análises, foram realizadas as seguintes etapas de pré-processamento:

Criação de um dataset limpo (df_clean) a partir dos dados brutos

Tratamento de valores ausentes em campos descritivos

Conversão de tipos de dados:

Datas para datetime

Valores monetários para float

Ano e mês para valores numéricos

Essas etapas garantiram maior confiabilidade para as análises posteriores.

📈 Análise Univariada

Foram realizadas análises individuais das variáveis, incluindo:

Frequência de transações por órgão

Frequência de transações por portador

Total gasto por favorecido

Os resultados indicam concentração das transações em poucos órgãos e favorecidos.

📊 Análise Bivariada

Na análise bivariada, foram exploradas relações entre variáveis categóricas e numéricas, como:

Órgão × Valor total gasto

Portador × Valor total gasto

Mês × Valor total gasto

Órgão × Ticket médio

Observou-se que órgãos com menor número de transações podem apresentar ticket médio significativamente maior, demonstrando que frequência de uso não implica, necessariamente, maior volume financeiro.

🔍 Principais Insights

O MID concentra o maior número de transações no período analisado

Os gastos estão majoritariamente associados a:

Bebidas

Mercados

Alimentos

Construtoras

A ausência de informações completas sobre o nome de alguns órgãos limita análises mais detalhadas

Existe diferença relevante entre frequência de uso e valor médio das transações

🚀 Próximos Passos (Sugestões)

Análise temporal com séries mais longas

Detecção de outliers em valores de transação

Análise multivariada para identificar padrões mais complexos

📌 Observação

Este projeto tem caráter exploratório e educacional, com foco em práticas de análise de dados e visualização, não constituindo auditoria ou juízo de valor sobre os gastos analisados.
