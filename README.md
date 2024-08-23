# Caso de Análisis: Campaña de Marketing

**Proyecto Final para Data Science II de Coderhouse**  
**Lorenzo Guimaraes; Comisión 60895.**

## Introducción
Se seleccionó un dataset titulado "Marketing Campaign", el cual contiene información sobre la respuesta de clientes a diversas campañas de marketing de una empresa del sector venta y delivery de alimentos en Brasil.

## Objetivo
El objetivo de este proyecto es, a partir de este conjunto de datos, entrenar un modelo de predicción que nos permita visualizar con anticipación la posibilidad de respuesta de los clientes en una próxima campaña promocional.

## Hipótesis
A partir de un análisis de los datos y el desarrollo de un modelo predictivo ajustado al caso, se podrá inferir y clasificar qué tipos de cliente tienen mayor probabilidad de participar en una campaña promocional, aumentando así la precisión y rendimiento de la próxima campaña de marketing.

## Fuente y Autoría
- **Fuente de Datos:** [Marketing Campaign - Kaggle](https://www.kaggle.com)  
- **Referencia:** O. Parr-Rud. *Business Analytics Using SAS Enterprise Guide and SAS Enterprise Miner*. SAS Institute, 2014.

## Descripción de los Datos
| **Variable**           | **Descripción**                                                           |
|------------------------|---------------------------------------------------------------------------|
| `ID`                   | Identificador de cliente.                                                 |
| `Year_Birth`           | Año de nacimiento del cliente.                                            |
| `Education`            | Nivel de educación del cliente.                                           |
| `Marital_status`       | Estado civil del cliente.                                                 |
| `Income`               | Ingresos anuales del hogar del cliente.                                   |
| `Kidhome`              | Número de niños pequeños en el hogar del cliente.                         |
| `Teenhome`             | Número de adolescentes en el hogar del cliente.                           |
| `DtCustomer`           | Fecha de alta del cliente en la empresa.                                  |
| `Recency`              | Número de días desde la última compra.                                    |
| `MntFishProducts`      | Monto gastado en productos pesqueros en los últimos 2 años.               |
| `MntMeatProducts`      | Monto gastado en productos cárnicos en los últimos 2 años.                |
| `MntFruits`            | Monto gastado en productos frutícolas en los últimos 2 años.              |
| `MntSweetProducts`     | Monto gastado en productos dulces en los últimos 2 años.                  |
| `MntWines`             | Importe gastado en productos vitivinícolas en los últimos 2 años.         |
| `MntGoldProds`         | Monto gastado en productos de categoría "oro" en los últimos 2 años.      |
| `NumDealsPurchases`    | Número de compras realizadas con descuento.                               |
| `NumCatalogPurchases`  | Número de compras realizadas mediante un catálogo.                        |
| `NumStorePurchases`    | Número de compras realizadas en tiendas físicas.                          |
| `NumWebPurchases`      | Número de compras realizadas a través de la página web de la empresa.     |
| `NumWebVisitsMonth`    | Número de visitas al sitio web de la empresa en el último mes.            |
| `AcceptedCmp1`         | Si el cliente aceptó la oferta en la primera campaña (1 = Sí, 2 = No).    |
| `AcceptedCmp2`         | Si el cliente aceptó la oferta en la segunda campaña (1 = Sí, 2 = No).    |
| `AcceptedCmp3`         | Si el cliente aceptó la oferta en la tercera campaña (1 = Sí, 2 = No).    |
| `AcceptedCmp4`         | Si el cliente aceptó la oferta en la cuarta campaña (1 = Sí, 2 = No).     |
| `AcceptedCmp5`         | Si el cliente aceptó la oferta en la quinta campaña (1 = Sí, 2 = No).     |
| `Complain`             | Si el cliente hizo algún reclamo en los últimos 2 años (1 = Sí, 2 = No).  |
| `Response`             | Si el cliente aceptó la oferta en la ÚLTIMA campaña (1 = Sí, 2 = No).     |
