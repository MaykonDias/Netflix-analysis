# Netflix Movies and TV Shows - Análise Exploratória

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-008080?style=for-the-badge&logo=python&logoColor=white)

## 📌 Sobre o Projeto

Este projeto consiste em uma **análise exploratória de dados (EDA)** do dataset **Netflix Movies and TV Shows**, disponível no Kaggle. O objetivo é investigar a distribuição de filmes e séries, identificar padrões de produção por país, analisar classificações indicativas e compreender a evolução temporal do catálogo da Netflix.

## 📊 Principais Insights

- **70%** do catálogo é composto por filmes | **30%** por séries
- A partir de **2015**, houve um aumento significativo na adição de séries
- **Estados Unidos** lidera a produção, seguido pela **Índia**
- Classificação predominante: **TV-MA** (conteúdo adulto)
- Pico de adições entre **2017 e 2019**

## 🛠️ Tecnologias Utilizadas

| Biblioteca | Versão | Finalidade |
|------------|--------|------------|
| pandas | ≥ 1.5.0 | Manipulação e limpeza dos dados |
| matplotlib | ≥ 3.5.0 | Criação de gráficos e visualizações |
| seaborn | ≥ 0.12.0 | Gráficos estatísticos avançados |
| plotly | ≥ 5.0.0 | Mapas interativos (choropleth) |
| jupyter | ≥ 1.0.0 | Ambiente de notebook |
| numpy | ≥ 1.21.0 | Operações matemáticas |

## 📁 Estrutura do Projeto

```
Netflix-analysis/
├── netflix_analysis.ipynb   # Notebook principal
├── data/                    # Pasta contendo o dataset
│   └── netflix_titles.csv
├── requirements.txt         # Dependências do projeto
├── .gitignore               # Arquivos ignorados pelo Git
└── README.md                # Documentação do projeto
```

## 🚀 Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/MaykonDias/Netflix-analysis.git
cd Netflix-analysis
pip install -r requirements.txt
jupyter notebook netflix_analysis.ipynb
