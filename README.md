# AnalisisLFP
1) Descripción del dataset: Siguiendo la línea de la práctica anterior, el dataset contiene estadísticas de todos los jugadores de la Primera División de la Liga de Fútbol Nacional. El dataset es importante porque contiene datos acumulados de los jugadores tras disputarse las 38 jornadas de la temporada 2017/2018.Se pretende resolver, al menos, una de las siguientes preguntas:
   - ¿Es posible estimar los goles anotados por un futbolista a partir de otros parámetros medidos sobre el futbolista?
   - ¿Qué parámetros clave debe cumplir un futbolista para ser importante dentro de cualquier equipo en Primera División?

2) Integración y selección de los datos: La web de la LFP ofrece estadísticas de los jugadores agrupadas por tipo (generales, disciplinarias, ofensivas, defensivas y de eficiencia). Para responder a las preguntas objeto de la práctica con la mayor certidumbre posible, es necesario integrar todos los tipos diferentes de estadísticas disponibles. Tras este hito, debemos verificar que todos los datos son consistentes y coherentes. Por ello, se verificarán una serie de condiciones para validar los datos.

3) Limpieza de los datos: Se identificarán los ceros y los elementos vacíos, con el objeto de definir la política de tratamiento de los mismos. Además, se identificarán los valores extremos, se decidirá sobre su veracidad y se planteará el tratamiento a aplicar.

4) Análisis de los datos: en esta fase no sólo haremos uso de los datos existentes, sino que definiremos ratios entre datos y otros agregados que puedan ayudar a dar respuesta a la pregunta planteada (% de minutos jugados, minutos por cada falta recibida o cometida, tiros a puerta / tiros totales, etc). A continuación, aplicaremos tests de normalidad (Shapiro) a los datos seleccionados, así como los correspondientes análisis de homogeneidad de varianzas específicos en función del cumplimiento previo de la normalidad o no. Finalmente, plantearemos pruebas de contrastes de hipótesis (), correlaciones () y regresiones ().

5) Tablas y gráficas de resultados:
