# Taller integrador — Parte A: Auditoría y corrección de sitio web

**Nombre completo:** _(complete aquí)_

## Tabla de hallazgos

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
|---|---|---|
| Nombres de archivo `Mi Pagina De Notas.HTML` / `Estilos Del Sitio.CSS` | Espacios, mayúsculas y extensión en mayúscula rompen la convención de nombres | Se renombraron a `index.html` y `styles.css` |
| Variable `x` usada como divisor | No indicaba qué representaba el número 3 | Se reemplazó por la constante `CANTIDAD_NOTAS` |
| Variable `TempValue2` | Nombre sin relación con el promedio que almacenaba | Se renombró a `promedio` |
| Variable `data1` | Estaba declarada y nunca se usaba | Se eliminó |
| Parámetros `a`, `b`, `c` | No indicaban qué nota representaba cada uno | Se renombraron a `nota1`, `nota2`, `nota3` |
| Función `calc()` | Nombre genérico que no describía la acción | Se renombró a `calcularPromedio()` |
| IDs `n1`, `n2`, `n3`, `r`, `r2` y clase `cont1` | No describían su contenido ni propósito | Se renombraron a `nota1`, `nota2`, `nota3`, `resultadoPromedio`, `resultadoEstado` y `contenedor` |
| Título `<title>pagina</title>` | No identificaba el sitio en la pestaña del navegador | Se cambió a "Calculadora de Promedio de Notas" |
| `console.log(...)` en el código | Código de depuración olvidado en producción | Se eliminaron las tres líneas |
| Función comentada `calcularAntiguo(...)` | Código muerto sin ninguna función | Se eliminó el bloque comentado |

## Enlace al sitio publicado

_(pegue aquí la URL de Netlify una vez desplegado)_
