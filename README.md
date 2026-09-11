# MANUALES

Consolidación de los manuales de procesos de los macroprocesos de apoyo del **Negocio de Celulosa de Celulosa Arauco y Constitución S.A.**, levantados mediante entrevistas y sesiones de trabajo con los dueños de proceso a nivel de negocio.

Este repositorio sostiene el **OE1** del trabajo de AFE (MSGIC, Universidad de La Frontera): modelar la arquitectura de procesos de MP8 y MP21 en cinco niveles jerárquicos bajo el Modelo de Gestión Operacional (MGO). Los manuales resultantes son el insumo del OE2 (evaluación de riesgos COSO II por tarea) y del OE3 (sistema de gestión de riesgos).

## Ramas

| Rama | Propósito |
|---|---|
| `main` | Rama base. No se trabaja aquí. |
| `DOCUMENTACION` | **Fuente única de verdad del contexto.** Alberga lo más reciente de acuerdo a lo levantado en cada reunión: marco del AFE, contexto organizacional, convenciones, arquitectura vigente, brechas abiertas y bitácora de reuniones. |
| `MANUAL-MP8` | Redacción del manual de procesos del MP8 · Gestión de Personas. |
| `MANUAL-MP21` | Redacción del manual de procesos del MP21 · Servicios Generales. |

**Estado actual:** solo se está consolidando el **MP8**. El MP21 no ha iniciado levantamiento.

## Flujo de trabajo

```
reunión / entrevista
        │
        ▼
DOCUMENTACION ──► se registra en la bitácora, se actualiza la arquitectura
        │          vigente y se cierran o abren preguntas
        │
        ▼
MANUAL-MP8 ──► se redacta el manual sobre la arquitectura ya confirmada
```

Regla: **nada entra a `MANUAL-MP8` mientras su definición siga marcada como propuesta o pendiente en `DOCUMENTACION`.**

## Estructura de la rama DOCUMENTACION

```
00-CONTEXTO/          marco del AFE, contexto Arauco, convenciones, fuentes
10-MP8/               arquitectura vigente, detalle caja por caja, brechas, bitácora
20-MP21/              placeholder: sin levantamiento
90-REFERENCIAS/       bibliografía del AFE
fuentes/              documentos fuente operativos
```

Empezar por [`00-CONTEXTO/00-INDICE.md`](00-CONTEXTO/00-INDICE.md).
