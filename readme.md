# Análise de Segmentação de Clientes - Mall Customers

## Visão Geral
Este projeto foca na análise de segmentação de clientes utilizando o conjunto de dados "Mall Customers". A segmentação de clientes é uma técnica crucial no marketing que agrupa clientes com base em características semelhantes, facilitando estratégias de marketing personalizadas, melhorando a eficácia de vendas e a satisfação do cliente.

## Objetivos
- **Explorar e analisar o conjunto de dados** para compreender o comportamento de compra dos clientes.
- **Identificar segmentos de clientes** baseando-se em atributos como gênero, idade, renda anual e pontuação de gastos.
- **Desenvolver estratégias de marketing** personalizadas para cada segmento identificado, visando otimizar as abordagens de marketing e vendas.

## Conjunto de Dados
Foi utilizado o conjunto de dados "Mall Customers", que contém informações sobre os clientes de um shopping, incluindo:
- `CustomerID`: Identificador único para cada cliente.
- `Gender`: Gênero do cliente (Masculino ou Feminino).
- `Age`: Idade do cliente.
- `Annual Income (k$)`: Renda anual do cliente, em milhares de dólares.
- `Spending Score (1-100)`: Pontuação atribuída pelo shopping com base no comportamento de compra do cliente, variando de 1 a 100.

## Ferramentas e Tecnologias
- **Python**: Utilizado para análise e modelagem de dados.
- **Pandas & NumPy**: Para manipulação e análise de dados.
- **Matplotlib & Seaborn**: Para visualizações gráficas.
- **Scikit-learn**: Para algoritmos de clusterização e pré-processamento de dados.

## Metodologia
### 1. Exploração de Dados
Realizamos uma análise exploratória para entender a distribuição e as relações entre as variáveis. Utilizamos estatísticas descritivas para resumir as características dos dados.

### 2. Pré-processamento de Dados
Procedemos com a limpeza de dados, tratando valores ausentes e outliers. Os dados foram normalizados para garantir a eficácia da análise de clusterização.

### 3. Seleção de Características
Selecionamos as características mais impactantes para a análise de segmentação, focando em `Age`, `Annual Income (k$)` e `Spending Score (1-100)`.

### 4. Análise de Clusterização
Foi utilizado o algoritmo K-means para identificar segmentos de clientes, utilizando o método do cotovelo para determinar o número ótimo de clusters. Cada cluster foi analisado para entender suas características dominantes.

### 5. Interpretação dos Resultados
Cada segmento de clientes foi detalhadamente analisado, identificando padrões específicos de comportamento de compra e preferências.

## Resultados
Identificamos [n] segmentos principais de clientes, cada um com características distintas:
1. **[Nome do Grupo 1]**: [Descrição]
2. **[Nome do Grupo 2]**: [Descrição]

## Como Executar
Para reproduzir esta análise, siga os passos:
1. **Configuração do Ambiente**: Certifique-se de ter Python instalado, junto com as bibliotecas Pandas, NumPy, Matplotlib, Seaborn e Scikit-learn.
2. **Instalação das Dependências**: Execute `pip install pandas numpy matplotlib seaborn scikit-learn` para instalar as dependências necessárias.
3. **Execução do Script**: Execute o script Python que contém a análise exploratória, o pré-processamento, a clusterização e a interpretação dos resultados.