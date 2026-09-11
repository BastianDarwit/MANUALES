# MP8 · Estado de la consolidación

**Última actualización:** consolidación inicial desde `Borrador preliminar - Manual de Procesos Gestión de Personas.pptx`.

## Qué es lo que hay hoy

La **arquitectura preliminar de procesos del MP8**, construida sobre el diseño del manual de procesos de la compañía (estructura heredada del manual del MP15). Traduce a estructura de procesos la clasificación de «cajitas» revisada con Isi para las **fases 1 a 14** del flujo único MP8 v3.

## Qué NO es

No es el manual final ni una definición cerrada. Los nombres, agrupaciones y jerarquías marcados como `Propuesta` o `Pendiente` requieren validación. Las fases **0 y 15 a 18 no fueron revisadas** y por eso no se modelan.

## Cifras

| Métrica | Valor |
|---|---|
| Procesos preliminares | **5** |
| Subprocesos identificados | **17** |
| Fases clasificadas | **14** |
| Fases aún sin revisar | **5** |
| Cajas numeradas clasificadas | **185** según el cuadro de cobertura · **191** al sumar las tablas de detalle |
| Decisiones identificadas | **13** |
| Controles identificados | **6** |

## Cobertura por fase

| Fase | Nombre | Cajas | Decisiones | Controles | Estado |
|---|---|---|---|---|---|
| F0 | Fase 0 | — | — | — | **No incluida en la revisión** |
| F1 | Necesidad estratégica y plan de dotación | 11 | 1 | — | Clasificada |
| F2 | Valoración de cargo y banda de renta | 13 | — | — | Clasificada |
| F3 | Requisición y apertura de vacante | 15 | 1 | — | Clasificada |
| F4 | Reclutamiento y filtro curricular | 9 | — | — | Clasificada |
| F5 | Revisión del área solicitante | 7 | 1 | — | Clasificada |
| F6 | Evaluación área selección · psicolaboral | 11 | 1 | — | Clasificada |
| F7 | Evaluación área solicitante · entrevistas | 10 | 2 | — | Clasificada |
| F8 | Examen preocupacional | 10 | 1 | — | Clasificada |
| F9 | Flujo de contratación y carta oferta | 16 | 2 | — | Clasificada |
| F10 | Onboarding e incorporación | 8 | — | — | Clasificada |
| F11 | Formación y habilitación | 19 | 1 | — | Clasificada |
| F12 | Gestión del desempeño · ciclo anual | 30 | 1 | — | Clasificada |
| F13 | Carrera, sucesión y movilidad | 9 | — | 1 | Clasificada |
| F14 | Revisión de renta y beneficios | 17 | 2 | 5 | Clasificada |
| F15 | Administración de nómina | — | — | — | **No revisada** |
| F16 | Clima, asistencia y retención | — | — | — | **No revisada** |
| F17 | Desvinculación y salida | — | — | — | **No revisada** |
| F18 | Backbone de datos y gobernanza | — | — | — | **No revisada** |

> Nota de consistencia: F13 se reporta con 9 cajas numeradas en el cuadro de cobertura del borrador, pero su tabla de detalle lista 10 cajas. F14 se reporta con 17 cajas en el cuadro de cobertura y su tabla de detalle lista 22. **Ambas discrepancias hay que resolverlas** — ver [`03-brechas-y-preguntas-abiertas.md`](03-brechas-y-preguntas-abiertas.md).

## Estado por proceso

| Proceso | APQC | Estado | Subprocesos |
|---|---|---|---|
| **P1** · Necesidad estratégica y plan de dotación | 7.1.1 · 7.1.2 | `Confirmado` | 3 |
| **P2** · Valoración de cargo y banda de renta | 7.1.2.2 · 7.1.2.15 · 7.5.1 | `Confirmado` proceso / `Propuesta` en la equivalencia de fase | 4 |
| **P3** · Atracción y selección de personas | 7.2 · fases 3 a 10 | `Propuesta` | 5 |
| **P4** · Desarrollo organizacional | 7.3 · 7.6.1 | `Confirmado` | 3 |
| **P5** · Compensaciones y beneficios | 7.5.1 · 7.5.2 | `Propuesta` | 2 |

## Bloqueo para redactar el manual

Hay **9 preguntas abiertas** que deben cerrarse antes de llenar fichas resumen, SIPOC y flujogramas. Están en [`03-brechas-y-preguntas-abiertas.md`](03-brechas-y-preguntas-abiertas.md).

## Próximos pasos

| # | Paso | Estado |
|---|---|---|
| 1 | **Validar con Isi.** Cerrar las nueve preguntas abiertas y fijar los nombres propuestos. | Pendiente |
| 2 | **Completar el alcance.** Revisar las fases 0 y 15 a 18 e incorporarlas a la arquitectura. | Pendiente |
| 3 | **Redactar el manual.** Recién entonces llenar fichas resumen, SIPOC y flujogramas por subproceso. | Bloqueado por 1 y 2 |

## Brecha frente al indicador CAP

El CAP exige los **cinco niveles jerárquicos completos**. Estado real:

| Nivel | Cobertura |
|---|---|
| Macroproceso | 1 de 1 — completo |
| Proceso | 5 identificados, 3 confirmados · **faltan los procesos de F0 y F15–F18** |
| Subproceso | 17 identificados · varios con nombre `Propuesta` |
| Actividad | Parcial. F3 completo sin jerarquía interna; F12 y F13 con actividades sin nombre |
| Tarea | Parcial. F4–F10 tienen tareas identificadas pero **sujetas a depuración**; F1, F2, F11, F13, F14 están clasificadas a nivel de actividad, sin desglose de tareas |

Además, el anteproyecto exige documentar por nivel: **nombre, descripción, entradas y salidas, responsables (RACI simplificado), sistemas de apoyo y frecuencia de ejecución**. Hoy el borrador solo cubre nombre, responsable parcial y sistema parcial. **Descripción, entradas/salidas, RACI completo y frecuencia están sin levantar en todas las fases.**
