# Proyecto DON MARIO

## Objetivo
Este proyecto tiene como objetivo procesar, calcular y segmentar datos de temperatura abrigo para el equipo de ingenieros agrónomos especializados en la siembra y cosecha de Maiz de la empresa DON MARIO. El procesamiento de estos datos facilitará su posterior análisis para la toma de decisiones en la producción agrícola.

## Descripción del Proyecto
El proyecto implica el manejo de datos de temperatura abrigo desde 2014 hasta la actualidad. Se realizan varios procesos y cálculos sobre estos datos para proporcionar información valiosa al equipo de ingenieros agrónomos.

## Procedimientos Principales

1. **Carga y Limpieza de Datos**
   - Carga de datos de temperatura abrigo desde 2014.
   - Conversión de la columna de fecha a formato datetime.
   - Identificación de valores faltantes o nulos.

2. **Cálculo de Grados Día**
   - Implementación del cálculo de GDU (grados día) utilizando los datos de temperatura.

3. **Segmentación por Quincena**
   - División de los datos en quincenas para un análisis más detallado.

4. **Cálculo de Acumulados**
   - Cálculo del acumulado de grados día por quincena.
   - Exclusión de valores negativos en los cálculos de acumulado.

5. **Creación de DataFrame Resumido**
   - Generación de un nuevo DataFrame con columnas: quincena, mes, y GDU acumulado.

6. **Análisis por Mes**
   - Cálculo de la suma y promedio de GDU acumulado para cada quincena de cada mes.

7. **Identificación de Datos Faltantes**
   - Detección de fechas faltantes en el conjunto de datos.
   - Opción para imputar valores faltantes (a criterio de los ingenieros).

8. **Promedio diario**
   - Luego de imputar los datos faltantes, obtenemos un promedio para cada día del año durante todo el período (2014-2024). Este procedimiento fue realizado en promedios_diarios.ipynb

## Datos Utilizados
- Tipo de datos: Temperatura abrigo
- Período: 2014 - actualidad (2024)
- Frecuencia: Diaria

## Resultados
El proyecto genera varios outputs de archivos excel que incluyen:
- GDU acumulado por quincena y mes.
- Resumen de GDU acumulado (suma y promedio) por quincena para cada mes.
- Identificación de valores nulos en el conjunto de datos.
- Promedio diario de GDU para todo el período.

## Nota Importante
- La imputación de valores faltantes se deja a criterio y aplicación de los ingenieros agrónomos.
- Se debe recalcular el promedio y acumulado de GDU por quincena luego de imputar valores.

## Contacto

Si deseas saber más sobre el proyecto, colaborar o hacer alguna consulta, no dudes en contactarme:

[LinkedIn](https://www.linkedin.com/in/santos-iparraguirre-b738a82b3/)

E-Mail: santosiparraguirrem@gmail.com