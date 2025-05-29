# 📊 Projeto de Análise de Dados e Estatística Descritiva com Python — Escola DNC

Este repositório contém os scripts e análises desenvolvidos durante o curso da Escola DNC, com foco na aplicação de conceitos de estatística descritiva e na utilização prática das bibliotecas **pandas**, **Matplotlib** e **Seaborn** para análise e visualização de dados em Python. O desenvolvimento foi realizado utilizando o VS Code, explorando diversas facetas da manipulação de **DataFrames** para extrair insights.

---

## 📁 Estrutura do Projeto e Acesso aos Códigos
Os códigos e análises estão organizados em diferentes arquivos (scripts `.py` ou notebooks Jupyter `.ipynb`) dentro deste repositório. Você pode navegar pelas pastas para acessar os scripts específicos relacionados a cada etapa da análise.

---

## 📚 Conteúdo Abordado

-   **Introdução ao pandas e Manipulação de DataFrames**:
    -   Leitura de arquivos CSV (`pd.read_csv`) e escrita (`.to_csv()`).
    -   Visualização inicial de DataFrames (`.head()`, `.info()`, `.dtypes`).
    -   Seleção de colunas de interesse e criação de subconjuntos de dados.

-   **Limpeza e Preparação de Dados**:
    -   Classificação de variáveis em numéricas e categóricas/booleanas (`.select_dtypes()`).
    -   Identificação e tratamento de valores ausentes (NaNs) (conforme necessidade do dataset).
    -   Identificação e análise de dados duplicados (conforme necessidade do dataset).
    -   Limpeza de strings (remoção de espaços, tratamento de caracteres especiais, se aplicável).
    -   **Identificação e Remoção de Outliers**:
        -   Utilização do método do intervalo interquartil (IQR) com `.quantile()`.
        -   Criação de DataFrames com e sem outliers para análise comparativa.
        -   Cálculo do percentual de outliers.

-   **Análise Exploratória de Dados (EDA)**:
    -   Análise descritiva univariada para diferentes tipos de variáveis.
    -   Cálculo e interpretação de frequências com `value_counts()` para variáveis categóricas.
    -   **Cálculo de Medidas de Tendência Central**:
        -   Moda (`.mode()`) para variáveis categóricas, booleanas e numéricas.
        -   Média (`.mean()`) para variáveis numéricas.
        -   Mediana (`.median()`) para variáveis numéricas.
    -   **Cálculo de Medidas de Dispersão**:
        -   Amplitude (máximo - mínimo).
        -   Variância (`.var()`).
        -   Desvio Padrão (`.std()`).
    -   Utilização da função `describe()` para um resumo estatístico completo.
    -   Discretização de variáveis numéricas contínuas em faixas (ex: `pd.cut()`, se aplicável).
    -   Agrupamentos básicos de dados.

-   **Análise de Correlação**:
    -   Cálculo da matriz de correlação entre variáveis numéricas com `.corr()`.
    -   Análise de correlação entre variáveis categóricas (Quali vs Quali) utilizando tabelas de contingência (`pd.crosstab`) e análise percentual.

-   **Visualização de Dados**:
    -   Criação de gráficos de barras com **Matplotlib** para representar frequências.
    -   Criação de gráficos de Boxplot com **Matplotlib** (`plt.boxplot()`) para identificar outliers e analisar distribuições.
    -   Visualização da matriz de correlação com **Seaborn** (`sns.heatmap()`).
    -   Criação de Scatter plots (gráficos de dispersão) com **Seaborn** (`sns.scatterplot()`) para analisar a relação entre duas variáveis numéricas.

-   **Exportação de Dados**:
    -   Salvamento do DataFrame limpo e processado em um novo arquivo CSV (`.to_csv()`).

---

## 📂 Dados Utilizados

Neste projeto, foram analisados os seguintes conjuntos de dados:

1.  **`analise_imoveis_sao_paulo.csv`**:
    * Descrição: Dataset contendo informações sobre imóveis na cidade de São Paulo.
    * Disponibilidade: O arquivo está incluído neste repositório.
    * 🔗 **[Clique aqui para baixar o dataset analise_imoveis-sao_paulo.csv via Google Drive](LINK_DO_GOOGLE_DRIVE_IMOVEIS)** 
