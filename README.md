# 📊 CPDC — Análise Exploratória de Dados

Este projeto realiza uma **Análise Exploratória de Dados (EDA)** a partir de dados públicos do **Cartão de Pagamento da Defesa Civil (CPDC)**, com o objetivo de compreender padrões de gastos, estrutura dos dados e possíveis pontos de atenção.

---

## 🎯 Objetivo
Explorar os dados do CPDC buscando responder perguntas como:
- Qual o volume e a estrutura dos dados disponíveis?
- Existem valores ausentes ou inconsistências?
- Como os gastos se distribuem por órgão, categoria ou período?
- Que insights iniciais podem ser extraídos a partir da análise exploratória?

---

## 🗂 Estrutura do Projeto

CPDC/
│
├── data/
│ ├── raw/ # Dados brutos
│ └── processed/ # Dados tratados
│
├── notebooks/ # Notebooks Jupyter
│ └── CPDC.ipynb
│
├── results/
│ └── figures/ # Gráficos gerados
│
├── requirements.txt
└── README.md

---

## 🛠 Ferramentas Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔎 Metodologia
1. Carregamento dos dados
2. Inspeção inicial (`head`, `info`, `shape`)
3. Verificação de valores ausentes
4. Análise exploratória univariada e bivariada
5. Geração de visualizações para apoio aos insights

---

📈 Resultados

Os resultados da análise exploratória permitem uma melhor compreensão da estrutura dos dados e servem como base para análises mais avançadas ou auditorias futuras.

Os gráficos e outputs gerados podem ser encontrados em:

results/figures/

▶️ Como Executar o Projeto

1. Clone o repositório

git clone https://github.com/bgambaroni/CPDC.git

2. Instale as dependências

pip install -r requirements.txt

3. Execute o notebook

jupyter notebook notebooks/CPDC.ipynb




Este projeto tem caráter educacional e analítico, utilizando dados públicos para fins de estudo e demonstração de técnicas de análise de dados.
