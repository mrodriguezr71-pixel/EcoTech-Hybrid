# Estudio de variables mediante Arduino

## 1. Contexto

Dentro del proyecto **EcoTech Hybrid – Innovación Verde para un Futuro Sostenible**, se ha desarrollado una línea de experimentación orientada a la incorporación de tecnologías de automatización, sensorización y control en un entorno de cultivo protegido.

Esta experiencia se relaciona especialmente con el estudio de un sistema de cultivo hidropónico integrado en el entorno del invernadero, analizando diferentes variables que pueden influir en las condiciones de cultivo y en la futura automatización de la instalación.

El trabajo con Arduino se planteó como una experiencia práctica de aprendizaje basada en la experimentación, la resolución de problemas y el método de ensayo y error.

---

## 2. Objetivos del estudio

Los principales objetivos de esta experiencia fueron:

* Explorar las posibilidades de Arduino como herramienta de adquisición y tratamiento de datos.
* Identificar variables relevantes para el control de un entorno de cultivo.
* Experimentar con diferentes sensores y dispositivos de entrada.
* Comprender la relación entre las variables ambientales y las necesidades de las plantas.
* Introducir conceptos básicos de automatización y control.
* Desarrollar competencias de programación y resolución de problemas.
* Analizar la posibilidad de integrar posteriormente la sensorización en el prototipo EcoTech Hybrid.

---

## 3. Variables estudiadas

Durante la experiencia se trabajó sobre diferentes variables relacionadas con el funcionamiento del sistema:

| Variable        | Finalidad del estudio                                                                      |
| --------------- | ------------------------------------------------------------------------------------------ |
| **Temperatura** | Conocer las condiciones térmicas del entorno de cultivo.                                   |
| **Iluminación** | Analizar las condiciones de luz disponibles para las plantas.                              |
| **pH**          | Controlar una variable fundamental de la solución nutritiva en el cultivo hidropónico.     |
| **Ventilación** | Estudiar la posibilidad de controlar la renovación del aire y las condiciones ambientales. |
| **Movimiento**  | Explorar sistemas de detección y posibles respuestas automatizadas.                        |

Estas variables fueron seleccionadas por su relación con el funcionamiento de un entorno de cultivo protegido y con las posibilidades de automatización del prototipo.

---

## 4. Temperatura

La temperatura es una de las variables ambientales básicas que pueden afectar al desarrollo de los cultivos.

En el proyecto se plantea su monitorización mediante Arduino con el objetivo de:

* Obtener información sobre las condiciones térmicas.
* Detectar variaciones de temperatura.
* Analizar el comportamiento de la variable a lo largo del tiempo.
* Estudiar posibles respuestas automatizadas ante determinadas condiciones.

La incorporación de esta variable permite avanzar desde una simple medición hacia un sistema de control ambiental.

---

## 5. Iluminación

La disponibilidad de luz es otro factor fundamental en el desarrollo vegetal.

La experimentación permite estudiar:

* La intensidad de iluminación existente.
* Las variaciones producidas durante el día.
* La relación entre iluminación natural y condiciones del cultivo.
* La posibilidad de utilizar la información obtenida para establecer estrategias de control.

En una futura evolución del prototipo, esta información podría utilizarse para activar o regular determinados elementos del sistema de forma automatizada.

---

## 6. pH

El pH adquiere especial importancia en el estudio del cultivo hidropónico, ya que permite caracterizar la acidez o alcalinidad de la solución nutritiva.

Su incorporación al sistema de experimentación permite introducir al alumnado en:

* La importancia del control de parámetros del agua.
* La adquisición de datos mediante sensores.
* La interpretación de valores.
* La necesidad de calibración y comprobación de las mediciones.
* La relación entre parámetros físico-químicos y producción vegetal.

El pH constituye, por tanto, una de las variables con mayor relación directa entre la parte tecnológica y la parte agronómica del proyecto.

---

## 7. Ventilación

La ventilación está relacionada con la renovación del aire y con el control de las condiciones ambientales del espacio de cultivo.

Dentro de la experimentación se estudia la posibilidad de utilizar Arduino para:

1. Obtener información relacionada con las condiciones del entorno.
2. Establecer una lógica de control.
3. Generar una respuesta ante determinadas condiciones.
4. Integrar posteriormente actuadores relacionados con la ventilación.

De esta forma se introduce el concepto de **automatización mediante condiciones**, en el que una determinada lectura puede provocar una respuesta del sistema.

---

## 8. Detección de movimiento

La detección de movimiento permite explorar otro tipo de entrada al sistema.

Su utilización sirve para comprender cómo Arduino puede:

* Detectar la presencia o movimiento.
* Interpretar una señal procedente de un sensor.
* Ejecutar una acción programada.
* Integrar diferentes entradas dentro de un mismo sistema.

Aunque esta variable no está directamente relacionada con las necesidades fisiológicas de la planta, resulta útil para estudiar funciones de automatización, seguridad, interacción y control.

---

## 9. Metodología de experimentación

La metodología seguida se basa en un proceso progresivo de experimentación.

### Fase 1. Identificación de la variable

Se determina qué variable se quiere estudiar y qué información puede aportar al sistema.

### Fase 2. Prueba individual

Cada elemento se prueba inicialmente de forma independiente para comprender su funcionamiento.

### Fase 3. Programación

Se desarrolla la programación necesaria para realizar la lectura o gestionar la respuesta del sistema.

