# 📊 Laboratorio 3.1 de APIs para Localización de Rodajes

Bienvenido a este laboratorio en el cual trabajamos con **APIs** para la obtención de información geolocalizada que ayudará a la empresa **SetMagic Productions**, especializada en servicios para producciones audiovisuales. A lo largo de este proyecto, utilizamos herramientas avanzadas de scraping y APIs para ayudar a esta empresa a encontrar locaciones y atrezzo de manera eficiente.

## 🚀 Objetivos del Proyecto

1. Obtener información detallada de locaciones y servicios cercanos utilizando la **API de Foursquare**.
2. Implementar funciones que permitan filtrar la información geográfica por categorías relevantes para la empresa.
3. Analizar los datos obtenidos y almacenarlos en un formato reutilizable como **CSV**.

## 🛠️ Herramientas Utilizadas

- **Python**: Lenguaje principal para la interacción con la API y el manejo de datos.
- **Foursquare API**: Para la búsqueda de lugares cercanos basados en coordenadas geográficas.
- **Pandas**: Para la manipulación y limpieza de datos.
- **MongoDB**: Base de datos utilizada para almacenar datos relevantes sobre locaciones.
- **Beautiful Soup & Selenium**: Herramientas de web scraping que facilitan la extracción de datos adicionales.

## 📝 Instrucciones del Laboratorio

### Paso 1: Obtener las Credenciales de la API

- Crea una cuenta en [Foursquare](https://location.foursquare.com/developer/) para obtener una **API Key** y poder realizar las solicitudes.
- Revisa la documentación oficial para comprender cómo funciona la API.

### Paso 2: Definir Funciones para Búsquedas

- Desarrolla una función para realizar búsquedas de servicios cerca de cada municipio, basándote en coordenadas.
- Aplica filtros por categorías relevantes y distancias, como la proximidad a lugares de producción o servicios clave.

### Paso 3: Limpieza de la Información

- Analiza la estructura de los datos obtenidos de la API y selecciona únicamente los campos relevantes (nombre, dirección, coordenadas, etc.).
- Elimina duplicados y valores nulos para garantizar la calidad de los datos.

### Paso 4: Almacenamiento de los Datos

- Exporta los datos limpios y organizados en formato **CSV** para reutilizar en futuros análisis.

## 🎯 Resultados Esperados

Este laboratorio debe culminar con:

- Un conjunto de datos limpios y organizados sobre locaciones y servicios relevantes para producciones audiovisuales.
- Un análisis justificado de las mejores ubicaciones en base a la proximidad de servicios clave.
  
## 📂 Estructura del Proyecto

```
📁 Proyecto-APIs-Rodajes
│
├── 📄 README.md
├── 📄 notebook.ipynb   # Jupyter Notebook con todo el código y análisis
├── 📄 resultados.csv   # Archivo con los resultados limpios y listos para análisis
└── 📄 requirements.txt # Librerías necesarias para ejecutar el código
```

## 📚 Referencias

- [Documentación de Foursquare API](https://location.foursquare.com/developer/)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)

 
