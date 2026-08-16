# Changelog

Los cambios relevantes del repositorio se documentan en este archivo.

## [Unreleased]

- No existen cambios pendientes.

## [v1.1.0] - 2026-08-15

### Agregado

- Registro de estados con diez elementos de configuración.
- Plantilla de Pull Request con controles de trazabilidad, seguridad y verificación.
- Evidencias de pruebas y referencias al Issue #1 y al Pull Request #2.

### Cambiado

- Se formalizó la baseline mediante versionado SemVer.
- Se documentaron los hallazgos y las correcciones de la auditoría.
- Se preparó el repositorio para una liberación trazable y verificable.

## [v1.0.1] - 2026-08-15

### Seguridad

- Se retiró `config/.env` del seguimiento de Git.
- Se agregó `config/.env.example` con valores simulados.
- Se incorporó `config/.env` en `.gitignore`.

### Documentación

- Se definieron los criterios funcionales y el estado de `REQ-003`.
- Se documentó la corrección del commit ambiguo mediante un commit compensatorio trazable.

## [v1.0.0] - 2026-08-15

- Baseline inicial con estructura del repositorio.
- SRS v1.
- Código mínimo de la API de Inventario.
- Prueba mínima.