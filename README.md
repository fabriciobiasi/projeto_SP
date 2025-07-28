# 🌫️ Análise da Poluição do Ar em São Paulo (2015–2021)

Este projeto analisa dados reais da qualidade do ar na cidade de São Paulo, com foco nos poluentes **MP10** (material particulado) e **O₃** (ozônio troposférico). A análise cobre o período entre 2015 e 2021, abordando também os possíveis impactos da pandemia de COVID-19 nos níveis de poluição.

## 🎯 Objetivo

Investigar padrões temporais, variações anuais e diferenças entre os dois principais poluentes urbanos em SP, relacionando os dados com eventos externos (como a pandemia).

## 📁 Dados

- Fonte: CETESB / IBGE (base usada em estudo acadêmico)
- Estrutura: Data, Hora, Poluente, Valor
- Período: 2015 a 2021
- Formato: CSV

## 📊 Análises realizadas

- Frequência de medições por poluente
- Evolução da concentração de MP10 e O₃ ao longo dos anos
- Comparações gráficas (linha, barras, boxplot)
- Destaque para possíveis quedas de poluentes em 2020

## 🧠 Principais insights

- **O₃ apresentou queda entre 2015 e 2017**, com estabilização nos anos seguintes.
- **MP10 mostrou tendência de crescimento**, com alta variação e picos frequentes.
- A pandemia pode ter contribuído para **redução pontual** de poluentes, mas efeitos foram distintos para cada tipo.

## 🛠️ Tecnologias usadas

- Python
- pandas
- matplotlib
- seaborn
- Google Colab

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabriciobiasi/projeto_SP.git
   
2. ⚠️ Sobre os dados

O arquivo `SP_poluicao_dados.csv` **não está incluso** neste repositório devido ao tamanho.

Você pode baixá-lo manualmente no seguinte link:

👉 [Baixar CSV](https://www.kaggle.com/datasets/samirnunesdasilva/sao-paulo-pollution-data)

Após o download, crie uma pasta chamada `dados/` no mesmo diretório do notebook e salve o arquivo lá. 

## Fonte dos Dados

Os dados foram obtidos através do Kaggle.

👨‍💻 Autor
Feito com 💻 por Fabricio Biasi
