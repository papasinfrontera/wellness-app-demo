# WELLNESS APP — Inventario para preservar la demo

## Regla de protección
El proyecto Vercel `wellness-app-demo-sprint1` es la referencia aprobada. **No modificarlo ni sustituirlo durante el desarrollo de WELLNESS APP Platform.**

- URL: https://wellness-app-demo-sprint1-papasinfronteras-projects.vercel.app
- Proyecto Vercel ID: `prj_K7xoHaOV7xqh9phKcplodipQ6JfE`
- Último despliegue de producción verificado: `dpl_FLAC8vCCHHXrcG7YyUYgkkSJQsk9`
- Estado: `READY` (verificado vía Vercel).
- Repositorio del nuevo desarrollo: `papasinfrontera/wellness-app-platform` (pendiente de creación PRIVADA por el titular).
- Repositorio de andamiaje provisional: `papasinfrontera/wellness-app-demo` / rama `sprint-6-1-foundation`.

## Inventario público verificado
Se verificó respuesta HTTP 200 para cada página. Las sumas son huellas rápidas FNV-1a sobre UTF-16 del HTML hasta la primera etiqueta de cierre `</html>`, no SHA-256 ni firmas criptográficas.

| Página | Longitud (caracteres) | FNV-1a |
|---|---:|---|
| `index.html` | 58395 | `670a7eef` |
| `apob.html` | 36669 | `65a0435d` |
| `trigliceridos.html` | 39020 | `65dbd2ba` |
| `relacion-trigliceridos-hdl.html` | 37537 | `99079e17` |

## Contenido a preservar
- Catálogo de 128 indicadores: 56 con resultados y 72 sin resultado.
- Las fichas longitudinales de ApoB, Triglicéridos y relación TG/HDL, sus gráficos y los mensajes educativos aprobados.
- Escalas, clasificación original de la fuente, colores, controles y navegación.
- Saludo aprobado en análisis de sangre: «Rafael, tus resultados cuentan una historia.» / «Descubre cómo evolucionan tus indicadores.»
- No confundir `wellness-app-web-final-` con la procedencia verificable del despliegue actual: la vinculación no se ha comprobado.

## Precaución de privacidad
**El HTML publicado contiene resultados de salud del usuario. Nunca subir copias de estas páginas a un repositorio público ni incorporarlas a la futura aplicación pública.** Migrar solo a repositorio privado y a almacenamiento protegido; idealmente sustituir los datos reales por fixtures sintéticos en el código.

## Requisitos antes de migrar
1. Crear `wellness-app-platform` con visibilidad **Private**.
2. Transferir el andamiaje desde la rama actual sin información privada.
3. Crear otro proyecto Vercel, con dominio independiente y acceso restringido en previews.
4. Crear Supabase privado; configurar RLS, acceso mínimo, almacenamiento y auditoría.
5. Hacer una copia de seguridad **privada** de los archivos del demo y comprobar su restauración.
6. Validar paridad visual/funcional con el demo antes de considerar cualquier reemplazo.

Documento de inventario; **no constituye por sí mismo una copia de seguridad de los archivos**.