# TelecomX_1

📊 Análise de Evasão de Clientes - TelecomX
📌 Descrição do Projeto

Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes (churn) em uma empresa de telecomunicações fictícia chamada TelecomX.
Foram aplicadas etapas de extração, transformação, análise exploratória e modelagem preditiva, utilizando técnicas de ciência de dados e machine learning para identificar padrões e propor estratégias de retenção.

🗂️ Estrutura do Projeto

O notebook segue o fluxo de pipeline de Data Science:

📌 Extração

Importação das bibliotecas necessárias (pandas, numpy, matplotlib, seaborn).

Leitura do dataset em formato JSON hospedado no GitHub.

🔧 Transformação

Normalização de colunas aninhadas (customer, internet, account, phone).

Conversão de tipos de dados (inteiros, floats e strings).

Verificação de inconsistências e duplicidades.

Limpeza e preparação dos dados para análise.

🔎 Análise Exploratória

Estatísticas descritivas.

Visualizações gráficas (distribuições, correlações, proporções de churn).

Identificação das variáveis mais relevantes para explicar a evasão.

🤖 Modelagem Preditiva

Criação e treinamento de modelos de classificação (Regressão Logística, Árvore de Decisão, Random Forest etc.).

Avaliação de desempenho com métricas: Acurácia, Precisão, Recall e F1-score.

Comparação entre modelos para selecionar o de melhor desempenho.

📈 Resultados

Identificação dos principais fatores que impactam a evasão.

Sugestões estratégicas para retenção de clientes com base nos resultados.

📂 Fonte dos Dados

O conjunto de dados utilizado foi obtido diretamente do GitHub:
🔗 TelecomX Data

⚙️ Tecnologias Utilizadas

Python 3.x

Pandas / NumPy → Manipulação e transformação de dados

Matplotlib / Seaborn → Visualização gráfica

Scikit-learn → Modelagem estatística e machine learning

🚀 Como Executar

Clone este repositório:

git clone https://github.com/suellensilva86/TelecomX_1


Instale as dependências:

pip install -r requirements.txt


Abra o notebook:

jupyter notebook nome_do_arquivo.ipynb

📊 Principais Insights

Clientes com contratos mensais apresentam maior chance de evasão.

A qualidade da internet e o suporte técnico são variáveis cruciais.

Estratégias de fidelização (como descontos em pacotes e contratos de longo prazo) podem reduzir o churn.
