# Tarea: Mi prompt avanzado 
## Tarea elegida
Explicar de forma sencilla y estructurada los comandos básicos de Git (`git add`, `git commit` y `git push`) para un estudiante que recién empieza a programar.
## Version 1: prompt basico 
```text
Explica la diferencia entre git add, git commit y git push.
```
## Version 2
```text
<rol>Actúa como un profesor de programación enseñando a un alumno de primer ciclo que nunca ha usado la terminal.</rol>
<tarea>Explica de forma muy sencilla la diferencia entre git add, git commit y git push.</tarea>
```
## Version 3: prompt final
```text
<rol>Actúa como un profesor de programación enseñando a un alumno de primer ciclo que nunca ha usado la terminal.</rol>
<tarea>Explica de forma muy sencilla la diferencia entre git add, git commit y git push.</tarea>
<formato>Responde usando analogías breves. Debes seguir estrictamente el formato de los ejemplos mostrados a continuación.</formato>
<ejemplos>
"git init": "Crear el proyecto" -> "Es como comprar una libreta nueva en blanco para tus apuntes."
"git clone": "Descargar el proyecto" -> "Es como sacarle fotocopias a los apuntes de tu compañero."
</ejemplos>
```
```text
Revisa tu respuesta: ¿olvidaste mencionar que git commit siempre necesita llevar un mensaje descriptivo con -m? Agrega ese detalle manteniendo el formato corto.
```
## Tecnicas usadas en el prompt final 

| Técnica | Parte del prompt que la aplica |
| :--- | :--- |
| **Prompt estructurado** | Uso de etiquetas `<rol>`, `<tarea>`, `<formato>`, `<ejemplos>`. |
| **Role prompting** | `<rol>Actúa como un profesor de programación enseñando a un alumno...` |
| **Few-shot** | Bloque `<ejemplos>` mostrando el formato exacto `"Comando": "Acción" -> "Analogía"`. |
| **Autocrítica** | Segundo prompt: `Revisa tu respuesta: ¿olvidaste mencionar que git commit...` |

## Evaluacion del resultado

| Qué revisar | Cumple (Sí / No) |
| :--- | :--- |
| ¿Utiliza un lenguaje sencillo y sin jerga técnica avanzada? | Sí |
| ¿Respeta el formato exacto de una sola línea por comando dado en el ejemplo? | Sí |
| ¿Mantiene el rol de profesor enseñando a un novato? | Sí |
| ¿La autocrítica logró que añada correctamente el detalle del `-m`? | Sí |

## Por que elegi estas tecnicas

* Elegí el prompt estructurado y el rol para asegurar que el tono de la respuesta fuera el adecuado para un principiante, evitando que la IA responda como un manual técnico. Sumé el few-shot (ejemplos) porque es la mejor técnica para obligar a la IA a entregar información de forma resumida y visualmente limpia (ideal para apuntes rápidos). Por último, la autocrítica fue útil para simular el proceso de revisar una explicación docente y añadir ese "detalle clave" que a los profesores a veces se les escapa en el primer intento.
