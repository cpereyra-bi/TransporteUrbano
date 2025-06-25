Este proyecto fue desarrollado en el marco de una clase práctica del curso de análisis de datos con Power BI. El objetivo principal es construir un informe interactivo para **Transporte Urbano S.A.**, una empresa ficticia de transporte de pasajeros, utilizando datos simulados y un modelo de datos en esquema estrella. La propuesta permite visualizar y optimizar la frecuencia y distribución de los viajes. Este enfoque es clave para mejorar el servicio, la eficiencia operativa y la satisfacción del usuario en el transporte urbano.

---

## Objetivos del Proyecto

- Crear una tabla de dimensiones `[Horas]` para análisis detallado por componente horario.  
- Separar los valores de fecha y hora en los datos brutos para obtener mayor granularidad.  
- Construir un modelo de datos en **esquema estrella** que conecte las tablas `[Viajes]`, `[Fechas]` y `[Horas]`.
- Aplicar **medidas DAX avanzadas** para interpretar el comportamiento por fecha, hora y tipo de día.
- Implementar visualizaciones dinámicas que favorezcan el análisis detallado y filtrado de los datos.

---

## Tareas Realizadas

-  Generación de la tabla de hechos `[Viajes]` a partir del archivo de datos.  
-  Creación de tabla de dimensiones `[Horas]` mediante DAX/Power Query.  
-  Construcción de una tabla `[Fechas]` ajustada al rango de datos disponible.  
-  Modelado relacional en esquema estrella conectando `[Viajes]`, `[Fechas]` y `[Horas]`.  
-  Diseño de visualizaciones con segmentadores, matrices y tarjetas para analizar patrones temporales.

## Visualizaciones Principales

- **Segmentadores dinámicos**: mes, tipo de día, franja horaria.
- **Matriz de viajes por día y hora**: para identificar picos de demanda.
- **Tarjetas resumen**: total de viajes, viajes por fin de semana, promedio por franja horaria.
- **Gráficos temporales**: evolución de viajes en fechas clave.
