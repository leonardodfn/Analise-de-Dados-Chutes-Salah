# ⚽ Análise de Dados — Chutes de Mohamed Salah

Este projeto é uma análise exploratória e visual das finalizações do jogador **Mohamed Salah**, utilizando R e o pacote `ggplot2` para gerar gráficos estatísticos a partir de dados reais.

## 📊 Sobre o projeto

A análise aborda questões como:

- Qual a relação entre a qualidade das chances (xG) e o minuto da partida?
- Salah finaliza melhor com o pé esquerdo ou direito?
- Qual a taxa de conversão em pênaltis?
- Quem são os principais assistentes dos seus gols?
- Como seu desempenho varia entre jogos em casa e fora?

Além disso, são apresentados diversos tipos de visualizações:

- Gráficos de dispersão (*scatter plots*)
- Histogramas
- Boxplots
- Gráficos de barras e colunas
- Gráficos de linha

Todas as visualizações foram construídas com `ggplot2`, respeitando boas práticas de visualização de dados e comunicação científica.

## 💻 Ferramentas utilizadas

- **R** e **RMarkdown**
- **tidyverse**, **ggplot2**, **janitor**, **lubridate**, **summarytools**
- GitHub Pages para publicação do HTML interativo

## 📈 Visualização Online

Acesse o relatório completo com os gráficos interativos diretamente no navegador:

👉 [Clique aqui para visualizar](https://leonardodfn.github.io/Analise-de-Dados-Chutes-Salah/index.html)

## 📁 Estrutura do projeto
```
├── docs/ # Arquivos publicados no GitHub Pages
│ ├── index.html # Relatório final gerado via RMarkdown
│ └── html_files/ # Recursos auxiliares do HTML
├── ShotsAnalizeSalah.csv # Base de dados utilizada
├── visualizacao.Rmd # Código-fonte em RMarkdown
├── .gitignore
└── README.md
```

## 🚀 Como visualizar localmente

Você pode abrir o arquivo `visualizacao.Rmd` no RStudio e executar os chunks para gerar novamente o HTML. Ou apenas abrir `index.html` em qualquer navegador moderno.

---


**Autor:** [Leonardo de Freitas Nogueira](https://github.com/leonardodfn)