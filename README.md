## FREELANCER

#### ITEM ARCHIVO HTML.
El archivo html contiene dos etiquetas principales: Head y Body; dentro de estas etiquetas hay otras sub-etiquetas las cuales le van dando la estructura a nuestra página.

HEAD: 
Titulo: Freelancer, nombre que saldrá en la pestaña al momento de abrir nuestra página.
Enlazamos nuestro archivo CSS para que al momento de atribuirles estilos a las etiquetas se vean reflejados en el navegador.
Enlazamos la tipografia Montserrat y Lato con sus diferentes pesos visuales (400,700,800,900).
Enlazamos Font awesome, para colocar los iconos.

BODY:
La etiqueta body se sub-dividio en 6 partes, para que al momento de realizar un cambio o leer el codigo se nos sea más entendible.

1- HEADER (o encabezado): En esta sección va el menu principal de la página. A la etiqueta header se le dio el atributo "position: fixed;" ya que de esta manera cuando se haga un scroll hacia abajo, el menu siempre se encontrará en la parte superior de la página. 

2- SECTION ID="PART1": Portada de la página. Insertamos una imagen a través de la etiqueta: img src=""

3- SECTION ID="PART2": Portafolio, en esta sección van 6 imagenes insertadas con la etiqueta: img src=""

4- SECTION ID="PART3": About, se creo dentro de esta etiqueta otra etiqueta llamada: div class="columnas" la cual se vuelve a subdividir en: div class="columnaizquiera" y div class="derecha" esto para colocar los dos parrafos solicitados.

5- SECTION ID="PART4": Contac Me, en esta sección va un formulario el cual se hizo a travez de la etiqueta input. Se repitio en diferentes div esta etiqueta (input) para cada uno de los items a llenar (nombre, e-mail, phone, message)

6- SECTION ID="PART5": Esta sección es el FOOTER de la página. El cual se dividio en 3 columnas (location, redessociales y freelancer)
en la columna de redes sociales, se insertaron los iconos correspondientes a travez de la etiqueta: i class=" ".


Otras etiquetas a conciderar:

1- ANCHOR: se utilizó la etiqueta anchor: a href="#" para cada uno de los enlaces de nuestra página (en esta ocación los enlaces se encuentran inactivos)

2- BOTONES: Los botones (boton 1 y boton 2) se hicieron a travez de div los cuales se le dieron atributos en CSS.


#### ITEM ARCHIVO CSS.
Hoja de estilo, donde controlamos los resultados finales de la página (colores, tamaños, posiciones).

1- background: #2c3e50; (azul) #18bc9c; (calipso) #ffffff (blanco).

2- color (para las fonts): #2c3e50; (azul) #18bc9c; (calipso) #ffffff (blanco) 

3- h2 class="tex1" equivale a .tex1{ tiene una font-size: 80px;

4- h3 con class="tex2" , class="tex3" y class="tex4" equivalen a .tex2{ .tex3{ .tex4{ tiene una font-size: 50px;

5- h4 class="tex5" equivale a .tex5{ tiene una font-size: 28px;

6- Font-family: 'Montserrat', sans-serif; y 'Lato', sans-serif;

7- Utilizamos box-sizing: border-box; para que cuando utilizemos padding y/o border el elemento no incremente su ancho.

8- :HOVER (a:hover { color:): Para que cuando nos situemos con el puntero sobre algún elemento, (en este caso enlaces e iconos) cambien de color. 