# AmbevChallenge

Repositório criado para documentação do Dashboard Ambev-BEES.


<h1 align="center">Análise do PNAD COVID19 - IBGE </h1>


<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>




## Sumário

- [Tables and data source](#Tables and data source)
- [Estrtura de Dados](#estudo-pnad-covid-19-ibge)
- [Medidas](#organização-do-banco-de-dados)
- [Gráficos](#características-clínicas-dos-sintomas)
- [Theme](#Theme)



# Tables and data source
O projeto continha 4 tabelas, em formato Planilha de Excel.

Table 1- Targets



Table 2- Users

| Column Name	 | Type | Description |
|:------------|:------------|:------------|
| user_id      | Numeric      | User Id (Primary Key)      |
| category	       | String       | Category of the Place      |
| city	       | String       | City of the user      |

Column Name	     Type            Description
user_id          Numeric         User Id (Primary Key)
category	       String          Category of the Place
city             String          City of the user


Table 3- Orders
Column Name	     Type            Description
order_id	       Numeric         Order Id
order_date	     Date            Order date
user_id          Numeric         User Id
product_id	     Numeric         Product Id
revenue	         Float           Order Revenue


Table 4- Items
Column Name	     Type            Description
item_id	         Numeric         Item Id (Primary Key)
category	       String          Category of the beverage. 




# Theme

To match the visual identity of the Bees company, we generated a color palette, which was used in the Dashboard theme.

<h1 align="center">Theme Colors </h1>
<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>

  General Font used: Segoe UI
  Title Font: Segoe UI Semibold
  Cards and KPIS Font: Segoe UI Semibold
  Headers Font: Segoe UI Semibold

  Page Size
  Cover: Type 16:9
  Overall: Height (px): 1000 x Width (px) 1280
  Users: Height (px): 1000 x Width (px) 1280
  Items: Height (px): 1000 x Width (px) 1280
  Forecast: Height (px): 800 x Width (px) 1280

  Cover WallPaper
  <h1 align="center">Theme Colors </h1>
<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>

  Background WallPaper

   <h1 align="center">WallPaper </h1>
<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>
