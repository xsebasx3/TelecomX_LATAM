# 📊 Análisis de Evasión de Clientes – TelecomX

Este proyecto analiza datos de clientes de una empresa de telecomunicaciones 
para identificar patrones relacionados con la evasión de clientes (*Churn*).  
El objetivo es comprender qué factores influyen en la cancelación del servicio 
y proponer acciones estratégicas para reducirla.

---

## 📌 Objetivos
- Analizar la distribución de clientes que se dieron de baja vs. los que permanecen.
- Identificar características demográficas, contractuales y de consumo asociadas al *Churn*.
- Visualizar patrones utilizando gráficos estadísticos.
- Generar un informe final con conclusiones y recomendaciones.

---

## 🗂️ Estructura del proyecto

Owner avatar
telecomx_latam/
├── TelecomX_LATAM.ipynb
├── challenge2-data-science-LATAM-main/ 
│   ├── TelecomX_Data.json
│   ├── TelecomX_diccionario.md
│   ├── TelecomX_LATAM.ipynb
├── README.md 
└── LICENSE 

---

## 🛠️ Instalación y requisitos
Este proyecto utiliza Python 3.x y las siguientes librerías:

- **Pandas**: Manipulación y análisis de datos.
- **NumPy**: Operaciones numéricas.
- **Matplotlib** y **Seaborn**: Visualización de datos.

Para instalar las dependencias:

```bash
pip install pandas numpy matplotlib seaborn
```
---

## ▶️ Ejecución
1. Clona este repositorio:

   ```bash
   git clone git@github.com:xsebasx3/TelecomX_LATAM.git
   ```
   o descarga los archivos.
3. Abre el notebook TelecomX_LATAM.ipynb en Jupyter Notebook o Google Colab [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/?hl=es-ES 
)
4. Ejecuta todas las celdas en orden para:
     - Cargar y limpiar los datos.
     - Realizar análisis exploratorio.
     - Generar visualizaciones.
     - Obtener el informe final con conclusiones y recomendaciones.

---

## 📊 Metodología
El análisis se realizó en varias etapas:
  1. Carga de datos desde archivo JSON.
  2. Limpieza y tratamiento:
     - Eliminación de espacios en blanco en categorías.
     - Conversión de columnas numéricas mal tipadas.
     - Eliminación de valores nulos en campos clave.
  3. Análisis exploratorio:
      - Distribución de Churn.
      - Comparación por variables categóricas y numéricas.
  4. Visualizaciones con Matplotlib y Seaborn.
  5. Informe final con hallazgos y recomendaciones.

---

## 📌 Resultados destacados
  - Los clientes con contrato mensual y pago electrónico presentan mayor Churn.
  - Clientes con menor antigüedad y menor gasto total tienden a abandonar más.
  - Los primeros meses de relación son críticos para la retención.

---

## 🛠️ Posibles problemas y soluciones
   - Error al convertir account.Charges.Total a numérico: 
       Asegurarse de limpiar valores vacíos y espacios antes de la conversión.
   - Gráficos que no se muestran en PDF exportado desde Colab:
        Usar la opción Archivo → Imprimir → Guardar como PDF.

---

## 📜 Licencia
   Este proyecto se distribuye bajo licencia MIT. Puedes usarlo, 
   modificarlo y distribuirlo libremente.

---

