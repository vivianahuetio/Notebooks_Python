# Clonar Repositorio

Cuando se crea un repositorio en GitHub, existe como un repositorio remoto. 
Se clona un repositorio para crear una copia local en el compu y sincronizarlo en las dos ubicaciones (GitHub y compu). Esta copia  incluye todas las versiones de cada archivo y carpeta del proyecto. Se puede copiar un repositorio propio o de otra persona.

## Pasos

1. Ingresar al Repositorio en GitHub que se desea clonar, y dar click en Code/Codigo.

Ubicación de code:<img width="1422" alt="CODE" src="https://user-images.githubusercontent.com/124466848/219689327-e22dc997-f30d-4f22-ae35-b147e2fd8645.png">


> Nota: Como insertar imagen. Para abrir una imagen del PC, abro un issue y arrastrar la imagen a la casilla de comentarios (dentro de git hub) y una vez me entrega la url la copio, y la pego dentro del lugar que voy a usar esa imagen, incluyendo ":" antes.



2. Copiar la URL del repositorio. Se despliega Code, y se da click en el siguiente simbolo de Code para copiar la URL. Simbolo de Code:



<img width="836" alt="Captura de pantalla 2023-02-17 a la(s) 10 07 20 a m" src="https://user-images.githubusercontent.com/124466848/219692032-94db12af-3fc9-41f5-9b68-9f013d150f76.png">


3. Abrir el Terminal de Mac. Al abrir el temrinal escribir "git clone" y pegar la dirección URL que copie.

5. Ir a Visual Code (editor de texto). Arrastrar la carpeta desde donde Se clono, o dar click dentro del editor a "abrir carpeta".

7. Al modificar algo en el code y guardar ese cambio (comando+S, o file-Save), el archivo debe aparecer con una M al lado de modificado. Así:


<img width="837" alt="Captura de pantalla 2023-02-17 a la(s) 10 30 29 a m" src="https://user-images.githubusercontent.com/124466848/219696986-eb05c34b-68d0-4048-8073-68513e0ad1fd.png">

8. Abrir el terminal de Visual Code. Para abrilo: Abrir terminal: New terminal

Escribir "Git Status", aparece el mismo nombre del archivo modificado en rojo. Así:


<img width="835" alt="Captura de pantalla 2023-02-17 a la(s) 10 37 00 a m" src="https://user-images.githubusercontent.com/124466848/219698316-f84c8d4d-26e2-4c73-ad0e-dd3e455d8e43.png">

9. Agregar el archivo modificado al Git. Para ello, escribo en la terminal del Visual Code, el comando "Git add" espacio y pego el nombre del archivo que aparecio en rojo, doy enter, y escribo de nuevo "Git satutus", debe aparecer en verde el archivo. Así:


<img width="833" alt="Captura de pantalla 2023-02-17 a la(s) 10 40 54 a m" src="https://user-images.githubusercontent.com/124466848/219699407-f75af88f-060d-478c-b792-c5c2649a7883.png">

Cuando aparece en verde, significa que ya se agrego al Git.

10. Confirmar estos cambios.

Escribir en el terminal git commit -m "nombre de referencia de este cambio" y enter.

Con el ejemplo de ponerle como referencia "first commit":

<img width="828" alt="Captura de pantalla 2023-02-17 a la(s) 10 45 44 a m" src="https://user-images.githubusercontent.com/124466848/219700264-c44db5cb-8e6c-43c9-8538-49a4b0be2aff.png">

11. Llevar los cambios al GitHub

Escribir en el terminal git push y enter.

12. Comprobar en GitHub estos cambios 

Como ya actualice GitHub y Visual Code, no tengo necesidad del token, debe reflejarse en el repositorio copiado el cambio. De esta manera:


<img width="839" alt="Captura de pantalla 2023-02-17 a la(s) 10 49 13 a m" src="https://user-images.githubusercontent.com/124466848/219701352-615c96bc-ec4f-49f4-a1a5-875f7a19539a.png">


















 
 
 



 
   



