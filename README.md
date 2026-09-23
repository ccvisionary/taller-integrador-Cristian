# Taller Integrador Individual - Cortes 1 y 2
**Estudiante:** Cristian cantillo

## Tabla de Hallazgos de Auditoría

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
| :--- | :--- | :--- |
| Nombres de archivos con espacios y mayúsculas | Rompen convenciones web y causan errores en servidores | Se renombraron a minúsculas y sin espacios (`index.html` y `styles.css`) |
| Título genérico en la pestaña | No aporta contexto al usuario ni a buscadores | Se actualizó a un título descriptivo |
| Variables mal nombradas (`data1`, `TempValue2`, `x`) | Son crípticas y dificultan la lectura del código | Se cambiaron por nombres descriptivos y semánticos |
| Nombre de función genérico (`calc`) | No describe la acción específica que realiza | Se renombró a `calcularPromedioNotas` |
| Identificadores HTML crípticos (`n1`, `n2`, `r`, etc.) | Dificultan el mantenimiento del DOM | Se actualizaron a identificadores descriptivos |
| Código muerto y logs innecesarios | Contamina el código y aumenta el peso | Se eliminaron funciones comentadas y logs de prueba |
| Formato e indentación inconsistente | Rompe estándares de legibilidad | Se aplicó indentación uniforme |

[Enlace al sitio publicado en Netlify](https://tu-sitio.netlify.app)