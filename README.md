# Consumo de sustancias y factores sociodemográficos y de personalidad

Proyecto de análisis exploratorio de datos para la asignatura AED del Máster en Ciencia de Datos de la Universitat de València, realizado con R y R Markdown.

El estudio explora las características de la muestra y las asociaciones del consumo de sustancias con el perfil sociodemográfico, los rasgos psicológicos y el policonsumo. Los resultados son descriptivos y no permiten establecer relaciones causales.

## Datos y fuentes

Se utiliza el conjunto [Drug Consumption (Quantified)](https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified), del repositorio UCI, con 1.885 participantes y 32 columnas. Incluye características sociodemográficas, puntuaciones psicológicas y categorías temporales del último consumo declarado.

Para agrupar las sustancias se emplean las siete familias de *The Drugs Wheel*, recogidas en una [publicación del Gobierno de Escocia](https://www.gov.scot/publications/understanding-patterns-use-motives-harms-new-psychoactive-substances-scotland/pages/3/), con las correspondencias y excepciones descritas en el informe.

## Contenido del análisis

- Descripción, comprobación de integridad y preprocesamiento de las variables.
- Caracterización univariante de la muestra y del consumo.
- Revisión de la fiabilidad de las respuestas y detección de valores atípicos.
- Asociaciones entre rasgos psicológicos y último consumo de cada sustancia.
- Comparaciones del consumo reciente según edad, género y nivel educativo.
- Relación de la impulsividad y la búsqueda de sensaciones con el policonsumo.

El consumo reciente corresponde a los últimos doce meses. El policonsumo se estudia mediante el número de sustancias distintas consumidas durante ese periodo, con las exclusiones indicadas en el informe; no implica consumo simultáneo.

## Estructura del repositorio

| Archivo o carpeta | Contenido |
| --- | --- |
| `ProyectoAED.Rmd` | Código, texto y representaciones del informe. |
| `Definitions/` | Plantilla LaTeX personalizada, clase MDPI y recursos necesarios para generar el PDF. |
| `README.md` | Descripción del proyecto e instrucciones de ejecución. |

La carpeta `data/` se crea al ejecutar el documento. El PDF y otros archivos de compilación se generan localmente y están incluidos en las reglas de exclusión de Git.

## Autores

- Pau Bover Femenias.
- Francesc Oliver Catany.
- Marino Fernandez Perez.
