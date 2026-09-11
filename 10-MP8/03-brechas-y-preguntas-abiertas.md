# MP8 · Brechas y preguntas abiertas

Este documento es el **bloqueador del manual**. Mientras haya entradas sin cerrar, no se llenan fichas resumen, SIPOC ni flujogramas.

## Las 9 preguntas para validar

Definiciones que requieren confirmación antes de completar el manual.

| # | Pregunta | Afecta a | Estado |
|---|---|---|---|
| 01 | ¿El proceso padre de la fase 3 es «Atracción y selección de personas» o se define otro nombre? | P3 completo | Abierta |
| 02 | ¿Las fases 4 a 10 se agrupan en los cuatro subprocesos propuestos o en otra estructura? | P3 · F4–F10 | Abierta |
| 03 | ¿«Carrera, sucesión y movilidad» queda bajo «Desarrollo organizacional»? | P4 · F13 | Abierta |
| 04 | ¿«Remuneración y compensación» y «Beneficios» son subprocesos de un proceso mayor? | P5 · F14 | Abierta |
| 05 | ¿Ese proceso mayor absorbe también la fase 2 o la fase 2 se mantiene como proceso propio? | P2 y P5 | Abierta |
| 06 | ¿Cómo se llama el subproceso 4 de la fase 2 y qué cajas lo componen finalmente? | P2 · F2 cajas 10–13 | Abierta |
| 07 | ¿Dónde se aloja el calendario anual de evaluación que salió de la fase 12? | F12 caja 1 | Abierta |
| 08 | ¿Qué nombre reciben las actividades sin denominar de la fase 13? | F13 · A3 y A5 | Abierta |
| 09 | ¿Las cajas «Ola» de la fase 12 se conservan como cajas del flujo? | F12 cajas 5 y 30 | Abierta |

**Cómo se cierran:** cada respuesta se marca sobre este mismo documento y sobre la arquitectura. El estado pasa de `Propuesta` o `Pendiente` a `Confirmado`. Así el repositorio registra qué se validó y qué sigue abierto, sin necesidad de una planilla aparte.

## Observaciones y tensiones detectadas

Puntos donde la clasificación quedó abierta o donde el contenido tensiona la agrupación.

| Dónde | Qué se observó | Qué hay que resolver |
|---|---|---|
| **F1 · caja 7** | «Estimar dotación futura según proyecciones» rotula el subproceso 2, pero no quedó dentro de las actividades 2–6. | Confirmar si es actividad de cierre o solo el rótulo. |
| **F2 · cajas 12–13** | Revalorización anual del grado y administración transversal del marco quedaron en el subproceso 4. | Por contenido podrían pertenecer al subproceso 3, que es justamente la administración periódica. |
| **F3** | El subproceso está definido, pero no la jerarquía interna de sus 15 cajas. | Definir qué cajas son actividades y qué cajas son tareas. |
| **F4 a F10** | Cada fase es una actividad y sus cajas son tareas. | Depurar las tareas demasiado operativas para el manual. |
| **F11** | 19 cajas sin agrupar. | Se propone una agrupación en 6 actividades según APQC 7.3.4. Validar. |
| **F12 · caja 1** | «Establecer el calendario del proceso de evaluación» es de nivel estratégico. | Requiere un proceso transversal de programación anual que hoy no existe. |
| **F12 · cajas 5 y 30** | Los marcadores «Ola 2 · mayo» y «Ola 3 · octubre a diciembre» no quedaron asignados. | Definir si son cajas del flujo o solo hitos de calendario. |
| **F13 · cajas 5 y 6** | La caja 5 es control; la caja 6 quedó sin definir entre control y tarea. | Cerrar la definición de la caja 6. |
| **F14** | Dos bloques: remuneración y beneficios. | Se propone que sean subprocesos de un mismo proceso. Validar. |

## Brechas adicionales detectadas en la consolidación

Estas no venían marcadas en el borrador. Surgieron al consolidar y contrastar con lo que el anteproyecto exige.

