## CHANGELOG (decisión 2026-10-09)

### Contexto y motivo
El CHANGELOG sigue Keep a Changelog 2.0.0 y se escribe para personas, no para
máquinas. Sigo su sección "Changelogs, automation, and LLMs": una máquina puede
redactar el borrador, pero la persona decide qué es notable y cómo se cuenta.
Es un repo público y nada escrito por Claude se publica sin mi revisión.

### Reglas
- Solo propones. Nunca escribas directamente en CHANGELOG.md ni hagas commit
  de él: enséñame el borrador y espera a que lo apruebe.
- Resume solo los cambios notables para quien lee el repo. Nunca vuelques
  el `git log` ni conviertas cada commit en una línea: un cambio notable
  puede abarcar varios commits, y muchos commits no merecen entrada.
- Clasifica cada cambio en una de las seis categorías de Keep a Changelog
  (Added, Changed, Deprecated, Removed, Fixed, Security) y omite las vacías.
- Explica en el propio texto el motivo del cambio, no solo qué cambió.
- Marca de forma explícita los cambios que rompen algo. En este repo, sobre
  todo mover o renombrar ficheros y carpetas, porque rompe enlaces externos.
- Elimina todo lo que no merezca la pena leer.
- No incluyas nada que no puedas comprobar en el diff desde la última versión.
  Si algo es dudoso, pregúntame en vez de suponerlo.
- El esquema de versionado está declarado en la cabecera del CHANGELOG.
  Respétalo; no lo cambies ni lo deduzcas por tu cuenta.
- Los cambios se acumulan en `[Unreleased]` hasta que yo diga que se cierra versión.
