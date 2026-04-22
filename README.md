# Retail Sales Optimization & Customer Analytics | AdventureWorks Case Study

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-Data_ETL-blue?style=for-the-badge)
![Power Pivot](https://img.shields.io/badge/Power_Pivot-Modeling-yellow?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-Analysis-orange?style=for-the-badge)

## 1. 📈Executive Summary 
Este análisis integral de ventas y segmentación de clientes revela una *transformación clave* en el modelo de negocio tras la diversificación de categorías en el 2016, logrando un incremento de **$2.9M** en ventas y triplicando la base de clientes, con respecto al 2015. El estudio destaca un contraste crítico de valor: mientras el volumen masivo proviene de clientes *"Bronce"* (ticket promedio $50), el motor de ingresos reside en el segmento *"Diamante"*, con un ticket promedio de $2,058.

En términos geográficos, el análisis identifica una brecha de eficiencia al comparar los polos opuestos del mercado: *Australia*, que genera el segundo mayor volumen de ingresos a nivel global, opera con la rentabilidad más baja del modelo; por el contrario, *Canadá* registra los ingresos más bajos pero alcanza la rentabilidad más alta. Esta disparidad sugiere una oportunidad para optimizar los márgenes en mercados de alto volumen replicando las políticas de eficiencia canadienses. La estrategia final propone **capitalizar el flujo masivo de nuevos clientes de accesorios** para convertirlos en compradores de productos de alta gama (bicicletas), escalando la rentabilidad en las regiones de mayor escala.
_______

## 2. 🚩 Problem Statement & Objectives
**The Problem**

AdventureWorks enfrentaba una dispersión de datos que impedía conocer la rentabilidad real por región y el perfil exacto de sus consumidores lo que dificultaba la toma de decisiones informada. Los desafíos principales eran:
- *Dispersión de Datos:* Incapacidad para identificar con precisión qué productos, mercados o territorios eran realmente los más rentables.
- *Fluctuaciones sin explicación:* Se detectaron variaciones en las ventas a lo largo del tiempo, pero no se comprendían las causas ni el desempeño histórico real.
- *Desconocimiento del Cliente:* No se tenía claridad sobre el tamaño de la base de clientes ni sobre su comportamiento de compra, lo que impedía diferenciar a los segmentos más valiosos de los ocasionales.

**Project Objectives**

- **1. Centralize & Clean Data:** Unificar los datos dispersos en una sola fuente de verdad utilizando Power Query para facilitar el análisis.
- **2. Performance Tracking:** Desarrollar visualizaciones que permitan entender la evolución de las ventas e identificar tendencias y causas de fluctuación.
- **3. Customer Profiling:** Implementar una lógica dinámica en DAX para conocer cuántos clientes existen y categorizarlos según su comportamiento de compra (Diamante, Oro, Plata, Bronce).
- **4.Strategic Insights:** Crear un dashboard interactivo que permita visualizar qué territorios y productos generan el mayor impacto financiero para la empresa.







## 3. 📊 Dashboard Interactivo
![Dashboard de Adventure Works](imagen/Adventure_dashboard.png)
*Nota. Este dashboard interactivo permite filtrar por año y país, además contiene KPIs importantes de venta, utilidad, órdenes y clientes. Se desataca tambien la segmentación dinámica de clientes donde se observa la diferencia entre el volumen de clientes "Bronce" con la alta rentabilidad del segmento "Diamante".*
