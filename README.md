# 🩺 Predicting Student Health Risk

## 📌 Sobre o projeto

Este projeto tem como objetivo prever o risco de saúde de estudantes utilizando técnicas de Machine Learning. A classificação é realizada a partir de informações relacionadas aos hábitos de vida, características físicas e indicadores de saúde dos estudantes.

O projeto foi desenvolvido em Python utilizando bibliotecas para manipulação de dados, visualização e aprendizado de máquina.

---

## 📊 Dataset

Os dados utilizados foram obtidos no **Kaggle** e contêm informações sobre diferentes aspectos da saúde e do estilo de vida dos estudantes.

As principais variáveis utilizadas foram:

* Health Condition (variável alvo)
* Sleep Duration
* Heart Rate
* BMI
* Calorie Expenditure
* Step Count
* Exercise Duration
* Water Intake
* Diet Type
* Stress Level
* Sleep Quality
* Physical Activity Level
* Smoking/Alcohol
* Gender

---

## 🛠 Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

---

## 🔎 Pré-processamento dos dados

Antes da construção do modelo foi realizada uma etapa de limpeza e preparação dos dados.

As principais atividades foram:

* Identificação de valores ausentes (Missing Values);
* Substituição dos valores numéricos ausentes pela média da respectiva variável;
* Substituição dos valores categóricos ausentes pela moda;
* Conversão das variáveis categóricas para formato numérico;
* Normalização dos atributos para melhorar o desempenho do modelo.

---

## 📈 Análise Exploratória

Foi realizada uma análise exploratória para compreender a distribuição das classes presentes na variável alvo.

Também foram analisadas características do conjunto de dados para verificar possíveis desbalanceamentos e entender o comportamento das variáveis antes da modelagem.

---

## 🤖 Modelo de Machine Learning

O algoritmo utilizado foi o **Gaussian Naive Bayes**, implementado através da biblioteca **Scikit-Learn**.

Etapas realizadas:

* Treinamento do modelo;
* Predição dos dados de teste;
* Avaliação da acurácia no conjunto de treinamento;
* Geração do arquivo `submission.csv` para submissão no Kaggle.

---

## 📊 Avaliação

A avaliação do modelo foi realizada utilizando a métrica **Accuracy**, permitindo medir o percentual de classificações corretas obtidas pelo algoritmo.

Além disso, foi gerado o arquivo de submissão para comparação dos resultados na plataforma Kaggle.

---

## 👨‍💻 Autor

**Iago Comin**

Bacharel em Matemática pela Universidade de São Paulo (USP), com interesse em Ciência de Dados, Machine Learning, Inteligência Artificial e Estatística Aplicada.
