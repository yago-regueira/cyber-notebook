## CHANGELOG (decisión 2026-10-09)

### Contexto y motivo
El CHANGELOG sigue Keep a Changelog 2.0.0 y lo escribo para personas, no para
máquinas. Durante el primer mes lo mantengo yo a mano para aprender el criterio
de qué es un cambio notable. A partir de ahí delego la redacción, pero la
decisión final siempre es mía: es un repo público y nada escrito por Claude se
publica sin mi revisión.

### Reglas
- Solo propones. Nunca escribas directamente en CHANGELOG.md ni hagas commit
  de él: enséñame la propuesta y espera a que la apruebe.
- Agrupa por cambios notables, no por commits. Nunca vuelques el `git log`.
- Usa solo las categorías de Keep a Changelog (Added, Changed, Deprecated,
  Removed, Fixed, Security) y omite las que queden vacías.
- Cada línea describe el cambio para alguien que no ha visto el repo.
- No incluyas nada que no puedas comprobar en el diff desde la última versión.
  Si algo es dudoso, pregúntame en vez de suponerlo.
- El esquema de versionado está declarado en la cabecera del CHANGELOG.
  Respétalo; no lo cambies ni lo deduzcas por tu cuenta.
- Los cambios se acumulan en `[Unreleased]` hasta que yo diga que se cierra versión.
