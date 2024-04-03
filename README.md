# Indicadores-Historicos-Sector-Microfinanciero
El objetivo del proyecto es recopilar la información histórica de saldos de balance de los últimos 12 meses de las entidades del sector microfinancero, disponibles en la página de la Superintendencia Financiera

# Problemática
Inexistencia de información del sector microfinanciero agrupada por entidad y periodo, que permita visualizar graficamente los indicadores financieros de relevancia para la gestión de riesgo de crédito:
-	Cartera vigente
-	Cartera vencida
-	Deterioro de cartera
-	ICV - Indicador de cartera vencida
-	Cartera en riesgo
-	ICR - Indicador de cartera en riesgo
-	Pérdida tolerada
-	Coberturas de cartera vencida y en riesgo

<img width="458" alt="image" src="https://github.com/amachadouao/Indicadores-Historicos-Sector-Microfinanciero/assets/165512267/c64ea186-e303-4e02-beff-f6db7891dfd0">     <img width="537" alt="image" src="https://github.com/amachadouao/Indicadores-Historicos-Sector-Microfinanciero/assets/165512267/3eddbabf-7691-44a0-bc9b-c0bc113f597a">

# Contenido del repositorio:
Base_historica_sector_financiero

Diccionario_de_datos

Notebook de limpieza y preparación de datos

Notebook de manipulación de datos

Base de datos data_microfinanciera

df_microfinancieras

# Cantidad y naturaleza de los datos:

La información inicial esta disponible en el siguiente link: 
https://www.superfinanciera.gov.co/publicaciones/10084493/informes-y-cifrascifrasestablecimientos-de-creditoinformacion-periodicamensualindicadores-gerenciales-niif-10084493/

La base de datos contiene 32 columnas y 46.140 filas, donde la primera columna corresponde al AÑOMES, las siguientes dos columnas, RUBRO Y CONCEPTO, almacenan las variables disponibles, y las 29 columnas restantes contiene la información expresada en millones, de cada una de las entidades financieras, lo que da un total de registros de 1.338.060.

La base dispone de 3.845 variables, de las cuales se seleccionaron 81 variables que están relacionadas con la gestión de riesgo de crédito, las cuales se describen en el diccionario de datos.

# Conclusiones y generación de valor:
La base de datos contiene una gran cantidad de variables que pueden utilizarse para el calculo de diversos indicadores, que podrían ser de gran utilidad para las entidades microfinancieras en sus actividades de seguimiento al desempeño comercial y financiero.
La base de datos permite actualizar la información conforme a lo repartado en la página de la Superfinanciera, obteniendo los indicadores más recientes.
La generación de los indicadores no solo se puede realizar para las entidades microfinanciero, sino también para todas las que pertencen al sector financiero.

El valor generado con este proyecto es el de poder gestionar la información recopilada de manera automática, permitiendo visualizar gráficamente los datos de variables y diversos indicadores que son relevantes en la toma de decisiones en la gestión del riesgo de crédito; realizar comparativos entres los pares más representativos, observar tendencias, comportamientos y oportunidades.

<img width="503" alt="image" src="https://github.com/amachadouao/Indicadores-Historicos-Sector-Microfinanciero/assets/165512267/7e90a3be-15c1-45b3-a791-2e856641c824">  <img width="502" alt="image" src="https://github.com/amachadouao/Indicadores-Historicos-Sector-Microfinanciero/assets/165512267/81f435bb-f0cd-40c5-b6b1-e4f414e20468">

