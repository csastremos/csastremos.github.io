# Estructura del sitio
### Configuración
**_layouts**  
  [default](/_layouts/default.html)  
  post : utiliza estructura default, con alguna particularidad más  
  **_posts:** aquí se almacenan los posts del blog. 
  - Los ficheros deben tener nombre YYYY-MM-DD-name.md  
  **_config.yml**
  - Versión de Markdown
  - Formato de links de los post del blog
  - PENDIENTE ampliar posibilidades de esto.
 
### DIRECTORIOS:
**/about :** descripción del sitio  
**/blog:** contiene relación de posts publicados (bucle for).  
**/css:** estilos  
**/fiction:** contendrá historias de ficción, separadas del blog.
  - No he conseguido que el bucle for de /blog funcione aquí con otra carpeta
  separada (_stories). Pendiente.
  - Por el momento, quizás pueda poner simples links a mano y publicar las historias en el blog.
