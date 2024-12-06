# Explorando a Biodiversidade de Pinguins na Antártica: Análise das Características Físicas e Mudanças de 2007 a 2009


<p align="center">
    <img src="./assets/image/image-cover.png" alt="Imagem de pinguins">
</p>
        
Este projeto visa explorar e analisar as características físicas de três espécies de pinguins da região de Palmer (Chinstrap, Gentoo, Adélie), na Antártica, utilizando o conjunto de dados "palmerpenguins". O foco está em examinar variáveis como comprimento e profundidade do bico, comprimento da nadadeira, massa corporal, além de aspectos geográficos e temporais, como a ilha de origem e o ano de observação. A análise busca identificar padrões físicos entre as espécies, explorar relações entre as variáveis, e investigar possíveis mudanças nas características dos pinguins entre os anos de 2007 a 2009.


## Desenvolvedora
 - Halane Moreira -> https://github.com/HalaneMoreira
 
## Justificativa
Estudos sobre a fauna polar, incluindo pinguins, são essenciais para entender o impacto das mudanças climáticas e das atividades humanas em ecossistemas sensíveis. A análise das características físicas dos pinguins ao longo dos anos pode revelar informações importantes sobre adaptações biológicas e a saúde das populações de pinguins em resposta a mudanças ambientais. Este projeto busca não apenas caracterizar as espécies, mas também contribuir para a compreensão das possíveis transformações no habitat antártico, informando estratégias de preservação e fornecendo dados relevantes para futuras pesquisas ambientais e biológicas.


## Metodologia
O projeto será desenvolvido utilizando a metodologia CRISP-DM, seguindo os seguintes passos:

1. Entendimento de negócio
2. Entendimento de dados
3. Preparação dos dados
4. Modelagem
O projeto também é dividido em duas entregas, a saber:

1. Análise Exploratória de Dados (EDA): entendimento das variáveis que influenciam o MPG e identificação de padrões nos dados através de hipóteses, visualizações e insights.
2. Análise comparativa de modelos: construção de modelos de aprendizado de máquina para rpevisão de consumo, com métricas de desempenho para avaliação da performance.

## Resultados Esperados

Esperamos identificar diferenças nas características físicas dos pinguins dependendo da ilha de origem (Biscoe, Dream, Torgersen). Essas diferenças podem revelar como as condições geográficas influenciam as adaptações físicas das diferentes espécies. Podendo incluir aumento ou diminuição no tamanho médio das variáveis (como massa corporal ou comprimento de nadadeiras), refletindo possíveis efeitos ambientais.

## Tecnologias Utilizadas

<div align="center" style="display: inline_block">
<img align="center" alt="github" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img align="center" src="https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="icon jupyter notebook">
<img align="center" src="https://img.shields.io/badge/Python-133DAB?style=for-the-badge&logo=python&logoColor=y1CC0C0" alt="icon python" >
<img align="center" src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="icon pandas">
<img align="center" src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="icon numpy">
<img align="center" src="https://img.shields.io/badge/Matplotlib-0B2C4A?style=for-the-badge&logo=python&logoColor=white" alt="icon matplotlib">
<img align="center" src="https://img.shields.io/badge/Seaborn-4C4C4C?style=for-the-badge&logo=python&logoColor=white" alt="icon seaborn">
<img align="center" src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="icon scikit-learn">
</div>

## Organização de Diretórios

```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```
