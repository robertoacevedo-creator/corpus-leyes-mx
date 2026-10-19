# corpus-leyes-mx

Texto vigente de leyes mexicanas, dividido por artículo, en formato JSON Lines.

**Fuente:** compilación de leyes federales de la Cámara de Diputados (diputados.gob.mx/LeyesBiblio). Esa compilación es de carácter informativo; el texto oficial es el publicado en el Diario Oficial de la Federación.

## Archivos

- `corpus/articulos.jsonl`: una fila por artículo (ley, id, tipo, estado, ubicación, texto, notas de reforma, fecha de última reforma del artículo y de la ley).
- `corpus/decretos.jsonl`: decretos de reforma con sus artículos transitorios.
- `corpus/leyes.jsonl`: índice de leyes con su fecha de última reforma.
- `manifest.json`: versión del corpus y huella SHA-256 de cada archivo, para comprobar que la descarga llegó completa.
- `CAMBIOS.md`: historial de versiones.

## Leyes incluidas

Ver `manifest.json`.
