---
Fecha de creación: 2025-11-11 18:23
Fecha de Modificación: 2025-11-11 18:23
tags: 
Tema:
---


## 📚 Idea/Concepto 
Un Broker es un componente en las arquitecturas Event Driven que permite manejar el flujo de datos de un mecanismo conocido como Broadcast. Imagine el flujo de datos en el Broker de la siguiente manera: el evento iniciador se envía a un canal en el broker para ser transmitido a los procesadores de eventos, cuando un procesador de eventos completa una tarea, anuncia asincrónicamente su acción al resto del sistema mediante la creación de un evento de procesamiento, el cual se envía de vuelta al bróker para su posterior procesamiento si es necesario. Esta variante no utiliza un mediador o orquestador, por lo que la hace más apta para el procesamiento de eventos relativamente simple.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Requerimientos No Funcionales]]
- [[Requerimientos de Negocio]]
- [[Acoplamiento en desarrollo de software]]
- [[Cohesión en desarrollo de software]]
- [[Trade-off en el diseño y arquitectura de software]]
- [[Estrategia de modelado de la arquitectura por puntos de vista]]
- [[Disponibilidad de la aplicación]]
- [[Arquitectura Event Driven]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 