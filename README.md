# Previsão de Temperatura: Fortaleza (2003 - 2026)

## 📌 Introdução
Este projeto é um estudo pessoal dedicado à análise e previsão das variações de temperatura na cidade de **Fortaleza, Ceará**. O trabalho nasce de uma observação prática e empírica sobre o aumento do calor urbano ao longo das últimas décadas.

O diferencial desta análise é a sua perspectiva multidisciplinar: embora focado em **Ciência de Dados**, o projeto carrega a bagagem da **Arquitetura e Urbanismo**. Para um arquiteto, o clima, a incidência solar e os regimes de ventos não são apenas números, mas pilares fundamentais para o planejamento de espaços habitáveis e sustentáveis.

## 🎯 Objetivos
* **Análise Histórica:** Explorar os dados meteorológicos fornecidos pelo **INMET** (2003 até o presente).
* **Tratamento de Dados:** Realizar a limpeza e o tratamento de séries temporais complexas.
* **Modelagem Preditiva:** Desenvolver um modelo de *Machine Learning* para identificar tendências térmicas futuras.
* **Conscientização:** Utilizar a tecnologia para documentar as mudanças climáticas em nível local.

## 🛠️ Tecnologias e Bibliotecas
A solução foi desenvolvida em Python, utilizando uma abordagem teórica e prática com as seguintes bibliotecas:
* **Pandas & NumPy:** Manipulação e estruturação das séries temporais.
* **Seaborn & Matplotlib:** Visualização estatística e identificação de padrões climáticos.
* **Scikit-Learn:** Implementação de algoritmos de regressão e validação cruzada.

## 📊 Estrutura do Dataset
O conjunto de dados original contém 28 colunas com medições horárias, incluindo:
* **Térmicas:** Temperatura de bulbo seco, ponto de orvalho e umidade relativa.
* **Cinéticas:** Velocidade, direção e rajadas máximas de vento.
* **Atmosféricas:** Pressão ao nível da estação e precipitação total (mm).
* **Energéticas:** Radiação global (KJ/m²).

### Desafios Técnicos Identificados
Durante a fase de exploração, detectou-se uma alta taxa de valores nulos nas colunas de **Radiação Global** (mais de 150 mil registros ausentes em uma das métricas). O projeto aborda a necessidade de lidar com essas lacunas sem comprometer a integridade da análise temporal.

## 🔬 Metodologia de Desenvolvimento
1.  **EDA (Análise Exploratória):** Estudo das médias de temperatura e comportamento dos ventos em Fortaleza.
2.  **Feature Engineering:** Extração de atributos temporais (ano, mês, dia e dia do ano) para capturar a sazonalidade característica da região.
3.  **Data Cleaning:** Identificação e tratamento de *missing values* e *outliers*.
4.  **Validação:** Uso de validação cruzada robusta para garantir que as previsões reflitam tendências reais e não ruídos estatísticos.


## 📝 Créditos
O dataset utilizado foi coletado no [Kaggle](https://www.kaggle.com/datasets/paulogladson/clima-fortaleza) por Paulo Gladson, mas podem ser encontrados também no site do [INMET](https://portal.inmet.gov.br/).
---

> **Reflexão Pessoal:** > "Como arquiteto, entendo que este planeta é nossa casa. Este projeto é minha pequena contribuição, unindo dados e tecnologia, para lembrarmos que cuidar do clima é cuidar do lugar onde moramos."
