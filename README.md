<h2 align="center"><strong style="font-size: 1.2em;"> &nbsp; Análisis del Negocio de Airbnb</strong></h2>

<h2 align="center"><img src="Img/AirBnB.jpg" alt="AirBnB" style="width: 50%;"></h2>


## Introducción

Airbnb es una plataforma en línea que permite a las personas alquilar sus propiedades o habitaciones a corto plazo a huéspedes de todo el mundo. Desde su creación, ha revolucionado la industria de la hospitalidad al ofrecer una alternativa a los hoteles tradicionales y proporcionar una fuente adicional de ingresos para los anfitriones.

El objetivo de este proyecto es realizar un análisis exhaustivo de los datos de Airbnb para identificar oportunidades de inversión. Este análisis permitirá comprender mejor las tendencias del mercado, los factores que influyen en el éxito de las propiedades y las áreas con mayor potencial de rentabilidad.

Para lograrlo, se utilizarán los datos proporcionados por Airbnb, los cuales serán sometidos a un proceso de extracción, transformación y carga (ETL) para garantizar su integridad y calidad. Posteriormente, se llevará a cabo un análisis exploratorio de datos (EDA) utilizando Python, con el fin de descubrir patrones, relaciones y características clave de los datos.

El análisis se enfocará en varios aspectos, como la distribución geográfica de las propiedades, los precios, la ocupación, las valoraciones de los huéspedes y otros factores relevantes que puedan influir en la toma de decisiones de inversión. Los resultados se presentarán de manera clara y concisa para facilitar la comprensión y apoyar la toma de decisiones informadas.


### Análisis Descriptivo

- **Descripción del Negocio de Airbnb**: A través de los datasets, se puede observar la distribución de precios, ocupación y reviews de las propiedades.
- **Mejores Formas de Invertir**: Se identificaron propiedades con alta demanda y buena rentabilidad, recomendando inversiones en propiedades con características específicas como ubicación y tipo de vivienda.
- **Comparación con Otras Inversiones**: Airbnb ofrece una alternativa de inversión competitiva, con potenciales altos retornos debido a la demanda creciente de alquileres a corto plazo.

### Recomendaciones de Inversión

1. **Ubicación**: Se recomienda invertir en áreas urbanas con alta demanda turística.
2. **Tipo de Propiedad**: Propiedades pequeñas y bien ubicadas tienden a tener mejor desempeño.
3. **Estrategias de Inversión**: Considerar diversificación en diferentes ubicaciones y tipos de propiedades para mitigar riesgos.

## Tecnología Utilizada

- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI

## Recursos Utilizados

- `calendar.csv`: Incluye datos de ocupación, precio, etc.
- `listings.csv`: Detalle de cada operación de listing, incluyendo datos descriptivos de la vivienda (ambientes, host, noches mínimas y máximas, cantidad de reviews).
- `reviews.csv`: Datos de review de los usuarios.

## EDA (Exploratory Data Analysis)

El análisis exploratorio de los datos se realizó en un notebook de Python, documentando cada paso con claridad y conclusiones correspondientes en cada gráfico empleado. Entre los aspectos destacados se encuentran la búsqueda de valores faltantes, valores atípicos/extremos u outliers y registros duplicados, así como la utilización de gráficos coherentes según la tipología de variable.

## Dashboard

Se diseñó un dashboard funcional y coherente con el storytelling del proyecto. El dashboard incluye filtros que permiten explorar detalladamente los datos, facilitando la interpretación de la información y su análisis de manera interactiva.

## Elementos del Repositorio

- `EDA.ipynb`: Análisis exploratorio de los datos.
- `Dashboard.pbix`: Dashboard diseñado para la exposición de este trabajo.
- Carpeta `imgs`: Imágenes utilizadas para este README.


<div style="text-align: center;">
  <h2>Autor</h2>
  <img src="https://avatars.githubusercontent.com/u/166779106?v=4" alt="Facundo Corvalan" style="width: 150px; height: 150px; border-radius: 50%;"><br>
  <strong>Facundo Corvalan</strong><br>
  <a href="https://www.linkedin.com/in/facundo-corvalan" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" style="width: 100px;">
  </a>
  <a href="mailto:adrian.facundo2001@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white" alt="Gmail" style="width: 80px;">
  </a>
</div>
