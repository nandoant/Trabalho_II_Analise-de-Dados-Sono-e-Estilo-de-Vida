# Análise de Dados: Sono e Estilo de Vida

Este projeto analisa a relação entre estilo de vida, saúde e qualidade do sono utilizando técnicas de Machine Learning para classificação e regressão.

## Descrição

O notebook `analise.ipynb` contém uma análise completa de um conjunto de dados sobre hábitos de sono e estilo de vida de 400 indivíduos. O projeto aborda dois problemas:

1. **Classificação**: Previsão de distúrbios do sono (Nenhum, Insônia ou Apneia do Sono)
2. **Regressão**: Previsão da qualidade do sono (escala de 1 a 10)

## Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

```
pandas
numpy
matplotlib
seaborn
scikit-learn
```

## Instalação

1. Clone este repositório ou baixe os arquivos para sua máquina local
2. Instale as dependências necessárias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Como executar o projeto

1. Certifique-se de que o arquivo de dados `02_sono_estilo_vida.csv` está na mesma pasta que o notebook
2. Execute o Jupyter Notebook:

```bash
jupyter notebook analise.ipynb
```

Ou, se estiver usando Google Colab:
1. Faça upload do notebook `analise.ipynb` e do arquivo `02_sono_estilo_vida.csv`
2. Execute todas as células do notebook em ordem