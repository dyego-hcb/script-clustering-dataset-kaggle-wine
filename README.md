# Machine Learning: Segmentação de Clientes de Seguradoras de Saúde com Agrupamento do Dataset Wine

Este repositório contém um projeto de Machine Learning desenvolvido para analisar e segmentar clientes de uma seguradora de saúde. O projeto utiliza o conjunto de dados Wine, adaptado para focar na segmentação de clientes de seguradoras de saúde, disponível no Kaggle.

## Objetivo

O objetivo deste projeto é aplicar algoritmos de agrupamento para analisar e segmentar clientes de uma seguradora de saúde. A segmentação é baseada em diferentes características dos vinhos, conforme detalhado no conjunto de dados.

## Sobre o Conjunto de Dados

O conjunto de dados utilizado neste projeto é uma versão adaptada do Wine Data Set, originalmente disponível na UCI Machine Learning Repository. As informações sobre os tipos de vinho foram removidas para focar em uma abordagem de agrupamento. Os dados são o resultado de uma análise química de vinhos cultivados na mesma região da Itália, mas derivados de três cultivares diferentes. O conjunto de dados foi adaptado para focar na segmentação de clientes de seguradoras de saúde.

Os dados foram extraídos do site do Kaggle e podem ser encontrados no seguinte link: Wine Dataset for Clustering.

O conjunto de dados contém as seguintes informações:

- Alcohol: Percentual de álcool no vinho.
- Malic acid: Concentração de ácido málico no vinho.
- Ash: Quantidade de cinzas presentes no vinho.
- Alcalinity of ash: Nível de alcalinidade das cinzas no vinho.
- Magnesium: Quantidade de magnésio no vinho.
- Total phenols: Total de compostos fenólicos no vinho.
- Flavanoids: Quantidade de flavonóides no vinho.
- Nonflavanoid phenols: Quantidade de compostos fenólicos não flavonóides no vinho.
- Proanthocyanins: Quantidade de proantocianinas no vinho.
- Color intensity: Intensidade da cor do vinho.
- Hue: Matiz da cor do vinho.
- OD280/OD315 of diluted wines: Proporção entre as absorbâncias ópticas a 280/315 nm.
- Proline: Quantidade de prolina no vinho.

## Algoritmos Utilizados

Foram implementados os seguintes algoritmos de agrupamento:

- K-Means
- Algoritmo Hierárquico
- DBSCAN
- MeanShift
- K-Prototypes
- K-Modes

## Resultados

Após a implementação e avaliação dos algoritmos, o melhor desempenho foi obtido com o algoritmo K-Means, apresentando um coeficiente de silhueta de 0.55.

## Pastas

O projeto está organizado nas seguintes pastas:

- script: Diretório contendo o código do projeto.
- dataset: Diretório contendo o conjunto de dados utilizado no projeto.
- output: Diretório contendo os dados independentes do conjunto de dados, dados dependentes (custos de planos de saúde) do conjunto de dados.

***

# Machine Learning: Health Insurance Customer Segmentation with Wine Dataset Clustering

This repository contains a Machine Learning project developed to analyze and segment customers of a health insurance company. The project uses the Wine dataset, adapted to focus on customer segmentation for health insurers, available on Kaggle.

## Objective

The objective of this project is to apply clustering algorithms to analyze and segment customers of a health insurance company. The segmentation is based on different wine characteristics, as detailed in the dataset.

## About the Dataset

The dataset used in this project is an adapted version of the Wine Data Set, originally available from the UCI Machine Learning Repository. Information about the types of wine was removed to focus on a clustering approach. The data are the result of a chemical analysis of wines grown in the same region of Italy but derived from three different cultivars. The dataset has been adapted to focus on the segmentation of health insurance customers.

The data were extracted from the Kaggle website and can be found at the following link: Wine Dataset for Clustering.

The dataset contains the following information:

- **Alcohol**: Alcohol percentage in wine.
- **Malic acid**: Concentration of malic acid in wine.
- **Ash**: Amount of ash in wine.
- **Alcalinity of ash**: Alkalinity level of ash in wine.
- **Magnesium**: Amount of magnesium in wine.
- **Total phenols**: Total phenolic compounds in wine.
- **Flavanoids**: Amount of flavonoids in wine.
- **Nonflavanoid phenols**: Amount of non-flavonoid phenolic compounds in wine.
- **Proanthocyanins**: Amount of proanthocyanins in wine.
- **Color intensity**: Color intensity of wine.
- **Hue**: Hue of the wine color.
- **OD280/OD315 of diluted wines**: Ratio of optical densities at 280/315 nm.
- **Proline**: Amount of proline in wine.

## Algorithms Used

The following clustering algorithms have been implemented:

- K-Means
- Hierarchical Clustering
- DBSCAN
- MeanShift
- K-Prototypes
- K-Modes

## Results

After implementing and evaluating the algorithms, the best performance was achieved with the K-Means algorithm, presenting a silhouette coefficient of 0.55.

## Folders

The project is organized into the following folders:

- **script**: Directory containing the project code.
- **dataset**: Directory containing the dataset used in the project.
- **output**: Directory containing the independent data from the dataset and dependent data (health insurance costs) from the dataset.
