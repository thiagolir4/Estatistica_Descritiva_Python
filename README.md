# 📊 Projeto de Estatística Descritiva com Pandas — Escola DNC

Este repositório contém os scripts e análises desenvolvidos durante o curso da Escola DNC, focando na aplicação de conceitos de estatística descritiva e na utilização prática da biblioteca **pandas** para análise de dados em Python. Todo o desenvolvimento foi realizado utilizando o VS Code.

## 📁 Estrutura do Projeto e Acesso aos Códigos

Os códigos e análises estão organizados em diferentes arquivos (scripts `.py` ou notebooks Jupyter `.ipynb`) dentro deste repositório. Você pode navegar pelas pastas para acessar os scripts específicos relacionados a cada etapa da análise.

## 📚 Conteúdo Abordado

- **Introdução ao pandas**: Leitura e escrita de arquivos (CSV, Excel), criação e manipulação de DataFrames, seleção de colunas de interesse.
- **Exploração Inicial de Dados**: Utilização de funções como `.info()`, `.dtypes`, `.head()` para entender a estrutura e o conteúdo dos datasets.
- **Limpeza e Preparação de Dados**:
    - Identificação e tratamento de valores ausentes (NaNs): contagem, cálculo de percentuais e visualização.
    - Identificação e análise de dados duplicados.
    - Limpeza de strings: remoção de espaços desnecessários em dados textuais e (se aplicável) tratamento de caracteres especiais.
- **Análise Exploratória de Dados (EDA)**:
    - Separação e análise de variáveis por tipo (numéricas, categóricas e booleanas).
    - Cálculo e interpretação de frequências para variáveis categóricas.
    - **Cálculo de Medidas de Tendência Central**:
        - Moda: para variáveis categóricas, booleanas e numéricas.
        - Média: para variáveis numéricas.
        - Mediana: para variáveis numéricas.
    - Utilização da função `describe()` para um resumo estatístico completo de variáveis numéricas.
    - Análise de outras estatísticas descritivas (ex: máximo, mínimo).
    - Discretização de variáveis numéricas contínuas em faixas (utilizando `pd.cut()`).
    - Agrupamentos básicos de dados.
- **Visualização de Dados com Matplotlib**:
    - Criação de gráficos de barras para representar frequências e distribuições.
    

## 📂 Dados Utilizados

Neste projeto, foram analisados os seguintes conjuntos de dados:

1.  **`analise_imoveis_sao_paulo.csv`**:
    * Descrição: Dataset contendo informações sobre imóveis na cidade de São Paulo.
    * Disponibilidade: O arquivo está incluído neste repositório.
    * 🔗 **[Clique aqui para baixar o dataset `analise_imoveis-sao_paulo.csv` via Google Drive](LINK_DO_GOOGLE_DRIVE)**
2.  **`ifood-restaurants-november-2020.csv`**:
    * Descrição: Dataset com informações de restaurantes cadastrados no iFood em novembro de 2020.
    * Disponibilidade: Este arquivo foi utilizado para algumas análises exploratórias e de visualização. Devido ao seu tamanho, ele não está incluído diretamente no repositório.
    * 🔗 **[Clique aqui para baixar o dataset `ifood-restaurants-november-2020.csv` via Google Drive](LINK_DO_GOOGLE_DRIVE)**
        *(Lembre-se de substituir pelo link de compartilhamento público do seu arquivo no Google Drive).*
3.  **`ifood-restaurants-february-2021.csv`**:
    * Descrição: Dataset com informações de restaurantes cadastrados no iFood em fevereiro de 2021, utilizado para análise de medidas de tendência central.
    * Disponibilidade: Este arquivo foi utilizado para análises estatísticas.
    * 🔗 **[Clique aqui para baixar o dataset `ifood-restaurants-february-2021.csv` via Google Drive](LINK_DO_GOOGLE_DRIVE)**

## 🛠️ Tecnologias Utilizadas

- [Python 3.x](https://www.python.org/)
- [pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [NumPy](https://numpy.org/)
- VS Code (Ambiente de Desenvolvimento)

## 🎯 Objetivo

O objetivo principal deste projeto é aplicar e consolidar os conhecimentos adquiridos em estatística descritiva e manipulação de dados com Python, utilizando a biblioteca pandas para realizar análises exploratórias, limpeza de dados, cálculo de medidas estatísticas e geração de insights a partir de diferentes conjuntos de dados. Este trabalho serve como um portfólio prático das técnicas aprendidas durante o curso da Escola DNC.

## 🚀 Como Utilizar

1.  **Clone o repositório:**
    ```bash
    git clone(https://github.com/thiagolir4/Estatistica_Descritiva_Python.git)
    cd Estatistica_Descritiva_Python
    ```
2.  **Instale as dependências:**
    Recomenda-se criar um ambiente virtual. As principais bibliotecas são:
    ```bash
    pip install pandas matplotlib numpy openpyxl
    ```
3.  **Navegue pelos scripts ou notebooks** nas pastas do projeto para ver as análises.
4.  **Execute os scripts Python ou as células dos notebooks** no VS Code ou no seu ambiente Python preferido.
5.  Certifique-se de que os datasets (`analise_imoveis_sao_paulo.csv`, `ifood-restaurants-november-2020.csv`, `ifood-restaurants-february-2021.csv`) estejam acessíveis para os scripts que os utilizam. O arquivo de imóveis já estará na pasta do projeto após o clone. Para os datasets do iFood, baixe os arquivos utilizando os links fornecidos na seção "Dados Utilizados" e coloque-os nos caminhos esperados pelos scripts.

## 📌 Observações

- Este projeto foi desenvolvido como parte das atividades do curso de formação em engenheiro de dados da Escola DNC.
- Os códigos são apresentados com fins didáticos e de demonstração das técnicas de análise de dados.

---