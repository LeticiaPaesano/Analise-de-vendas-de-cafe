
![Sem título](https://github.com/user-attachments/assets/1242034c-d0b0-4db3-afe2-5ed633b610f2)

# Análise de Vendas de Café

Este repositório contém uma análise detalhada das vendas de café de uma máquina de venda automática, utilizando um conjunto de dados disponível no Kaggle. O objetivo é explorar padrões de compra, tendências de vendas e preferências dos clientes.

## Visão Geral

O conjunto de dados utilizado neste projeto foi fornecido por Yaroslav Isaienkov e está disponível no [Kaggle](https://www.kaggle.com/datasets/ihelon/coffee-sales/data). Ele contém registros detalhados das transações de venda de café, incluindo informações sobre data, hora, tipo de café, valor da venda e método de pagamento.

## Linguagem e Bibliotecas Utilizadas

  <img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="Python Logo" width="50"/>
</p>

- Bibliotecas:
  
  - pandas
<img src="https://pandas.pydata.org/static/img/pandas_mark.svg" alt="Pandas Logo" width="50"/>
  
  - matplotlib.pyplot
 <img src="https://matplotlib.org/stable/_images/sphx_glr_logos2_001.png" alt="Matplotlib Logo" width="50"/>
 
  - seaborn
<img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="Seaborn Logo" width="100"/>

  - statsmodels.tsa.seasonal / statsmodels.tsa.arima.model
  - <img src="https://www.statsmodels.org/stable/_images/statsmodels-logo-v2.svg" alt="Statsmodels Logo" width="100"/>
</p>
  
## Análise e Visualizações

### 1. Distribuição das Vendas ao Longo do Tempo
![Vendas ao Longo do Tempo](https://github.com/user-attachments/assets/40c7b008-052c-4c26-acee-adee6ee80c8e)


### 2. Relação entre Vendas de Café e Preço
![Relação entre Vendas de Café e Preço](https://github.com/user-attachments/assets/417c367c-bbce-4f4f-9f67-ecf82b0893b9)


### 3. Distribuição das Vendas por Dia da Semana
![Distribuição das Vendas por Dia da Semana](https://github.com/user-attachments/assets/c81a3df4-c53e-4b29-9faf-d11753672f3f)


### 4. Distribuição das Vendas por Mês
![Distribuição das Vendas por Mês](https://github.com/user-attachments/assets/96fecd5d-112f-40ea-811c-25209e8923f9)


### 5. Distribuição das Vendas por Intervalo de 15 Minutos
![Distribuição das Vendas por Intervalos de 15 Minutos](https://github.com/user-attachments/assets/4de94a3f-6edd-469a-b826-c745d9c201d2)

### 6. Decomposição da Série Temporal das Vendas
![Decomposição da Série Temporal das Vendas](https://github.com/user-attachments/assets/70486403-e9ff-4178-afc0-cc23bd9b032d)

- **Série Original**: Representa os dados brutos de vendas ao longo do tempo.
- **Tendência**: Indica a direção geral dos dados ao longo do tempo, revelando se há um aumento ou diminuição nas vendas.
- **Sazonalidade**: Mostra padrões recorrentes ou ciclos nos dados que ocorrem em intervalos regulares, como flutuações sazonais.
- **Resíduos**: São os dados restantes após a remoção da tendência e da sazonalidade, representando variações aleatórias ou ruído nos dados.

  ### 7. Previsão de Vendas para os Próximos 30 Dias
  ![Previsão de Vendas para os Próximos 30 Dias](https://github.com/user-attachments/assets/dd4c057b-2776-40ba-9b5b-b1e39df2a1e5)
  

  




