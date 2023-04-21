# Proyecto Curso Programación

*Indice de Marginalización México*

## Descripción

El presente repositorio contiene un notebook exploratorio referente a los indicadores más importantes para la medición multidimensional de la pobreza (indice de marginalización) en México.

**Nota**: El Consejo Nacional de Población (CONAPO) del gobierno mexicano, realiza cada 5 años un análisis sobre un estudio multidimensional de la pobreza y establece un índice de marginación.

## Contenido del Notebook

El notebook ('notebook_1.ipynb`) contiene lo siguiente:

1. Lectura del archivo de Base de Datos por Municipio 2020 del índice de marginación desde la página de descargas del gobierno federal mexicano en un dataframe. 

2. Descripción del DataFrame (medias, máximos mínimos, etc...).

3. Gráfica que permite ver el porcentaje de municipios por estado con índices de marginación "muy bajo", "bajo", "medio", "alto" y "muy alto". Tambien se guarda la gráfica en archivo png.

4. Gráfica que muestra el porcentaje de la población, respecto a la población total de cada estado, con índices de marginación "muy bajo", "bajo", "medio", "alto" y "muy alto". Tambien se guarda la gráfica en archivo jpg.

5. Se responde a las preguntas: ¿Hay coincidencias entra la gráficas anteriores?  ¿Algún hallazgo? Y se comenta un análisis.

6. Gráfica de la relación de porcentaje de analfabetismo respecto al porcentaje de poblaciones en localidades de menos de 5.000 habitantes.

7. Se responde a las preguntas: ¿Existe una relación? ¿Cómo podrías analizar con que variable tiene más correlación el porcentaje de analfabetismo en personas mayores de 15 años?

8. Se desarrolla un nuevo DataFrame con indicadores interesantes por estado que se obtienen de los datos a nivel municipal. Se justifican las decisiones, y se guarda el nuevo dataframe en formato parquet.