### Fase 4. Comprobación

Se realizan pruebas para comprobar que la información obtenida resulta coherente con las condiciones observadas.

### Fase 5. Resolución de problemas

Cuando aparecen errores de programación, conexión o funcionamiento, se realizan modificaciones y nuevas pruebas.

### Fase 6. Integración

Una vez comprendido el funcionamiento individual, se plantea la posibilidad de integrar diferentes variables dentro de un mismo sistema.

Este procedimiento favorece un aprendizaje práctico basado en la investigación, la autonomía y la resolución de problemas.

---

## 10. Relación entre las variables y el sistema EcoTech Hybrid

Una de las principales aportaciones de esta experiencia es conectar diferentes áreas de conocimiento dentro de un mismo proyecto.

```text
                 ECOTECH HYBRID
                       │
        ┌──────────────┼──────────────┐
        │              │              │
   Cultivo         Energía       Tecnología
   protegido      fotovoltaica    y control
        │              │              │
        └──────────────┼──────────────┘
                       │
                  SENSORACIÓN
                       │
        ┌──────────────┼──────────────┐
        │       │      │      │       │
   Temperatura Luz    pH  Ventilación Movimiento
        │       │      │      │       │
        └───────┴──────┴──────┴───────┘
                       │
                  AUTOMATIZACIÓN
```

La experimentación permite establecer un puente entre:

* **Agricultura**, mediante el estudio de las necesidades del cultivo.
* **Electrónica**, mediante sensores y dispositivos de control.
* **Programación**, mediante Arduino.
* **Construcción**, mediante la aplicación de la tecnología al espacio de cultivo.
* **Energías renovables**, mediante la integración con la generación fotovoltaica.
* **Digitalización**, mediante la adquisición y tratamiento de información.

---

## 11. Registro de experimentación

Para documentar las pruebas se recomienda utilizar una tabla como la siguiente:

| Fecha | Variable    | Sensor/dispositivo | Valor obtenido | Unidad | Condiciones | Observaciones |
| ----- | ----------- | ------------------ | -------------- | ------ | ----------- | ------------- |
|       | Temperatura |                    |                | °C     |             |               |
|       | Iluminación |                    |                |        |             |               |
|       | pH          |                    |                |        |             |               |
|       | Ventilación |                    |                |        |             |               |
|       | Movimiento  |                    |                |        |             |               |

Este registro permitirá documentar la evolución de la experiencia y facilitará posteriormente la comparación de resultados.

---

## 12. Aprendizaje basado en la experimentación

La experiencia con Arduino se desarrolló como un proceso de aprendizaje eminentemente práctico.

El alumnado tuvo que enfrentarse a situaciones reales de prueba y error, analizando los resultados obtenidos y modificando progresivamente la programación o la configuración del sistema.

Este enfoque permite desarrollar competencias relacionadas con:

* Pensamiento lógico.
* Programación.
* Resolución de problemas.
* Interpretación de datos.
* Trabajo autónomo.
* Experimentación científica.
* Trabajo interdisciplinar.
* Competencia digital.

Además, permite comprender que el desarrollo de una solución tecnológica requiere sucesivas fases de prueba, comprobación y mejora.

---

## 13. Estado actual de la documentación técnica

Esta documentación recoge las variables y el enfoque general de la experiencia realizada dentro del proyecto.

Para garantizar la **trazabilidad y fidelidad del trabajo desarrollado**, los datos técnicos concretos deberán completarse a partir de la configuración realmente utilizada durante las pruebas.

Queda pendiente incorporar, cuando se disponga de la información original:

* Modelo exacto de placa Arduino.
* Modelo de cada sensor.
* Esquemas de conexión.
* Distribución de pines.
* Librerías utilizadas.
* Código original desarrollado durante las pruebas.
* Procedimientos de calibración.
* Valores y registros obtenidos.
* Fotografías del montaje.
* Resultados de las pruebas.

No se incorporan datos técnicos no verificados con el fin de mantener la documentación del proyecto fiel al trabajo efectivamente realizado.

---

## 14. Evolución prevista

La experimentación inicial constituye una base para futuras ampliaciones del sistema.

Entre las posibles líneas de evolución se encuentran:

* Integración de diferentes sensores.
* Registro automático de datos.
* Visualización de información.
* Comunicación inalámbrica.
* Automatización de actuadores.
* Control de ventilación.
* Gestión de variables ambientales.
* Integración con sistemas IoT.
* Comunicación mediante tecnologías de largo alcance.
* Análisis histórico de datos.

La evolución hacia un sistema conectado permitiría avanzar desde una experiencia de sensorización básica hacia un modelo de **agricultura inteligente y cultivo protegido digitalizado**.

---

## 15. Conclusión

La experimentación con Arduino representa una de las líneas tecnológicas del proyecto EcoTech Hybrid.

El estudio de temperatura, iluminación, pH, ventilación y movimiento permite introducir la sensorización y la automatización dentro de un proyecto interdisciplinar relacionado con la agricultura, la construcción y las energías renovables.

Más allá del resultado técnico concreto, la experiencia tiene un importante valor educativo, ya que permite al alumnado aprender mediante la experimentación, afrontar problemas reales y comprender la relación existente entre sensores, datos, programación y toma de decisiones.

Esta documentación servirá como base para incorporar progresivamente los detalles técnicos, evidencias y resultados obtenidos durante el desarrollo del proyecto.
