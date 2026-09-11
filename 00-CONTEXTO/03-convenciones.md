# Convenciones

Documento normativo. Se aplica a toda la rama `DOCUMENTACION` y a las ramas de manual.

## Niveles jerárquicos

Definiciones aplicadas para clasificar cada caja del flujo.

| Nivel | Definición |
|---|---|
| **Macroproceso** | Agrupación mayor del MGO. MP8, MP21. |
| **Proceso** | Conjunto de subprocesos con un resultado propio y un dueño identificable. |
| **Subproceso** | Bloque con entradas y salidas propias dentro de un proceso; agrupa actividades. |
| **Actividad** | Unidad de trabajo con responsable y resultado verificable; agrupa tareas. |
| **Tarea** | Paso operativo concreto dentro de una actividad. |

Dos elementos que **no son niveles jerárquicos** pero se representan en el flujo:

| Elemento | Definición |
|---|---|
| **Control** | Verificación que valida o autoriza el avance del flujo. |
| **Decisión** | Compuerta que bifurca el flujo según una condición. |

### Ejemplo de anidamiento en el MP8

```
Macroproceso  ·  MP8 · Gestión de Personas
  Proceso     ·  P4 · Desarrollo organizacional
    Subproceso   ·  Formación
      Actividad     ·  A4 · Ejecución de la formación   (cajas 8 a 12)
        Tarea          ·  Formación e-learning: nivelación teórica de fundamentos técnicos
```

## Estados de definición

El estado indica el grado de madurez de cada nombre, agrupación o jerarquía. En el borrador original se codificaba por **color del texto**; aquí se codifica de forma explícita.

| Estado | Marca en este repositorio | Significado |
|---|---|---|
| **Confirmado** | `Confirmado` | Definido y acordado en la revisión con la contraparte. No requiere validación adicional. |
| **Propuesta** | `Propuesta` | Nombre, agrupación o jerarquía propuesta con base en APQC y en los antecedentes levantados. **Requiere validación.** |
| **Pendiente** | `Pendiente` | Sin definición todavía. Se deja explícitamente vacío para no inventar contenido. |
| **Por definir** | `Por definir` | La caja existe pero su nivel jerárquico no está resuelto. |

**Regla de oro:** donde ninguna fuente formal permite decidir, la caja queda marcada como `Pendiente` en lugar de rellenarse.

**Cómo se cierran:** cada respuesta se marca sobre el mismo documento; el estado pasa de `Propuesta` o `Pendiente` a `Confirmado`. Así el repositorio registra qué se validó y qué sigue abierto, sin necesidad de una planilla aparte.

## Regla de numeración de cajas

Numeración **serpenteante** sobre el diagrama de flujo:

```
1ª fila · de izquierda a derecha
  caja 1  →  caja 2  →  caja 3  →  caja 4
                                     ↓
2ª fila · de derecha a izquierda
  caja 8  ←  caja 7  ←  caja 6  ←  caja 5
    ↓
3ª fila · de izquierda a derecha
  caja 9  →  caja 10 →  caja 11 →  caja 12
```

Dos reglas que se derivan:

1. **Las decisiones y los controles no consumen número.** Se representan en el flujo, pero se listan con `—` en la columna de número.
2. Por eso, en la fase 1, la caja 11 es «Emitir organigrama, perfil de cargo y costo organigrama», aunque antes de ella exista la decisión «¿Aprobado por Gerencia de Personas?».

## Marca «específico de Arauco»

Las cajas señaladas como **específico de Arauco** son propias de la compañía y **no existen en el PCF genérico** de APQC. Son puntos de interés particular: no tienen código APQC de respaldo, por lo que su clasificación depende exclusivamente del criterio interno y de la validación con la contraparte.

## Codificación de fases, procesos y actividades

| Prefijo | Significado | Ejemplo |
|---|---|---|
| `MP` | Macroproceso | `MP8` |
| `F` | Fase del flujo único levantado | `F11` |
| `P` | Proceso preliminar de la arquitectura | `P4` |
| `A` | Actividad dentro de un subproceso | `A4` |

Nota: la numeración `F` corresponde al **flujo único MP8 v3**, que es el artefacto de levantamiento. La numeración `P` corresponde a la **arquitectura de procesos**, que es el entregable. No son equivalentes uno a uno: la tabla de equivalencia está en [`../10-MP8/01-arquitectura-preliminar.md`](../10-MP8/01-arquitectura-preliminar.md).

## Actores del MP8

Roles que aparecen en las cajas del flujo, tal como fueron levantados.

| Actor | Abreviatura |
|---|---|
| Equipo Atracción y Selección | A&S |
| Consultora de Selección | — |
| Generalista de Personas | — |
| Superintendente de Personas | — |
| Gerencia de Personas | — |
| Subgerencia de Formación / Jefe de Formación | SG Formación |
| Subgerencia de Formación y Cultura | SG Formación y Cultura |
| Subgerencia de Compensaciones y Beneficios | SG Compensaciones y Beneficios |
| Especialista de Formación | — |
| Área Solicitante / Jefatura Solicitante | — |
| Jefatura Directa | — |
| Tutores Internos | — |
| Superintendentes e Ingenieros | — |
| Gerente de Planta | — |
| Gerencia Técnica | — |
| Recursos Humanos Local | RRHH Local |
| Equipo de Inclusión / DEI | DEI |
| Terapeuta Ocupacional | — |
| Salud y Seguridad Ocupacional | SSO |
| Estructura de Personal / Estructura y Planificación | EP |
| Trabajador | — |

## Sistemas de apoyo

| Sistema | Uso |
|---|---|
| **SuccessFactors** (`SSFF`) | Sistema corporativo de gestión de personas. Módulos usados: Reclutamiento e Incorporación de Personal, Desempeño, y módulos complementarios de planes de desarrollo. |
| Portal ARAUCO de empleo | Publicación interna y externa de vacantes. |
| LinkedIn y portales externos | Fuentes de búsqueda. |
| Sistema de remuneraciones | Ingreso de ajustes salariales. |
| Microsoft Office 365 | Herramienta de consolidación (licencia corporativa). |

## Siglas del dominio

| Sigla | Significado |
|---|---|
| **MGO** | Modelo de Gestión Operacional (Arauco) |
| **APQC PCF** | Process Classification Framework del American Productivity & Quality Center |
| **COSO II** | Marco de Enterprise Risk Management de COSO (2004; actualizado 2017) |
| **ERM** | Enterprise Risk Management |
| **RACI** | Responsible, Accountable, Consulted, Informed |
| **KRI** | Key Risk Indicator |
| **PcD** | Persona con Discapacidad |
| **EPP** | Elemento de Protección Personal |
| **HAL** | Encuesta aplicada en evaluación psicolaboral |
| **compa-ratio** | Sueldo dividido por el punto medio de su banda salarial |
| **AFE** | Actividad Formativa Equivalente |
| **MSGIC** | Magíster en Sistemas de Gestión Integral de la Calidad |
