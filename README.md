# Adventure Works Analytics – Business Intelligence with Microsoft Fabric

## 📘 Descripción general
Proyecto de Inteligencia de Negocios **`end-to-end`** desarrollado en **`Microsoft Fabric`** ,siguiendo la arquitectura **`Medallion (Bronze–Silver–Gold)`**.  
El objetivo es integrar datos comerciales de *Adventure Works* provenientes de distintas fuentes para generar **insights gerenciales** que aporten a la toma de decisiones estratégicas.

---

## ⚙️ Requisitos técnicos
- **Plataforma:** Microsoft Fabric  
- **Fuentes de datos:**
  - Archivos **CSV** desde GitHub (Customers, Employees, Orders, Products, etc.)  
  - Base de datos **MySQL** (tabla *Stores*)  
  - Archivo **Excel** (presupuestos por tienda)
- **Transformaciones:** realizadas mediante **Dataflows Gen2** y **Notebooks PySpark**  
- **Carga:** archivos (capa Bronze) y tablas Delta(capas Silver y Gold) en Lakehouse. 
- **Visualización:** dashboards gerenciales en Power BI integrados en Fabric  

---

## 🏢 Resumen de la empresa – Adventure Works

**Adventure Works Cycles** es una compañía **`manufacturera y distribuidora`** de bicicletas de alto rendimiento, accesorios y componentes.  
La empresa opera a nivel internacional, con presencia en **América del Norte, Europa y Asia**, gestionando un modelo de negocio mixto que combina **ventas al por mayor** y **distribución minorista a través de tiendas asociadas**.

### 🌍 Contexto operativo
Adventure Works cuenta con una amplia red de **tiendas físicas y distribuidores**, además de un canal de ventas en línea.  
Su estructura organizativa incluye:
- Un equipo comercial dividido por **territorios** (país, región y ciudad).  
- Un catálogo de productos organizado jerárquicamente en **categorías y subcategorías**.  
- Relaciones estratégicas con **proveedores (vendors)** responsables del suministro de componentes y materias primas.  

### 💼 Objetivo comercial
El principal objetivo de Adventure Works es **optimizar sus procesos de ventas y distribución**, incrementando la rentabilidad y fortaleciendo la relación con clientes y proveedores.  
Para lograrlo, la compañía busca aprovechar la **analítica de datos** para:
- Medir el desempeño de tiendas y empleados.  
- Analizar la rentabilidad de productos y líneas de negocio.  
- Evaluar el cumplimiento de presupuestos y metas comerciales.  


---
## 🧱 Arquitectura del proyecto
<img src="ArquitecturaFabric.png" alt="ArquitecturaFabric">


## 🛢️ Modelo de datos:
<img src="esquemaestrella_ms_simplified.png" alt="ArquitecturaFabric">

---


## 🧠 Herramientas y tecnologías
- **Microsoft Fabric:** Lakehouse, Data Factory, Dataflows Gen2, Notebooks, Power BI  
- **Lenguajes:** PySpark, SQL, DAX  
- **Fuentes externas:** GitHub (CSV), MySQL, Excel  

---

## 📊 Dashboards gerenciales

| Dashboard | Objetivo | Principales KPIs |
|------------|-----------|------------------|
| **Ejecutivo** | Resumen de ventas, margen y cumplimiento de presupuesto | Ventas totales, % cumplimiento, margen global |
| **Productos y Categorías** | Análisis del portafolio de productos | Ventas por categoría, rentabilidad, top 10 productos |
| **Fuerza de Ventas y Tiendas** | Desempeño comercial por empleado y tienda | Ventas por vendedor, cumplimiento por tienda |
| **Financiero y Rentabilidad** | Análisis de costos, impuestos y márgenes | Margen bruto, costos totales, rentabilidad neta |

---
## 🏁 Resultados
- Proyecto end-to-end automatizado y documentado dentro de Fabric.  
- Modelo dimensional limpio y validado con auditoría.  
- Dashboards gerenciales con indicadores accionables.  
- Solución 100% implementada con **servicios gratuitos de Fabric**.  

---

## 👨‍💻 Autor
**Bryan Guapulema - 2025**  
---