| # | Brecha | Impacto | Acción propuesta |
|---|---|---|---|
| B1 | **Fases 0 y 15 a 18 sin revisar.** Administración de nómina, clima/asistencia/retención, desvinculación y salida, backbone de datos y gobernanza. | El CAP no puede llegar a 100%. Además, «desvinculación» está en la definición del MP8 del anteproyecto (ciclo de vida completo del colaborador), por lo que su ausencia es una brecha de alcance, no solo de avance. | Agendar revisión de F0 y F15–F18 con la contraparte. |
| B2 | **Discrepancia en el conteo de cajas.** F13: 9 cajas en el cuadro de cobertura vs. 10 en la tabla de detalle. F14: 17 vs. 22. | El total pasa de 185 a 191 según qué fuente se use. Afecta el denominador del CAP. | Recontar F13 y F14 sobre el diagrama y fijar la cifra oficial. |
| B3 | **Atributos exigidos por el anteproyecto sin levantar.** El OE1 exige documentar por nivel: nombre, **descripción**, **entradas y salidas**, **responsables bajo RACI simplificado**, **sistemas de apoyo** y **frecuencia de ejecución**. | Hoy solo hay nombre, responsable parcial y sistema parcial. Sin descripción, entradas/salidas, RACI completo ni frecuencia en **ninguna** fase. | Definir una ficha estándar y levantar estos atributos en las próximas sesiones. Es trabajo de volumen: aplica a 191 cajas. |
| B4 | **Nivel de tarea incompleto.** Solo F4–F10 tienen tareas identificadas, y están sujetas a depuración. F1, F2, F11, F13 y F14 están clasificadas a nivel de actividad. | El OE2 evalúa riesgos **por tarea**. Sin nivel de tarea completo, el TCER no tiene universo definido. | Desglosar tareas en F1, F2, F11, F13 y F14. |
| B5 | **Anidación inválida en F13 caja 7.** «Formación para el desarrollo» está clasificada como subproceso dentro del subproceso «Carrera, sucesión y movilidad». | Contradice las definiciones de nivel jerárquico de las convenciones. | Reclasificar como actividad, o elevar a subproceso hermano, o modelarla como referencia cruzada al subproceso Formación de F11. |
| B6 | **Cajas «específico de Arauco» sin respaldo APQC.** 8 cajas identificadas (F6·11, F7·8, F7·9, F8·10, F10·2, F11·12, F11·14, F11·15, F11·17). | Su clasificación depende solo del criterio interno. Son también candidatas naturales a riesgo operacional en el OE2, por ser prácticas no estandarizadas en el marco genérico. | Validar cada una explícitamente con la contraparte y registrar la justificación. |
| B7 | **F12 caja 1 no tiene proceso donde alojarse.** Requiere un proceso transversal de programación anual que no existe en la arquitectura. | Deja una caja huérfana. | Decidir: crear un proceso transversal, o dejarla fuera del alcance del MP8 documentando la exclusión. |
| B8 | **Nivel de detalle de tareas sin criterio fijado.** F4 a F10 arrastran la nota «tareas sujetas a revisión: algunas pueden ser demasiado operativas». | Sin criterio, la depuración es arbitraria y el conteo de tareas es inestable. | Fijar un criterio explícito de granularidad mínima y aplicarlo uniformemente. |

## Orden sugerido de resolución

```
1. Cerrar preguntas 01 a 06   ──►  fija la estructura de procesos y subprocesos
2. Resolver B2, B5, B7        ──►  limpia la arquitectura
3. Cerrar preguntas 07 a 09   ──►  resuelve las cajas huérfanas de F12
4. Fijar criterio B8          ──►  habilita el desglose de tareas
5. Resolver B4 y B3           ──►  completa niveles y atributos
6. Levantar F0 y F15–F18 (B1) ──►  cierra el alcance
7. Recién entonces: redactar
```

Las preguntas 01 a 06 son la ruta crítica: **la mitad de la arquitectura del MP8 está marcada como `Propuesta` y depende de ellas.**
