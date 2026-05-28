# Proyecto Final: Machine Learning con PySpark y Docker

**Autor:** Camilo Andrés Velandia Suárez  
**Programa:** Estadística  
**Universidad:** Santo Tomás — 2026-I  
**Profesora:** Luz Adriana Gutiérrez Rodríguez  
**Curso:** Machine Learning con PySpark y Docker

---

## 1. Descripción del Problema

Este proyecto realiza un análisis 360° del mercado mayorista agropecuario colombiano mediante el dataset SIPSA de Precios Mayoristas (P-Mensual 2013-2017) del DANE, que comprende 281,386 registros de cotizaciones de productos de la canasta familiar. El objetivo es integrar técnicas de análisis exploratorio distribuido, aprendizaje automático supervisado y no supervisado, y procesamiento de lenguaje natural para comprender la estructura de precios, identificar patrones de volatilidad y explorar la capacidad predictiva de las descripciones textuales de los productos.

El análisis responde a preguntas clave para la política agroalimentaria: ¿cómo evolucionaron los precios mayoristas entre 2013 y 2017?, ¿qué factores determinan si un producto tendrá un precio alto o bajo?, y ¿es posible clasificar productos agropecuarios a partir de su descripción textual?

---

## 2. Datasets Utilizados

| Bloque | Dataset | Fuente Oficial | Registros | Periodo |
|--------|---------|---------------|-----------|---------|
| 1, 2, 3 (corpus) | SIPSA Precios Mayoristas P-Mensual 2013-2017 | [microdatos.dane.gov.co](https://microdatos.dane.gov.co/index.php/catalog/776) | 281,386 | 2013-2017 |

**Variables principales:** Fecha, Grupo (CARNES, FRUTAS, VERDURAS, etc.), Producto, Fuente (Ciudad, Lugar/Mercado), Precio promedio mayorista (COP).

---

## 3. Cómo Ejecutar

### Requisitos
- Python 3.10+
- PySpark 3.5.0
- Java 11 (OpenJDK)
- Dependencias: `pandas`, `matplotlib`, `seaborn`, `transformers`, `datasets`

### Entorno recomendado
**Google Colab** (entorno usado en desarrollo):
1. Abrir cada notebook desde GitHub con el botón "Open in Colab"
2. Ejecutar la celda de instalación de dependencias (Java + PySpark)
3. Subir el dataset SIPSA a Drive o al entorno de Colab

### Orden de ejecución
