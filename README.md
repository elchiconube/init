Init
====

Init it's a HTML5 initializer


reset.css: Todo lo relacionado al reseteo de etiquetas, basado en el proyecto modernizr a poder ser debería de utilizarse conjuntamente con un polyfill de HTML5 para versiones antiguas de IE.
fonts.css: Todo lo relacionado a fuentes embebidas, Google Fonts e iconografía
layout.css: Todo lo relacionado a la estructura. Debería estar hecha toda con ID's
common.css: Todo las reglas comunes de CSS: Ej. Fuente por defecto
modules.css: Cada módulo irá maquetado y deberá funcionar de forma independiente de tal forma que se pueda exportar a otros proyectos y reutilizar el código. Cada módulo comenzará con un comentario descriptivo.
main.css: Información del proyecto e importación de archivos css utilizados anteriormente

El árbol de carpetas y archivos ideal sería este:

css
reset.css
fonts.css
layout.css
common.css
modules.css
main.css
js
main.js
vendor (carpeta con librerías)
jquery.js
moderinzr.min.js
img
fakes (carpeta para imágenes ejemplo que se borrará)
noise.png
fonts
icons.ttf
