# 🎬 **ShowMatch** 🎬

<img src="https://github.com/No-Country-simulation/S20-15-data/blob/main/img/Portada.webp" alt="Portada" width="600"/>

### 📝 **Índice**:

- [**Introducción**](#introducción)
- [**Objetivo**](#objetivo)
- [**Metodología**](#metodología)
- [**Datos**](#datos)
- [**Visualización en Streamlit**](#visualización-en-streamlit)
- [**Herramientas utilizadas en el proyecto**](#herramientas-utilizadas-en-el-proyecto)
- [**Contacto**](#contacto)

---

### 🎬 **Introducción** 🎬  
En el mundo actual, donde el contenido es abundante, muchas personas enfrentan el problema de pasar demasiado tiempo eligiendo qué ver. Los buscadores de las plataformas de streaming suelen ser poco flexibles, lo que dificulta encontrar contenido específico, como series de un género particular o con un actor favorito.

Este proyecto busca resolver ese problema mediante un recomendador que permite realizar búsquedas detalladas usando múltiples filtros combinados, ayudando a los usuarios a encontrar contenido de manera rápida y eficiente.

---

### 🎯 **Objetivo** 🎯  
Nuestro recomendador de series está diseñado para:  

- **Reducir el tiempo de búsqueda**: Ofrecer resultados basados en filtros avanzados y personalizados.  
- **Filtrado detallado**: Posibilitar la búsqueda por género, título, sinopsis, red de transmisión y actores.  
- **Interfaz amigable**: Presentar resultados claros y fáciles de explorar.

Este proyecto está dirigido a:  
- **Usuarios comunes**: Que desean optimizar su tiempo al buscar contenido de su interés.  
- **Amantes del cine y las series**: Que quieren descubrir contenido basado en sus preferencias.  

---

### 🔍 **Metodología** 🔍  
El proyecto sigue un flujo de trabajo estructurado en tres fases principales:

1. **Gestión de datos**:  
   Los datos de series se almacenan en un lago de datos en **Microsoft Fabric**.

2. **Transformación y limpieza**:  
   Procesamos los datos utilizando **Python** para asegurarnos de que estén completos y en el formato adecuado.

3. **Interfaz interactiva**:  
   Desarrollamos una aplicación web usando **Streamlit**, permitiendo a los usuarios realizar búsquedas detalladas mediante filtros personalizados.

---

### 📂 **Datos** 📂  
Los datos utilizados provienen del conjunto de datos de **TMDB**. Incluyen información detallada sobre series de distintas plataformas de streaming, como:  
- Nombre de la serie  
- Género(s)  
- Red de transmisión  


---

### 🌐 **Visualización en Streamlit** 🌐  
La aplicación tiene una estructura simple pero efectiva:  
- **Página de búsqueda**: Los usuarios pueden ingresar diferentes filtros como género, título, sinopsis o red de transmisión.  
- **Resultados**: Los resultados se muestran en tarjetas visuales con imágenes y una descripción rápida.  
- **Detalles de la serie**: Al seleccionar una serie, se despliega información más detallada, como calificaciones, temporadas y sinopsis.

---

## 🛠️ **Herramientas utilizadas en el proyecto** 🛠️  

| Herramienta          | Logo | Descripción                                                                                 |
|----------------------|------|---------------------------------------------------------------------------------------------|
| **Microsoft Fabric** | <img src="https://debruyn.dev/2023/all-microsoft-fabric-icons-for-diagramming-old-version/Fabric_final_x256.png" width="100" height="100"> | Plataforma para la gestión y procesamiento de datos.                                     |
| **Streamlit**        | <img src="https://streamlit.io/images/brand/streamlit-mark-color.svg" width="100" height="100">      | Herramienta para crear la interfaz de usuario.                                           |
| **Python**           | <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="100" height="100"> | Lenguaje utilizado para la limpieza y transformación de datos.                           |
| **Google Drive**     | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Google_Drive_icon_%282020%29.svg/1024px-Google_Drive_icon_%282020%29.svg.png?20221103153031" width="100" height="100"> | Almacenamiento y sincronización de archivos.                                              |

---

### 📬 **Contacto** 📬  

| **Integrantes**       |                                    | **Rol**                             | **GitHub**                             | **LinkedIn**                           |
|-----------------------|------------------------------------|--------------------------------------|-----------------------------------------|-----------------------------------------|
| Miguel Ismerio        | <img src="https://github.com/No-Country-simulation/s18-18-t-data-bi/blob/main/img/Miguel.png" width="100" height="100" style="border-radius: 50%;"> | Data Scientist / Project Manager     | [GitHub](https://github.com/mikeismerio) | [LinkedIn](https://www.linkedin.com/in/miguel-ismerio/) |
| Sergio González         | <img src="https://github.com/No-Country-simulation/S20-15-data/blob/main/img/Sergio.jpeg" width="100" height="100" style="border-radius: 50%;"> | Frontend Developer                  | [GitHub](https://github.com/gonzalezrivera)                              | [LinkedIn](https://www.linkedin.com/in/gonzalez-rivera/)                            |

---

✨ **¡Gracias por explorar nuestro proyecto!** 🎥🍿
