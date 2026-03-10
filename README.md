# 📊 Challenge Telecom X — Análise de Evasão de Clientes (Churn)

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte do **Challenge Telecom X**, com o objetivo de aplicar conceitos de **ETL (Extract, Transform, Load) e Análise Exploratória de Dados (EDA)** utilizando **Python**.

No desafio, atuo como **assistente de análise de dados** em uma empresa fictícia de telecomunicações chamada **Telecom X**. A empresa enfrenta um problema recorrente de **evasão de clientes (churn)** e precisa entender os fatores que levam os clientes a cancelarem seus serviços.

A análise realizada neste projeto tem como objetivo **explorar os dados da empresa, identificar padrões de comportamento e gerar insights que possam ajudar a equipe de Data Science a desenvolver modelos preditivos para reduzir o churn**.

---

## 🎯 Objetivo da análise

O objetivo principal do projeto é **investigar os fatores associados à evasão de clientes**, analisando características demográficas, contratuais e financeiras presentes na base de dados.

A partir dessa análise, busca-se:

- Identificar **padrões relacionados ao cancelamento de clientes**
- Compreender **quais perfis apresentam maior risco de churn**
- Fornecer **insights que possam orientar estratégias de retenção**

---

## 📂 Base de dados

Os dados utilizados neste projeto foram disponibilizados por meio de uma **API hospedada em um repositório no GitHub**.

A base está estruturada no formato **JSON**, contendo informações sobre clientes da empresa Telecom X, incluindo:

- Informações demográficas
- Informações de contrato
- Serviços utilizados
- Métodos de pagamento
- Valores de cobrança mensal e total
- Status de evasão (Churn)

Os dados foram importados diretamente da API e convertidos em um **DataFrame utilizando a biblioteca Pandas**.

---

## 🔄 Processo de ETL

Durante o desenvolvimento do projeto, foi aplicado o processo de **ETL (Extract, Transform, Load)**.

### Extract (Extração)

Os dados foram obtidos a partir de uma **API em formato JSON hospedada no GitHub**, utilizando a biblioteca `requests`.  
Em seguida, os dados foram convertidos para um **DataFrame do Pandas** utilizando `json_normalize`.

### Transform (Transformação)

Foram realizadas diversas etapas de limpeza e tratamento dos dados, incluindo:

- Verificação de **valores nulos e vazios**
- Remoção de **registros duplicados**
- Padronização de **variáveis categóricas**
- Conversão de **colunas numéricas**
- Criação de uma nova variável chamada **Contas_Diarias**, derivada do valor mensal de cobrança

Essas etapas garantem que os dados estejam **consistentes e prontos para análise**.

### Load

Após o tratamento, os dados foram organizados em um **DataFrame estruturado**, possibilitando a realização da análise exploratória e das visualizações.

---

## 📊 Análise Exploratória de Dados (EDA)

A análise exploratória teve como objetivo identificar **padrões e possíveis relações entre as variáveis e o churn**.

Foram realizadas análises como:

- Estatísticas descritivas das variáveis numéricas
- Distribuição geral de clientes que cancelaram ou permaneceram
- Comparação de churn entre diferentes **variáveis categóricas**
- Comparação entre churn e **variáveis numéricas**, como tempo de contrato e valor gasto

---

## 📈 Visualizações de dados

Para facilitar a interpretação dos dados, foram criadas visualizações utilizando **Matplotlib e Seaborn**, incluindo:

- Distribuição geral de churn
- Distribuição de churn por gênero
- Comparação de churn por tempo de contrato
- Comparação de churn por valor total gasto

Esses gráficos ajudam a identificar **padrões de comportamento e possíveis fatores associados à evasão de clientes**.

---

## 🛠 Ferramentas utilizadas

- Python  
- Pandas  
- Requests  
- Matplotlib  
- Seaborn  
- Google Colab  
- GitHub  

---

## 📑 Principais insights

A análise dos dados revelou alguns padrões relevantes:

- Clientes com **menor tempo de contrato** apresentam maior probabilidade de cancelar o serviço
- Clientes com **menor valor total gasto** também apresentam maior incidência de churn
- Não foram identificadas diferenças significativas de churn entre os **gêneros**

Esses padrões indicam que **clientes mais recentes tendem a ser mais propensos à evasão**, o que sugere a necessidade de estratégias de fidelização voltadas para esse público.

---

## 💡 Recomendações

Com base na análise realizada, algumas estratégias podem ser consideradas pela empresa:

- Desenvolver **programas de fidelização para novos clientes**
- Criar **benefícios progressivos para clientes com maior tempo de permanência**
- Monitorar clientes com **baixo nível de consumo**
- Oferecer **planos ou serviços personalizados** para aumentar o engajamento

Essas ações podem contribuir para **reduzir a taxa de evasão e melhorar a retenção de clientes**.

---

## 🚀 Aprendizados

Este projeto permitiu praticar conceitos importantes da área de **Data Science**, incluindo:

- Extração de dados via API
- Estruturação de dados em formato tabular
- Limpeza e transformação de dados
- Análise exploratória de dados (EDA)
- Criação de visualizações
- Interpretação de padrões em dados

---

## 📎 Como executar o projeto

1. Baixe ou clone este repositório  
2. Abra o arquivo `.ipynb` no **Google Colab**  
3. Execute as células para reproduzir a análise completa  

---

## 👩‍💻 Autora

Projeto desenvolvido por **Evillyn Viturino** como parte dos estudos em **Data Science**.
