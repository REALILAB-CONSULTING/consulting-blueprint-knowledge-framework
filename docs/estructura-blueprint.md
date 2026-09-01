# Estructura del blueprint

Resumen de las carpetas del repositorio y de la responsabilidad que concentra cada una.

| Carpeta | Propósito |
| ------- | --------- |
| `Assets/` | Recursos reutilizables, como snippets para VS Code. |
| `ci/` | Documentación y scripts para validaciones locales y automatización de CI. |
| `copilot/` | Flujos de trabajo, prompts y configuración de apoyo para GitHub Copilot. |
| `diagrams/` | Diagramas Mermaid de la arquitectura global y de las etapas del blueprint. |
| `docs/` | Documentación general del framework y de su estructura. |
| `governance/` | Gobierno documental: KPIs, retención, roles, responsabilidades y auditoría. |
| `integrations/` | Guías y configuraciones para conectar el framework con servicios externos. |
| `security/` | Controles de acceso, protección de ramas, cifrado y políticas de seguridad. |
| `stages/` | Etapas operativas del blueprint; cada etapa contiene módulo, metadatos y diagrama. |
| `staging-inputs/` | Material fuente organizado por obra y capítulo, pendiente de transformación o integración. |
| `templates/` | Plantillas base para módulos, frontmatter, metadatos y diagramas. |
| `tools/` | Herramientas de validación, conversión, renderizado Mermaid y gestión de archivos cifrados. |

## Detalle de carpetas clave

- `governance/audit/`: listas de comprobación y procedimientos de auditoría.
- `governance/onboarding/`: materiales para incorporar colaboradores al framework.
- `integrations/docker/`: sincronización y operación mediante Docker.
- `integrations/jira/`: sincronización con Jira y plantillas de incidencias.
- `integrations/notion/`: mapeo y sincronización con Notion.
- `stages/01-determinacion-UdA/` y `stages/02-planeacion-estrategica/`: módulos operativos actualmente definidos.
- `staging-inputs/EL-ABC/`: fuente principal, separada por capítulos y acompañada de texto, figuras, anexos y frontmatter.
- `tools/convert-to-md/`: conversión de documentos fuente a Markdown.
- `tools/ci-scripts/`: utilidades usadas por los procesos de integración continua.

## Convenciones de organización

- Los contenidos fuente viven en `staging-inputs/` y los contenidos estructurados en `stages/`.
- Las nuevas etapas deben partir de las plantillas de `templates/` y conservar sus metadatos y diagramas asociados.
- Las reglas de calidad, seguridad y mantenimiento se consultan en `governance/` y `security/`.
