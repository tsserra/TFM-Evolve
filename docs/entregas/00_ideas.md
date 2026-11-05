
# Actividad 0 - Ideas de producto

## Propuesta 1: Álvaro Álvarez Zazo

### 1. Título y descripción

**BusMatch — Plataforma inteligente de detección de oportunidades de transporte colectivo.**

BusMatch es una plataforma basada en Data Science que analiza datos de movilidad, población y transporte público para identificar oportunidades de creación de nuevas rutas de autobús.

Su primera versión se centrará en generar y comercializar informes estratégicos para empresas de transporte, ayudándolas a descubrir posibles rutas y evaluar su atractivo comercial. El proyecto comenzará utilizando la **provincia de Toledo como caso de estudio**, con posibilidad de ampliación a otras regiones.

### 2. Problema y usuario

**Problema:**

En numerosos municipios existen desplazamientos recurrentes que no siempre disponen de conexiones adecuadas de transporte público. Paralelamente, las empresas de autobuses pueden desconocer dónde existen oportunidades para establecer nuevas rutas, lo que dificulta su expansión y aumenta el riesgo económico.

**Usuario objetivo:**

Pequeñas y medianas empresas de transporte interesadas en descubrir nuevas oportunidades comerciales. Como clientes secundarios se contemplan asociaciones empresariales, centros educativos y otras organizaciones con necesidades de movilidad colectiva.

**Solución actual:**

Las empresas identifican oportunidades mediante solicitudes de clientes, experiencia del mercado local, estudios específicos y consultas manuales de datos públicos. Estos métodos pueden requerir tiempo, recursos y conocimientos especializados, sin proporcionar necesariamente una visión integrada de la movilidad.

### 3. Uso y propuesta de valor

**Situación de uso:**

Una empresa de autobuses quiere ampliar su actividad en la provincia de Toledo, pero desconoce qué conexiones podrían presentar oportunidades comerciales.

Solicita a BusMatch un estudio de movilidad de la zona. La plataforma analiza los desplazamientos entre municipios, los patrones horarios y los servicios existentes para detectar posibles rutas de interés.

La empresa recibe un **informe comercial con los corredores identificados, estimaciones de movilidad, conexiones conocidas y oportunidades priorizadas**, que utiliza para decidir qué rutas merece la pena investigar.

**Valor aportado:**

- Descubrir oportunidades comerciales todavía no identificadas.
- Ahorrar tiempo en la recopilación y análisis de información.
- Reducir la incertidumbre inicial antes de estudiar nuevas rutas.
- Priorizar oportunidades utilizando criterios basados en datos.

**Modelo de negocio:** venta de informes de oportunidades y estudios personalizados, con posibilidad futura de ofrecer una plataforma mediante suscripción.

A largo plazo, BusMatch podría evolucionar hacia un marketplace donde los viajeros propongan rutas, la plataforma valide la demanda y las empresas presenten ofertas para operarlas.

### 4. Datos y fuentes candidatas

**Datos necesarios:**

Desplazamientos origen-destino, patrones horarios, población municipal, rutas y horarios de transporte existentes, información geográfica y referencias de costes operativos.

**Fuentes candidatas:**

| Fuente | Información |
|---|---|
| [Ministerio de Transportes](https://www.transportes.gob.es/ministerio/proyectos-singulares/estudio-de-movilidad-con-big-data) | Matrices origen-destino y patrones de movilidad |
| [NAP](https://nap.transportes.gob.es/) | Rutas, paradas y horarios de transporte |
| [INE](https://www.ine.es/) | Población y datos demográficos |
| [OpenStreetMap](https://www.openstreetmap.org/) | Red viaria y datos geográficos |
| [Junta de Castilla-La Mancha](https://educacion.castillalamancha.es/educacion/estadistica-educativa/estadistica-20242025) | Centros educativos y estadísticas de alumnado |
| Empresas colaboradoras | Costes operativos y presupuestos históricos |

**Estado del acceso:**

Las fuentes públicas están identificadas, pero **todavía está pendiente descargar y comprobar los datos específicos de Toledo**, su cobertura y su nivel de detalle. El acceso a datos privados de empresas tampoco está confirmado.

**Restricciones:**

Los datos de movilidad no representan directamente demanda dispuesta a pagar y pueden presentar limitaciones en municipios pequeños. Será necesario comprobar las licencias de reutilización y comercialización, la calidad de las fuentes y la confidencialidad de los posibles datos empresariales.

### 5. MVP - Producto mínimo viable

**Funciones principales:**

El MVP consistirá en una herramienta que permita analizar la movilidad de la provincia de Toledo y generar informes comerciales sobre posibles nuevas rutas.

Incluirá tres funciones:

1. **Análisis de movilidad:** procesar datos públicos de desplazamientos, población y conexiones existentes.
2. **Detector de oportunidades:** identificar y priorizar corredores con movilidad relevante y posibles carencias de transporte.
3. **Generador de informes:** presentar rutas candidatas, indicadores, visualizaciones, limitaciones y conclusiones útiles para empresas.

**Demostración:**

Se analizarán datos reales de la provincia de Toledo para identificar una o dos oportunidades potenciales y generar un informe comercial que pueda presentarse a una empresa de transporte.

El objetivo será comprobar si BusMatch puede transformar datos públicos en **información comercial útil y potencialmente monetizable**.

**Fuera del MVP:**

Registro de viajeros, campañas de captación de demanda, subastas, contratación de rutas, pagos y explotación de servicios reales. Estas funcionalidades corresponderían a futuras etapas.

### 6. Viabilidad y dudas

**Principal dificultad:**

Comprobar si los datos disponibles tienen suficiente detalle geográfico y temporal para detectar oportunidades útiles, especialmente en municipios pequeños.

Además, una elevada movilidad no garantiza que exista demanda comercial suficiente. También habrá que validar si las empresas estarían dispuestas a pagar por los informes generados.

**Comprobaciones pendientes:**

1. Verificar la disponibilidad, granularidad y calidad de los datos de movilidad de Toledo.
2. Comprobar la cobertura de rutas y horarios de transporte existentes.
3. Evaluar si es posible identificar oportunidades mediante un análisis reproducible.
4. Revisar las condiciones legales de utilización y comercialización de los datos.


**Primera prueba de viabilidad:**

Obtener una muestra real de movilidad de Toledo, identificar un corredor potencialmente interesante y elaborar un informe que permita recibir feedback de una empresa de transporte.

**Conclusión:** BusMatch busca transformar datos de movilidad en oportunidades de negocio. Su viabilidad dependerá de la calidad de las fuentes, la utilidad de los informes y la existencia de clientes dispuestos a pagar por ellos.
