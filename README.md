# Proyecto utilizando TailwindCSS

Proyecto realizado siguiendo el tutorial : [TailwindCSS - El mejor Framework CSS para 2019](https://www.youtube.com/watch?v=FjuEJ6sY1Ok&t=620s) y la [Documentación Oficial](https://tailwindcss.com/)

## Configuración

Para realizar la configuración es necesario tener intalado nodejs

>1.- Posicionarte en el directorio de tu proyecto
>
>2.- Crear el archivo package.json con el comando:

    npm init -y

>3.- Instalar tailwindcss con el comando:

    npm install --save-dev tailwindcss
    
    
Listo, con esto iniciamos.

### Proyecto

LLegó el momento dar el primer paso del proyecto, de igual manera que la configuración pondré lo pasos esenciales.

>1.- Crear los siguientes directorios: img, css
>
>2.- Crear los archivos index.html y app.css
>
>3.- En el archivo **app.css** agregar lo siguiente:

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

>4.- Compilar la hoja de estilos recien editada:

    npx tailwind build app.css -o css/app.css

>Puedes visualizar el resultado en css/app.css

>5.- Editar el index.html:

    
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="css/app.css">
        <title>Document</title>
    </head>
    <body>
        
    </body>
    </html>
> Notar que se agrega la referencia del archivo app.css
>
>6.-Y agregamos la primera utilidad:

    <div class="container mx-auto">
        1
    </div>

> Si visualizas esto en un navegador te darás cuenta que el elemento ya no está con margin izquierdo 0, si no que ahora tiene un margin auto.

Y listo, con esto inicia el proyecto, te invito a visualizar el contenido completo y puedas continuar con el proyecto.


    