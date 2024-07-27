<h2 align="center"><strong style="font-size: 1.2em;"> &nbsp; Análisis del Negocio de Airbnb</strong></h2>

<h2 align="center"><img src="Img/AirBnB.jpg" alt="AirBnB" style="width: 50%;"></h2>


## Presentación

En el presente proyecto se nos encomienda, como analistas de datos, investigar sobre el negocio de alquileres de corto plazo a través de Airbnb. Vamos a explorar las distintas dinámicas del mercado y generar estrategias de inversión personalizadas para maximizar el retorno de inversión.

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
- `calendar.csv`, `listings.csv`, `reviews.csv`: Datos utilizados para el análisis.
- `Dashboard.pbix`: Dashboard diseñado para la exposición de este trabajo.
- Carpeta `imgs`: Imágenes utilizadas para este README.

---