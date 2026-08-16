# Especificación de Requisitos de Software (SRS) v1

## Requisitos funcionales

**REQ-001 — Listar productos:** El sistema permitirá consultar la lista de productos registrados.

**REQ-002 — Agregar productos:** El sistema permitirá agregar un producto siempre que su nombre no esté vacío y su cantidad sea mayor o igual a cero.

**REQ-003 — Filtrar productos por fecha (en revisión):** El sistema permitirá filtrar productos mediante una fecha inicial y una fecha final en formato AAAA-MM-DD. El resultado deberá incluir únicamente los registros comprendidos dentro del intervalo indicado, incluidas las fechas límite.

> REQ-003 permanece en revisión y no forma parte de las versiones v1.0.0 ni v1.0.1 hasta que sea implementado y verificado.

## Requisitos no funcionales

**RNF-001 — Trazabilidad:** Los cambios deberán relacionarse con un Issue, commit, Pull Request y evidencia verificable.

**RNF-002 — Versionado:** Las versiones deberán seguir SemVer mediante tags con el formato `vMAJOR.MINOR.PATCH`.

## Referencia de auditoría

Las correcciones de este documento se relacionan con `ISSUE-21` y el Issue de GitHub `#1`.