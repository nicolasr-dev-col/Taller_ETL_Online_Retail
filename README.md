\# Taller ETL - Online Retail



\## Descripción



Este proyecto presenta la implementación de un proceso de Extracción, Transformación y Carga (ETL) aplicado a un conjunto de datos de transacciones comerciales denominado Online Retail.



El proyecto fue desarrollado utilizando Python y Pandas en Google Colab, con el objetivo de obtener, limpiar, transformar y estructurar los datos para su posterior utilización en procesos de Business Analytics.



\## Dataset



El conjunto de datos utilizado corresponde a \*\*Online Retail\*\*, disponible en UCI Machine Learning Repository.



El dataset original contiene 541.909 registros y 8 variables relacionadas con transacciones comerciales, productos, cantidades, precios, fechas, clientes y países.



Fuente:



https://archive.ics.uci.edu/dataset/352/online%2Bretail



\## Proceso ETL



\### Extracción



Se realizó la extracción de los datos desde el archivo:



`Online Retail.xlsx`



utilizando Python y Pandas.



\### Transformación



Durante esta etapa se realizaron diferentes procesos de limpieza y transformación:



\- Eliminación de registros duplicados.

\- Eliminación de registros con cantidades negativas.

\- Eliminación de registros con precios negativos.

\- Tratamiento de valores faltantes en la descripción de los productos.

\- Conservación de registros sin CustomerID para evitar pérdida innecesaria de información.

\- Conversión del tipo de dato de CustomerID.

\- Creación de la variable `TotalVenta`.

\- Creación de las variables `Año`, `Mes` y `Día`.



Después de la transformación se obtuvieron 526.052 registros y 12 variables.



\### Carga



Los datos transformados fueron almacenados en:



`online\_retail\_limpio.csv`



Posteriormente se verificó que el archivo generado conservara los 526.052 registros del DataFrame transformado.



\## Herramientas utilizadas



\- Python

\- Pandas

\- NumPy

\- Google Colab

\- Git

\- GitHub



\## Archivos del proyecto



\- `Taller\_ETL\_Online\_Retail.ipynb` — Notebook donde se desarrolla y documenta el proceso ETL.

\- `Online Retail.xlsx` — Archivo original utilizado como fuente de datos.

\- `online\_retail\_limpio.csv` — Resultado final del proceso de transformación.

\- `README.md` — Documentación general del proyecto.



\## Referencia sobre ETL



Microsoft Learn:



https://learn.microsoft.com/es-es/azure/architecture/data-guide/relational-data/etl

