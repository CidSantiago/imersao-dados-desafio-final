![Drug Discovery Image](https://www.drugtargetreview.com/wp-content/uploads/shutterstock_1464187604.jpg)

# Desafio Final da Terceira Imersão Dados da Alura
---

Olá! Bem vindo ao meu repositório relativo a Terceira imersão de dados da Alura! Aqui, na pasta **notebooks**, estará uma analise feita em cima dos dados com um modelo para prever qual ação dos mecanismos de ação foi utilizada! Abaixo detalherei melhor qual o escopo do projeto, quais dados serão utilizados e como eu pretendo achar um modelo para prever tal situação.


## Os dados
---

Nesse projeto, estão sendo utilizados dados fornecidos em uma competição no [kaggle](https://www.kaggle.com/c/lish-moa) pelo [Laboratory innovation science de Harvard](https://lish.harvard.edu/) relativo a *drug discovery*, que é a descoberta de novos medicamentos através de dados do efeito de compostos sobre determinados genes e grupo celulares. 

## O Objetivo
---

Após a aula 04 da imersão de dados, me surgiu o questionamento se seria possível predizer a ação dos Mecanismos de ação através da alteração nos genes e nos grupos celulares. Por isso, essa será o foco do meu trabalho final! Tentar prever essa ação 😊

## Como será feito
---

Para obter isso, primeiro de tudo será feito uma analise exploratória e contextualização dos dados. Feito isso, serão feitas algumas transformações, com o objetivo de deixar nossos dados melhores aptos para os nossos modelos de machine learning propriamente dito. O problema foi descrito de forma que se encaixa em problemas de classificação, portanto, serão tentadas 3 abordagens: *Linear Suport Vector Classification* - Linear SVC usando Scikit-learn, AutoML (Auto-sklearn) e *Gradient boosted trees* (XGBoost). Justificando as escolhas: Linear SVC é uma abordagem bastante comum em problemas de classificação, então parece um bom ponto inicial. Já AutoML em geral, é uma área bastante em alta devido a sua simplicidade e facilitação do trabalho dos Cientista de dados em geral. Por fim, o XGBoost é um dos modelos que mais aparecem nas melhores soluções de competições de problemas de classificação em geral, sendo, no meu caso pelo menos, o primeiro modelo a ser testado.

## Resultados
---

TODO

## Conclusões
---

TODO
