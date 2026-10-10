# Portafolio de analítica de datos · seguros y finanzas del Perú

José Caycho A. · Business Analyst Senior · Procesos · Datos

Índice de los proyectos de mi portafolio personal. Cada mes publico un proyecto con datos públicos (SBS, BCRP y otras entidades oficiales) o sintéticos. Cada uno vive en su propio repositorio y se puede reproducir desde cero. El README de cada proyecto explica el método y las limitaciones, e indica la fuente de cada cifra.

## Proyectos

| ID | Proyecto | Datos | Herramientas | Estado | Repositorio |
|---|---|---|---|---|---|
| PF-01 | Siniestralidad y primas del mercado asegurador peruano por ramo | SBS, Boletín Estadístico de Seguros | Por definir en la planificación | En preparación (noviembre de 2026) | Por crear |

La tabla se actualiza al cerrar cada proyecto.

## Método común

Cada proyecto sigue tres fases:

1. Planificación: acta, objetivos SMART, EDT y cronograma en Mermaid, que queda como línea base.
2. Ejecución: un issue por paquete de trabajo, gestionado en GitHub Projects, con código revisado mediante pull requests.
3. Seguimiento y cierre: comparación de la línea base con el avance real, lecciones aprendidas y una versión 1.0.0 publicada.

Todos los repositorios parten de la plantilla [plantilla-proyecto-datos](https://github.com/josecaychoa/plantilla-proyecto-datos). Usa Python 3.13 gestionado con uv, pruebas con pytest y revisión con ruff en GitHub Actions. El SQL se escribe primero para Oracle y los tableros de Power BI se guardan en formato PBIP.

## Reglas de datos

- Solo datos públicos u oficiales, o datos sintéticos declarados como tales.
- Ningún dato personal real, en cumplimiento de la Ley N.° 29733 y su reglamento (D.S. N.° 016-2024-JUS).
- Cada cifra publicada indica su fuente: "Fuente: <entidad>, <documento>, <fecha de corte>" o "Elaboración propia con base en <fuente>".
- Los análisis tienen fines demostrativos y no constituyen asesoría regulatoria, actuarial ni financiera.

## Licencia

El código de cada proyecto se publica bajo licencia MIT. Los datos conservan las condiciones de uso de su fuente original.

## Contacto

[LinkedIn](https://www.linkedin.com/in/jcaychoasin) · [GitHub](https://github.com/josecaychoa)
