# foundry-sandbox-css-template

## English
This repo contains a template for quickly making changes to the visual style of a Sandbox System Builder in FoundryVTT

### Tutorial
For CSS noobs. For now only in Spanish : https://www.youtube.com/watch?v=6vjKwlPjE0Y

### What is it?

If you know what FoundryVTT is and its Sandbox-World-Builder subsystem then you can continue reading!

This is a basic and easy template to modify the general appearance of your own creation.

This template is just started, so I accept suggestions and improvements!

Just with changing the .css file here you can achieve something like this:
![Example](https://cdn.discordapp.com/attachments/719998606412611684/758712351469600849/unknown.png)

### How to use:

Create a folder called `style` in your World folder and put `custom_style.css`, `img` and the `fonts` folder inside.

For example:

`C:\Users\myname\AppData\Local\FoundryVTT\Data\worlds\my-sandbox-world\style`

Then launch your world and go to the System Settings, in Sandbox settings `CSS Style file` you put:

`worlds/sandbox-world/style/custom_style.css`

And press save then F5

Feel free to rename file names to your liking (remember to update both file name and the link)

Once you loaded you can make changes to the .css file by customizing basic colors and such (Open with a text editor, I recommend Notepad++ but simple Notepad will suffice).

For Fonts, you can download them online, put them in the `fonts` folder and then enable them following the existing examples in the .css file 

For Colors, take color codes from a Color Picker: https://www.w3schools.com/colors/colors_picker.asp

**Press F5 to refresh Foundry after every changed on the file!**

Inside the .css file there are some notes more or less indicating what is that section for. Follow the notes and change the parameters following the comments, save the file and press F5 in Foundry to refresh and pull the changes! 

Or if you feel more like an explorer, you can press F12 and navigate through CSS styles to experiment real-time.  

## Español
Este repositorio contiene una plantilla para facilitar cambios visuales a Sandbox-World-Builder como color de letra y fondo de hoja de personaje facilmente.

### Tutorial
Para novatos en CSS. Solo en español: https://www.youtube.com/watch?v=6vjKwlPjE0Y

### Que es?
Si sabes lo que es FoundryVTT y su subsistema Sandbox-World-Builder entonces puedes seguir leyendo!

Esto es un template de estilo basico y facil para poder modificar la apariencia general de tu propia creación.

Esta plantilla está recién empezada, asi que acepto sugerencias y mejoras!

Solo cambiando las propiedades del archivo .css puedes lograr esto!

![Example](https://cdn.discordapp.com/attachments/719998606412611684/758712351469600849/unknown.png)

### Como se usa!

Crea una carpeta llamada `style` en tu carpeta World y pon `custom_style.css`, `img` y la carpeta `fonts` dentro.

Por ejemplo:

`C:\Users\myname\AppData\Local\FoundryVTT\Data\worlds\my-sandbox-world\style`

A continuación, inicie su mundo y vaya a la configuración del sistema, en Sandbox ajustes `CSS Style archivo` se pone:

`worlds/sandbox-world/style/custom_style.css`

Presiona guardar y aprieta F5 para ejecutar los cambios

Puedes cambiar los nombres de los archivos a gusto (recuerda cambiar el link tambien!)

Abre el archivo .css con un editor de texto (Puede ser Notepad++ o el simple Block de Notas). 

Cada sección en el .css tiene un comentario indicando qué modifica cada pieza. Haga cambios en los parametros, guarde el archivo y apriete F5 para ver los cambios inmediatamente en Foundry.

Las fonts las puedes descargar de internet y colocarlas en la carpeta Font, luego las tienes que cargar como en el ejemplo del archivo. Una vez cargado puede hacer cambios en el archivo .css mediante la personalización de colores básicos y tales.

Los colores, toma los codigos de colores de un selector de colores en: https://www.w3schools.com/colors/colors_picker.as

**Pulse F5 para actualizar Fundición después de cada cambio en el archivo!**

O si te sientes más como un explorador, puedes pulsar F12 y navegar a través de estilos CSS para experimentar en tiempo real.