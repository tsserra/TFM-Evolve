
# Actividad 0 - Ideas de producto

## Propuesta 1: BusMatch

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

---

## Propuesta 2: ReIngreso 30

### 1. Título y descripción

**ReIngreso 30 — Sistema inteligente de predicción de reingresos hospitalarios mediante IA.**

ReIngreso 30 es una herramienta basada en Data Science e Inteligencia Artificial que utiliza datos clínicos y asistenciales para estimar la probabilidad de que un paciente con enfermedades crónicas vuelva a ingresar en un hospital durante los 30 días posteriores al alta.

La plataforma emplea modelos de aprendizaje automático para identificar patrones asociados al reingreso y proporcionar **predicciones explicables que ayuden al personal sanitario a priorizar el seguimiento de pacientes con mayor riesgo**.

Su primera versión se desarrollará utilizando un conjunto de datos hospitalarios público, con el objetivo de demostrar la capacidad predictiva del sistema antes de considerar su posible aplicación en entornos clínicos reales.

### 2. Problema y usuario

**Problema:**

Los reingresos hospitalarios no planificados representan un desafío para los sistemas sanitarios, especialmente entre pacientes con enfermedades crónicas como diabetes, insuficiencia cardíaca o enfermedades respiratorias.

Estos reingresos pueden provocar complicaciones para los pacientes, incrementar los costes asistenciales y generar una mayor presión sobre las camas, el personal y los recursos disponibles.

Una de las principales dificultades consiste en identificar, antes de conceder el alta, qué pacientes presentan mayor probabilidad de regresar al hospital durante los siguientes 30 días.

**Usuario objetivo:**

Hospitales y organizaciones sanitarias interesadas en mejorar la planificación del alta y el seguimiento posterior de pacientes crónicos.

Los usuarios directos serían médicos, profesionales de enfermería, equipos de continuidad asistencial y gestores clínicos. Los principales beneficiarios serían los pacientes y sus familias.

**Solución actual:**

Los profesionales sanitarios evalúan el riesgo de reingreso mediante su experiencia clínica, el historial médico del paciente, los ingresos anteriores y los protocolos de seguimiento establecidos.

Algunos centros también utilizan escalas de riesgo o modelos de estratificación, aunque estas herramientas pueden presentar limitaciones en su capacidad predictiva y adaptación a distintos perfiles de pacientes.

ReIngreso 30 pretende complementar estos procedimientos mediante un análisis sistemático de los datos disponibles, sin sustituir el criterio de los profesionales sanitarios.

### 3. Uso y propuesta de valor

**Situación de uso:**

Un paciente con diabetes está a punto de recibir el alta hospitalaria. El equipo médico necesita determinar qué intensidad de seguimiento sería adecuada durante las semanas posteriores.

El profesional introduce en ReIngreso 30 información disponible antes del alta, como diagnósticos, ingresos anteriores, duración de la estancia y determinados antecedentes clínicos.

La plataforma procesa estos datos mediante un modelo predictivo y proporciona una **estimación del riesgo de reingreso durante los siguientes 30 días**, acompañada de una explicación de los factores que más han influido en el resultado.

Por ejemplo, el sistema podría identificar que los ingresos previos y una estancia hospitalaria prolongada están asociados a un mayor riesgo según los patrones aprendidos por el modelo.

El profesional puede utilizar esta información para valorar si conviene intensificar el seguimiento, programar revisiones o estudiar otras medidas preventivas.

**Valor aportado:**

- Identificar pacientes con mayor riesgo potencial de reingreso.
- Facilitar la planificación del seguimiento posterior al alta.
- Ayudar a priorizar los recursos sanitarios disponibles.
- Aprovechar información clínica que ya se recoge durante la asistencia.
- Proporcionar predicciones interpretables que complementen el criterio profesional.

**Modelo de negocio:** posible comercialización de la herramienta a hospitales y organizaciones sanitarias mediante licencias de software o contratos de servicio, condicionada a su validación clínica y al cumplimiento de la regulación aplicable.

A largo plazo, ReIngreso 30 podría integrarse en sistemas de información hospitalarios y evolucionar hacia una plataforma de apoyo a la gestión preventiva de pacientes crónicos.

### 4. Datos y fuentes candidatas

**Datos necesarios:**

