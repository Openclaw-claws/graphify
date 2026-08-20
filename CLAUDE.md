<!-- PORTABLE:START id=brain -->
# graphify-feed — Fork de graphify + banco de grafos ya procesados

Copia de **safishamsi/graphify** (PyPI: `graphifyy` v0.4.23, clon shallow de abr-2026):
herramienta que convierte cualquier carpeta (código, docs, papers, imágenes, videos) en un
knowledge graph consultable — pasa AST determinista + whisper local + subagentes Claude,
clusterea con Leiden y exporta HTML interactivo, JSON y reporte.

## Estado
Fork de referencia, SIN commits propios (todo el historial es de Safi, upstream).
Última actividad local: abril 2026. Dormido.

## Comandos
- CLI: `python3 -m graphify` (flags y modo skill `/graphify`: ver README.md).
- Sin instalación propia: se usa como skill / herramienta ya empaquetada.

## Gotchas
- La carpeta `worked/` NO es código fuente: son los **corpus ya procesados**
  (example/, httpx/, karpathy-repos/, mixed-corpus/ — cada uno con su raw/ y README).
  No borrar sin consultar.
- **NO confundir** con el graphify del monorepo OpenClaw: ese output vive en
  `~/.openclaw/graphify-out/` (stale desde 2026-04-08, regenerar antes de confiar).
- Clon shallow (1 solo commit): no sirve para ver historial ni hacer pull limpio.

## Ecosistema
- Upstream: github.com/safishamsi/graphify (licencia y CI propios).
- Relacionado con la práctica de knowledge-graphs del mesh (graphify-out de OpenClaw).
<!-- PORTABLE:END id=brain -->
