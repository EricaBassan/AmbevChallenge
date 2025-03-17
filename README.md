# AmbevChallenge

Repositório criado para documentação do Dashboard Ambev-BEES.

<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>




## Sumário

- [Tables and data source](#Tables and data source)
- [Data Structure](#data Structure)
- [Medidas](#organização-do-banco-de-dados)
- [Gráficos](#características-clínicas-dos-sintomas)
- [Theme](#Theme)



# Tables and data source
The project contains 4 tables, in Excel Spreadsheet format.

**Table 1- Targets**  

**Tabele structure**  
| Column Name	 | Type | Description |
|:------------|:------------|:------------|
| user_id      | Numeric      | User Id (Primary Key)      |
| category	       | String       | Category of the Place      |
| city	       | String       | City of the user      |
| monthly revenue target       | Float      | Total Target for User    |

**Tabele Parameters**  
Number of Columns: 4  
Periodicity of processing: at user request 
Expected volume: to be defined  
Purge routine: to be defined   
Data period: from 2024-01-01


---
**Table 2- Users**

**Tabele structure**
| Column Name	 | Type | Description |
|:------------|:------------|:------------|
| user_id      | Numeric      | User Id (Primary Key)      |
| category	       | String       | Category of the Place      |
| city	       | String       | City of the user      |

**Tabele Parameters**
Number of Columns: 3  
Periodicity of processing: at user request 
Expected volume: to be defined  
Purge routine: to be defined   
Data period: from 2024-01-01


---
**Table 3- Orders**

**Tabele structure**
| Column Name	 | Type | Description |
|:------------|:------------|:------------|
| user_id      | Numeric      | Order Id       |
| order_date	       | Date       | Order date      |
| user_id 	       | Numeric      | User Id      |
| product_id       | Numeric       | Product Id      |
| revenue       | Float     | Order Revenue     |

**Tabele Parameters**
Number of Columns: 5  
Periodicity of processing: daily and continuous  
Expected volume: to be defined  
Purge routine: to be defined   
Data period: from 2024-01-01


---
**Table 4- Items**

**Tabele structure**
| Column Name	 | Type | Description |
|:------------|:------------|:------------|
| item_id     | Numeric      | Item Id (Primary Key)      |
| category	       | String       | Category of the beverage      |

**Tabele Parameters**
Number of Columns: 2  
Periodicity of processing: at user request  
Expected volume: to be defined  
Purge routine: to be defined   
Data period: from 2024-01-01


# Data Structure

The data structure followed the Snowflake format, so we had a fact table (Order), connected to the dimension tables.
Some of the dimension tables had a unique relationship between them.  

<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>

# Theme

To match the visual identity of the Bees company, we generated a color palette, which was used in the Dashboard theme.



**Font parameters**  
  General Font used: Segoe UI  
  Title Font: Segoe UI Semibold  
  Cards and KPIS Font: Segoe UI Semibold  
  Headers Font: Segoe UI Semibold   

**Page Parameters**
  Page Size  
  Cover: Type 16:9  
  Overall: Height (px): 1000 x Width (px) 1280  
  Users: Height (px): 1000 x Width (px) 1280  
  Items: Height (px): 1000 x Width (px) 1280  
  Forecast: Height (px): 800 x Width (px) 1280  

  **Cover WallPaper**
<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>

  **Background WallPaper**

<p align="center">
  <a href="">
    <img src="Imagens\covid_cover.jpg"
         alt="version">
  </a>

</p>
