# Guía de experimentación con Arduino

## 1. Finalidad

Esta guía recoge una metodología básica para experimentar con Arduino dentro del proyecto **EcoTech Hybrid**.

El objetivo no es únicamente conseguir que un sensor funcione, sino comprender el proceso completo:

**sensor → lectura → programación → interpretación → respuesta → mejora**

---

## 2. Metodología de trabajo

La experimentación se plantea de forma progresiva.

### Paso 1. Identificar la variable

Determinar qué variable se quiere estudiar:

* Temperatura.
* Iluminación.
* pH.
* Ventilación.
* Movimiento.

### Paso 2. Identificar el dispositivo

Determinar qué sensor o dispositivo permite obtener información sobre esa variable.

### Paso 3. Realizar la conexión

Conectar el dispositivo a la placa Arduino siguiendo las especificaciones técnicas correspondientes.

### Paso 4. Preparar la programación

Desarrollar el código necesario para realizar la lectura de la información.

### Paso 5. Realizar una primera prueba

Comprobar que el sistema responde y que se reciben datos.

### Paso 6. Analizar los resultados

Comparar los valores obtenidos con las condiciones reales observadas.

### Paso 7. Modificar y repetir

Cuando se detecta un problema, modificar la programación o configuración y volver a realizar la prueba.

### Paso 8. Documentar

Registrar:

* Fecha.
* Dispositivo utilizado.
* Condiciones de la prueba.
* Valores obtenidos.
* Problemas detectados.
* Solución aplicada.
* Observaciones.

---

## 3. Filosofía de aprendizaje

La experiencia se basa en un proceso de:

**probar → observar → detectar → modificar → volver a probar**

Este planteamiento favorece el aprendizaje autónomo y permite al alumnado comprender que el desarrollo de un sistema tecnológico requiere pruebas sucesivas y resolución de problemas.

---

## 4. Registro de pruebas

| Prueba | Fecha | Variable | Configuración | Resultado | Problema | Solución | Observaciones |
| ------ | ----- | -------- | ------------- | --------- | -------- | -------- | ------------- |
| 1      |       |          |               |           |          |          |               |
| 2      |       |          |               |           |          |          |               |
| 3      |       |          |               |           |          |          |               |
| 4      |       |          |               |           |          |          |               |

---

## 5. Integración de sensores

Una vez comprobado individualmente el funcionamiento de cada elemento, se puede plantear la integración progresiva de varias variables.

Por ejemplo:

```text
Temperatura ─┐
Iluminación ─┤
pH ──────────┼──→ Arduino ──→ Análisis / Control
Movimiento ──┤
Ventilación ─┘
```

La integración deberá realizarse progresivamente para facilitar la identificación de errores.

---

## 6. Recomendaciones

* Probar inicialmente cada sensor de forma independiente.
* Documentar cada modificación realizada.
* Evitar modificar simultáneamente demasiados elementos.
* Guardar las versiones funcionales del código.
* Registrar los errores encontrados.
* Contrastar las lecturas con las condiciones reales.
* Mantener identificados los componentes utilizados.
* Documentar las soluciones encontradas.

---

## 7. Resultado esperado

El objetivo final es disponer de una base experimental que permita avanzar hacia un sistema de monitorización y automatización aplicado al entorno de cultivo protegido del proyecto EcoTech Hybrid.

La experiencia podrá ampliarse posteriormente mediante comunicaciones inalámbricas, almacenamiento de datos, visualización de información y automatización de actuadores.
