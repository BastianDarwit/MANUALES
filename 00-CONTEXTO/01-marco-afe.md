# Marco del AFE

Fuente: `Anteproyecto_Bastian_Darwit_v12_REV_PERSONAL.docx` (versión vigente). Ver [`05-historial-de-cambios-de-alcance.md`](05-historial-de-cambios-de-alcance.md) antes de reutilizar definiciones de versiones anteriores.

## Identificación

| Campo | Valor |
|---|---|
| Programa | Magíster en Sistemas de Gestión Integral de la Calidad (MSGIC) |
| Institución | Facultad de Ingeniería y Ciencias, Universidad de La Frontera |
| Estudiante | Bastián Darwit Vera |
| Profesora Guía | Sonia Salvo Garrido |
| Profesor Co-guía | Manuel Echiburú Fuenzalida |
| Modalidad | AFE (Actividad Formativa Equivalente), investigación aplicada en lugar de tesis |
| Horizonte de ejecución | 20 semanas · aprox. agosto 2026 a enero 2027 |

**Título:** Propuesta de un sistema de gestión de riesgos basado en la metodología COSO II para los macroprocesos de Gestión de Personas (MP8) y Servicios Generales (MP21) de Celulosa Arauco y Constitución S.A.

## Doble rol: empleado y estudiante

El trabajo es **uno solo, visto desde dos perspectivas**. No son dos proyectos paralelos.

- **Como Ingeniero de Gestión de Procesos en Arauco:** levanta MP8 y MP21, produce los manuales de procesos y el análisis de riesgos para uso operacional de la compañía.
- **Como estudiante del MSGIC:** documenta y teoriza ese mismo levantamiento como investigación aplicada, cumpliendo la estructura académica del programa.

El AFE es la **envoltura académica** del trabajo que ya se ejecuta como empleado. Esta distinción debe comunicarse explícitamente en las presentaciones de avance.

## Problema

En las grandes empresas industriales, los macroprocesos de apoyo suelen operar sin un sistema de gestión de riesgos estructurado. En el Negocio de Celulosa de Arauco esto se manifiesta en tres carencias concretas:

1. No existe una arquitectura de procesos formalizada de MP8 y MP21 en sus distintos niveles jerárquicos que sirva de base para analizar los riesgos.
2. Los riesgos operacionales asociados a las tareas de esos macroprocesos no han sido identificados ni evaluados con una metodología estructurada como COSO II.
3. La organización no cuenta con un sistema que integre esos riesgos con sus planes de mitigación, sus responsables y sus mecanismos de monitoreo.

La ausencia limita la trazabilidad de responsabilidades y la continuidad operacional, y genera brechas de estandarización entre las seis plantas.

## Objetivos

### Objetivo general

Estructurar un sistema de gestión de riesgos basado en la metodología COSO II para los macroprocesos de Gestión de Personas (MP8) y Servicios Generales (MP21) del Negocio de Celulosa de Celulosa Arauco y Constitución S.A.

### Objetivos específicos

| OE | Enunciado | Este repositorio |
|---|---|---|
| **OE1** | Modelar la arquitectura de procesos de MP8 y MP21, desde sus procesos hasta sus tareas, bajo el marco del MGO. | **Sí. Es el objeto de este repositorio.** |
| **OE2** | Evaluar los riesgos operacionales asociados a las tareas modeladas de ambos macroprocesos mediante la metodología COSO II. | No. Consume la salida de OE1. |
| **OE3** | Elaborar el sistema de gestión de riesgos para MP8 y MP21, integrando el catálogo de riesgos y sus planes de mitigación bajo COSO II. | No. |

## Indicadores de logro

| OE | Indicador | Definición | Línea base | Estado final esperado |
|---|---|---|---|---|
| OE1 | **CAP** · Cobertura de Arquitectura de Procesos | % de procesos, subprocesos, actividades y tareas de MP8 y MP21 formalmente modelados en los cinco niveles jerárquicos bajo el MGO | Ausencia de arquitectura de procesos formal | 100% modelada, consolidada en dos manuales de procesos validados |
| OE2 | **TCER** · Tasa de Cobertura de Evaluación de Riesgos | % de tareas modeladas en OE1 con al menos un riesgo identificado y valorado (inherente y residual) según COSO II | Ausencia de identificación y valoración por tarea | 100% de las tareas evaluadas |
| OE3 | **CRPM** · Cobertura de Riesgos con Plan de Mitigación | % de riesgos evaluados en OE2 integrados al sistema con plan de mitigación documentado | Ausencia de sistema y de planes de mitigación | 100% de los riesgos con plan integrado |

