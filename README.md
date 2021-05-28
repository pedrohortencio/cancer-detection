# Inteligência Artificial Destinada a Detecção de Câncer

# Table of Contents

- [Inteligência Artificial Destinada a Detecção de Câncer](#intelig-ncia-artificial-destinada-a-detec--o-de-c-ncer)
  * [Conjuntos de Dados](#conjuntos-de-dados)
    + [Descrição](#descrição)
      - [Amostra de Imagens (BreakHis):](#amostra-de-imagens-breakhis)
      - [Amostra de Imagens (PCam):](#amostra-de-imagens-pcam)
  * [Resultados](#resultados)
    + [BreakHis e Breast Cancer Wisconsin](#breakhis-e-breast-cancer-wisconsin)

## Conjuntos de Dados

### Descrição

Detecção Histopatológica de Câncer a partir de imagens, utilizando paradigmas de Visão Computacional para a classificação das amostras disponibilizadas por dois datasets: [PatchCamelyon (PCam)](https://github.com/basveeling/pcam) e [Breast Cancer Histopathological Database (BreakHis)](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/).

Classificação de tumores a partir de dados tabulares, utilizando o dataset [Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

#### Amostra de Imagens (BreakHis):

![](https://raw.githubusercontent.com/pedrohortencio/cancer-detection/main/BreakHis/Amostra-Imagens.png)

#### Amostra de Imagens (PCam):

![](https://raw.githubusercontent.com/pedrohortencio/cancer-detection/main/PCam/Amostra-Treino.png)

## Resultados

### BreakHis e Breast Cancer Wisconsin

Ambos os datasets foram explorados em um único momento, comparando os resultados obtidos por duas redes neurais. Os achados foram expostos em um relatório, que pode ser lido [nesse link](https://github.com/pedrohortencio/cancer-detection/blob/main/Relat%C3%B3rio%20(BreakHis%20e%20Wisconsin).pdf).

> A rede neural destinada à classificação de dados tabulares (Breast Cancer Wisconsin) obteve acurácia de 98.6% no conjunto de testes.
>
> A rede neural destinada à classificação de imagens (BreakHis) obteve acurácia de 87.2% no conjunto de testes.
