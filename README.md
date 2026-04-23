# Retail Sales Optimization & Customer Analytics | AdventureWorks Case Study
### Stack:
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-Data_ETL-blue?style=for-the-badge)
![Power Pivot](https://img.shields.io/badge/Power_Pivot-Modeling-yellow?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-Analysis-orange?style=for-the-badge)

## 1. 📌Executive Summary 
Este análisis integral de ventas revela una transformación clave tras la diversificación de 2016, logrando un incremento de **$2.9M** en ingresos y triplicando la base de clientes con respecto al 2015. El estudio destaca una estructura de consumo muy definida: el **34.86%** de la población son clientes *"Bronce"* (ticket promedio $50), mientras que el segmento *"Diamante"*, aunque representa el **30.84%** de los clientes, constituye el motor financiero con un ticket promedio de $2,058, evidenciando una sólida base de compradores de alto valor.

Geográficamente, el modelo identifica una brecha de eficiencia: Australia genera el segundo mayor volumen de ingresos con la rentabilidad más baja, mientras que Canadá registra los ingresos más bajos pero alcanza la rentabilidad más alta. La estrategia final propone optimizar márgenes en mercados de alto volumen replicando la eficiencia canadiense y capitalizar el flujo masivo de clientes de accesorios (como Tires and Tubes y Bottles) para escalarlos hacia productos de alta gama, mejorando la rentabilidad global.
___________

## 2. 📊 Interactive Dashboard 
![Dashboard de Adventure Works](imagen/Dashboard.png)
*Nota. Este dashboard interactivo ofrece una visión técnica de ventas y rentabilidad mediante filtros por año y país. Destaca la segmentación dinámica, revelando que mientras el 34.86% de los clientes son 'Bronce' (consumo masivo), el 30.84% pertenece al segmento 'Diamante', el cual impulsa la utilidad con un ticket promedio de $2,058.*
_____________
## 3. 🛠️ Methodology & Data Architecture
Para este proyecto se aplicó un flujo de trabajo optimizado, priorizando el rendimiento del modelo y la integridad de los cálculos.

* **ETL & Data Cleaning (Power Query):** Importación de datos mediante "Carga de conexión" para optimizar el uso de memoria.
    * Transformación de tipos de datos, creación de columnas de tiempo (Mes y año) a partir de la fecha original y consolidación de identidades (concatenación de nombres).
    * Eliminación de columnas irrelevantes para reducir el peso del modelo y mejorar el performance.
      
* **Data Modeling (Star Schema):** Implementación de un **Modelo Estrella** en Power Pivot, estableciendo relaciones sólidas entre la *Fact Table* (`Sales`) y las *Dimension Tables* (`Customers`, `Products`, `Territories`, `Categories`,`Subcategories`). 
    * Configuración de integridad referencial para garantizar que todas las visualizaciones respondan de forma sincronizada.
      
* **DAX Measures:** Desarrollo de medidas para **KPIs** base: Ingresos Totales, Margen, % Utilidad y Ticket Promedio.
    * **Lógica de Negocio:** Implementación de segmentación dinámica para categorizar a los 17,416 clientes según su volumen de consumo (Bronce, Plata, Oro y Diamante).
      
* **UI Design & Analytics:** Diseño de interfaz profesional con una paleta de colores armonizada para facilitar la lectura de métricas críticas.
    * Uso de segmentadores dinámicos para un análisis interactivo por tiempo y región.
 
![Data Model Architecture](imagen/Star_schema.png)
*Figura 1: Arquitectura de Modelo Estrella implementada en Power Pivot.*
____________

## 4. 💡Key Insights

