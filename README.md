# Thesis-Science-and-Technology-Policy
Políticas Públicas en Salud sobre el Uso de Inteligencia Artificial: Producción de conocimiento en América del Sur

Programa hecho en python para la extracción y procesamiento de información sobre artículos científicos relacionados a políticas públicas en salud sobre el uso de Inteligencia Artificial dentro de América del Sur.

Se hace uso del API de ElSevier cuya información se encuentra en https://dev.elsevier.com/

La estructura del repositorio es la siguiente:
* **data**: Carpeta que contiene los resultados de las búsquedas realizadas en la base de datos Scopus
* **Extracción_y_Procesamiento_ElSevier_API.ipynb**: Implementación del programa de búsqueda de información usando el API de Scopus y técnicas de Data Mining (https://github.com/ilaurente/Thesis-Science-and-Technology-Policy/blob/main/Extracci%C3%B3n_y_Procesamiento_ElSevier_API.ipynb)
* **README.md**: Explicación de la estructura del presente repositorio
* **config.json**: Archivo que debe contener el **API Key** para el uso de los recursos del API y que por cuestiones de seguridad en el presente repositorio se ha borrado para que pueda ser insertado por el propio **API Key** de aquel que desee ejecutar el código o modificarlo.

Para el tratamiento de los datos se siguió una serie de [Pasos para el procesos de revisión de los documentos](Descripción_proceso_revisión_documentos_Scopus_WoS.pdf)

A continuación, se presentará el flujograma de selección y exclusión de los documentos en los respositorios de Scopus y Web Of Science
[Flujograma Scopus](Flujograma_selección_exclusión_Scopus.pdf) y [Flujograma Web Of Science](Flujograma_selección_exclusión_WoS.pdf)

Según el [agrupamiento realizado](Comparativo_artículos_Scopus_WoS_por_grupos), se pudo comparar que ambos repositorios presentan temas como COVID-19, enfermedades diversas y gestión/salud pública.

Las tablas de recopilación de información de Scopus y Web Of Science, según los criterios y parámetros finales de la tesis
[Tabla Scopus](Tablas_Anexos_Scopus.pdf) y 
[Tabla Web Of Science](Tablas_Anexos_Web_of_Science.pdf)
