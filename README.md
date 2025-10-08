# Adventure Works Analytics – Business Intelligence with Microsoft Fabric

## 📘 Descripción general
Proyecto de Inteligencia de Negocios **`end-to-end`** desarrollado en **`Microsoft Fabric`** ,siguiendo la arquitectura **`Medallion (Bronze–Silver–Gold)`**.  
El objetivo es integrar datos comerciales de *Adventure Works* provenientes de distintas fuentes para generar **insights gerenciales** que aporten a la toma de decisiones estratégicas.

---

## ⚙️ Requisitos técnicos
- **Plataforma:** Microsoft Fabric  
- **Fuentes de datos:**
  - **API**: archivos CSV consumidosdesde GitHub (Customers, Employees, Orders, Products, etc.)  
  - **Base de datos MySQL**: tabla *Stores*
  - **Archivo Excel**: presupuestos por tienda (storesBudget)
- **Transformaciones:** realizadas mediante **Dataflows Gen2** y **Notebooks PySpark**  
- **Carga:** archivos (capa Bronze) y tablas Delta(capas Silver y Gold) en Lakehouse dentro de **`OneLake`**. 
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
<img src="esquemaestrella_ms_simplified.png" alt="Esquema estrella">

---


## 🧠 Herramientas y tecnologías
- **Microsoft Fabric:** Lakehouse, Data Factory, Dataflows Gen2, Notebooks, Power BI  
- **Lenguajes:** PySpark, SQL, DAX  
- **Fuentes externas:** GitHub (CSV), MySQL, Excel  

---

## 📊 Dashboards gerenciales

- Dashboard #1: Menú/Inicio

<img src="Dashboard_Menu.PNG" alt="Dashboard_Menu">

- Dashboard #2: Resumen Ejecutivo

<img src="Dashboard_ResumenEjecutivo.PNG" alt="Dashboard_Menu">

- Dashboard #3: Detalle Producto

<img src="Dashboard_Productos.PNG" alt="Dashboard_Menu">

- Dashboard #4: Detalle Tienda

<img src="Dashboard_Tiendas.PNG" alt="Dashboard_Menu">

---
## 🏁 Resultados

- Enlace de acceso al informe

<a href='https://app.fabric.microsoft.com/groups/4ed7945f-ed35-4eb6-9deb-814d2fe747e0/reports/f9794bec-3b14-4099-8f5c-dff26d2b3095?ctid=3d285e75-2402-401a-aa82-b00278f48a41&pbi_source=linkShare'>
https://app.fabric.microsoft.com/groups/4ed7945f-ed35-4eb6-9deb-814d2fe747e0/reports/f9794bec-3b14-4099-8f5c-dff26d2b3095?ctid=3d285e75-2402-401a-aa82-b00278f48a41&pbi_source=linkShare
</a>

- QR de acceso al informe

<img src="QR_BG_AdventureWorks_Report.jpg" alt="https://app.fabric.microsoft.com/groups/4ed7945f-ed35-4eb6-9deb-814d2fe747e0/reports/f9794bec-3b14-4099-8f5c-dff26d2b3095?ctid=3d285e75-2402-401a-aa82-b00278f48a41&pbi_source=linkShare
">

---

## 👨‍💻 Autor
**Bryan Guapulema - 2025**  
---