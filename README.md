# Mapa de afectaciones — Sismo Colombia 2026

Versión actualizada con corte de víctimas del 13 de agosto de 2026 y una capa de sitios/edificios reportados en fuentes publicadas el 12–13 de agosto.

Importante: varias ubicaciones no tienen coordenada exacta en la fuente. Se muestran como zonas aproximadas y están etiquetadas. Los registros de edificios no equivalen a autorización de ingreso o rescate.


## Actualización automática

El repositorio incluye un GitHub Action horario (`.github/workflows/actualizar-mapa.yml`).
Por seguridad, el Action **no usa medios de comunicación ni fuentes no oficiales**.

Para activar la consulta automática se debe configurar en GitHub:
**Settings → Secrets and variables → Actions → Variables → `OFFICIAL_SOURCE_URL`**
con la URL de un feed/dataset oficial de UNGRD que entregue los reportes actuales en formato descargable.

Mientras esa variable no exista, el Action no modifica el sitio.
Esto evita que un cambio de formato, una noticia o una fuente secundaria altere cifras de una emergencia.
