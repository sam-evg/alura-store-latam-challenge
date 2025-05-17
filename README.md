# 📊 Análisis de Desempeño de Tiendas - Proyecto Data Science

Este proyecto tiene como objetivo analizar el desempeño de cuatro tiendas ficticias mediante el uso de Python y bibliotecas de análisis de datos. A través de métricas clave como ingresos, calificaciones de clientes, categorías de productos, costos de envío y geolocalización, se busca identificar cuál de las tiendas debería ser vendida o reestructurada.

---

## 🧠 Objetivo

Ayudar al Sr. Juan, propietario de cuatro tiendas, a tomar una decisión informada sobre cuál de sus tiendas tiene el peor rendimiento y debería considerar vender, basándose en datos reales del negocio.

---

## 📁 Estructura del Proyecto

├── AluraStoreLatam.ipynb  # Notebook principal con todos los análisis y gráficos
├── README.md               # Este archivo
├── /graficos               # Carpeta opcional para guardar imágenes de los gráficos

📊 Tecnologías y Herramientas
Lenguaje de programación: Python
Librerías principales:
pandas para procesamiento y análisis de datos
matplotlib para la visualización de datos
numpy para manipulaciones matemáticas

## 🚀 Instalación y Uso
1. Clonar el repositorio
git clone [https://github.com/sam-evg/alura-store-latam-challenge.git]
cd alura-store-latam-challenge
2. Crear y activar un entorno virtual (opcional pero recomendado)
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
3. Instalar dependencias
pip install -r requirements.txt
4. Expplorar Notebooks
Accede a la carpeta notebooks/ y abre los archivos .ipynb para revisar el análisis realizado.

## 📈Resultados destacados
Cálculo de ingresos totales por tienda.

Análisis de las categorías más vendidas.

Evaluación de la eficiencia en función de ingresos, costos y satisfacción del cliente.

Visualización de los datos con gráficos de barras, pastel y dispersión.

## 📌 Contexto y Objetivo
La cadena Alura Store cuenta con cuatro sucursales y el Sr. Juan desea decidir cuál de ellas vender para lanzar un nuevo emprendimiento.
Objetivo: identificar, con base en datos de ventas y reseñas, la tienda menos eficiente y fundamentar una recomendación clara.

## 📋 Metodología
Carga y preparación de datos

Se importaron los archivos CSV de cada tienda usando Pandas.
Se validó integridad, consistencia de tipos y ausencia de valores faltantes.
Cálculo de métricas clave

Ingresos totales por tienda.
Número de ventas agrupado por categoría.
Promedio de calificaciones de clientes.
Top y bottom de productos según volumen de ventas.
Incremeneto y decremento de ingresos a lo largo del tiempo.
Costo promedio de envío.
Visualización

Gráficos (barras, pastel, dispersión, mapas de densisidad) implementados con Matplotlib y plotly para ilustrar comparaciones y tendencias.
