# IronStrong Web Meals (TheMealDB)

Módulo web del proyecto integrador IronStrong Fitness.  
Objetivo: consumir la API pública de TheMealDB y simular la importación de recetas a una base de datos, además de un POST simulado para sugerencias.

## Tecnologías
- HTML5
- Bootstrap 5
- jQuery
- API: TheMealDB (GET)
- API: ReqRes (POST simulado)

## Requisitos cumplidos
- GET: https://www.themealdb.com/api/json/v1/1/search.php?s=
- Manejo del objeto raíz `{ "meals": [...] }` (incluye caso `meals = null`)
- Render de tarjetas con: Imagen, Título, Categoría (badge) y País (badge)
- Truncado de instrucciones a 100 caracteres
- Filtro por categoría con `<select>` en cliente (sin recargar la API)
- Botón "Agregar al Menú Local" (modal + JSON en consola)
- Formulario de sugerencias (POST simulado con ReqRes)

## Cómo ejecutar
1. Abrir `index.html` en el navegador.
2. Buscar un término (ej: `chicken`).
3. Filtrar por categoría.
4. Usar "Agregar al Menú Local" y revisar la consola (F12).
5. Enviar una sugerencia y revisar la consola.
