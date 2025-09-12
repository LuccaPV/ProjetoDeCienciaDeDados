# Projeto De Ciencia De Dados
Neste repositório você encontrará dados sobre meu projeto da disciplina de Ciencia De Dados

# 1. Informações Básicas
- Nome do dataset: Smart Water Consumption Dataset
- Fonte (link): https://www.kaggle.com/c/titanic/data](https://archive.ics.uci.edu/dataset/733/water+quality+prediction-1)
- Dimensões (linhas x colunas): 45.000 registros x 12 colunas
- Tamanho em MB: Aprox 1

# 2. Problema de Machine Learning
- Tipo: [] Classificação [X] Regressão
- Variável alvo (target): Consumo de água (litros por hora)
- Número de classes (se classificação):
- Distribuição do target:
Média: 135 L/h

Mediana: 120 L/h

Desvio padrão: 35 L/h

Faixa: 50 a 250 L/h

# 3. Qualidade dos Dados
- % valores faltantes:~5% (principalmente em sensores de pressão e temperatura)
- Tipos de variáveis:
Numéricas contínuas: Fluxo de água, pressão, temperatura, litros consumidos
Categóricas: Dia da semana, tipo de residência, estação do ano
Datas: Timestamp (registro de cada hora)
Texto: Nenhuma
# 4. Justificativa
- Por que escolheram este dataset?
  O desperdício de água é um problema global. Esse dataset fornece medições reais que permitem entender padrões de consumo e prever picos de uso.
- Qual problema real vocês querem resolver?
  Prever o consumo de água em residências para ajudar empresas e governos a planejar campanhas de uso consciente e evitar sobrecarga em horários de pico.
- Que insights esperam encontrar?
Identificar os horários de maior consumo.

Descobrir o impacto da estação do ano no uso de água.

Prever anomalias que possam indicar vazamentos.

Criar recomendações personalizadas de economia de água para famílias.
