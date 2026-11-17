# Bitacora de tecnicas avanzadas

Laboratorio 07: Tecnicas Avanzadas de Prompting. Herramienta de IA usada: (escribe aqui cual usaste)
##	Ejercicio	2:	Zero-shot, one-shot y few-shot
| Tipo | Aciertos (de 5) | Formato de la respuesta | Todas con el mismo formato (Si/No) |
|---|---|---|---|
| Zero-shot |NO |DESIGUAL |SI, PERO NO ERA EL FORMATO |
| One-shot |SI |ESTRUCTURADO |SI |
| Few-shot |SI |ESTRUCTURADO |SI |

##	Ejercicio	3:	Chain of Thought
| Pedido | Respuesta de la IA | Muestra los pasos (Si/No) | Correcta (Si/No) |
|---|---|---|---|
| Directo |CORRECTO |NO |SI |
| Paso a paso |CORRECTO |SI |SI |

##	Ejercicio	4:	Role prompting
| Version | Vocabulario (sencillo/tecnico) | Usa ejemplos o codigo | A quien le sirve mas |
|---|---|---|---|
| A. Sin rol |SENCILLO |SI |APRENDICES |
| B. Rol docente |SENCILLO |SI |ESTUDIANTES |
| C. Rol senior |TECNICO |SI |PERSONAL TECNICO |

##	Ejercicio	5:	Descomposicion
Registrar en la bitacora una linea por paso indicado que te entrego la IA y una linea comparando el resultado con el pedido de una sola vez.

* Simple prompt: La IA devuelve una respuesta general basica de clase para luego ser evidenciado en un codigo de Java todo en una misma respuesta.
* Descomposision de prompt:
* Lista 5 requisitos con sus detlles y objetivos
* Diseña las clases con sus atributos
* Escribe los codigos en java utilizando las clases
* Revisa y sugiere 3 mejoras concretas.
##	Ejercicio	6:	Prompt estructurado y autocritica
```text
(<rol>Actua como analista de pruebas de software.</rol>
<contexto>Login web con correo y contrasena. La cuenta se bloquea despues de 3 intentos fallidos.</contexto>
<tarea>Piensa paso a paso que puede fallar y escribe 6 casos de prueba.</tarea>
<formato>Tabla con las columnas: ID, escenario, datos de entrada, resultado esperado.</formato>
)
Revisa tu tabla: faltan casos limite como campos vacios, correo sin @
o contrasena con espacios? Agrega los que falten e indica cuales agregaste.

```

