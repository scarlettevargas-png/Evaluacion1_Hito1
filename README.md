## Entradas

Los archivos de entrada se encuentran en la carpeta `data/`:

- `data/datos_viga.csv`: contiene la carga aplicada y la deflexión medida en el centro de la viga.
- `data/parametros_viga.xlsx`: contiene la geometría de la viga y el módulo de elasticidad utilizados en el ejercicio.
- `data/esquema_viga.png`: contiene el esquema del caso analizado.

Los archivos originales se conservan sin modificaciones y cualquier transformación se realiza sobre copias de trabajo.

## Procedimiento

1. Revisar los archivos originales y los parámetros entregados.
2. Identificar las unidades de las variables y realizar las conversiones necesarias.
3. Calcular el segundo momento de área de la sección de la viga.
4. Calcular la deflexión teórica en el centro de la luz para cada carga aplicada.
5. Comparar las deflexiones teóricas con las deflexiones medidas.
6. Generar una figura que permita visualizar la comparación entre los datos medidos y los valores teóricos.
7. Realizar una verificación adicional de los resultados obtenidos.

## Salidas

El análisis genera las siguientes salidas:

- El segundo momento de área de la sección de la viga.
- La deflexión teórica en el centro de la luz para cada valor de carga.
- La comparación entre la deflexión medida y la deflexión teórica.
- Una figura que distingue los datos medidos de los valores teóricos.
- Una verificación adicional de los resultados del análisis.

## Herramientas y unidades

El análisis se realizará mediante una planilla de cálculo y se documentarán las operaciones utilizadas para facilitar su reproducción.

Los parámetros originales del caso están expresados en las siguientes unidades:

- Luz de la viga: L = 4 m
- Ancho de la sección: b = 0,2 m
- Altura de la sección: h = 0,4 m
- Módulo de elasticidad: E = 25 GPa

Para realizar los cálculos de manera consistente, se utilizará el Sistema Internacional expresado en mm, N y MPa:

- L = 4000 mm
- b = 200 mm
- h = 400 mm
- E = 25 000 MPa

Las conversiones se documentarán en la planilla de análisis para mantener trazabilidad entre los valores originales y los valores utilizados en los cálculos.

## Limitaciones y verificaciones

Los datos de deflexión entregados son sintéticos y fueron preparados con fines docentes, por lo que los resultados del análisis se interpretan dentro de ese contexto. Los archivos originales se mantienen sin modificaciones y cualquier transformación se realiza sobre copias de trabajo.

Como verificaciones del análisis se realizará:

- comprobación independiente del segundo momento de área de la sección;
- revisión de las conversiones de unidades utilizadas;
- comparación entre la deflexión teórica y la deflexión medida;
- comprobación de que la figura represente correctamente ambas series de datos.