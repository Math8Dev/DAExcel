Add continent and flag to each country
    Upload data on "bar chart race" from https://app.flourish.studio/templates


1. Importando Dados da WEB (aba "time_series_covid19_deaths_glob"):

* Este [repo](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv) contem dados de mortes por COVID19 no Mundo.
* O import é feito através da escolha de dados RAW.
  * Definir o Header
  * Transformar colunas em linhas (wide to long)
  * Nomear as colunas
  * Definir o formato dos dados (textos, datas e valores numéricos)

2. Tratar os dados 
  * Agrupar dados por país pois alguns apresentam dados para diferentes regiões, padronizando a tabela (aba "dynamic")
  * Introdução manual de dados (aba "time_series_covid19_deaths_glob") para relacionar paises com seus continentes (e bandeiras)
  * Mescla dos dados (JOIN/MERGE) (na aba "flourish")

### Melhorias:

- Introduzir gráficos comparativos e outras vizualizações
- Fazer análises por continentes
- Identificar países com os piores e melhores quadros
