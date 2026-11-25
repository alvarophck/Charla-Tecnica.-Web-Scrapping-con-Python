# Web scraping con Python

Alumno: Álvaro García-Quismondo Lizana  
Fecha: 25/11/2026, 9:29:30

## Mercadona

1. Leemos el robots.txt
2. Comprobamos cuatro rutas: permitidas el sitemap y las fichas de producto, prohibidas /api y las categorías
3. Pedimos el sitemap.xml
4. Contamos palabras en los nombres de 4416 productos

Productos con «chocolate»: 166  
Del catálogo: 3,8 %

Productos con «sin gluten»: 36  
Del catálogo: 0,8 %

## Libros

1. Pedimos la primera página de books.toscrape.com
2. Escribimos el selector de los títulos: `h3 a`
3. Escribimos el selector de los precios: `.price_color`
4. Escribimos el selector de las estrellas: `.star-rating`
5. Escribimos el selector del stock: `.availability`
6. Recorremos la categoría Biography: 1 páginas, 5 libros
7. Contamos los libros de 5 estrellas: 0
8. Buscamos el libro más caro: £48.19

## Bot

1. Pedimos quotes.toscrape.com/js con requests: 0 frases
2. Lanzamos el bot con Playwright: 100 frases en 10 páginas