Información sobre diagnósticos, ingresos hospitalarios anteriores, duración de las estancias, medicación, procedimientos realizados, características demográficas y reingresos posteriores al alta.

Para desarrollar el modelo será necesario disponer de registros históricos que permitan identificar qué pacientes reingresaron antes de 30 días.

**Fuentes candidatas:**

| Fuente | Información |
|---|---|
| [UCI Machine Learning Repository — Diabetes 130-US Hospitals](https://archive.ics.uci.edu/dataset/296/diabetes+130+us+hospitals+for+years+1999+2008) | Registros hospitalarios de pacientes con diabetes, características clínicas y variable de reingreso |
| Historiales clínicos hospitalarios | Diagnósticos, tratamientos, antecedentes y evolución de pacientes |
| Sistemas de información hospitalaria | Fechas de ingreso y alta, duración de estancias y utilización de recursos |
| Hospitales y centros sanitarios colaboradores | Datos clínicos actuales para una posible validación externa del modelo |

**Estado del acceso:**

El acceso público al conjunto de datos de UCI está confirmado. Contiene información procedente de hospitales estadounidenses entre 1999 y 2008 y permite estudiar la predicción de reingresos.

La variable `readmitted` permite distinguir los reingresos producidos antes de 30 días del resto de registros, aunque todavía será necesario analizar las limitaciones de esta clasificación.

**Todavía está pendiente realizar una auditoría de calidad del conjunto de datos**, estudiar sus valores ausentes y comprobar la existencia de registros repetidos correspondientes a un mismo paciente.

El acceso a historiales clínicos de hospitales españoles no está confirmado y no será necesario para desarrollar la primera versión.

**Restricciones:**

El conjunto de datos de UCI dispone de una licencia Creative Commons Attribution 4.0 (CC BY 4.0), que permite su reutilización con atribución.

Aunque los registros públicos no incluyen identificadores personales directos, contienen información sensible de salud. Una futura aplicación con datos reales debería cumplir el RGPD y las demás obligaciones de protección de datos.

Además, los datos proceden de hospitales estadounidenses y son antiguos, por lo que **los resultados del modelo no pueden extrapolarse automáticamente a hospitales españoles actuales**.

También será necesario comprobar las obligaciones regulatorias aplicables a un sistema de IA destinado a apoyar decisiones clínicas.

### 5. MVP - Producto mínimo viable

**Funciones principales:**

El MVP consistirá en una aplicación que permita introducir información clínica de un paciente ficticio y obtener una predicción explicable de su riesgo de reingreso hospitalario.

Incluirá cuatro funciones:

1. **Preparación de datos:** limpiar y transformar los registros hospitalarios, tratar los valores ausentes y seleccionar las variables relevantes para la predicción.
2. **Modelo predictivo:** entrenar y comparar algoritmos como regresión logística, Random Forest y XGBoost para estimar la probabilidad de reingreso antes de 30 días.
3. **Evaluación y explicabilidad:** medir la sensibilidad, precisión, PR-AUC y calibración del modelo, utilizando técnicas como SHAP para interpretar las predicciones.
4. **Interfaz interactiva:** desarrollar una aplicación en Streamlit que permita introducir datos clínicos ficticios y visualizar la puntuación de riesgo junto con sus principales factores explicativos.

Las herramientas previstas incluyen Python, pandas, scikit-learn, XGBoost, imbalanced-learn, SHAP y Streamlit.

**Demostración:**

Se entrenará un modelo utilizando el conjunto de datos público de UCI y se desarrollará una interfaz en la que sea posible simular diferentes perfiles de pacientes.

La demostración mostrará cómo varía la probabilidad estimada de reingreso según las características introducidas y qué factores influyen más en cada predicción.

El objetivo será comprobar si ReIngreso 30 puede transformar registros hospitalarios en **información predictiva interpretable y potencialmente útil para la planificación sanitaria**.

**Fuera del MVP:**

Integración con historiales clínicos reales, utilización de datos identificables de pacientes, recomendaciones automáticas de tratamientos y aplicación efectiva en decisiones clínicas.

Estas funcionalidades requerirían validaciones adicionales y el cumplimiento de la regulación sanitaria correspondiente.

### 6. Viabilidad y dudas

**Principal dificultad:**

Desarrollar un modelo predictivo suficientemente fiable y generalizable a partir de datos históricos que no representan necesariamente las condiciones clínicas actuales.

Aunque existe un conjunto de datos público y documentado, será necesario comprobar si contiene información suficiente para identificar pacientes con riesgo de reingreso sin producir resultados artificialmente optimistas.

También constituye una dificultad importante la validación clínica y regulatoria necesaria para transformar un prototipo académico en una herramienta utilizada realmente por hospitales.

**Comprobaciones pendientes:**

1. Analizar la calidad del conjunto de datos, sus valores ausentes y posibles inconsistencias.
2. Comprobar si el modelo identifica reingresos con sensibilidad y precisión suficientes, prestando especial atención a los falsos negativos.
3. Evitar que registros de un mismo paciente aparezcan indebidamente repartidos entre entrenamiento y prueba.
4. Comparar diferentes algoritmos y evaluar la interpretabilidad de sus predicciones.
5. Estudiar las limitaciones de generalización de los resultados a otros hospitales y poblaciones.
6. Revisar los requisitos legales, de protección de datos y de regulación sanitaria necesarios para una futura aplicación real.

**Primera prueba de viabilidad:**

Entrenar un modelo con el conjunto de datos de UCI, evaluar su rendimiento sobre registros de prueba adecuadamente separados y desarrollar una interfaz demostrativa que genere predicciones explicables para pacientes ficticios.

Esta prueba permitirá determinar si los datos contienen suficiente información predictiva para justificar una investigación posterior.

**Conclusión:** ReIngreso 30 pretende utilizar técnicas de Inteligencia Artificial para facilitar la identificación temprana de pacientes con mayor riesgo de reingreso hospitalario. Su viabilidad dependerá de la calidad y representatividad de los datos, la capacidad predictiva del modelo y las exigencias de validación clínica y regulación sanitaria.

---

## Propuesta 3: GameVision AI

### 1. Título y descripción

**GameVision AI — Plataforma inteligente de análisis del rendimiento futbolístico y predicción de resultados.**

GameVision AI es una plataforma basada en Data Science e Inteligencia Artificial que analiza estadísticas avanzadas de jugadores y equipos de fútbol para evaluar su rendimiento y generar predicciones deportivas.

La herramienta permite comparar futbolistas, identificar fortalezas y debilidades y estimar las probabilidades de victoria, empate o derrota mediante modelos de aprendizaje automático.

Su primera versión estará orientada a **facilitar el acceso a herramientas de análisis deportivo a clubes, academias y organizaciones con recursos analíticos limitados**, utilizando conjuntos de datos públicos de competiciones futbolísticas.

### 2. Problema y usuario

**Problema:**

La evaluación del rendimiento de futbolistas y equipos es una tarea compleja que no siempre puede realizarse adecuadamente mediante estadísticas tradicionales como goles, asistencias o minutos disputados.

Existen numerosas variables que influyen en el rendimiento deportivo, como la precisión de los pases, la creación de oportunidades, la recuperación de balones o la participación en acciones ofensivas y defensivas.

Para los clubes con recursos limitados, analizar e interpretar esta información puede resultar complicado debido al coste de las plataformas especializadas y a la falta de personal dedicado al análisis de datos.

**Usuario objetivo:**

Clubes de fútbol, academias y organizaciones deportivas interesadas en mejorar sus decisiones mediante el análisis de datos.

Los usuarios principales serían entrenadores, analistas de rendimiento, directores deportivos y responsables de captación de talento.

La plataforma podría resultar especialmente interesante para equipos modestos y semiprofesionales que no disponen de grandes departamentos de análisis.

**Solución actual:**

Los clubes evalúan a los jugadores mediante la observación de partidos, informes de ojeadores, análisis de vídeo y estadísticas tradicionales.

Las organizaciones con mayores recursos utilizan plataformas profesionales como Wyscout o StatsBomb, que proporcionan datos avanzados y herramientas especializadas.

Sin embargo, estas soluciones pueden resultar difíciles de asumir para entidades con presupuestos reducidos.

GameVision AI pretende reunir y simplificar determinadas funcionalidades de análisis deportivo, ofreciendo información comprensible y accesible para apoyar las decisiones de los profesionales.

### 3. Uso y propuesta de valor

**Situación de uso:**

Un club de fútbol necesita incorporar un centrocampista y está considerando tres posibles fichajes.

El director deportivo quiere comparar a los candidatos teniendo en cuenta no solo sus goles y asistencias, sino también su precisión de pases, recuperaciones, creación de oportunidades y participación ofensiva.

Mediante GameVision AI, selecciona a los tres jugadores y consulta un panel comparativo que presenta sus principales indicadores de rendimiento, normalizados por minutos disputados y contextualizados según su posición.

La plataforma permite identificar fortalezas y debilidades de cada futbolista y destacar diferencias relevantes entre sus perfiles.

Adicionalmente, el entrenador puede utilizar el módulo predictivo para consultar las **probabilidades estimadas de victoria, empate o derrota en un próximo partido**, a partir del rendimiento histórico de ambos equipos.

La información obtenida ayuda a seleccionar candidatos para un análisis más profundo y a complementar la preparación de encuentros.

**Valor aportado:**

- Facilitar la comparación objetiva de futbolistas con características y posiciones similares.
- Identificar fortalezas y debilidades mediante indicadores avanzados.
- Reducir el tiempo necesario para recopilar e interpretar estadísticas deportivas.
- Apoyar decisiones relacionadas con fichajes, alineaciones y preparación de partidos.
- Acercar herramientas de análisis deportivo a organizaciones con presupuestos limitados.

**Modelo de negocio:** posible comercialización de la plataforma mediante suscripciones para clubes, academias y organizaciones deportivas, con diferentes niveles de acceso a funcionalidades analíticas.

A largo plazo, GameVision AI podría ampliar su cobertura a nuevas competiciones, incorporar indicadores avanzados adicionales y desarrollar herramientas de seguimiento de jugadores y equipos.

### 4. Datos y fuentes candidatas

**Datos necesarios:**

Estadísticas individuales de jugadores, resultados históricos de partidos, alineaciones, minutos disputados, posiciones, pases, tiros, recuperaciones, acciones ofensivas y defensivas e información contextual de los equipos.

Para desarrollar el módulo predictivo también serán necesarios resultados históricos y estadísticas disponibles antes de cada encuentro.

**Fuentes candidatas:**

| Fuente | Información |
|---|---|
| [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer) | Más de 25.000 partidos y 10.000 jugadores de 11 ligas europeas entre 2008 y 2016, incluyendo resultados, alineaciones y atributos |
| [StatsBomb Open Data](https://github.com/statsbomb/open-data) | Datos de eventos de partidos, alineaciones y acciones individuales y colectivas |
| Plataformas profesionales como Wyscout y StatsBomb | Estadísticas avanzadas y datos adicionales para una posible ampliación futura |
| Clubes y academias colaboradoras | Datos propios de rendimiento y seguimiento de jugadores para posibles validaciones |

**Estado del acceso:**

Se han identificado dos conjuntos de datos públicos con características complementarias.

La European Soccer Database contiene información histórica de partidos y jugadores, aunque **la descarga y la integridad de sus archivos todavía no se han verificado**. Además, combina estadísticas reales con atributos procedentes de videojuegos.

El repositorio de StatsBomb ofrece acceso público confirmado a archivos JSON con información detallada de eventos deportivos, aunque su cobertura está limitada a determinadas competiciones y temporadas.

Todavía será necesario evaluar si ambas fuentes contienen suficientes variables compatibles para desarrollar los módulos de comparación de jugadores y predicción de partidos.

**Restricciones:**

Los conjuntos de datos presentan diferencias en su cobertura, periodos históricos, disponibilidad de variables y metodología de cálculo de estadísticas.

El repositorio de StatsBomb establece condiciones de atribución y uso de su identidad visual. Será necesario comprobar las licencias antes de redistribuir datos o comercializar resultados.

Los datos públicos de jugadores profesionales pueden contener información personal, por lo que también deberán respetarse las obligaciones de protección de datos aplicables.

Además, la información histórica no garantiza que los modelos predictivos mantengan su rendimiento en competiciones y temporadas actuales.

### 5. MVP - Producto mínimo viable

**Funciones principales:**

El MVP consistirá en una aplicación web que permita comparar el rendimiento de futbolistas y estimar probabilidades de resultados de partidos utilizando datos históricos.

Incluirá cuatro funciones:

1. **Preparación de datos:** recopilar, limpiar e integrar estadísticas de jugadores y partidos, utilizando Python y pandas para transformar la información en conjuntos de datos analizables.
2. **Análisis de rendimiento:** calcular indicadores por 90 minutos, comparar jugadores de posiciones similares e identificar fortalezas y debilidades mediante gráficos.
3. **Predicción de resultados:** entrenar un modelo de clasificación con scikit-learn para estimar las probabilidades de victoria local, empate o victoria visitante.
4. **Panel interactivo:** desarrollar una aplicación con Streamlit que permita seleccionar jugadores, comparar estadísticas y consultar las predicciones de partidos.

Las herramientas previstas incluyen Python, pandas, NumPy, SciPy, scikit-learn, Matplotlib o Plotly y Streamlit.

El modelo predictivo se evaluará mediante métricas como accuracy, log loss y Brier score, comparándolo también con un modelo de referencia sencillo.

**Demostración:**

Se seleccionará una muestra de jugadores y partidos de las competiciones disponibles para construir un panel interactivo de análisis deportivo.

El usuario podrá comparar dos o tres futbolistas de una misma posición, visualizar sus principales estadísticas y observar las diferencias de rendimiento.

También podrá seleccionar dos equipos y consultar las probabilidades estimadas de los posibles resultados de un encuentro, utilizando únicamente información histórica disponible antes de su celebración.

El objetivo será demostrar que GameVision AI puede transformar estadísticas deportivas en **información visual, comprensible y útil para apoyar decisiones de clubes y profesionales del fútbol**.

**Fuera del MVP:**

Análisis automático de vídeo, seguimiento GPS de jugadores, predicciones en directo, integración con sistemas profesionales de clubes y cobertura completa de todas las competiciones.

Estas funcionalidades requerirían datos adicionales, mayor capacidad técnica y posibles acuerdos con proveedores especializados.

### 6. Viabilidad y dudas

**Principal dificultad:**

Combinar dos objetivos analíticos diferentes, la evaluación del rendimiento individual y la predicción de resultados deportivos, utilizando conjuntos de datos suficientemente completos, compatibles y representativos.

Además, el fútbol presenta un componente de incertidumbre elevado. Incluso un modelo correctamente entrenado puede generar probabilidades razonables sin acertar el resultado de cada encuentro.

Otra dificultad consiste en diferenciar entre el rendimiento estadístico individual y la verdadera contribución táctica de un futbolista, ya que unas mejores estadísticas no implican necesariamente una mayor aportación al equipo.

Desde el punto de vista comercial, la existencia de plataformas consolidadas como Wyscout y StatsBomb obliga a identificar una propuesta de valor diferenciada, especialmente para clubes modestos y academias.

**Comprobaciones pendientes:**

1. Verificar la disponibilidad, integridad y calidad de los conjuntos de datos identificados.
2. Comprobar qué estadísticas pueden utilizarse para comparar jugadores de forma consistente.
3. Evaluar la compatibilidad entre las fuentes y la posibilidad de integrar sus datos.
4. Entrenar y validar un modelo predictivo respetando el orden temporal de los partidos.
5. Comprobar las condiciones de licencia, reutilización y posible comercialización de los datos.
6. Analizar si clubes y academias con recursos limitados encontrarían utilidad en una herramienta de estas características.

**Primera prueba de viabilidad:**

Obtener una muestra real de estadísticas de jugadores y resultados históricos, construir un panel de comparación de futbolistas y entrenar un primer modelo de predicción de partidos.

La evaluación del modelo utilizará temporadas anteriores para el entrenamiento y partidos posteriores para comprobar su rendimiento, evitando incorporar información que no estuviera disponible antes de cada encuentro.

Esta prueba permitirá determinar si las fuentes públicas son suficientes para desarrollar una herramienta funcional y si los resultados obtenidos tienen utilidad para el análisis deportivo.

**Conclusión:** GameVision AI pretende acercar el análisis avanzado de datos deportivos a clubes y organizaciones con recursos limitados. Su viabilidad dependerá de la calidad y disponibilidad de las estadísticas, la fiabilidad de los modelos predictivos y la capacidad de ofrecer una propuesta diferenciada frente a las plataformas especializadas existentes.

