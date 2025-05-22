Este ejercicio analiza los datos de viaje de una empresa ficticia de transporte de pasajeros, **Transporte Urbano S.A.**, con el objetivo de mejorar la comprensión de los patrones de uso en periodos cortos (como horas y minutos). Para ello, se implementa una **tabla de tiempos personalizada** que permite descomponer la información intradía y potenciar la toma de decisiones en contextos urbanos.

---

## 🎯 Objetivos del Proyecto

- Crear una tabla de dimensiones `[Horas]` para análisis detallado por componente horario.  
- Separar los valores de fecha y hora en los datos brutos para obtener mayor granularidad.  
- Construir un modelo de datos en **esquema estrella** que conecte las tablas `[Viajes]`, `[Fechas]` y `[Horas]`.

---

## 📝 Contexto

En colaboración con la empresa ficticia **ServiTech**, que brinda soluciones tecnológicas a sus clientes, se aborda la necesidad de una herramienta de análisis que permita visualizar y optimizar la frecuencia y distribución de los viajes. Este enfoque es clave para mejorar el servicio, la eficiencia operativa y la satisfacción del usuario en el transporte urbano.

---

## 🕵️ Tareas Realizadas

- 🔄 Generación de la tabla de hechos `[Viajes]` a partir del archivo de datos.  
- 🕒 Creación de tabla de dimensiones `[Horas]` mediante funciones de DAX o Power Query.  
- 📅 Construcción de una tabla `[Fechas]` con parámetros ajustables según el rango de datos.  
- 🔗 Modelado relacional en esquema estrella conectando `[Viajes]`, `[Fechas]` y `[Horas]`.  
- 📊 Visualización con segmentadores, matrices y tarjetas para analizar patrones por hora y fecha.  

---

## 🛠️ Herramientas Utilizadas
- **Microsoft Excel**: Fuente de datos con viajes simulados. 
- **Power BI**: Para conexión, transformación, modelado de datos y visualización.  
- **DAX y Power Query**: Para construcción de tablas de fechas, horas y medidas analíticas.
