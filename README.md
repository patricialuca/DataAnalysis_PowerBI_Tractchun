> **Nota**: Este proyecto se desarrolló durante la certificación de Power BI Desktop de IBM, Fundae y Datahack.

Tractchun es una empresa ficticia que se encuadra en el sector manufacturero y que cuenta con un equipo de soporte de IT que se encarga de gestionar diferentes tipos de tickets relacionados con sistemas, hardware y software.

El objetivo del proyecto consistía en monitorizar y mejorar la eficiencia del servicio IT realizando un análisis en profundidad de los datos generados por los tickets y una clasificación de empleados.

## Descripción del Dashboard

Se compone de tres paneles principales que permiten visualizar y filtrar la información obteniendo los insights más importantes:

- **Panel de Resumen de Tickets (2016-2020):** En este panel podemos ver el total de tickets por año y agente, la satisfacción promedio escalada de 1 a 5 y la media de tiempo de resolución de ticket. Se incluyen una serie de visualizaciones como el total de tickets por día y categoría, la distribución de tickets según la calificación recibida y el tiempo de resolución por rango de días.

- **Panel de Tipo de Ticket:** Aquí segmentamos en dos categorías, por un lado los problemas y por otro las solicitudes. Podemos filtrar para evaluar el desempeño de cada ticket para identificar si los problemas se resuelven con la misma eficiencia que las solicitudes de servicio.

- **Ranking de Agentes:** Se clasifican en función del total de tickets atendidos, satisfacción promedio y media de días de resolución; todo ello proporciona una visión rápida del rendimiento individual. Se incluye una opción para alternar entre los agentes con mejor y peor desempeño.

## Análisis de Datos

### Aumento del volumen de tickets

De 2016 a 2020 hubo un incremento en el volumen de tickets de 13 a 29 mil, lo que hizo que se duplicara el trabajo entre los agentes, pero a pesar de este aumento el promedio de resolución se mantuvo en 4,5 días.

### Mejora en la satisfacción del usuario

La calificación positiva aumentó un 5% en promedio ya que pasó de 3.98 en el año 2016 a una calificación promedio de 4.16 en el año 2020.

### Distribución por tipo de ticket

La mayor parte de los tickets están relacionados con solicitudes que tienen que ver con el servicio mientras que los problemas suponen alrededor de un 25% del total anual.

## Aspectos Técnicos

- **Transformación y limpieza de datos:** Se llevó a cabo utilizando Power Query.
- **Modelos de datos relacional:** Se implementó un esquema en estrella para poder manejar de forma eficiente grandes volúmenes de datos.
- **Cálculos y expresiones DAX:** Se utilizaron expresiones condicionales y se calcularon medidas con DAX que nos permitieron obtener estadísticas clave y así facilitar la interpretación de los resultados.
- **Interactividad y bookmarks:** Se integraron diferentes bookmarks para ofrecer una navegación intuitiva entre los distintos tableros.

## Conclusión

En el dashboard se ha buscado mostrar la visión integral del desempeño del equipo de IT de Tractchun, aportando una optimización de sus operaciones para que los gerentes de la empresa puedan tomar decisiones informadas que mejoren la eficiencia de los servicios de IT y soporte técnico, lo que proporcionará un impacto positivo en la productividad y ambiente de la empresa.

## Autoría
Este proyecto fue realizado por [Patricia Luengo Carretero](https://www.linkedin.com/in/patricialuca/) y también lo puedes encontrar en Power BI en [Dashboard Tractchun]([https://www.kaggle.com/code/patrilc/proyecto-final-programa-de-ia-de-ibm](https://app.fabric.microsoft.com/view?r=eyJrIjoiODgwMTk5YzItMDYwZC00NjI5LWJkMDAtMWM5NTczNmQ2MzViIiwidCI6IjM4ODlmZDllLWIyNTgtNGM1Zi1hNzE1LTEzZjJjMDA2NDQzNCJ9)) Puedes ver más sobre mi trabajo en mi [sitio web personal](https://www.patricialuca.es).
