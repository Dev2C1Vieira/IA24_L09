# IA24_L09 - Exploração de Algoritmos de Aprendizagem Automática e Agendamento de Tarefas

## Descrição Geral

Este repositório apresenta dois projetos desenvolvidos no âmbito de Inteligência Artificial e Aprendizagem Automática. Cada projeto foca em objetivos distintos, com implementações detalhadas e análises para resolver problemas complexos usando diferentes abordagens de algoritmos.

---

## Projetos Incluídos

### 1. **Análise de Dados e Algoritmos de Aprendizagem Automática**
- **Objetivo**: Explorar e aplicar três abordagens principais de aprendizado automático:
  1. **Classificação Automática**: Previsão de classes baseadas em dados rotulados.
  2. **Agrupamento/Clustering**: Descoberta de padrões em dados não rotulados.
  3. **Regras de Associação**: Identificação de relações entre variáveis em grandes conjuntos de dados.
- **Ferramentas**: 
  - Algoritmos como KNN, Decision Tree, K-Means, e Apriori.
  - Bibliotecas de ciência de dados (`pandas`, `numpy`, `sklearn`, `mlxtend`).
- **Resultados**: Gráficos e análises que demonstram o desempenho dos modelos.

### 2. **Agendamento de Tarefas com Restrições**
- **Objetivo**: Resolver problemas de agendamento de tarefas com restrições como precedência, limitação de recursos e prazos de entrega.
- **Abordagem**: 
  - Definição do problema como um CSP (Problema de Satisfação de Restrições).
  - Uso de algoritmos de busca para encontrar soluções viáveis e ótimas.
- **Ferramentas**:
  - `python-constraint` para modelagem.
  - `matplotlib` para visualização (ex.: gráficos de Gantt).
- **Resultados**: Cronogramas otimizados com visualizações claras das restrições atendidas.

---

## Estrutura do Repositório

- **`Projetos/`**:
  - **`AprendizagemAutomatica/`**: Contém notebooks e scripts para classificação, clustering e regras de associação.
  - **`AgendamentoTarefas/`**: Inclui notebooks e gráficos de Gantt para agendamento com restrições.
- **`datasets/`**: Arquivos de entrada para análise e modelagem.
- **`results/`**: Saída dos algoritmos, incluindo gráficos e resultados das simulações.
- **`README.md`**: Arquivo de descrição principal do repositório.

---

## Tecnologias e Ferramentas Utilizadas

- **Linguagem**: Python 3.8 ou superior.
- **Bibliotecas**:
  - Manipulação e análise de dados: `pandas`, `numpy`.
  - Modelagem e aprendizado de máquina: `sklearn`, `mlxtend`.
  - Visualização: `matplotlib`, `seaborn`.
  - Problemas de restrições: `python-constraint`.

---

## Como Explorar os Projetos

1. Clone o repositório:
   ```bash
   git clone https://github.com/Dev2C1Vieira/IA24_L09.git
   cd IA24_L09
   ```
2. Navegue até a pasta do projeto desejado (`AprendizagemAutomatica` ou `AgendamentoTarefas`).
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Execute os notebooks no Jupyter:
   ```bash
   jupyter notebook
   ```

---

## Autores

- **Pedro Vieira (25626)**  
- **Rafael Silva (25690)**  
- **Gonçalo Costa (26007)**