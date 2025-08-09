# Practicando Challenge Alura Store 2
 Segundo challenge para practicar con  Python en  Data Science: Challenge Alura Store
# Alura Store — Análisis Comparativo de Tiendas


Este repositorio contiene el análisis reproducible del *challenge* de Alura Store para comparar el desempeño de cuatro tiendas y fundamentar la decisión de venta.

## 🎯 Objetivo
- Integrar datos de las 4 tiendas.
- Calcular KPIs: **Facturación**, **#Ventas**, **Ticket Promedio**, **Calificación Promedio**, **Costo de Envío Promedio**.
- Identificar **Top/Bottom** categorías y productos.
- Entregar recomendación ejecutiva.

## 📁 Datos
Coloca los CSV en `data/` con los nombres:
- `tienda_1.csv` 
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`



## 📓 Notebook principal
- `AluraStoreLatam.ipynb` — contiene el flujo de análisis y visualizaciones.
- La acción de CI ejecuta el notebook y publica un **HTML** como artefacto.


---

## 📊 Ejemplos de gráficos e insights

**1️⃣ Facturación total por tienda**


**Insight:** La tienda con menor facturación y ticket promedio fue **tienda_4**, lo que la convierte en candidata para vender.

---

**2️⃣ Ticket promedio por tienda**

**Insight:** Las diferencias de ticket promedio son clave para explicar la brecha de ingresos entre tiendas.

---

**3️⃣ Costo de envío promedio**


**Insight:** Aunque **tienda_4** tiene el menor costo de envío, esto no compensa su bajo ticket promedio.

---

## 🚀 Instrucciones para ejecutar el notebook

### 1. Clonar el repositorio
```bash
git clone https://github.com/<usuario>/<repo>.git
cd <repo>


