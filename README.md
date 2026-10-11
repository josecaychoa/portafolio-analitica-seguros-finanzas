# Portafolio de analítica de datos · seguros y finanzas del Perú

José Caycho A. · Business Analyst Senior · Procesos · Datos

Índice de los proyectos de mi portafolio personal. Cada mes publico un proyecto con datos públicos (SBS, BCRP y otras entidades oficiales) o sintéticos. Cada uno vive en su propio repositorio y se puede reproducir desde cero. El README de cada proyecto explica el método y las limitaciones, e indica la fuente de cada cifra.

## Proyectos

| ID | Proyecto | Datos | Herramientas | Estado | Repositorio |
|---|---|---|---|---|---|
| PF-01 | Producción y siniestralidad por riesgo del mercado asegurador peruano, 2019-2026 | SBS, Boletín Mensual (S-367) | Python, Oracle AI Database 26ai Free, SQL Developer y Power BI (opcional) | En preparación (publicación: 26 de noviembre de 2026) | [pf-01-siniestralidad-sbs](https://github.com/josecaychoa/pf-01-siniestralidad-sbs) |

La tabla se actualiza al cerrar cada proyecto.

## Método común

Cada proyecto sigue tres fases:

1. Planificación: acta, objetivos SMART, EDT y cronograma. La línea base se fija en Microsoft Project; el repositorio guarda un Gantt en Mermaid como vista resumida.
2. Ejecución: un issue por paquete de trabajo, gestionado en GitHub Projects, con código revisado mediante pull requests. Cuando el problema lo pide, la arquitectura y el modelo de datos se diagraman en Visio y el proceso de negocio actual y propuesto se modela en BPMN 2.0 con Bizagi Modeler.
3. Seguimiento y cierre: comparación de la línea base con el avance real en Project, desvíos explicados, lecciones aprendidas y una versión 1.0.0 publicada.

Además del código, cada repositorio publica los entregables de gestión y diseño que apliquen:

| Entregable | Herramienta | Carpeta |
|---|---|---|
| Cronograma con línea base y seguimiento | Microsoft Project | `gestion/cronograma/` |
| Arquitectura y modelo de datos | Microsoft Visio | `docs/diagramas/` |
| Proceso actual y propuesto (BPMN 2.0) | Bizagi Modeler | `docs/procesos/` |

Todos los repositorios parten de la plantilla [plantilla-proyecto-datos](https://github.com/josecaychoa/plantilla-proyecto-datos). Usa Python 3.13 gestionado con uv, pruebas con pytest y revisión con ruff en GitHub Actions. El SQL se escribe primero para Oracle y los tableros de Power BI se guardan en formato PBIP.

## Reglas de datos

- Solo datos públicos u oficiales, o datos sintéticos declarados como tales.
- Ningún dato personal real, en cumplimiento de la Ley N.º 29733 y su reglamento (D.S. N.º 016-2024-JUS).
- Las citas, figuras, tablas y referencias siguen las normas APA (7.ª edición): cita en el texto, como (SBS, 2026); nota bajo cada figura o tabla, como «*Nota.* Elaboración propia con datos de SBS (2026).»; y una sección «Referencias» en cada README e informe.
- La ortografía sigue las normas de la RAE: punto decimal, millares separados con espacio y porcentajes con espacio (12.5 %).
- Los análisis tienen fines demostrativos y no constituyen asesoría regulatoria, actuarial ni financiera.

## Licencia

El código de cada proyecto se publica bajo licencia MIT. Los datos conservan las condiciones de uso de su fuente original.

## Contacto

[LinkedIn](https://www.linkedin.com/in/jcaychoasin) · [GitHub](https://github.com/josecaychoa)
