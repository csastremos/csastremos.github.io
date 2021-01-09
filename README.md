# Estructura del sitio
### Configuración
**[_layouts](_/layouts)**  
  - [default](/_layouts/default.html)  
  - [post](/layouts/post.html) : utiliza estructura default, con alguna particularidad más  
**[_posts](/_posts):** aquí se almacenan los posts del blog. 
  - Los ficheros deben tener nombre YYYY-MM-DD-name.md  
**[_config.yml](/_config.yml)**
  - Versión de Markdown
  - Formato de links de los post del blog
  - PENDIENTE ampliar posibilidades de esto.
 
### DIRECTORIOS:
**[/about](/about) :** descripción del sitio  
**[/blog](/blog)** contiene relación de posts publicados (bucle for).  
**[/css](/css):** estilos  
**[/fiction](/fiction):** contendrá historias de ficción, separadas del blog.
  - No he conseguido que el bucle for de /blog funcione aquí con otra carpeta
  separada (_stories). *Pendiente*.
  - Por el momento, quizás pueda poner simples links a mano y publicar las historias en el blog.
