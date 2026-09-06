# Esquemas de conexión Arduino

## 1. Finalidad

Este documento está destinado a recoger los esquemas de conexión correspondientes a los elementos de sensorización y automatización utilizados en el proyecto **EcoTech Hybrid**.

Los esquemas definitivos se incorporarán a partir del montaje realmente utilizado durante la experimentación.

---

## 2. Esquema general

La arquitectura experimental puede representarse conceptualmente de la siguiente manera:

```text
                  ┌─────────────────┐
                  │     ARDUINO     │
                  │                 │
                  └────────┬────────┘
                           │
          ┌────────────────┼────────────────┐
          │        │       │       │        │
          ▼        ▼       ▼       ▼        ▼
     Temperatura  Luz      pH  Ventilación Movimiento
          │        │       │       │        │
          └────────┴───────┴───────┴────────┘
                           │
                           ▼
                  Datos / Automatización
```

Este esquema es conceptual y no representa todavía la distribución física de pines.

---

## 3. Conexiones

La tabla siguiente se utilizará para documentar las conexiones reales:

| Dispositivo            | Alimentación | Señal     | Pin Arduino | Observaciones |
| ---------------------- | ------------ | --------- | ----------- | ------------- |
| Sensor de temperatura  | Pendiente    | Pendiente | Pendiente   |               |
| Sensor de iluminación  | Pendiente    | Pendiente | Pendiente   |               |
| Sensor de pH           | Pendiente    | Pendiente | Pendiente   |               |
| Sistema de ventilación | Pendiente    | Pendiente | Pendiente   |               |
| Sensor de movimiento   | Pendiente    | Pendiente | Pendiente   |               |

---

## 4. Esquemas detallados

### 4.1 Temperatura

Pendiente de incorporar el esquema correspondiente al sensor realmente utilizado.

### 4.2 Iluminación

Pendiente de incorporar el esquema correspondiente al sensor realmente utilizado.

### 4.3 pH

Pendiente de incorporar el esquema correspondiente al sensor realmente utilizado.

### 4.4 Ventilación

Pendiente de incorporar el esquema correspondiente al sistema realmente utilizado.

### 4.5 Movimiento

Pendiente de incorporar el esquema correspondiente al sensor realmente utilizado.

---

## 5. Documentación gráfica

Cuando se disponga de los esquemas y fotografías originales del montaje, se incorporarán en este apartado para facilitar la reproducción de la experiencia.

---

## 6. Trazabilidad

Los esquemas definitivos deberán corresponder al montaje realmente utilizado durante las pruebas.

No se incorporarán conexiones, componentes o asignaciones de pines que no hayan sido comprobados previamente.

Esta metodología garantiza que la documentación técnica publicada en el repositorio sea coherente con el trabajo desarrollado por el alumnado.
