---
title: "Mejores prácticas para la construcción de modelos"
chapter: true
weight: 80
---

![Header](/images/BestPractices.jpg)

## Definición de Intenciones
Un modelo es más que intenciones, también es un flujo y un viaje.
Definición de intenciones:
* Examine primero el flujo comercial (independientemente de si el bot puede hacer algo o no) antes de definir las intenciones y las ranuras
* Defina las intenciones, definiciones: estas deben estar basadas en los objetivos comerciales. ¿Qué hacen ya aquí? (es decir) presione 1 para ventas, presione 2 para soporte, etc.
* Asegúrese de que sus definiciones tengan límites claros, sin superposición
## Ejemplos de intención

* Proporcione al menos 20-30 ejemplos típicos por intención
* Asegúrese de proporcionar variaciones:
     * en forma de preguntas/declaraciones que las personas pueden hacer
     * en las palabras clave que pueden representar la intención
     * asegúrese de incluir sinónimos de intención (reservar un hotel, reservar una habitación, hacer una reserva, etc.)
* Si la intención tiene ranuras (entidades) para llenar,
     * asegúrese de definir la entidad y sus posibles valores
     * incluir sinónimos de valor
     * proporcionar ejemplos de intención con y sin entidades en las oraciones
     * seleccione avisos (prompts) predeterminados o personalizados para cada entidad