2.  **`ifood-restaurants-november-2020.csv`**:
    * Descrição: Dataset com informações de restaurantes cadastrados no iFood em novembro de 2020.
    * Disponibilidade: Utilizado para algumas análises exploratórias. Não incluído diretamente no repositório.
    * 🔗 **[Clique aqui para baixar o dataset ifood-restaurants-november-2020.csv via Google Drive](LINK_DO_GOOGLE_DRIVE_IFOOD_NOV2020)** 
3.  **`ifood-restaurants-february-2021.csv`**:
    * Descrição: Dataset com informações de restaurantes cadastrados no iFood em fevereiro de 2021. Utilizado para cálculo de medidas de tendência central, dispersão, tratamento de outliers e análise de correlação.
    * Disponibilidade: Utilizado extensivamente para análises estatísticas.
    * 🔗 **[Clique aqui para baixar o dataset ifood-restaurants-february-2021.csv via Google Drive](LINK_DO_GOOGLE_DRIVE_IFOOD_FEV2021)** 
4.  **`base_ifood_limpa.csv`**:
    * Descrição: Dataset gerado após o processo de limpeza e tratamento de outliers do `ifood-restaurants-february-2021.csv`.
    * Disponibilidade: Pode ser gerado ao executar os scripts ou incluído no repositório.
    * 🔗 **[Clique aqui para baixar o dataset ifood-restaurants-february-2021.csv via Google Drive](LINK_DO_BASE_IFOOD_LIMPA)**

---

## 🛠️ Tecnologias Utilizadas

-   [Python 3.x](https://www.python.org/)
-   [pandas](https://pandas.pydata.org/) (para manipulação e análise de DataFrames)
-   [NumPy](https://numpy.org/) (para operações numéricas, especialmente no tratamento de outliers)
-   [Matplotlib](https://matplotlib.org/) (para visualizações estáticas como boxplots e gráficos de barras)
-   [Seaborn](https://seaborn.pydata.org/) (para visualizações estatísticas mais elaboradas, como heatmaps e scatter plots)
-   VS Code (Ambiente de Desenvolvimento)

---

## 🎯 Objetivo

O objetivo principal deste projeto é aplicar e consolidar os conhecimentos adquiridos em estatística descritiva e manipulação de dados com Python. Utilizando as bibliotecas **pandas**, **NumPy**, **Matplotlib** e **Seaborn**, o projeto demonstra a capacidade de realizar um ciclo completo de análise de dados: desde a leitura e limpeza, passando pela exploração estatística e visual, até a interpretação de correlações e exportação de resultados. Este trabalho serve como um portfólio prático das técnicas aprendidas durante o curso de Engenheiro de Dados da Escola DNC.

---

## 🚀 Como Utilizar

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/thiagolir4/Estatistica_Descritiva_Python.git](https://github.com/thiagolir4/Estatistica_Descritiva_Python.git)
    cd Estatistica_Descritiva_Python
    ```

2.  **Instale as dependências:**
    Recomenda-se criar um ambiente virtual. As principais bibliotecas são:
    ```bash
    pip install pandas numpy matplotlib seaborn openpyxl
    ```

3.  **Navegue pelos scripts ou notebooks** nas pastas do projeto para ver as análises.
4.  **Execute os scripts Python ou as células dos notebooks** no VS Code ou no seu ambiente Python preferido.
5.  Certifique-se de que os datasets originais (`analise_imoveis_sao_paulo.csv`, `ifood-restaurants-november-2020.csv`, `ifood-restaurants-february-2021.csv`) estejam acessíveis. Para os datasets do iFood e imóveis, se não estiverem no repositório, baixe-os utilizando os links fornecidos na seção "Dados Utilizados" e coloque-os nos caminhos esperados pelos scripts, ou ajuste os caminhos nos scripts. O arquivo `base_ifood_limpa.csv` será gerado por um dos scripts.

---

## 📌 Observações

-   Este projeto foi desenvolvido como parte das atividades do curso de formação em Engenheiro de Dados da Escola DNC.
-   Os códigos são apresentados com fins didáticos e de demonstração das técnicas de análise de dados.

---