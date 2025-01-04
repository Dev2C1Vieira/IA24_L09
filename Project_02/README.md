# IA24_L09 - Análise de Dados e Algoritmos de Aprendizagem Automática

## Descrição

Este projeto explora três abordagens de aprendizado automático, com foco em classificação, agrupamento e regras de associação. Cada seção é dedicada a um objetivo específico, aplicando métodos apropriados para análise e modelagem de dados.

1. **Classificação Automática**: Identificar padrões em dados rotulados e prever classes com base em algoritmos de classificação.
2. **Agrupamento/Clustering**: Encontrar grupos em dados não rotulados, usando técnicas de clusterização.
3. **Regras de Associação**: Descobrir relações entre variáveis em grandes conjuntos de dados transacionais.

O projeto é desenvolvido em Python e utiliza ferramentas populares de ciência de dados.

---

## Estrutura do Projeto

- `Apriori.ipynb`: Notebook principal com a implementação do Algoritmo Apriori.
- `Supervised.ipynb`: Notebook principal com a implementação do Algoritmo Supervised.
- `Unsupervised.ipynb`: Notebook principal com a implementação do Algoritmo Unsupervised.
- `README.md`: Este ficheiro, com informações detalhadas sobre o projeto.
- `datasets/`: Contém o ficheiro de configuração do dataset do `Kaggle` usados para análise.
  - Exemplo: `house-prices-advanced-regression-techniques.zip`
- `results/`: Resultados e visualizações gerados.

---

## Algoritmos Implementados

### 1. **Classificação Automática**
   - **Objetivo**: Prever classes com base em características de entrada.
   - **Processo**:
     - Definição do objetivo de negócio.
     - Seleção de algoritmos de classificação (ex.: Decision Tree, Naive Bayes, KNN).
     - Preparação dos dados e ajuste de parâmetros.
     - Avaliação de modelos (métricas de desempenho).
   - **Exemplo de Aplicação**: Identificação de categorias de preços de imóveis.

### 2. **Agrupamento/Clustering**
   - **Objetivo**: Identificar grupos naturais em dados não rotulados.
   - **Processo**:
     - Definição do objetivo.
     - Aplicação de algoritmos como K-Means, DBSCAN e Birch.
     - Ajuste de parâmetros para otimizar resultados.
   - **Exemplo de Aplicação**: Agrupamento de clientes com base em comportamento.

### 3. **Regras de Associação**
   - **Objetivo**: Encontrar relações entre variáveis em grandes conjuntos de dados.
   - **Processo**:
     - Preparação dos dados.
     - Aplicação do algoritmo Apriori.
     - Análise das regras geradas.
   - **Exemplo de Aplicação**: Análise de itens frequentemente comprados juntos.

---

## Como Executar

### Requisitos
- Python 3.8 ou superior.
- Bibliotecas necessárias:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`
  - `mlxtend`

### Passos
1. Clone o repositório:
   ```bash
   git clone https://github.com/Dev2C1Vieira/IA24_L09.git
   cd IA24_L09
   cd Project 02
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook no Jupyter:
   ```bash
   jupyter notebook Apriori.ipynb
   ```
   ```bash
   jupyter notebook Supervised.ipynb
   ```
   ```bash
   jupyter notebook Unsupervised.ipynb
   ```

---

## Tecnologias Utilizadas

- **Python 3.8**
- **Bibliotecas**:
  - `pandas`, `numpy`: Manipulação de dados.
  - `matplotlib`, `seaborn`: Visualização de dados.
  - `scikit-learn`: Modelagem e análise de dados.
  - `mlxtend`: Descoberta de regras de associação (ex.: Apriori).



## Autores

- **Pedro Vieira (25626);**
- **Rafael Silva (25690);**
- **Gonçalo Costa (26007).**