# ⚽ Análise de Dados - Ligas Nacionais Europeias 2024/25

## 📌 Sobre o Projeto
Análise exploratória de dados das principais ligas nacionais europeias na temporada 24/25, identificando os melhores jogadores e construindo um Dream Team baseado em estatísticas.

## 🗂️ Estrutura do Projeto
```
projeto/
│
├── data/                              # Dataset utilizado
│   └── players_data_light-2024_2025.csv
│
├── aed.ipynb                          # Notebook com a análise completa
├── README.md                          # Documentação do projeto
└── .gitignore                         # Arquivos ignorados pelo Git
```

## 🎯 Objetivos da Análise

- Identificar os melhores jogadores ofensivos e defensivos
- Comparar a qualidade técnica das 5 principais ligas europeias
- Montar um Dream Team (formação 3-5-2) com os melhores da temporada

## 📊 Principais Insights

🏆 **Melhor Liga:** Premier League - domina ofensiva e defensivamente com médias superiores

🧤 **Goleiro Destaque:** Mark Flekken (Brentford) - 150 defesas na temporada

⭐ **Jogador Destaque:** Mohamed Salah (Liverpool) - 47 participações em gols (G+A)

🎨 **Diferencial:** Visualização tática do Dream Team usando a biblioteca mplsoccer

## 🛠️ Tecnologias Utilizadas

- **Python** - Linguagem principal
- **Pandas** - Manipulação de dados
- **Seaborn / Matplotlib** - Visualizações
- **mplsoccer** - Visualização tática do campo
- **Jupyter Notebook** - Ambiente de análise

## 📁 Fonte dos Dados

Dataset: [Kaggle - Football Players Stats 2024-2025](https://www.kaggle.com/datasets/hubertsidorowicz/football-players-stats-2024-2025/data)

## 🚀 Como Executar

1. Clone o repositório:
```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Instale as dependências:
```bash
   pip install pandas seaborn matplotlib mplsoccer
```

3. Abra o notebook:
```bash
   jupyter notebook aed.ipynb
```

## 📈 Análises Realizadas

- ✅ Top 10 goleadores, assistentes e jogadores ofensivos (G+A)
- ✅ Top 10 melhores defensores e goleiros
- ✅ Análise de melhores times por média ofensiva e defensiva
- ✅ Comparação entre as 5 principais ligas europeias
- ✅ Dream Team com visualização tática no esquema 3-5-2

---
