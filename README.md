# 🚀 Adventure Works Analytics – Business Intelligence with Microsoft Fabric

## 📘 Descripción general
Proyecto de Inteligencia de Negocios **end-to-end** desarrollado en **Microsoft Fabric**, siguiendo la arquitectura **Medallion (Bronze–Silver–Gold)**.  
El objetivo es integrar datos comerciales de *Adventure Works* provenientes de múltiples fuentes para generar **insights gerenciales** sobre ventas, rentabilidad y desempeño comercial.

---

## ⚙️ Requisitos técnicos
- **Plataforma:** Microsoft Fabric  
- **Fuentes de datos:**
  - Archivos **CSV** desde GitHub (Customers, Employees, Orders, Products, etc.)  
  - Base de datos **MySQL** (tabla *Stores*)  
  - Archivo **Excel** (presupuestos por tienda)
- **Transformaciones:** realizadas mediante **Dataflows Gen2** y **Notebooks PySpark**  
- **Carga:** archivos (capa Bronze) y tablas Delta en Lakehouse (capas Silver y Gold)  
- **Visualización:** dashboards gerenciales en Power BI integrados en Fabric  

---

## 🧱 Arquitectura del proyecto
**Flujo de datos:** Ingesta → Bronze → Silver → Gold → Dashboards  

**Modelo de datos:** esquema estrella con una tabla de hechos y ocho dimensiones:  
- **FactSales** (tabla de hechos)  
- **DimCustomer**, **DimEmployee**, **DimProduct**, **DimProductCategory**, **DimProductSubCategory**, **DimVendor**, **DimStore**, **DimFecha**  

---

## 📊 Dashboards gerenciales

| Dashboard | Objetivo | Principales KPIs |
|------------|-----------|------------------|
| **Ejecutivo** | Resumen de ventas, margen y cumplimiento de presupuesto | Ventas totales, % cumplimiento, margen global |
| **Productos y Categorías** | Análisis del portafolio de productos | Ventas por categoría, rentabilidad, top 10 productos |
| **Fuerza de Ventas y Tiendas** | Desempeño comercial por empleado y tienda | Ventas por vendedor, cumplimiento por tienda |
| **Financiero y Rentabilidad** | Análisis de costos, impuestos y márgenes | Margen bruto, costos totales, rentabilidad neta |

---

## 🧠 Herramientas y tecnologías
- **Microsoft Fabric:** Lakehouse, Data Factory, Dataflows Gen2, Notebooks, Power BI  
- **Lenguajes:** PySpark, SQL, DAX  
- **Fuentes externas:** GitHub (CSV), MySQL, Excel  

---

## 🏁 Resultados
- ETL automatizado y documentado dentro de Fabric.  
- Modelo dimensional limpio y validado con auditoría.  
- Dashboards gerenciales con indicadores accionables.  
- Solución 100% implementada con **servicios gratuitos de Fabric**.  

---

## 👨‍💻 Autor
**Bryan Guapulema**  
Proyecto académico – 2025  
