# Desafio Cientista de Dados - Séries temporais - Lighthouse - Indicium

## Previsão do crescimento do índice GDP ##

## Proposta do desafio

O objetivo deste desafio é testar os conhecimentos sobre a resolução de problemas de análise de dados e aplicação de modelos preditivos, testar os conhecimentos sobre os conceitos estatísticos de modelos preditivos, a criatividade na resolução de problemas e a aplicação de modelos básicos de machine learning.

Para tanto, foi desenvolvida uma EDA (exploratory data analysis) avaliando as principais estatíscas em série temporal. Ademais, os campos "no data" foram substituídos por valores numéricos, utilizando a mediana dos grupos ecômicos. Assim, foi previsto o crescimento do índice GDP de cada país nos anos de 2024-2028 com o modelo ARIMA, e posteriormente os resultados foram comparados com o previsto pelo Statistica. 

"In most years since 1980, global GDP growth has been relatively consistent, generally fluctuating between two and five percent growth from year to year. The most notable exceptions to this were during the Great Recession in 2009, and again in 2020 during the Covid-19 pandemic, where the global economy actually shrank in both of these years. As the world economy continues to deal with the economic impact of the pandemic, as well as the fallout from Russia's invasion of Ukraine in 2022, the future remains uncertain, however current estimates suggest that annual growth will return to steady figures of around 3 percent in 2028."

Aaron O'Neill, May 10, 2023


## Como executar o projeto ##
1. Colne o repositório.
2. Utilize o Colab ou jupyter nootebook, para rodar o projeto.
3. Baixe/atualize as bibibliotecas especificadas no requirements.txt.
4. Anexe/salve o arquivo **Continentes e sub_regiões.csv** ao Colab ou jupyter nootebook. Anexe/salve o arquivo **database.sxlsx** ao Google Drive e atualize o código abaixo que está no passo **'1. Importar as bibliotecas necessárias e ler dataframe'** com o link do seu arquivo no seu Google Drive:
   
   "from google.colab import drive

      drive.mount('/content/drive')"
    
O arquivo database.sxlsx contém a base de dados analisada, enquanto o arquivo Continentes e sub_regiões.csv contém os dados para imputação de novas colunas. 

6. Execute o arquivo 'desafio_ds_time_series_gdp.ipynb'.
   Esse arquivo contém todo o código do projeto: a EDA, substituição dos 'no data' e o código para previsão do GDP.

Depois de executar o projeto, serão extraídos dois arquivos:
1. forecast_results.xlsx: contém as previões e as métricas avaliadas.
2. predicted.csv: contém a imputação de dados que estavam como 'no data' e as previsões para os anos de 2024 a 2028.
   
-------------------


## Author

* [Luzia Neri](https://www.linkedin.com/in/luzia-neri-correia-souza-481141182//)

## Agradecimentos

* **Alisson Louly**
* **Ítalo Batista**
* **Léo Carlos Michel**.
* **Lucas Dias**
* **Lucas Sabino**

