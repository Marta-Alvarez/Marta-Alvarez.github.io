# 1. Análisis de Datos: Flujo de Gestión de Inventario (SQL Server & Power BI)

## 📌 Contexto del Proyecto

Este proyecto simula un escenario de **Administración y Análisis de Datos** habitual en cualquier entorno empresarial o local (Ej. gestión de un almacén municipal o un sistema de activos). El objetivo es transformar datos operativos en información procesable para optimizar la toma de decisiones.

## 🛠 Habilidades Técnicas Demostradas

* **SQL Server / Administración de BBDD:** Diseño de un esquema relacional (tablas de Hechos y Dimensiones), manejo de comandos DDL y DML, y optimización básica de consultas.
* **Business Intelligence (BI):** Creación de un modelo de datos robusto, definición de métricas clave (DAX) y visualización de resultados con Power BI.
* **Flujos ETL:** Simulación de la Extracción, Transformación y Carga de datos operativos a la base de datos SQL.

## 📁 Estructura y Código

| Ruta | Descripción |
| :--- | :--- |
| **`/SQL_Scripts/create_schema.sql`** | Código SQL (CREATE TABLE) para definir la estructura de la base de datos relacional (Ej: Tablas `Fact_Pedidos`, `Dim_Productos`, `Dim_Tiempo`). |
| **`/SQL_Scripts/queries.sql`** | Consultas SQL clave para extraer datos para el informe (Ej: Rotación de inventario, stock por proveedor). |
| **`/Assets/Dashboard_Final.png`** | Captura de pantalla del informe interactivo de Power BI. |

## 📊 Resultados y Visualización (Power BI)

[**[PON AQUÍ EL ENLACE AL INFORME PUBLICADO DE POWER BI]**]

* **Métricas Clave:** Se desarrollaron medidas **DAX** para calcular el Valor Total de Stock y la Tasa de Rotación de Inventario.
* **Impacto:** El informe permite segmentar el inventario por proveedor y ubicación geográfica, detectando cuellos de botella y oportunidades de optimización en la gestión de almacenes.

---
*Marta Álvarez | [[Marta-Alvarez.github.io]](https://github.com/Marta-Alvarez/Marta-Alvarez.github.io/tree/main)*