> **Consecuencia para este repositorio:** el CAP se calcula sobre los **cinco niveles jerárquicos completos**. Una fase clasificada solo a nivel de subproceso no aporta al indicador. Por eso el detalle caja por caja importa.

## Alcance

**Incluye:**

- Modelamiento en cinco niveles: macroproceso → proceso → subproceso → actividad → tarea, para ambos macroprocesos.
- MGO de Arauco como marco normativo de referencia.
- APQC PCF v8.0 como referencia de clasificación de apoyo.
- Para cada nivel se documenta: nombre, descripción, entradas y salidas, responsables (RACI simplificado), sistemas de apoyo y frecuencia de ejecución.
- Evaluación COSO II sobre la totalidad de las tareas modeladas.
- Capa de gobernanza: roles, taxonomía de riesgos, KRI, esquema de monitoreo y reporte.

**No incluye:**

- Implementación del sistema de gestión de riesgos.
- Ejecución de los planes de mitigación diseñados.
- Mejora de rendimiento ni reestructuración operacional de los procesos.

**Unidad de análisis:** el Negocio de Celulosa **en su conjunto**, no una planta en particular, porque MP8 y MP21 se definen a nivel de negocio y se ejecutan en las seis plantas. El levantamiento y la validación se hacen con los **dueños de proceso a nivel de negocio** (responsables corporativos).

## Metodología

- **Diseño:** descriptivo-aplicado, estrategia descriptiva de tipo observacional (clasificación de Ato, López y Benavente).
- **Tipo de estudio:** caso único (Negocio de Celulosa de Arauco).
- **Carácter:** no experimental; prospectivo y transversal respecto del modelamiento, longitudinal respecto de la evaluación de riesgos y la elaboración del sistema.
- **No busca** probar hipótesis causales ni generar resultados estadísticamente generalizables.
- **Recolección de datos:** revisión documental + entrevistas y sesiones de trabajo con los dueños de proceso.

## Plan de trabajo · actividades de OE1

Las actividades que alimentan este repositorio:

| Código | Actividad | Duración | Condición de cumplimiento |
|---|---|---|---|
| A1.1 | Revisión documental y diagnóstico preliminar de MP8 y MP21 | 2 sem | — |
| A1.2 | Entrevistas con los dueños de proceso a nivel de negocio | 3 sem | — |
| A1.3 | Modelamiento de la arquitectura de procesos de MP8 (niveles 1 a 5) | 3 sem | — |
| A1.4 | Modelamiento de la arquitectura de procesos de MP21 (niveles 1 a 5) | 3 sem | — |
| A1.5 | Consolidación de los manuales de procesos MP8 y MP21 bajo formato MGO, con diagramas de flujo y matrices RACI | 2 sem | Manuales validados con los dueños de proceso |
| A1.6 | Entrega y validación formal de los manuales | 1 sem | Acta de validación de ambos manuales |

Actividades posteriores: A2.1 a A2.4 (OE2), A3.1 a A3.4 (OE3). Transversales: A-G (documentación continua), A-P1 (hito 1, semana 10), A-P2 (hito 2, semana 16), A-PF (defensa final, semana 20).

## Entregables

| Entregable | Objetivo | Dónde vive |
|---|---|---|
| Manual de procesos MP8 (5 niveles) | OE1 | Rama `MANUAL-MP8` |
| Manual de procesos MP21 (5 niveles) | OE1 | Rama `MANUAL-MP21` |
| Matriz de riesgos consolidada por tarea | OE2 | Fuera de este repositorio |
| Sistema de gestión de riesgos COSO II | OE3 | Fuera de este repositorio |

## Confidencialidad

La totalidad de los datos, procesos, riesgos y entregables generados se tratan con carácter **confidencial**, conforme a los acuerdos entre el investigador y Celulosa Arauco y Constitución S.A. El informe final del AFE será marcado como reservado, con circulación restringida a la Comisión Evaluadora del Magíster y a la Dirección Académica de Postgrado de la UFRO.

> **Nota operativa:** el repositorio `MANUALES` es actualmente **público**. Dado el carácter confidencial del contenido levantado, conviene evaluar cambiarlo a privado antes de cargar detalle operacional adicional, nombres completos de personas o documentos internos de Arauco.
