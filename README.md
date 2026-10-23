# Desempenho estudantil e curso preparatório

## Visão geral

Projeto de análise de dados educacionais sobre a relação entre concluir um curso preparatório e o desempenho em matemática. Compara médias e proporções de aprovação, com visualizações para contextualizar diferenças e variabilidade.

## Origem dos dados

O arquivo `StudentsPerformance.csv` é uma cópia local do dataset **Students Performance in Exams**, publicado por Jakki Seshapanpu (spscientist) no [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams). O conjunto possui 1.000 registros e oito variáveis: gênero, grupo étnico, escolaridade dos responsáveis, tipo de almoço, preparação para o teste e notas de matemática, leitura e escrita. O cartão do Kaggle indica a licença como desconhecida; confira os termos vigentes e atribua a fonte antes de redistribuir os dados.

## Perguntas

1. A média de matemática é maior entre quem concluiu o curso?
2. A proporção com nota de matemática ≥ 60 é maior entre quem concluiu o curso?

O ponto de corte 60 é uma definição operacional escolhida para esta análise, não uma regra oficial universal.

## Métodos e ferramentas

- Tratamento e validação de tipos, ausências, categorias e limites das notas.
- Estatística descritiva e gráficos de distribuição para as três disciplinas.
- Teste t de Welch unilateral para a média de matemática.
- Teste Z unilateral para duas proporções de aprovação.
- Python, pandas, NumPy, SciPy, statsmodels, Seaborn e Matplotlib.

## Limitação

Os dados são observacionais. Associações encontradas descrevem esta amostra e não demonstram que o curso causou as diferenças. Representatividade e fatores de confusão devem ser considerados.

## Como executar

Mantenha `Teste de hipótese.ipynb` e `StudentsPerformance.csv` na mesma pasta, instale as bibliotecas listadas e execute as células do notebook em ordem.
