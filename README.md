# consulting-blueprint-knowledge-framework

Framework modular de consultoría que transforma EL‑ABC‑DE‑LA‑CONSULTORIA en documentación Markdown, etapas operativas y diagramas, integrando gobernanza digital, mejora continua y formación profesional para equipos, asegurando trazabilidad, calidad documental y colaboración efectiva

## Problema que resuelve

Evita la dispersión de entregables y la pérdida de conocimiento entre proyectos consultivos. Provee un único punto de verdad con plantillas estandarizadas, metadatos obligatorios y validaciones automáticas para mejorar calidad y reutilización.

## Usuarios y roles

- **Owner**: responsable final del repositorio.
- **Maintainer**: gestiona PRs, CI y gobernanza.
- **Consultor Senior**: crea y valida módulos.
- **Consultor Jr.**: redacta contenidos y pruebas.
- **Cliente / Sponsor**: revisa entregables ejecutivos.

## Entregables mínimos (primer push)

- Plantillas: `templates/stage-frontmatter.template.yml`, `templates/meta.json.template`.
- Módulos: al menos `stages/01-determinacion-UdA/module.md` con frontmatter y `meta.json`.
- Insumos: `staging-inputs/EL-ABC/CAPITULO-I/texto.md`.
- Integraciones: `integrations/docker/docker-sync.md`, `integrations/notion/notion-sync.md`.
- Gobernanza: `governance/KPIs.md`, `governance/audit/audit-checklist.md`.
- CI: workflows básicos en `.github/workflows/` para validar frontmatter y meta.json.

## Límites y exclusiones

- No almacenar credenciales ni datos personales sensibles en el repositorio.
- No incluir contratos finales sin cifrado.
- No usar el repositorio como gestor de tareas; enlazar con Jira o Notion.

## Criterios de éxito iniciales

- **Completeness**: porcentaje de módulos con `status: approved`.
- **Freshness**: porcentaje de módulos actualizados en los últimos 12 meses.
- **Validation pass rate**: porcentaje de PRs que pasan validaciones CI en la primera ejecución.

## Contacto y gobernanza

- Owner: Nombre Apellido —  <https://www.example.com/>
- Maintainer: Nombre Apellido — <https://www.example.com/>
- Ver `governance/roles-and-responsibilities.md` para detalles de permisos y procesos.
