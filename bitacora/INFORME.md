| Hallazgo | Dónde estaba | Técnica de Git | Comando exacto | Referencia |
|---|---|---|---|---|
| FRAG-01 | rama principal | Historial de borrados | `git log --all --diff-filter=D --oneline -- bitacora/frag-01.txt` | `b75c0ce` |
| FRAG-02 | etiqueta de respaldo | Inspección de objetos | `git cat-file -p refs/bundle/tags/respaldo/pre-incidente` | `1195724` |
| Glifo | etiqueta de respaldo | Extracción de archivo | `git checkout refs/bundle/tags/respaldo/pre-incidente -- assets/sello.svg` | `1195724` |