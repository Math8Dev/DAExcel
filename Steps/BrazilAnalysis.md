1. Importando Dados da WEB (aba "deaths-new"):

* Este [repo](https://github.com/elhenrico/covid19-Brazil-timeseries/blob/master/deaths-new.csv) contem dados de mortes por COVID19 no Brazil.
* O import é feito através da escolha de dados RAW.
  * Definir o Header
  * Transformar colunas em linhas (wide to long)
  * Nomear as colunas
  * Definir o formato dos dados (textos, datas e valores numéricos)

2. Agrupando dados por estado para entender a distruição estadual dos casos
  * Use de tabela dinâmica para agregar dados (aba "death-new_dynamic-states")
  * Visualização no formato de um mapa ("deaths-new_states")

3. Análise temporal dos casos no Brasil como um todo (aba "death-new_brazil")
  * Filtro dos dados referentes a todo o Brasil
  * Tratando os dados com uma média movel de 7 dias, para suavizar erros de medição devido principalmente aos finais de semana
  * Visualização dos dados temporais com um gráfico de linha (mortes ao longo do tempo), suavizado pela média móvel

4. Agrupando dados por região para entender a distruição percentual regional dos casos (abas "death-new_dynamic-regions" e "deaths-new_regions"),
utilizando uma escala de cor vermelha para destacar os piores cenários

5. Apresentação dos principais insights e conclusões na aba "dashboard"
