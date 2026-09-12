# 📊 Dados

Este diretório reúne os datasets utilizados durante o desenvolvimento e os testes do **DataCross**.

Os dados foram utilizados em diferentes etapas do projeto, desde a compreensão do problema até a validação do motor de scoring.

## 1. Dataset do SUS

O primeiro dataset utilizado no projeto é uma base de dados relacionada ao **Sistema Único de Saúde (SUS)**.

A partir desse dataset, foi realizada uma **análise exploratória dos dados (EDA)** com o objetivo de compreender melhor o cenário estudado, identificar padrões e observar características relevantes dos casos analisados.

A análise exploratória foi utilizada principalmente para:

- compreender melhor o problema;
- identificar padrões nos dados;
- analisar características dos casos;
- observar situações consideradas mais relevantes para a solução;
- apoiar a definição das informações utilizadas pelo DataCross;
- servir como referência para a construção do dataset sintético.

O dataset original foi utilizado como **referência para entendimento do domínio**, e não como fonte de prontuários reais utilizados diretamente pelo sistema.

---

## 2. Dataset Sintético

O segundo dataset utilizado no projeto é um **dataset sintético**, criado especificamente para os testes do DataCross.

Como o MVP não realiza, neste momento, uma conexão direta com os sistemas dos hospitais para obtenção de prontuários, foi necessário criar uma representação fictícia das informações que seriam obtidas a partir desses registros.

O dataset sintético representa, portanto, **informações derivadas de prontuários médicos** que podem ser utilizadas pelo sistema para realizar a análise e o cálculo do score dos pacientes.

Esses dados foram estruturados para permitir a execução e validação do **motor de scoring** desenvolvido no projeto.
