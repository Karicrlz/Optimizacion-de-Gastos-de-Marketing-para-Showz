# 🎫🎪Optimización de Gastos de Marketing para Showz ✨🎟️
## Descripción del proyecto
En este proyecto, trabajé con el departamento de analítica de Showz, una empresa dedicada a la venta de entradas para eventos. El objetivo principal fue analizar los gastos de marketing y proponer estrategias para optimizarlos, con el fin de mejorar la rentabilidad de la empresa y ofrecer experiencias más memorables a los asistentes.
Se llevó a cabo un análisis detallado de los datos disponibles sobre las campañas de marketing pasadas, evaluando su impacto en las ventas y la efectividad de las inversiones. A partir de los resultados obtenidos, se generaron recomendaciones para ajustar y redistribuir los recursos de manera más eficiente, asegurando una mayor rentabilidad.
Este análisis no solo impactó positivamente en la rentabilidad de la empresa, sino que también permitió mejorar la planificación de futuras campañas, garantizando mejores experiencias para el público y maximizando el retorno de inversión en marketing.

## Motivación 
Analizar los gastos de marketing y proponer estrategias para optimizarlos no solo mejora el desempeño financiero de Showz, sino que también contribuye a crear experiencias más memorables para los asistentes a eventos. Al evaluar las campañas pasadas, es posible identificar qué estrategias realmente funcionan y cuáles no, lo que permite ajustar recursos de forma más eficiente. Esto no solo mejora el retorno de inversión, sino que también facilita la planificación de futuras campañas, generando un ciclo positivo de crecimiento. Además, el proyecto permite adquirir valiosas habilidades en análisis de datos y toma de decisiones estratégicas, lo cual es fundamental en el mundo del marketing digital. 

## Características del Dataset

### La tabla visits (registros del servidor con datos sobre las visitas al sitio web):

-Uid: identificador único del usuario.

-Device: dispositivo del usuario.

-Start Ts: fecha y hora de inicio de la sesión.

-End Ts: fecha y hora de término de la sesión.

-Source Id: identificador de la fuente de anuncios de la que proviene el usuario.

-Todas las fechas de esta tabla están en formato AAAA-MM-DD.

### La tabla orders (datos sobre pedidos):

-Uid: identificador único del usuario que realiza un pedido.

-Buy Ts: fecha y hora del pedido. Revenue: el ingreso de Showz por el pedido.

### La tabla costs (datos sobre gastos de marketing):

-source_id: identificador de la fuente de anuncios.

-dt: fecha.

-costs: gastos en esta fuente de anuncios en este día.

## Herramientas Utilizadas
### Lenguaje:
Python 
### Librerías:
pandas,
seaborn, 
matplotlib.pyplot, 
numpy.

## Proceso del Proyecto
### Introducción
### Carga y Exploración de Datos
Análisis inicial del dataset: revisión de los valores faltantes, tipos de datos y distribuciones.
Exploratory Data Analysis (EDA) para entender las relaciones entre las variables

### Calculo de métricas
Se respondieron las siguientes preguntas
##### Visitas
¿Cuántas personas lo usan cada día, semana y mes?

¿Cuántas sesiones hay por día? (Un usuario puede tener más de una sesión).

¿Cuál es la duración de cada sesión?

¿Con qué frecuencia los usuarios regresan?

 ##### Ventas
¿Cuándo empieza la gente a comprar? (En el análisis de KPI, generalmente nos interesa saber el tiempo que transcurre entre el registro y la conversión, es decir, cuando el usuario se convierte en cliente. Por ejemplo, si el registro y la primera compra ocurren el mismo día, el usuario podría caer en la categoría Conversion 0d. Si la primera compra ocurre al día siguiente, será Conversion 1d. Puedes usar cualquier enfoque que te permita comparar las conversiones de diferentes cohortes para que puedas determinar qué cohorte o canal de marketing es más efectivo.)

¿Cuántos pedidos hacen durante un período de tiempo dado?

¿Cuál es el tamaño promedio de compra?

¿Cuánto dinero traen? (LTV)

##### Marketing
¿Cuánto dinero se gastó? (Total/por fuente de adquisición/a lo largo del tiempo)

¿Cuál fue el costo de adquisición de clientes de cada una de las fuentes

¿Cuán rentables eran las inversiones? (ROMI)

### Conclusión 
Se especifica los resultados del LVC, CAC y ROMI 





