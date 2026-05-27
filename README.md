# Monorepo Lab 7

Estructura monorepo con:

- **frontend/** — Aplicación frontend
- **backend/** — API backend
- **infra/** — Infraestructura (Docker, Terraform)
- **docs/** — Documentación

## Selective Execution

Los workflows detectan cambios por ruta y ejecutan solo pipelines relevantes.

## Optimización

- Concurrency control para cancelar runs duplicados
- Paths-filter para detección precisa de cambios
- Reusable workflows para evitar duplicación lógica
- Cache de dependencias
- Jobs condicionales

## Reporting

Cada ejecución genera un resumen en GitHub Actions con componentes afectados, pipelines ejecutados y jobs omitidos.
