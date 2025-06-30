# n8n en Render

Este proyecto está listo para desplegar `n8n` en Render utilizando un Dockerfile compatible.

## Instrucciones

1. Crea un nuevo repositorio en tu GitHub.
2. Sube el contenido de este `.zip` al nuevo repositorio.
3. Entra a https://render.com y crea un **Web Service** desde ese repositorio.
4. Render detectará automáticamente el Dockerfile y usará `render.yaml` para configurar todo.
5. Accede a tu instancia desde el subdominio asignado.

Usuario: admin  
Contraseña: admin  
Puedes cambiar esto en las variables de entorno de Render.
