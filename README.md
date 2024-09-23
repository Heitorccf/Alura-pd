# Projeto de Data Science com Pandas - Alura

Este repositório contém o projeto desenvolvido durante o curso de **Data Science com Pandas** da Alura, no qual aplicamos os principais recursos dessa biblioteca para análise de dados.

## Descrição do Projeto

O objetivo do projeto é aprender a manipular e analisar bases de dados utilizando o **Pandas**, uma das bibliotecas mais populares em Python para Data Science. Durante o curso, desenvolvemos habilidades para realizar análises exploratórias, criar visualizações e transformar dados para gerar insights.

### Principais Tópicos Abordados

1. **Conhecendo a base de dados**
   - Importação e compreensão dos dados
   - Estruturas de dados do Pandas
   - Exploração inicial da base

2. **Análise exploratória de dados**
   - Cálculo de estatísticas descritivas
   - Uso de `groupby` para agrupamento e sumarização
   - Seleção de dados específicos com `query`
   - Visualização de dados com gráficos

3. **Tratando e filtrando dados**
   - Lidar com dados nulos (remoção e substituição)
   - Uso do método `drop` para remover colunas e linhas
   - Filtragem e seleção de dados relevantes
   - Salvamento dos dados filtrados em diferentes formatos

4. **Manipulando os dados**
   - Criação de colunas numéricas e categóricas
   - Operações entre colunas
   - Criação de colunas binárias
   - Manipulação e transformação de dados

## Ferramentas Utilizadas

- **Python 3.x**
- **Jupyter Notebook**
- **Biblioteca Pandas**
- **Matplotlib/Seaborn** (para visualizações gráficas)

## Como Executar o Projeto

1. Clone este repositório
   
2. Navegue até o diretório do projeto
   
3. Instale as dependências necessárias:
   ```bash
   pip install pandas matplotlib seaborn
   ```

4. Abra o arquivo Jupyter Notebook para explorar a análise dos dados:
   ```bash
   jupyter notebook real-estate.ipynb
   ```

## Estrutura do Repositório

```bash
.
├── README.md          # Documentação do projeto
├── raw-data           # Diretório com a base de dados original
│   └── renting.csv    # Dados de imóveis para aluguel
└── real-estate.ipynb  # Jupyter Notebook com a análise e manipulação dos dados
```

- **`raw-data/renting.csv`**: Arquivo CSV contendo a base de dados de imóveis para aluguel.
- **`real-estate.ipynb`**: Notebook Jupyter com todas as etapas da análise de dados, desde a importação até a visualização e transformação.
